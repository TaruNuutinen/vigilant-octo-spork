# vigilant-octo-spork
Cybersecurity and data privacy

# Logbook

| Date | Used hours | Subject(s) | outcomes | 
|:---|:---:|:---:|:---:|
| 30.10.2025 | 1.5 h | Kikc-off | Login for the netacad, studying material | 
| 30.10.2025 | 0.5 h | Week 1 | Github repo, Logbook | 
| 1.11.2025 | 2 h | Introduction of Cybersecurity | studying material 1 & 2, Quiz 1 |
| 2.11.2025 | 0.5 h | Introduction of Cybersecurity | studying material 2 |
| 4.11.2025 | 2 h | Lecture 2 | Info material & PortSwigger account |
| 5.11.2025 | 0.5 h | Introduction of Cybersecurity | Quiz 2 |
| 6.11.2025 | 3.5 h | Introduction of Cybersecurity | studying material 3, 4 & 5, Quiz 3, 4 & 5 |
| 7.11.2025 | 0.75 h | Introduction of Cybersecurity | final exam |
| 8.11.2025 | 2.75 h | PortSwigger | Learning SQL injection and choosing topics, first lab complited |
| 9.11.2025 | 2.5 h | PortSwigger | SQL injection lab, learning more about vulnerabilities, two authentication labs, two access control labs |

Notes (Write a short reflection (50-100 words) for each lab you complete. You can use the following questions to guide you: What did you learn? What was the most challenging part?):
1. lab: SQL injection vulnerability in WHERE clause allowing retrieval of hidden data. <br>
     Opin, kuinka etsitään haavoittuvuuksia muuttamalla kyselyä ja saamalla aikaiseksi erroreita. Opin myös käyttämään PortSwigger alustaa ja vähän Burp suitea. Opin myös, jos suodattimet on rakennettu sen pohjalle, että kaikista tuotteista näytetään tietyt ja loput piilotetaan, voi saada ihan kaikki näkyviin, myös 'aina piilotetut' tuotteet. Vaikeinta oli ymmärtää ohjeet, kun kaikki termit ovat vielä ihan uusia. Video selkeytti ja lisäsi paljon ymmärrystä.
2.  Lab: SQL injection vulnerability allowing login bypass <br>
     Opin, että sql-koodissa voi olla sellaisia haavoittuvuuksia, että username kyselyyn laittamalla oikean usernamen perään '-- poistaa se komento kyselyssä tarvitun loppuosan eli salasanaa ei tarvita sisäänkirjautumiseen. Tämä on aika helppo tapa hakkeroitua sisään, jos tällainen haavoittuvuus löytyy. Olin iloinen, kun opin ratkaisemaan labin käyttämättä apuvideoita. Tässä labrassa ei ollut oikeastaan mitään vaikeaa.
3. Username enumeration via different responses <br>
   Opin sisäänkirjautumisen haavoittuvuuksista ja kuinka käytetään burp suiten työkaluja brute-force hyökkäykseen. On mielenkiintoista, että tällaisia työkaluja on olemassa. Opin löytämään oikean tunnuksen tai salasanan poikkeavan vastauksen ansiosta. Vaikeinta labissa oli uusien työkalujen omaksuminen. Onneksi luennolla oli näytetty, kuinka labra tehtiin, niin se helpotti löytämään tien ratkaisuun helpommin ja käyttämään työkaluja tehokkaasti.
4. Lab: 2FA simple bypass <br>
     Opin, että kaksivaiheisen tunnistautumisen voi ohittaa helposti, jos sivustojen kaksivaiheinen tunnistautuminen on kehnosti toteutettu. Pienillä kepulikonsteilla kirjautuminen sivustoille voi onnistua ihan vain käyttäjätunnuksella ja salasanalla. Lähdin tekemään labraa ja läpäisin sen todella nopeasti ihan vahingossa. Eli tämä sivuston kaksivaiheinen tunnistautuminen oli tehty niin kehnosti, että sen pystyi ohittamaan jopa täysin vahingossa. Vaikeampaa labran suorittaminen oli ohjeita noudattamalla.
5. Lab: Unprotected admin functionality <br>
     Opin, että jos sivustojen toiminnallisuutta ei ole suojattu, pystyy kuka vain esimerkiksi poistamaan minkä tahansa käyttäjä tunnuksen vain löytämällä oikean sivuston. Ei riitä, että sivustot pelkästään piilotetään käyttäjän näkyviltä, jos ne pystyy muuten saavuttamaan. Tätä kutsutaan vertikaalisten käyttöoikeuksien eskaloitumiseksi. Vertikaalisiin oikeuksiin kuuluvat toiminnalliset asiat, kun taas horisontaalisiin käyttöoikeuksiin kuuluvat resurssien käyttöoikeudet. Labra oli aika helppo.
6. Lab: Unprotected admin functionality with unpredictable URL <br>
     Opin, että vaikka admin sivuston nimi on vaikea eikä sitä pysty arvaamaan, voi admin-sivuston löytää koodista, esimerkiksi toiminnallisesta javascript osiosta, jollei sitä suojata tai salata esim cryptaamalla tai käyttämällä avainsanaa oikean linkin nimen sijasta. Koko cybersecurity on alueena minulle niin vieras, että kaikki tällainen yksinkertainenkin on mielenkiintoista ja oppimisen määrä on valtavaa. Vaikeinta labrassa oli oppia käyttämään burp-työkalua ja löytää sieltä haluamansa asiat. 
