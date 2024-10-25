# Korkeat standardit

## Tutustu kurssin sanastoon, joka on määritelty SFS-EN ISO/IEC 27000:2020:en standardissa, kappaleessa 3. Terms and Definitions. Selvitä seuraavien kappaleiden määritteet ja selitä omin sanoin mitä ne tarkoittavat: 3.2, 3.31, 3.56, 3.58, 3.77.

### Kappale 3.2 Attack (Hyökkäys)

Hyökkäys tarkoittaa yritystä tuhota, paljastaa, muuttaa, ottaa pois käytöstä, varastaa tai saada luvaton pääsy, tai käyttää luvattomasti toisen omaisuutta (Suomen Standardisoimisliitto SFS ry 2020). Hyökkäys voi kohdistua esimerkiksi järjestelmiin, dataan tai fyysiseen omaisuuteen. 

### Kappale 3.31 Information security incident (Tietoturvapoikkeama)

Tietoturvapoikkeama on yksittäinen tai sarja tahdottomia tai odottamattomia tietoturvallisuus tapahtumia. Joilla on merkittävä vaikutus vaarantaa liiketoiminta ja tietoturva (Suomen Standardisoimisliitto SFS ry 2020, Digi- ja väestötietovirasto). Poikkeamat voivat johtua esimerkiksi hyökkäyksistä, inhimillisitä virheistä tai järjestelmävirheistä. 

### Kappale 3.56 Requirement (Vaatimus)

Vaatimus on tarve tai oletus joka on annettu, yleisesti implikoitu tai vaadittu (Suomen Standardisoimisliitto SFS ry 2020). Vaatimukset voivat tulla esimerkiksi lainsäädännöstä, käytännöistä tai organisaation odotuksista. 

### Kappale 3.58 Review (Katselmointi)

Katselmointi on toteutettu toiminta päättääkseen sopivan, riittävän ja toimivuuden aihepiiriin liittyen, millä saavutetaan asetetut tavoitteet (Suomen Standardisoimisliitto SFS ry 2020). Katselmointia voidaan toteuttaa esimerkiksi prosesseille, projekteille tai tuotteille. 

### Kappale  3.77 Vulnerability (Haavoittuvuus)

Haavoittuivuus on puute omaisuudessa tai sen kontrollissa jota pystyy hyväksikäyttämään yhdessä tai useammassa potentiaalisessa uhassa (Suomen Standardisoimisliitto SFS ry 2020). Haavoittovuudet voivat olla esimerkiksi ohjelmistovirheitä, konfiguraatiovirheitä tai puutteellisia toimia takaamaan turvan. 

## Tutustu standardiin ISO 27034-1 - 5. Selvitä mistä standardi kokonaisuudesta on kyse.

Systemaattinen lähestymistapa organisaatioille turvallisuuden integroimisesta ohjelmistoille koko ohjelmiston elämänkaaren ajan. Ottaa kantaa sovelluksen taustalla olevaan ohjelmistoon ja sen turvallisuuteen vaikuttaviin tekijöihin. Sopii kaiken kokoisille ja tyyppisille organisaatiolle. Ei kuitenkaan anna ohjeita fyysiseen tai verkon tietoturvaan, eikä toimi ohjeena turvalliseen koodin luontiin millekkään ohjelmointikielelle! (Suomen Standardisoimisliitto SFS ry 2020)

## Kuuntele podcast: Meurman 2021: Laatulöpinät 30: Tietoturvallisuus ohjelmistokehityksessä. Mitä mieltä olet podcastin väittämistä?

### Onko mikään ohjelma täysin tietoturvallinen? 

Olen samaa mieltä podcastissa todettuun että ei ole, poislukien ohjelmat joita kukaan ei käytä.

### Hallinnollinen tietoturva on teknisen tietoturvan edellytys? 

Näinhän se on ja kuten podcastissakin todettiin niin hallinollisen tietoturvan määrittelyssä saadaan tietää minkälaista teknistä tietoturvaa vaaditaan.

### Automaatiotestaus on tietoturvan kannalta erittäin tärkeä?

Se voi nopeuttaa testaamista mutta jos testaus ei kata kaikkea niin voi jäädä katveita tietoturvaan jatkuvasti.

### Ohjelmistoa suunniteltaessa voidaan auttaa käyttäjää toimimaan tietoturvallisesti?

Pidän sitä mahdollisena jos se ei ärsytä käyttäjää, esimerkiksi salasanoissa vaadittu että on isoa kirjainta, numeroita ja erikoismerkkejä usein johtaa laiskoihin salasanoihin jos ei käytä salasanan hallintaan tarkoitettua työkalua, pidän esimerkiksi useamman vaiheen todennus erilaisilla turvatunnisteilla(USB avaimet) tai SSH-avaimiin perustuvaa turvaa helpompana vaihtoehtona kuin tyypilliset salasanat jolloin saadaan käyttäjän näkökulmasta hyötyä käytettävyyden sekä tietoturvan kannalta.
 
### Ohjelmiston tietoturvaan vaikuttaa kuinka arkaluonteisia tietoja käsitellään?

Aina kannattaa yrittää tehdä tietoturvallinen ratkaisu, lainsäädäntö myös vaikuttaa siihen miten tietoja pitää käsitellä joka vaikuttaa myös miten tietoja käsitellään.

### Ohjelmiston kehittäjät näkevät omat ohjelmat huomattavasti riskialttiimpina kuin muiden kehittämät ohjelmat?

Kun tuntee ohjelman niin tuntee myös sen heikkoudet paremmin, kuten tunnillakin todettiin että iso osa ohjelmoijista ei pitäisi omia taitojaan hyvänä vaikka olisi 10 vuotta kokemusta kielestä. 


## Lähteet:

Suomen Standardisoimisliitto SFS ry 2020.  SFS-EN ISO/IEC 27000:2020:en. Luettu: 23.10.2024.

Digi- ja väestötietovirasto. OHJE: TIETOTURVA- TAI TIETOSUOJAPOIKKEAMIEN KÄSITTELYSTÄ HENKILÖ-
TIETOJA SISÄLTÄVISSÄ PALVELUISSA. Luettavissa: [https://dvv.fi/documents/16079645/17325934/..](https://dvv.fi/documents/16079645/17325934/Tietoturva-+tai+tietosuojapoikkeamien+käsittelyohje.pdf/). Luettu: 23.10.2024.

Meurman 2021. Laatulöpinät-podcast: Tietoturvallisuus ohjelmistokehityksessä – Tarkastele kokonaisuutta ja hyödynnä viitekehykset. Kuunneltavissa: [https://www.arter.fi/podcast/laatulopinat-podcast...](https://www.arter.fi/podcast/laatulopinat-podcast-tietoturvallisuus-ohjelmistokehityksessa-tarkastele-kokonaisuutta-ja-hyodynna-viitekehykset/) Kuunneltu: 25.10.2024.

Karvinen, T. 2024. Sovellusten hakkerointi ja haavoittuvuudet. Luettavissa: [https://terokarvinen.com/application-hacking/](https://terokarvinen.com/application-hacking/).
