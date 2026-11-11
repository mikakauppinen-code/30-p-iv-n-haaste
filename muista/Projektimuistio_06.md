# Muista! – projektimuistio 06: kalenterilomakkeen uudistus
Päivitetty 11.11.2026

## Tehty v2-selainkokeiluun
- Viimeksi valittu kalenterinäkymä tallennetaan selaimen paikalliseen muistiin ja palautetaan avauksessa.
- Tapahtumalle oma alku- ja loppuaika, molemmat erillisillä tunti- ja minuuttirullilla.
- Tuntien ja minuuttien rullat matalia, kapeita ja metallinharmaita mustilla numeroilla.
- Koko päivä -valinta piilottaa kellonaikarullat.
- Lisäasetuksissa monivalinta kalentereille ja Lisää kalenteri -valinta (paikallinen kalenterinimi).
- Valinnoissa Muista! sekä Google- ja iPhone-kalenteriin vientikohteet. Ulkoisiin kalentereihin EI vielä kirjoiteta suoraan.
- Osallistujien sähköpostiosoitteet ja painike sähköpostikutsuluonnoksen avaamiseksi (ei automaattista lähetystä).
- Videokokouspalvelun valinta ja linkki, josta voi avata kokouksen.
- Sijaintikenttä ja Googlen karttahaun avaaminen.
- Tapahtumaväri, näkyvyys, vapaa/varattu, lisätiedot sekä liite-URL.
- Tapahtuman ICS-kalenteritiedoston vientipainike ulkoiseen kalenteriin käsin tuontia varten.
- Web-app-manifesti ja SVG-kuvake, jotta selainversio voidaan lisätä iPhonen Koti-valikkoon.
- Asetuksissa Koti-valikkoon lisäämisen ohje.
- Aikaisemmat tapahtumat ja tallennusavaimet säilytetty; Auru Rutiiniin ei tehty muutoksia.

## Tarkista käyttäjän iPhonessa
1. Sulje Muista!-selainkokeilu ja avaa uudelleen: palaako viimeksi valittu näkymä?
2. Luo esim. 17.11. klo 8–9 tapahtuma ja tarkista tiedot sekä kuukausinäkymä.
3. Valitse Koko päivä: piiloutuvatko kellonaikarullat ja näkyykö merkintä?
4. Avaa Lisäasetukset ja valitse useita kalentereita, lisää paikallinen nimi, vahvista ja tallenna.
5. Lisää osallistuja ja avaa sähköpostiluonnos tapahtumatiedoista. Tarkista osoite ennen käsin lähettämistä.
6. Lisää Teams/Meet/Zoom-kokouslinkki ja sijainti; testaa avaus.
7. Vie .ics-tiedosto ja testaa tuonti ulkoiseen kalenteriin. Vältä kaksoiskappaleita.
8. Lisää Koti-valikkoon Safarin Jaa-valikosta ja tarkista, että kuvake avaa testiversion.

## Ei vielä toteutettu / ei saa väittää toimivaksi
- Todellinen Google Calendar API -kirjautuminen tai kirjoittaminen, usean ulkoisen kalenterin muokkaus.
- Apple EventKit -synkronointi oikeaan iPhone-kalenteriin.
- Kutsujen lähetys palvelimelta tai osallistujien hyväksynnän seuranta.
- Teams/Meet/Zoom-kokouksen automaattinen luominen.
- Drive-tilin tiedostovalitsin tai tiedostojen turvallinen lataus.
- Luotettavat iPhonen AlarmKit-hälytykset.
- iCloud/CloudKit-varmuuskopiointi ja palautus.
- Täysi natiivin iPhone-sovelluksen asennuspaketti.

## Turva ja tietojen säilyminen
Tämä on edelleen pelkkä paikalliseen selaintallennukseen perustuva testisovellus. Älä vielä käytä tärkeiden muistutusten tai yksityisten kokous- ja osallistujatietojen ensisijaisena tallennuspaikkana. Testisovelluksen mahdollinen poistaminen tai selaimen tietojen tyhjentäminen voi hävittää tiedot.
