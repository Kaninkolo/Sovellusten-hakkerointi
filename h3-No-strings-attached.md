# No strings attached

## Strings. Lataa ezbin-challenges.zip Aja 'passtr'. Selvitä oikea salasana 'strings' avulla. Selvitä myös lippu. 

Aloitin tehtävän purkamalla tehtävät, kokeilin aluksi ajamalla ohjelman, ohjelma toimi odotetusti mutta en tietänyt salasanaa.

	./passtr

Kokeilin strings ohjelmaa ja tulosteesta pystyin selvittämään salasanan

	strings passtr

![images/passtr-strings.png]

Testasin vielä ratkaisua.

![images/passtr-ratkaisu.png]

FLAG{Tero-d75ee66af0a68663f15539ec0f46e3b1}

## Tee passtr.c -ohjelmasta uusi versio, jossa salasana ei näy suoraan sellaisenaan binääristä. Osoita testillä, että salasana ei näy.

Lähdin etsimällä netistä tietoa obfuskoinnista ja löysin memfrob() funktion ja kokeilin sitä, sen lopputulos oli osittain obfuskoitu teksti mutta olisin pystynyt selvittämään salasanan kohtuu helposti silti strings:in avulla joten ryhdyin etsimään monimutkaisempaa ratkaisua.

## Packd. Aja 'packd' paketista ezbin-challenges.zip. Mikä on salasana? Mikä on lippu? (Tämä tehtävä on hieman haastavampi. Kirjaa ylös kokeilemasi lähestymistavat ja keksimäsi hypoteesit. Toivottavasti pääset itse maaliin, mutta jos et, läpikävely paljastuu tunnilla...)

Kokeilin aluksi strings kautta ja huomasin tulosteessa osittain luettavaa tekstiä, teksti vastasi osittain aiemman tehtävän tulosteita(kuvassa oikealla), lähdin sen kautta etsimään löytyisikö strings:in tulosteesta muuta jonka voisi yhdistää luomaan kokonaisen lauseen ja salasanan. 

	strings packd

![images/packdvaara.png]

En löytänyt mitään millä olisin loogisesti voinut luoda kokonaista lausetta tulosteesta, kokeilin myös Base64 dekoodausta osaan string:in tulosteista saaden vain sotkua(koska oli mainittu vinkeissä vaikkakin Cryptopals osiolle), lopulta huomiota herätti teksti jossa luki "$Info: This file is packed with the UPX executable packer http://upx.sf.net ", sen kautta päädyin UPX manuaali sivuille josta löytyi komento jolla pystyi purkamaan pakkauksen. Asensin upx:n ja ajoin komennon

	sudo pacman -S upx

	upx -d packd

![images/upxd.png]

Sen jälkeen pystyin uudestaan ajamaan strings komennon ja löysin salasanan

![images/packdratkaisu.png]

Testasin vielä että salasana toimii.

![images/packdtesti.png]

FLAG{Tero-0e3bed0a89d8851da933c64fefad4ff2}

En tiedä oliko tämä haluttu tapa ratkaista tehtävä koska ensimmäisessä tehtävässä oli erikseen mainittu strings ohjelma.

## Lähteet

https://linux.die.net/man/1/upx
