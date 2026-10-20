# Muista! – pakolliset suunnittelu- ja kehityssäännöt

## 1. Lue suunnitelmat alusta asti
Ennen jokaista toteutusosaa tai merkittävää muutosta:
1. Käy läpi Muista!-projektin alkuperäiset suunnitelmat ja keskustelussa hyväksytyt päätökset, aloittaen ensimmäisistä vaatimuksista.
2. Vertaa niitä myöhempiin tarkennuksiin. Uudempi nimenomainen päätös korvaa vanhan ristiriitaisen päätöksen.
3. Tarkasta nykyinen lähdekoodi ja merkitse ominaisuudet: toteutettu / osittain tehty / puuttuu / vaatii iPhonen natiivisovelluksen.
4. Tee ennen koodausta tehtävälista siitä, mitä säilytetään, mitä parannetaan ja mitä ei vielä voida toteuttaa.
5. Älä poista aikaisemmin hyväksyttyä toiminnallisuutta ilman käyttäjän nimenomaista päätöstä.
6. Pidä Auru Rutiinin tiedostot ja toiminta koskemattomina. Muista! on erillinen sovellus.
7. Toteuta osissa ja anna käyttäjälle kokeiltava versio ennen seuraavaa osaa.
8. Päivitä numeroitu projektimuistio jokaisen osan jälkeen ja kirjaa toteutetut muutokset ja puutteet.
9. Testaa mahdollisuuksien mukaan koodin syntaksi ja keskeiset toiminnallisuudet, älä väitä testaamatonta valmiiksi.
10. Älä yhdistä testiversiota tärkeisiin oikeisiin kalenteritietoihin ennen toimivaa iCloud-synkronointia ja palautusvarmistusta.

## 2. Säilytettävät hyväksytyt ominaisuudet
- Oma itsenäinen kalenteri; ulkoiset Google- ja iPhone-kalenterit valinnaisia ja toisistaan riippumattomia.
- Päivä-, 7-päiväinen viikko-, kuukausi- ja listanäkymä. Tänään palauttaa aina todelliseen nykyiseen päivään. Päivän vaakapyyhkäisy vaihtaa päivää.
- Viikon kaikkien päivien tapahtumat ja vasemman reunan kellonajat; pienet tapahtumatekstit, napautuksella kaikki tiedot. Päivä- ja viikkoaikajanan tyhjän kohdan napautus avaa uuden tapahtuman valmiilla ajalla ja päivällä.
- Tiivis käyttöliittymä, näkymävalikko ja + Lisää lähellä toisiaan, asetukset pois kalenterin etuosasta.
- Kuukauden ja vuoden suoraan sormella pyöritettävät kompaktit rullat, Peruuta ja Siirry.
- Tapahtuman nimi itse kirjoittaen TAI valmiista vaihtoehdoista (lääkkeet, juo vettä, syntymäpäivä, nimipäivä, koulu, oppitunti, palaveri, lääkäri jne.).
- Omat usein käytettävät tapahtumapohjat; lisää, muokkaa ja poista pyyhkäisemällä. Pohjan poistaminen ei poista kalenteritapahtumia.
- Kellonaika iPhonen herätyskellon tapaan tunti- ja minuuttirullilla, minuutit 1 minuutin askelin.
- Toisto päivittäin, valittuina viikonpäivinä, viikoittain, kuukausittain ja vuosittain; toistaiseksi tai tiettyyn päivään saakka.
- Tapahtuman tietokortti ja muokkaus; toistuvista tapahtumista yksi kerta / tämä ja tulevat / koko sarja.
- Poistovahvistus, välitön Kumoa, 30 päivän roskakori ja Palauta. Poistot peruvat tulevat hälytykset; palautus ajastaa tulevat.
- Kalenterin ensihälytys 5 min–12 h ennen ja valinnainen toinen muistutus esimerkiksi edellisenä päivänä; toistuva muistutus toiminnan alkaessa.
- Tavoiteltu erottuva kuitattava herätys, torkku ja valittavat äänet iPhonen natiivisovelluksessa; älä väitä selaimen tukevan niitä luotettavasti.
- Paikallinen tallennus + oman iCloudin synkronointi + erilliset versioidut varmuuskopiot ja palautus sekä synkronointitilan näyttö. Tietojen säilyminen puhelimen vaihtuessa etusijalla.
- Google- tai iPhone-kalenteriyhteyden irrottaminen EI saa poistaa alkuperäisiä eikä Muista!-sovelluksen omia tapahtumia. Huolehdi mahdollisista kalenterikaksoiskappaleista.
- Käyttäjä testaa ominaisuudet osa kerrallaan; käyttöliittymää voi tarkentaa myöhemmin.

## 3. Erota testiversio ja varsinainen sovellus
Selainkokeilussa voidaan näyttää näkymiä ja testata tapahtumalogiikkaa. Se ei ole luotettava lääkemuistutin eikä sisällä oikeita AlarmKit-hälytyksiä tai iCloud/CloudKit-synkronointia ilman erillistä toteutusta. Merkkaa nämä erot aina.

## 4. Muutosten hyväksyminen
Käyttäjän uudet tarkennukset lisätään tähän tiedostoon; ristiriitatapauksessa kysy vain tarvittaessa, kumpi ratkaisu säilytetään.
