# PortSwigger

## Screenshot of dashboard

<img width="943" height="322" alt="image" src="https://github.com/user-attachments/assets/a9bbc2ca-e21d-4239-a744-7546b3428e7e" />

## Labs
 * SQL injection vulnerability in WHERE clause allowing retrieval of hidden data
 * SQL injection vulnerability allowing login bypass
   
 * Reflected XSS into HTML context with nothing encoded
 * Stored XSS into HTML context with nothing encoded
 * DOM XSS in document.write sink using source location.search
 * DOM XSS in innerHTML sink using source location.search
 * Reflected XSS into attribute with angle brackets HTML-encoded
   
 * File path traversal, simple case
   
 * Unprotected admin functionality
 * Unprotected admin functionality with unpredictable URL
 * User role controlled by request parameter
 * User role can be modified in user profile
 * User ID controlled by request parameter
 * User ID controlled by request parameter, with unpredictable user IDs
 * User ID controlled by request parameter with data leakage in redirect
   
 * Username enumeration via different responses
 * 2FA simple bypass
 * Password reset broken logic


# The Booking system project
## Phase1 Osa1
Ensimmäinen osa projektia tuntui syvälliseltä harjoittelulta. Opin käyttämään paljon minulle entuudestaan vieraita työkaluja, kuten docker ja zap. Opin/muistuttelin mieleen SQL komentoja ja linux terminaalin käyttöä. Kaikki raportointi oli ihan uutta ja opeteltavaa. Tässä osassa projektia luotiin/käynnistettiin ympäristö omalle koneelle penetraatio testausta varten. Eli dockerilla nettisivu ja tietokanta pystyyn. Sivusto testattiin Zapilla useilla hyökkäyksillä ja etsittiin haavoittuvuudet rekisteröitymisestä. Lopuksi ladattiin raportti Zapista ja kirjoitettiin myös oma raportti testauksesta ja löydetyistä haavoittuvuuksista sekä niiden korjaamisesta. Eniten aikaa vei raportin kirjoittaminen tai testiympäristön luominen. Kaikki toimi suhteellisen helposti ohjeita noudattaen. 

## Phase1 Osa2
Tässä osassa vertailtiin haavoittuvuutta edelliseen osaan projektia. Samat zap hyökkäykset tehtiin ja testattiin sivuston haavoittuvuuksia. Täytyis selvittää oliko osassa 1 kirjoitetut välttämättömät toimenpiteet tehty. Selvityksestä kirjoitettiin raportti. Tätä osaa tehdessä olin erittäin epävarma omasta tekemisestäni. Ajattelin, että olin kirjoittanut liian laajat toimenpiteet osassa1 ja niiden korjausten tarkistaminen tuntui mutkikkaalta ja vaikelta. Onneksi on tekoäly ja tehtävässä opin paljon eri haavoittuvuuksien käytännön testaamisesta ja työskentelystä yhdessä tekoälyn kanssa oppimismielessä.

## Phase2
Tässä osiossa keskityttiin salasanojen hakkeroimiseen. Opin käyttämään decryptaus työkaluja ja että MD5 salauksena yksin on erittäin helppo ja todella nopeasti hakkeroitavissa. Tiedostot eivät ole turvassa, vaikka ne olisi salattu. Tämä osio oli aika helppo ja nopea, eniten taisi viedä aikaa Zap hyökkäykset.

## Reflektio
Penetraatiotestaus aihealueena sekä muu cyperturvallisuus oli minulle entuudestaan melko vierasta. Hakkerointi podeja spotifystä ja sarjoja areenasta olen katsonut, että ymmärtäisin jotain. Opintojakso oli aika vaike ja raskas ja tuntui vievän paljon aikaa. Samaan aikaan opin erittäin paljon uutta ja oli mielenkiintoista päästä oikeasti käsiksi tekemiseen eikä vain lukea ja kuunnella aiheista. Jatkuvuus ja progressio näissä tehtävissä oli myös miellyttävää. Samoja asioita toistamalla ne jää muistiin oikeasti. Mielelläni olisin tehnyt loputkin osiot tehtävästä, mutta välillä täytyy priorisoida näin. Onneksi tehtävät löytyvät varmaan jonkin aikaa täältä githubista, ehkä vielä palaan niiden pariin harjoittelemaan. Raporttien kirjoittaminen ei ole lempipuuhaani, mutta on ollut hyvä että sitä on ollut pakko myös tehdä. Ainahan niidenkin tekeminen raportti raportilta helpottuu. Englannin kieli on ollu minulle myös haaste ja olen oppinut sanastoa tällä opintojaksolla erittäin paljon. 

# Logbook
Linkki: https://github.com/TaruNuutinen/vigilant-octo-spork/blob/main/README.md

Total hours: 72 h
Hours per topic
* PortSwigger: 14 h
* The Booking System project: 39 h
* Muut: 19 h
  
# Feedback
Kurssi oli erittäin mielenkiintoinen ja mukavan haastava. Opin erittäin paljon kurssin aikana ja toivon että opit pääsevät käyttöön. Pidän sinun huumorista ja kiva, että sitä on mukana tehtävissä! Kiitos kurssista!
