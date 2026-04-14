# 📘 DAN 4 - PRODUCT BACKLOG: KREIRANJE I GRANULARNOST

## 📋 Table of Contents

- [PREDAVANJE: Kako kreirati i organizirati Product Backlog](#predavanje-kako-kreirati-i-organizirati-product-backlog)
- [📋 Pregled sadržaja](#-pregled-sadr%C5%BEaja)
- [🎯 Ciljevi učenja](#-ciljevi-u%C4%8Denja)
- [⏰ Raspored predavanja](#-raspored-predavanja)
- [Sekcija 3.1 — Kreiranje Product Backloga](#slajd-1-naslovni-slajd-sekcije-31)
  - [Slajd 1: Naslovni slajd sekcije 3.1](#slajd-1-naslovni-slajd-sekcije-31)
  - [Slajd 2: What is a backlog?](#slajd-2-what-is-a-backlog)
  - [Slajd 3: Components of a backlog item](#slajd-3-components-of-a-backlog-item)
  - [Slajd 4-5: How to create a backlog - Hijerarhija](#slajd-4-5-how-to-create-a-backlog---hijerarhija)
  - [Slajd 6: How to create a backlog - 6 koraka](#slajd-6-how-to-create-a-backlog---6-koraka)
  - [Slajd 7: Common mistakes to avoid](#slajd-7-common-mistakes-to-avoid)
  - [Slajd 8: Grupna vježba - EduTrack scenarij](#slajd-8-grupna-vje%C5%BEba---edutrack-scenarij)
  - [Slajd 9: Grupna vježba - Upute](#slajd-9-grupna-vje%C5%BEba---upute)
  - [Slajd 10-11: Savjeti za kreiranje backloga](#slajd-10-11-savjeti-za-kreiranje-backloga)
- [Sekcija 3.2 — Granularnost Backlog Itema](#slajd-12-naslovni-slajd-sekcije-32)
  - [Slajd 12: Naslovni slajd sekcije 3.2](#slajd-12-naslovni-slajd-sekcije-32)
  - [Slajd 13: Different granularities - Dijagram](#slajd-13-different-granularities---dijagram)
  - [Slajd 14-15: WBS vs RBS](#slajd-14-15-wbs-vs-rbs)
  - [Slajd 16-17: Feature vs Epic](#slajd-16-17-feature-vs-epic)
  - [Slajd 18-19: Epic vs User Story](#slajd-18-19-epic-vs-user-story)
  - [Slajd 20: Task](#slajd-20-task)
  - [Slajd 21: Relations between different cards](#slajd-21-relations-between-different-cards)
  - [Slajd 22: Three good reasons to use RBS](#slajd-22-three-good-reasons-to-use-rbs)
  - [Slajd 23: MoSCoW Method](#slajd-23-moscow-method)
  - [Slajd 24-25: Tips za kreiranje backloga](#slajd-24-25-tips-za-kreiranje-backloga)
  - [Slajd 26: Epic Cards by Screenful (opciono)](#slajd-26-epic-cards-by-screenful-opciono)
- [📝 Recap dana](#-recap-dana-10-min)
- [❓ Pitanja za provjeru razumijevanja](#-pitanja-za-provjeru-razumijevanja)
- [🔄 Backup Aktivnosti](#-backup-aktivnosti)
  - [BA1: User Story Challenge](#backup-aktivnost-1-user-story-challenge-10-min)
  - [BA2: Backlog Refinement simulacija](#backup-aktivnost-2-backlog-refinement-simulacija-15-min)
  - [BA3: MoSCoW debate](#backup-aktivnost-3-moscow-debate-10-min)
  - [BA4: Epic razbijanje](#backup-aktivnost-4-epic-razbijanje-10-min)
  - [BA5: Acceptance Criteria radionica](#backup-aktivnost-5-acceptance-criteria-radionica-15-min)
  - [BA6: Backlog Item Card Design](#backup-aktivnost-6-backlog-item-card-design-10-min)
  - [BA7: Quick Quiz - Kahoot stil](#backup-aktivnost-7-quick-quiz---kahoot-stil-5-min)
- [📚 Dodatni resursi za facilitatora](#-dodatni-resursi-za-facilitatora)

---

## **PREDAVANJE: Kako kreirati i organizirati Product Backlog**
**TRAJANJE:** 9:00-12:30 (3.5 sata, s pauzama)  
**PDF MATERIJAL:** AGILE_3_v2.pdf (Slajdovi 1-26)  
**BROJ STUDENTICA:** 8-30  
**MODUL:** Agile Methodologies - Dan 4

---

## 📋 **PREGLED SADRŽAJA**

**PDF sadrži ukupno ~45 slajdova organiziranih u 4 sekcije:**

**Za Dan 4 - MUST COVER (~180 min):**
- ✅ Slajdovi 1-11: Kako kreirati backlog (Sekcija 3.1)
- ✅ Slajdovi 12-26: Granularnost kartica (Sekcija 3.2)

**Za Dan 5 - Obrađuje se sljedeći dan:**
- ⏸️ Slajdovi 27-40: Capacity planning (Sekcija 3.3)
- ⏸️ Slajdovi 41-45: Praktični workshop (Sekcija 3.4)

---

## 🎯 **CILJEVI UČENJA:**

Na kraju ovog predavanja, studentice će moći:

1. **Definirati** što je Product Backlog i zašto je središnji dokument u Agileu
2. **Nabrojati** 5 ključnih komponenti svake backlog stavke (naslov, opis, kriteriji prihvaćanja, prioritet, procjena)
3. **Napisati** ispravnu User Story koristeći format "Kao [korisnik], želim [funkcionalnost] kako bih [korist]"
4. **Razlikovati** hijerarhiju: Scope of Work → Epic → User Story → Task
5. **Objasniti** razliku između WBS (Waterfall) i RBS (Agile) pristupa
6. **Primijeniti** MoSCoW metodu za prioritizaciju backloga
7. **Kreirati** mini Product Backlog za zadani scenarij

---

# ⏰ **9:00-10:00 - SEKCIJA 1: ŠTO JE BACKLOG I KAKO GA KREIRATI**

---

### **Slajd 1: Naslovni slajd sekcije 3.1**

"Dobro došle na četvrti dan Agile modula!

Prethodna tri dana smo prošle:
- Dan 1: Agile fundamentals - povijest, manifest, MVP, iteracije
- Dan 2: Kanban vs Scrum - usporedba pristupa
- Dan 3: Scrum uloge i rituali - tko radi što u Scrum timu

Danas ulazimo u **najvažniji dokument u Agileu** - **Product Backlog**.

Backlog je lista svega što tim treba napraviti. Bez dobro strukturiranog backloga, tim ne zna na čemu raditi, a Product Owner ne može planirati.

Do kraja dana znat ćete **napisati korisničke priče (User Stories)** i **organizirati backlog** - vještine koje ćete koristiti u svakom IT projektu!"

---

### **Slajd 8: What is a backlog?**

"**Što je Product Backlog?**

Zamislite backlog kao **'master listu želja'** za proizvod - ali ne bilo kakvu listu, već:

📋 **Prioritizirana lista** koja sadrži:
- **Features** (funkcionalnosti) - nove mogućnosti proizvoda
- **Enhancements** (poboljšanja) - nadogradnje postojećeg
- **Bug fixes** (ispravci grešaka) - popravci problema
- **Tasks** (zadaci) - tehnički ili administrativni poslovi

**4 ključne karakteristike backloga:**

1. **Prioritiziran** 
   - Najvažnije stavke su na vrhu
   - Tim uvijek zna što je sljedeće za rad

2. **Vlasništvo Product Ownera**
   - Product Owner odlučuje što je u backlogu
   - Product Owner određuje prioritete
   - Tim može predlagati, PO odlučuje

3. **Živi dokument** 
   - Nikad nije 'završen'
   - Stalno se ažurira novim zahtjevima
   - Stavke se dodaju, brišu, mijenjaju prioritet

4. **Jedini izvor istine**
   - Sve promjene na proizvodu moraju biti u backlogu
   - Ako nije u backlogu, ne radi se na tome
   - Izbjegava se 'radim nešto što je šef rekao u hodniku'

**Primjer iz prakse:**
Zamislite Spotify. Njihov backlog vjerojatno ima tisuće stavki:
- Feature: 'Dodaj AI preporuke na temelju raspoloženja'
- Enhancement: 'Poboljšaj brzinu učitavanja playlista'
- Bug fix: 'Pjesma se prestaje reproducirati nakon 30 min'
- Task: 'Ažuriraj dokumentaciju API-ja'"

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Backlog je kao **popis stvari za kupiti u dućanu**, samo za softver. Zamislite da gradite kuću:
- 'Kupiti cement' - Task
- 'Sagraditi kuhinju' - Feature
- 'Popraviti curenje u kupaonici' - Bug fix
- 'Povećati prozore za više svjetla' - Enhancement

**Česta pitanja:**
Q: "Tko može dodavati stavke u backlog?"
A: "Bilo tko može **predložiti** (developeri, stakeholderi, korisnici), ali samo **Product Owner odlučuje** hoće li to ući u backlog i s kojim prioritetom."

Q: "Koliko stavki obično ima u backlogu?"
A: "Varira - od 20 do nekoliko stotina. Važno je da su gornje stavke detaljne i spremne za rad, donje mogu biti 'rough ideas'."

---

### **Slajd 9: Components of a backlog item**

"Svaka stavka u backlogu mora imati **5 ključnih komponenti**. Ovo je kao **recept** - bez svih sastojaka, nećete dobiti željeni rezultat.

**1. 📝 TITLE (Naslov)**
- Kratak, jasan sažetak
- Maksimalno 5-10 riječi
- Primjer: 'Implementirati login s Google računom'

**2. 📖 DESCRIPTION (Opis)**
- Detaljna objašnjenje ŠTO se treba napraviti
- Obično u formatu **User Story** (objasnit ćemo uskoro)
- Primjer: 'Kao korisnik, želim se prijaviti Google računom kako bih izbjegao pamćenje još jedne lozinke'

**3. ✅ ACCEPTANCE CRITERIA (Kriteriji prihvaćanja)**
- Uvjeti koji moraju biti ispunjeni da bi zadatak bio 'gotov'
- Mjerljivi i provjerljivi
- Primjer:
  - ✅ Gumb 'Prijava s Googleom' vidljiv na login stranici
  - ✅ Korisnik se uspješno prijavi s Google računom
  - ✅ Prikazuje se error poruka ako prijava ne uspije

**4. 🎯 PRIORITY (Prioritet)**
- Redoslijed važnosti
- Obično: Critical, High, Medium, Low
- Ili brojevi: 1, 2, 3, 4, 5
- Primjer: Priority 1 (Critical - moramo imati)

**5. 📊 ESTIMATION (Procjena)**
- Koliko truda je potrebno
- Story Points (1, 2, 3, 5, 8, 13...) ili sati
- Primjer: 5 Story Points (~1 dan rada)

**Primjer kompletne backlog stavke:**

| Komponenta | Sadržaj |
|------------|---------|
| **Title** | Implementirati login s Google računom |
| **Description** | Kao korisnik, želim se prijaviti Google računom kako bih izbjegao pamćenje još jedne lozinke |
| **Acceptance Criteria** | 1. Gumb vidljiv na login stranici 2. Uspješna prijava s Google računom 3. Error handling |
| **Priority** | 1 (Critical) |
| **Estimation** | 5 Story Points |"

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Ovih 5 komponenti osigurava da:
- Svi znaju ŠTO se radi (title, description)
- Svi znaju KADA je gotovo (acceptance criteria)
- Svi znaju KOLIKO JE VAŽNO (priority)
- Svi znaju KOLIKO DUGO TRAJE (estimation)

**Česta pitanja:**
Q: "Moramo li uvijek imati sve 5 komponenti?"
A: "Za stavke na vrhu backloga (koje idu u sljedeći sprint) - DA. Za stavke na dnu (future ideas) - mogu biti manje detaljne."

Q: "Što su Story Points?"
A: "Relativna mjera kompleksnosti. 2 je duplo teže od 1. Nećemo ulaziti u detalje danas, ali nije isto što i sati."

---

### **Slajd 10-11: How to create a backlog - Hijerarhija**

"Backlog ima **hijerarhiju** - od najvećeg do najmanjeg. Zamislite to kao **rusku babuška** - svaka lutka sadrži manju lutku unutra.

**4 RAZINE HIJERARHIJE:**

```
🎯 SCOPE OF WORK (Opseg rada)
    └── 📦 EPIC (Velika cjelina)
            └── 📝 USER STORY (Korisnička priča)
                    └── ✅ TASK (Zadatak)
```

**Primjer - Natječaj za projekt:**

**SCOPE OF WORK:** Prijaviti se na EU natječaj za IT projekt

**EPIC 1:** Tehnička dokumentacija
- USER STORY 1.1: Napisati tehničke specifikacije
  - TASK 1.1.1: Ispuniti Prilog 1 (tehnički opis)
  - TASK 1.1.2: Ispuniti Prilog 2 (metodologija)

**EPIC 2:** Ekonomska dokumentacija  
- USER STORY 2.1: Napraviti budžet projekta
  - TASK 2.1.1: Kreirati Excel simulaciju troškova
  - TASK 2.1.2: Izračunati troškove osoblja

**EPIC 3:** Administrativna dokumentacija
- USER STORY 3.1: Pripremiti pravne dokumente
  - TASK 3.1.1: Prikupiti izvode iz registra
  - TASK 3.1.2: Pripremiti izjave partnera

**Zašto je ovo važno?**

1. **Lakše planiranje** - Velike stvari razbijaš na manje
2. **Lakše praćenje** - Vidiš napredak po epicima
3. **Lakše dodjeljivanje** - Taskovi su dovoljno mali da ih jedna osoba napravi
4. **Lakša komunikacija** - Svi razumiju razinu o kojoj pričaš"

📚 **FACILITATOR NOTES:**

**Analogija za objašnjavanje:**
Zamislite da pripremate vjenčanje:
- **Scope:** Organizirati vjenčanje
- **Epic:** Cateringe, Lokacija, Glazba
- **User Story:** 'Odabrati menu za večeru'
- **Task:** 'Kontaktirati 3 catering firme za ponude'

**Česta pitanja:**
Q: "Moramo li uvijek imati sve 4 razine?"
A: "Ne! Manji projekti mogu imati samo Epics → Tasks. Vi birate razinu detalja koja vam odgovara."

**Vizualno na ploči:**
Nacrtaj piramidu s 4 razine i primjerima za svaku razinu.

---

### **Slajd 12: How to create a backlog - 6 koraka**

"Sada kada znamo strukturu, pogledajmo **6 koraka za kreiranje backloga:**

**KORAK 1: Kreni s ciljevima visoke razine 🎯**
- Pitaj se: 'Koji problem rješavamo?'
- Definiraj viziju proizvoda
- Primjer: 'Učiteljima treba jednostavniji način praćenja prisutnosti'

**KORAK 2: Napiši User Stories 📝**
- Koristi format: **'Kao [korisnik], želim [funkcionalnost] kako bih [korist]'**
- Fokusiraj se na KORISNIKA, ne na tehničko rješenje
- Primjer: 'Kao učitelj, želim jednim klikom označiti sve prisutne kako bih uštedio vrijeme'

**KORAK 3: Razbij Epics na manje Stories 🔨**
- Velike stvari podijeli na manje
- Svaka Story treba biti dovoljno mala za jedan sprint
- Primjer: Epic 'Praćenje prisutnosti' → Story 1: 'Označiti prisutnost', Story 2: 'Generirati izvještaj'

**KORAK 4: Prioritiziraj prema vrijednosti i hitnosti ⚖️**
- Što donosi najviše vrijednosti korisnicima?
- Što je najhitnije?
- Koristi MoSCoW metodu (objasnit ćemo kasnije)

**KORAK 5: Procijeni trud s timom 👥**
- Cijeli tim procjenjuje, ne samo jedna osoba
- Koristi Story Points ili sate
- Konsenzus je ključan

**KORAK 6: Redovito pregledavaj i dorađuj 🔄**
- **Backlog Grooming/Refinement** - sastanak za čišćenje backloga
- Brisanje nebitnog
- Ažuriranje prioriteta
- Dodavanje novih stavki"

📚 **FACILITATOR NOTES:**

**Najvažnije za naglasiti:**
User Story format je KLJUČAN! Ponovite ga nekoliko puta:
> "Kao [TKO], želim [ŠTO] kako bih [ZAŠTO]"

**Česta greška:**
❌ "Napraviti login funkcionalnost" (tehnički opis)
✅ "Kao korisnik, želim se prijaviti kako bih pristupila svom profilu" (User Story)

---

### **Slajd 13: Common mistakes to avoid**

"Prije nego idemo na vježbu, pogledajmo **4 česte greške** koje timovi rade:

**❌ GREŠKA 1: Premaglovite ili previše detaljne priče**
- Premaglovito: 'Poboljšati UX' (što to znači?)
- Previše detaljno: 'Promijeniti boju gumba iz #3366FF u #3377FF' (to je task, ne story)
- ✅ Ispravno: 'Kao korisnik, želim jasniju navigaciju kako bih lakše pronašla što tražim'

**❌ GREŠKA 2: Tim nije uključen u refinement**
- Product Owner sam piše i procjenjuje
- Tim ne razumije što treba napraviti
- ✅ Ispravno: Cijeli tim sudjeluje u Backlog Refinement sastancima

**❌ GREŠKA 3: Zanemariti tehnički dug i bugove**
- Fokus samo na nove feature-e
- Bugovi se gomilaju
- Performanse postaju sve gore
- ✅ Ispravno: Uključi bug fixeve i technical debt u backlog s realnim prioritetima

**❌ GREŠKA 4: Pustiti backlog da nekontrolirano raste**
- Backlog ima 500+ stavki
- Nitko ne zna što je relevantno
- Stare stavke nikad se ne čiste
- ✅ Ispravno: Redovito 'čišćenje' - briši stare/nerelevantne stavke"

📚 **FACILITATOR NOTES:**

**Praktični savjet:**
Zdravi backlog ima obično 50-100 stavki. Ako ima 300+, vjerojatno treba čišćenje.

**Analogija:**
Backlog je kao hladnjak - ako ne čistiš redovito, imat ćeš hranu koja je istekla i ne znaš što imaš.

---

### **Slajd 14: Grupna vježba - EduTrack scenarij**

"Sada ćemo raditi **grupnu vježbu**! Ali prvo da upoznamo scenarij koji ćemo koristiti kroz ostatak Agile modula:

**📚 EDUTRACK SCENARIJ:**

EduTrack je web platforma za upravljanje učionicom koja ima cilj:
- ✅ Pojednostaviti administrativne zadatke za učitelje
- ✅ Poboljšati angažman učenika
- ✅ Pružiti uvid u akademski napredak u stvarnom vremenu

**Funkcionalnosti uključuju:**
- 📋 Praćenje prisutnosti
- 📤 Predaja zadaća
- 📊 Upravljanje ocjenama
- 💬 Komunikacija učitelj-učenik

**Korisnici su:**
- 👩‍🏫 Učitelji
- 👨‍🎓 Učenici
- 👨‍👩‍👧 Roditelji (potencijalno)

Ovaj scenarij ćemo koristiti za sve vježbe danas i sutra!"

---

### **Slajd 15: Grupna vježba - Upute**

**Cilj:** Primijeniti naučeno pisanje User Stories i prioritizaciju

**Upute:**
1. Podijelite se u grupe od 3-4 osobe (2 min)
2. Smislite **5 funkcionalnosti** koje bi učenici ili učitelji mogli trebati (5 min)
3. Napišite **5 User Stories** koristeći format:
   > "Kao [učenik/učitelj], želim [funkcionalnost] kako bih [korist]."
4. Svakoj Story dodijelite:
   - **Prioritet** (1-5, gdje je 1 najviši)
   - **Procjenu** (1-3 poena)
5. Pripremite kratku prezentaciju za grupu (3 min)

**Primjer:**

| User Story | Prioritet | Procjena |
|------------|-----------|----------|
| Kao učenik, želim vidjeti sve svoje zadaće na jednom mjestu kako bih znao što moram napraviti | 1 | 2 |
| Kao učitelj, želim jednim klikom označiti sve prisutne kako bih uštedio vrijeme | 2 | 1 |

📚 **FACILITATOR NOTES:**

**Kako voditi vježbu:**
1. Podijeli papire/post-it-e svakoj grupi
2. Obilazi grupe i pomaži ako netko zapne
3. Nakon 10 min, najavi da imaju još 2 minute
4. Svaka grupa prezentira svoje Stories (po 2 min)

**Ako netko zapne:**
Predloži im da razmisle o:
- Što ih frustrira kod škole/faksa?
- Kako bi tehnologija mogla pomoći?
- Što bi olakšalo život učitelju?

**Tipične pogreške studenata:**
- Pišu task umjesto story: "Napraviti login" → pomozi im preformulirati
- Zaboravljaju "kako bih..." dio → podsjetite zašto je korist važna

---

### **Slajd 16: Savjeti za kreiranje backloga**

"Završimo ovu sekciju s nekoliko **praktičnih savjeta**:

**Na početku će biti teško!** I to je OK.

Česte situacije:

**📦 Kartica je PREVELIKA:**
- Znak: Ostaje u 'Doing' statusu danima
- Rješenje: Razbij na manje kartice

**📋 Kartica je PREMALA:**
- Znak: Prelazi ploču za 15 minuta
- Rješenje: Grupiraj s drugim malim zadacima

**💡 ZLATNO PRAVILO:**
> Kartica nikad ne bi trebala trajati duže od **4 sata** (pola radnog dana)

Zašto?
- Češće vidite napredak
- Motiviraniji ste kad pomičete kartice
- Lakše je identificirati blokere"

---

# ⏰ **10:00-10:15 - PAUZA ☕**

"Odlično! Imamo 15 minuta pauze. Vidimo se u 10:15!"

---

# ⏰ **10:15-11:00 - SEKCIJA 2: GRANULARNOST KARTICA**

---

### **Slajd 17: Naslovni slajd sekcije 3.2**

"Dobrodošle nazad!

U prethodnoj sekciji naučile ste strukturu backloga. Sada idemo dublje u **granularnost** - koliko detaljno trebaju biti vaše kartice.

Ovo je ključno jer:
- Prevelike kartice = nejasan napredak
- Premale kartice = previše administrativnog posla

Pronalaženje prave mjere je vještina koja dolazi s praksom!"

---

### **Slajd 18: Different granularities - Dijagram**

"Pogledajmo dva pristupa organizaciji backloga:

**PRISTUP A: S Epicima (3 razine)**
```
📦 EPICS (narančaste kartice)
    └── 📝 USER STORIES (plave kartice)
            └── ✅ TASKS (žute kartice)
```
- Koristi se za: Veće projekte, dulje trajanje
- Prednost: Jasna hijerarhija, lakši pregled

**PRISTUP B: Bez Epica (2 razine)**
```
📝 USER STORIES (plave kartice)
    └── ✅ TASKS (žute kartice)
```
- Koristi se za: Manje projekte, kraće sprinteve
- Prednost: Jednostavnije, manje overhead-a

**Što završava u 'Backlog' stupcu?**
U oba slučaja, u Backlog stupac idu **Tasks** - najniža razina koja je spremna za izvršenje.

**Vi birate granularnost!**
Ne postoji 'ispravna' razina - ovisi o:
- Veličini projekta
- Veličini tima
- Vašim preferencijama

**Primjer odluke:**
- Projekt od 2 tjedna → Pristup B
- Projekt od 6 mjeseci → Pristup A"

📚 **FACILITATOR NOTES:**

**Vizualno na ploči:**
Nacrtaj oba pristupa jedan pored drugog da studentice vide razliku.

---

### **Slajd 18-19: WBS vs RBS**

"Ovo je **ključna razlika** između Waterfall i Agile razmišljanja!

**WBS - Work Breakdown Structure (Waterfall)**
- Razbijamo projekt prema **POSLU koji se obavlja**
- Fokus na: faze, aktivnosti, korake
- Primjer strukture:
  ```
  Projekt
  └── Faza 1: Planiranje
      ├── Zadatak 1.1: Napisati plan
      └── Zadatak 1.2: Dobiti odobrenje
  └── Faza 2: Razvoj
      ├── Zadatak 2.1: Kodirati modul A
      └── Zadatak 2.2: Kodirati modul B
  ```
- **Problem:** Fokus na rad, ne na vrijednost za korisnika

**RBS - Requirements/Feature Breakdown Structure (Agile)**
- Razbijamo projekt prema **ZAHTJEVIMA / FUNKCIONALNOSTIMA proizvoda**
- Fokus na: što korisnik dobiva, koju vrijednost
- Primjer strukture:
  ```
  Vizija proizvoda
  └── Epic 1: Korisnički račun
      ├── Story 1.1: Registracija
      └── Story 1.2: Prijava
  └── Epic 2: Dashboard
      ├── Story 2.1: Pregled statistike
      └── Story 2.2: Izvoz podataka
  ```
- **Prednost:** Sve je povezano s vrijednošću za korisnika

**Ključna razlika:**
| WBS (Waterfall) | RBS (Agile) |
|-----------------|-------------|
| 'Kodirati modul A' | 'Korisnik može vidjeti svoj profil' |
| Fokus na RAD | Fokus na VRIJEDNOST |
| Tehničko razmišljanje | Korisničko razmišljanje |"

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
WBS je kao popis koraka za gradnju kuće (temelj → zidovi → krov).
RBS je kao popis što korisnik dobiva (kupaonica, spavaća soba, kuhinja).

Oba su validna, ali Agile preferira RBS jer:
- Korisnik razumije jezik
- Lakše je prioritizirati po vrijednosti
- Možete isporučiti djelomičnu funkcionalnost

---

### **Slajd 20-21: Feature vs Epic**

"Čest izvor zabune: **Feature vs Epic**

**FEATURE (Funkcionalnost)**
- Opisuje **rješenje** za određeni zahtjev
- Konkretan, specifičan
- Primjer: 'Login s Google računom'

**EPIC (Epik)**
- Veliki opseg rada koji se razbija na manje priče
- Općenitiji, širi koncept
- Primjer: 'Korisnička autentifikacija' (uključuje: login, registraciju, reset lozinke, 2FA...)

**Jednostavno:**
- Epic = VELIKI, ŠIROKI koncept
- Feature = SPECIFIČNO rješenje (može biti unutar Epica)

U praksi, mnogi timovi koriste ove termine naizmjence - važno je da **vaš tim ima konzistentno razumijevanje**."

---

### **Slajd 21: Epic vs User Story**

"Još jedna važna razlika: **Epic vs User Story**

**EPIC:**
- 📦 VELIK
- Grubozrnat (coarse-grained)
- Skiciran, nije detaljan
- Traje više sprinteva za implementirati

**USER STORY:**
- 📝 MALEN
- Detaljan
- Specifičan
- Može se završiti u jednom sprintu

**Vizualno:**
```
📦 EPIC (jedna velika kartica)
         ↓
📝📝📝 USER STORIES (više manjih kartica)
```

**Primjer:**

**Epic:** Praćenje prisutnosti
- Story 1: Kao učitelj, želim označiti prisutne studente
- Story 2: Kao učitelj, želim vidjeti izvještaj o prisutnosti
- Story 3: Kao administrator, želim dobiti notifikaciju o niskoj prisutnosti
- Story 4: Kao učenik, želim vidjeti svoju prisutnost

**Zašto imati Epic?**
Epic služi za:
- Grupiranje povezanih Stories
- Lakše praćenje napretka velike funkcionalnosti
- Bolju komunikaciju sa stakeholderima

Stakeholder razumije 'Praćenje prisutnosti', ali mu ne trebaju detalji svake Story."

📚 **FACILITATOR NOTES:**

**Česta pitanja:**
Q: "Koliko User Stories ima jedan Epic?"
A: "Nema pravila - može biti 3, može biti 30. Ovisi o kompleksnosti."

---

### **Slajd 20: Task**

"Posljednja razina: **TASK**

Task je **jedinica posla** potrebna za realizaciju User Story.

**Karakteristike taska:**
- ✅ Najmanji, najkonkretniji element
- ✅ Obično jedna osoba može završiti
- ✅ Traje od nekoliko sati do 1 dan
- ✅ Tehnički opis (ovdje je OK biti tehnički)

**Primjer:**

User Story: 'Kao učenik, želim vidjeti svoje ocjene'

Tasks:
- [ ] Dizajnirati UI za prikaz ocjena
- [ ] Kreirati API endpoint za dohvat ocjena
- [ ] Povezati frontend s backendom
- [ ] Napisati unit testove
- [ ] Testirati na mobilnim uređajima

**Tko piše taskove?**
- User Stories piše **Product Owner**
- Taskove kreiraju **developeri/tim** tijekom Sprint Planninga

Developeri najbolje znaju kako tehnički implementirati Story."

---

### **Slajd 21: Relations between different cards**

**Notes iz PDF-a:**
_"[Vizualni dijagram pokazuje: Theme → Epic → Story → Task hijerarhiju]"_

**Što reći studentima (5 min):**

"Pogledajmo **kompletnu hijerarhiju** od vrha do dna:

```
🌐 THEME (Tema)
    │
    ├── 📦 EPIC 1
    │       ├── 📝 Story 1.1
    │       │       ├── ✅ Task 1.1.1
    │       │       ├── ✅ Task 1.1.2
    │       │       └── ✅ Task 1.1.3
    │       └── 📝 Story 1.2
    │               └── ✅ Tasks...
    │
    └── 📦 EPIC 2
            └── 📝 Stories...
```

**THEME (Tema)**
- Najveća razina - strateški cilj
- Primjer: 'Poboljšati korisničko iskustvo'
- Koristi se rijetko, samo za vrlo velike organizacije

**EPIC → STORY → TASK**
- Ovo je najčešća struktura koju ćete koristiti
- Svaka razina je detaljnija od prethodne"

---

# ⏰ **11:00-11:15 - PAUZA ☕**

"Vrijeme za drugu pauzu! Vidimo se u 11:15 za MoSCoW metodu i praktičnu vježbu!"

---

# ⏰ **11:15-12:00 - SEKCIJA 3: MOSCOW + PRAKTIČNA VJEŽBA**

---

### **Slajd 22: Three good reasons to use RBS**

"Zašto koristiti RBS (Agile) pristup? **3 dobra razloga:**

**1. 🗣️ Zajednički jezik**
- Tim i klijent koriste termine koje oba razumiju
- Klijent ne mora znati tehnički žargon
- 'Praćenje prisutnosti' vs 'CRUD operacije za attendance entity'

**2. 🎯 Prioritizacija prema vrijednosti**
- Radimo prvo ono što korisnik najviše treba
- Nije 'što je lakše napraviti' već 'što donosi najveću vrijednost'
- Klijent može sam odlučiti prioritete

**3. 📊 Praćenje stvarne vrijednosti**
- Mjerimo napredak prema isporučenoj vrijednosti
- Nije '50% koda napisano' već 'korisnik sada može pratiti prisutnost'
- Konkretno i mjerljivo"

---

### **Slajd 23: MoSCoW Method**

"**MoSCoW metoda** je jednostavan način prioritizacije backloga. Ime dolazi od prvih slova kategorija:

**🔴 M - MUST HAVE (Mora imati)**
- Projekt NE MOŽE bez toga
- Kritične funkcionalnosti
- Ako ovo ne isporučimo, projekt je neuspješan
- Primjer: Login funkcionalnost za aplikaciju

**🟠 S - SHOULD HAVE (Treba imati)**
- Važno, ali projekt može preživjeti bez toga kratkoročno
- 'Must-have' za budućnost
- Primjer: Reset lozinke putem emaila

**🟡 C - COULD HAVE (Moglo bi imati)**
- 'Nice to have' - bilo bi lijepo
- Male prilagodbe, poboljšanja
- Ako ostane vremena, napravimo
- Primjer: Pamćenje zadnje korištene stranice

**⚪ W - WON'T HAVE (Neće imati)**
- Nećemo raditi **ovaj put**
- Možda u budućnosti
- Jasno komunicira što NE ulazi u opseg
- Primjer: Integracija sa socijalnim mrežama (verzija 2.0)

**Zašto je 'Won't Have' važan?**
- Sprječava 'scope creep' (nekontrolirano širenje projekta)
- Jasna komunikacija sa stakeholderima
- Nije 'nikad', već 'ne sada'

**Tipična distribucija:**
- Must Have: ~60% (projekta)
- Should Have: ~20%
- Could Have: ~20%
- Won't Have: ostalo za kasnije"

📚 **FACILITATOR NOTES:**

**Praktični savjet:**
Kad radite s klijentom, MoSCoW je odličan jer:
- Klijent se osjeća uključen u odluke
- Sprječava neugodna iznenađenja ('Mislili smo da to ulazi')
- Dokumentira dogovore

**Česta greška:**
Klijent želi SVE kao 'Must Have'. Objasni da ako je sve kritično, ništa nije kritično.

---

### **Slajd 24-25: Tips za kreiranje backloga**

"Još nekoliko savjeta za praksu:

**💡 SAVJET 1: Kreni od najvećeg prema najmanjem**
- Prvo identificiraj Epice
- Zatim razbij na Stories
- Tasks definiraj tek kad Story dođe u sprint
- Ne troši vrijeme na detalje za nešto što se neće raditi mjesecima

**💡 SAVJET 2: Ne tražite detalje prerano**
- Početne Stories mogu biti 'rough'
- Detaliziraj samo ono što se radi uskoro
- Klijent ne mora odlučiti sve danas

**💡 SAVJET 3: Koristi labele za razlikovanje kartica**
- U Trellu, Jiri i sl. možete koristiti boje/labele:
  - 🔴 Bug
  - 🟢 Feature
  - 🟡 Technical Debt
  - 🔵 Research
- Vizualno odmah vidite što je što"

---

### **Slajd 26: Epic Cards by Screenful (opciono)**

"Kratko o alatima - postoje dodatci (power-ups) za Trello i druge alate koji pomažu s organizacijom:

**Screenful za Trello:**
- Definira koje liste sadrže Epice
- Povezuje Tasks s Epicima
- Pokazuje napredak po svakom Epicu

Nećemo ulaziti u detalje, ali znajte da **alati postoje** koji olakšavaju upravljanje većim backlozima.

**Za vašu praksu:**
Trello Basic je dovoljan za učenje. Napredne dodatke istražite kad vam zatreba."

---

✏️ **PRAKTIČNA VJEŽBA: MoSCoW prioritizacija (15 min)**

**Cilj:** Primijeniti MoSCoW metodu na postojeći backlog

**Upute:**
1. Vratite se u svoje grupe od prije
2. Uzmite 5 User Stories koje ste napisali za EduTrack
3. Primijenite MoSCoW metodu:
   - Označite svaku kao M, S, C ili W
4. Budite realni - ne može sve biti MUST HAVE!
5. Pripremite obrazloženje za svoje odluke

**Primjer:**

| User Story | MoSCoW | Obrazloženje |
|------------|--------|--------------|
| Login funkcionalnost | M | Bez toga aplikacija nema smisla |
| Reset lozinke | S | Važno, ali može čekati v1.1 |
| Tamni način prikaza | C | Nice to have |
| VR classroom | W | Preambiciozno za sada |

📚 **FACILITATOR NOTES:**

**Kako voditi:**
1. Obilazi grupe, izazivaj njihove odluke: "Zašto je to Must Have?"
2. Potakni raspravu unutar grupa
3. Na kraju, jedna grupa prezentira (3 min)

**Česta situacija:**
Studentice žele sve kao 'Must Have'. Pitaj: "Ako imate samo 2 tjedna i možete napraviti samo 2 stvari, koje birate?"

---

# ⏰ **12:00-12:30 - SEKCIJA 4: GRUPNA VJEŽBA + RECAP**

---

✏️ **ZAVRŠNA GRUPNA VJEŽBA: Kompletan mini-backlog (15 min)**

**Cilj:** Kreirati strukturiran backlog s Epic → Story → Task hijerarhijom

**Upute:**
1. Ostanite u grupama
2. Odaberite **JEDAN Epic** za EduTrack (npr. 'Praćenje prisutnosti')
3. Definirajte:
   - 2-3 User Stories za taj Epic
   - 2-3 Taska za JEDNU Story
4. Prikažite na velikom papiru ili ploči

**Format:**

```
📦 EPIC: [Naziv]

📝 STORY 1: Kao [korisnik], želim [funkcionalnost] kako bih [korist]
   └── ✅ Task 1.1: [Opis]
   └── ✅ Task 1.2: [Opis]
   
📝 STORY 2: Kao [korisnik], želim [funkcionalnost] kako bih [korist]

📝 STORY 3: Kao [korisnik], želim [funkcionalnost] kako bih [korist]
```

📚 **FACILITATOR NOTES:**

**Pripremi unaprijed:**
- Veliki papiri (flipchart) ili whiteboard prostor za svaku grupu
- Markeri u boji
- Post-it-i ako ih imaš

---

## 📝 **RECAP DANA (10 min)**

**Što reći studentima:**

"Prije nego završimo, ponovimo ključne točke današnjeg dana:

**1. Product Backlog je:**
- Prioritizirana lista svega za napraviti
- Živi dokument - stalno se mijenja
- Vlasništvo Product Ownera

**2. Svaka backlog stavka ima 5 komponenti:**
- Title, Description, Acceptance Criteria, Priority, Estimation

**3. User Story format:**
> 'Kao [korisnik], želim [funkcionalnost] kako bih [korist]'

**4. Hijerarhija:**
- Scope → Epic → User Story → Task

**5. WBS vs RBS:**
- Waterfall: fokus na RAD
- Agile: fokus na VRIJEDNOST za korisnika

**6. MoSCoW prioritizacija:**
- Must Have, Should Have, Could Have, Won't Have

**Za sljedeći put:**
Sutra ćemo naučiti **Capacity Planning** - kako planirati rad prema kapacitetu tima, i radiće praktični **workshop** gdje ćete izgraditi kompletnu Agile ploču!"

---

## ❓ **PITANJA ZA PROVJERU RAZUMIJEVANJA**

**Osnovni level:**
1. Što je Product Backlog?
2. Tko je vlasnik backloga?
3. Koje su 5 komponenti backlog stavke?

**Srednji level:**
4. Koja je razlika između Epica i User Story?
5. Što znači 'Should Have' u MoSCoW metodi?
6. Zašto je RBS bolji od WBS u Agileu?

**Viši level:**
7. Kako bi prioritizirali funkcionalnosti za aplikaciju za dostavu hrane?
8. Kada bi koristili 3-razinsku vs 2-razinsku hijerarhiju backloga?

---

## 🔄 **BACKUP AKTIVNOSTI**

### **BACKUP AKTIVNOST 1: User Story Challenge (10 min)**

**Cilj:** Vježbanje pisanja User Stories iz loših primjera

**Upute:**
1. Podijeli papire s 'lošim' primjerima:
   - "Napraviti login"
   - "Poboljšati performanse"
   - "Dodati search"
   - "Implementirati bazu podataka"
   - "Fixati bugove"
2. Studentice preformuliraju u pravilne User Stories
3. Usporedite rješenja

**Primjer rješenja:**
- "Napraviti login" → "Kao korisnik, želim se prijaviti emailom i lozinkom kako bih pristupila svom profilu"

📚 **FACILITATOR NOTES:**
Ovo je izvrsno za one koji i dalje miješaju tehnički opis s User Story.

---

### **BACKUP AKTIVNOST 2: Backlog Refinement simulacija (15 min)**

**Cilj:** Simulirati Backlog Grooming sastanak

**Upute:**
1. Daj grupi 'zastarjeli' backlog s 15 stavki
2. Imaju 10 min da:
   - Izbrišu irelevantne stavke
   - Ažuriraju prioritete
   - Identificiraju stavke koje treba razbiti
3. Prezentiraju promjene i obrazlože

📚 **FACILITATOR NOTES:**
Pripremi primjer backloga unaprijed s očitim problemima (duplikati, stare stavke, preširoki opisi).

---

### **BACKUP AKTIVNOST 3: MoSCoW debate (10 min)**

**Cilj:** Razviti sposobnost argumentiranja prioriteta

**Upute:**
1. Podijeli grupu na 4 tima (M, S, C, W)
2. Daj jednu funkcionalnost: "Tamni način prikaza za EduTrack"
3. Svaki tim mora argumentirati zašto je to NJIHOVA kategorija
4. Glasanje na kraju

📚 **FACILITATOR NOTES:**
Nema ispravnog odgovora - poanta je vidjeti kako se argumenti mogu izgraditi za bilo koju kategoriju.

---

### **BACKUP AKTIVNOST 4: Epic razbijanje (10 min)**

**Cilj:** Vježbanje razbijanja velikog Epica na Stories

**Upute:**
1. Daj Epic: "Integracija s Google Classroomom"
2. Grupe imaju 5 min da napišu što više Stories
3. Pobjeđuje grupa s najviše validnih Stories

📚 **FACILITATOR NOTES:**
Potakni kreativnost - neka razmišljaju iz perspektive svih korisnika (učenik, učitelj, admin).

---

### **BACKUP AKTIVNOST 5: Acceptance Criteria radionica (15 min)**

**Cilj:** Vježbanje pisanja kriterija prihvaćanja

**Upute:**
1. Daj User Story: "Kao učenik, želim vidjeti svoje ocjene"
2. Grupe pišu 5-7 Acceptance Criteria
3. Usporedba - koje su najvažnije?

**Primjer:**
- ✅ Korisnik može vidjeti sve predmete
- ✅ Ocjene su sortirane od najnovije
- ✅ Prosječna ocjena je prikazana
- ✅ Korisnik može filtrirati po predmetu

---

### **BACKUP AKTIVNOST 6: Backlog Item Card Design (10 min)**

**Cilj:** Kreirati vizualni template za backlog karticu

**Upute:**
1. Svaka osoba dizajnira template kartice na papiru
2. Uključuje svih 5 komponenti
3. Glasanje za najbolji dizajn
4. Koristi se kao template za buduće vježbe

📚 **FACILITATOR NOTES:**
Može se kasnije digitalizirati u Canvi ili Figmi.

---

### **BACKUP AKTIVNOST 7: Quick Quiz - Kahoot stil (5 min)**

**Cilj:** Provjera znanja kroz igru

**Pitanja:**
1. Tko je vlasnik Product Backloga? (Product Owner)
2. Što znači 'M' u MoSCoW? (Must Have)
3. Što je veće - Epic ili User Story? (Epic)
4. Koliko dugo bi Task trebao trajati? (max 4h)
5. Što je RBS? (Requirements Breakdown Structure)

📚 **FACILITATOR NOTES:**
Ako imaš pristup internetu, koristi stvarni Kahoot. Ako ne, napravi 'podizanje ruku' kviz.

---

## 📚 **DODATNI RESURSI ZA FACILITATORA**

**Prije predavanja, pregledaj:**
1. [What is a Product Backlog - Scrum.org](https://www.scrum.org/resources/what-is-a-product-backlog)
2. [User Story Examples - Mountain Goat Software](https://www.mountaingoatsoftware.com/agile/user-stories)
3. [MoSCoW Method Explained - ProductPlan](https://www.productplan.com/glossary/moscow-prioritization/)

**Za tvoje dalje učenje:**
- [Atlassian Agile Coach - Epics, Stories, Tasks](https://www.atlassian.com/agile/project-management/epics-stories-themes)
- [Trello - How to use for Agile](https://trello.com/guide/agile)

**Pripremna lista:**
- [ ] Testiraj Trello/Miro pristup ako radite digitalno
- [ ] Pripremi velike papire za grupne vježbe
- [ ] Printaj primjere loših User Stories za backup aktivnost
- [ ] Provjeri internet vezu za eventualni Kahoot

---

**KRAJ SINOPSISA - DAN 4** ✅
