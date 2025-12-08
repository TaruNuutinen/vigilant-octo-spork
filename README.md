# Cybersecurity and data privacy

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
| 10.11.2025 | 0.5 h | Loihde tietoturvakatsaus | Independent Learning |
| 11.11.2025 | 0.5 h | Lecture 3 | Checking out material |
| 12.11.2025 | 1.75 h | Lecture 3 | Learning |
| 21.11.2025 | 6 h | Booking System | creat enviroment and pen testing |
| 22.11.2025 | 5 h | Booking System | writing raport |
| 24.11.2025 | 1.75 h | Booking System | finishing raports and task |
| 30.11.2025 | 2 h | Introduction to network; Network security fundamentals | learning |
| 2.12.2025 | 7,5 h | Booking System, part 2 | Lecture 4, pen test, the task done |
| 8.12.2025 | 6 h | Lecture 4, Booking System phase 2 | Learning, created enviroment, zap attack and report, hack passwords, writing report |


#2 Booking System phase 2

Crack at least 5 passwords using any methods you prefer.
  - whatsupdoc@looneytunes.tv, carrots123
  - doh@springfieldpower.net, donuts4life
  - darkknight@gothamwatch.org, iamvengeance
  - iamyourfather@deathstar.gov, darkside42
  - whysoserious@gothamchaos.net,  chaos123!
Create a report of your cracking process by answering directly in the answer box (or git).
Rekisteröidyin nettisivuille. Katsoin databasesta booking_users tietokannan. Löysin salasanani cryptattuna. Selvitin, että cryptaukseen on käytetty MD5 metodia. Löysin googlesta sivuston https://md5decrypt.net/en/ johon voi syöttää cryptatun salasanan ja sen saa decryptattuna takaisin. Tämä toimi helposti ja nopeasti. Kokeilin database listalta 5 eri käyttäjätunnusta ja salasanaa ja pääsin kaikilla kirjautumaan sisään. Tehtävä tuntui ihan liian helpolta, onneksi salasanat olivat hauskoja.
Voin todistaa, että kirjautuminen onnistui booking_login_logs tietokannasta ottamallani näyttökuvalla.
<img width="919" height="344" alt="Näyttökuva 2025-12-09 011658" src="https://github.com/user-attachments/assets/fd3e5562-4637-46ed-a807-9f8ed2f5a4ef" />

You may use any methods and tools you like.
For each cracked password, provide a short written explanation and a screenshot.
In your report, also answer the following questions:

What is the main difference between Dictionary and Non-Dictionary attacks?
What advantage does an attacker gain by having access to the system’s database that reveals the users and the password hashes?
What concrete security benefits are achieved by using longer passwords instead of shorter ones?
