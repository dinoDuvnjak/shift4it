# 📘 DAN 5 - CAPACITY PLANNING I PRAKTIČNI WORKSHOP

## **PREDAVANJE: Planiranje kapaciteta i izgradnja Agile ploče**
**TRAJANJE:** 9:00-12:30 (3.5 sata, s pauzama)  
**PDF MATERIJAL:** AGILE_3_v2.pdf (Slajdovi 27-45)  
**BROJ STUDENTICA:** 8-30  
**MODUL:** Agile Methodologies - Dan 5 (završni dan modula)

---

## 📋 **PREGLED SADRŽAJA**

**PDF slajdovi za ovaj dan:**

**PRIORITET 1 - MUST COVER (~180 min):**
- ✅ Slajdovi 27-40: Capacity Planning (Sekcija 3.3)
- ✅ Slajdovi 41-45: Praktični workshop - Izgradnja ploče (Sekcija 3.4)

---

## 🎯 **CILJEVI UČENJA:**

Na kraju ovog predavanja, studentice će moći:

1. **Objasniti** zašto je capacity planning ključan za uspješan sprint
2. **Primijeniti** tehniku težinskog bodovanja za prioritizaciju
3. **Izračunati** Focus Factor i efektivni radni kapacitet tima
4. **Definirati** Release Plan na temelju kapaciteta i prioriteta
5. **Kreirati** funkcionalnu Agile ploču (u Trellu, Miru ili fizički)
6. **Napisati** kvalitetne kartice s ispravnom strukturom
7. **Demonstrirati** kompletno razumijevanje Agile koncepta kroz praktični rad

---

## ⏰ **RASPORED PREDAVANJA:**

```
9:00-10:00   SEKCIJA 1: Capacity Planning - Teorija (60 min)
10:00-10:15  PAUZA ☕
10:15-11:00  SEKCIJA 2: Focus Factor i Release Plan (45 min)
11:00-11:15  PAUZA ☕
11:15-12:15  SEKCIJA 3: Praktični Workshop (60 min)
12:15-12:30  Recap modula + Završne riječi (15 min)
```
**Ukupno efektivno vrijeme: 180 min (3h)**

---

# ⏰ **9:00-10:00 - SEKCIJA 1: CAPACITY PLANNING - TEORIJA**

---

### **Slajd 27: Naslovni slajd sekcije 3.3**

**Notes iz PDF-a:**
_"3.3 How to manage capacity planning (2.5 hours)"_

**Što reći studentima (3 min):**

"Dobro došle na posljednji dan Agile modula!

Jučer smo naučile kako kreirati backlog - pisati User Stories, razumjeti hijerarhiju, prioritizirati s MoSCoW metodom.

Danas odgovaramo na ključno pitanje:
> **Koliko posla tim može realno napraviti u jednom Sprintu?**

Ovo se zove **Capacity Planning** (planiranje kapaciteta) i bez njega:
- Timovi preuzimaju previše posla
- Rokovi se probijaju
- Ljudi izgaraju

Na kraju dana ćete izgraditi vlastitu Agile ploču i **demonstrirati sve što ste naučile** kroz praktični workshop!"

---

### **Slajd 28: Managing capacity planning - Problem**

**Notes iz PDF-a:**
_"Our normal customer demands the maximum in the shortest possible time, with the twofold result: Capacity saturation, Complex releases. Factors that very often result in: Frustrated teams, Increasing time to market."_

**Što reći studentima (8 min):**

"Pogledajmo **realnost IT projekata**:

**Tipični zahtjev klijenta:**
> 'Trebamo SVE funkcionalnosti, do kraja mjeseca, i to mora biti savršeno!'

**Što se dogodi kad tim pristane?**

**Rezultat #1: Zasićenje kapaciteta**
- Tim preuzme više nego što može
- Svi rade prekovremeno
- Kvaliteta pada

**Rezultat #2: Kompleksna isporuka**
- Previše funkcionalnosti odjednom
- Teško testirati
- Veći rizik od bugova

**Posljedice:**

😤 **Frustrirani timovi**
- 'Nikad ne stignemo'
- 'Stalno se rokovi probijaju'
- Burnout, fluktuacija

📉 **Dulje vrijeme do tržišta (Time to Market)**
- Paradoksalno, želimo sve brže → dobijemo sve sporije
- Jer se vraćamo popravljati greške

**Agile rješenje:**
Umjesto da kažemo 'DA' na sve, **planiramo realno** prema kapacitetu tima."

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Ovo je kao da netko kaže 'Napuni mi kamion s 10 tona robe, a kamion može nositi 5 tona'. Možeš probati, ali nešto će pući.

**Pitanje za studentice:**
"Je li vam se dogodilo da ste preuzele previše obaveza na faksu i onda niste stigle ništa kvalitetno?"

---

### **Slajd 29: Što napraviti? Davanje težine ishodima**

**Notes iz PDF-a:**
_"1. Giving weight to outcomes. 2. Define a release plan."_

**Što reći studentima (3 min):**

"Rješenje ima **2 koraka:**

**KORAK 1: Daj težinu ishodima (outcomes)**
- Procijeni koliko je svaka funkcionalnost važna
- Procijeni koliko truda zahtijeva
- Usporedi vrijednost i trud

**KORAK 2: Definiraj Release Plan**
- Na temelju kapaciteta tima
- Odluči što ide u koji sprint
- Komuniciraj realna očekivanja

Sada ćemo detaljno proći oba koraka!"

---

### **Slajd 30-31: Giving weight to outcomes - Vrijednost**

**Notes iz PDF-a:**
_"How important are features (CARDs) to each other? Which of them are most likely to achieve the desired OUTCOME value?"_

**Što reći studentima (10 min):**

"Prvi korak: **procijeni VRIJEDNOST** svake funkcionalnosti.

**Pitanja za postavljanje:**
1. Koliko su funkcionalnosti važne **jedna u odnosu na drugu**?
2. Koja će najvjerojatnije postići željeni **ishod**?

**Tehnika: Relativno bodovanje**

Umjesto da kažemo 'ovo je važno', uspoređujemo kartice međusobno:

```
🟢 HIGHEST VALUE    🟡 HIGH VALUE    🔵 VALUABLE
(najvrijednije)     (visoka vrij.)   (vrijedno)
```

**Primjer za EduTrack:**

| Funkcionalnost | Kategorija |
|---------------|------------|
| Login sustav | 🟢 Highest Value (bez toga ništa ne radi) |
| Praćenje prisutnosti | 🟢 Highest Value (core funkcionalnost) |
| Izvještaji za roditelje | 🟡 High Value (važno, ali ne kritično) |
| Tamni način prikaza | 🔵 Valuable (nice to have) |

**Zašto relativno?**
- Lakše je reći 'A je važnije od B' nego 'A vrijedi 73 bodova'
- Tim se lakše složi
- Brža je procjena"

📚 **FACILITATOR NOTES:**

**Vizualno na ploči:**
Nacrtaj 3 stupca i stavi primjere kartica u svaki.

---

### **Slajd 32-33: Giving weight to outcomes - Težina**

**Notes iz PDF-a:**
_"How much do the most important features weigh individually? Note: let the team make the estimates!"_

**Što reći studentima (10 min):**

"Drugi dio: **procijeni TEŽINU** (trud) svake funkcionalnosti.

**Fibonacci skala:**
Agile timovi često koriste Fibonacci brojeve za procjenu:
```
1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 100...
```

**Zašto Fibonacci?**
- Razmaci se povećavaju
- Izbjegava lažnu preciznost
- 'Ovo je 5, ono je 8' je lakše nego '7 ili 8?'

**Primjer procjene:**

| Funkcionalnost | Story Points |
|---------------|--------------|
| Login sustav | 13 |
| Praćenje prisutnosti | 21 |
| Izvještaji za roditelje | 8 |
| Tamni način prikaza | 3 |

**⚠️ KLJUČNO PRAVILO:**
> Procjene radi **TIM**, ne menadžer ili Product Owner!

Zašto?
- Tim zna koliko truda zahtijeva implementacija
- Tim se obvezuje na ono što je procijenio
- Povećava ownership i odgovornost

**Tipična greška:**
❌ Šef kaže: 'To možete napraviti za 2 dana'
✅ Tim kaže: 'Procjenjujemo to na 8 Story Points, što je oko 3 dana'"

📚 **FACILITATOR NOTES:**

**Česta pitanja:**
Q: "Kako znamo koliko je 1 Story Point u satima?"
A: "Varira po timu. Neki timovi definiraju 1 SP = 1 sat idealne rad, drugi 1 SP = pola dana. Važna je konzistentnost unutar tima."

---

### **Slajd 34: Giving weight to outcomes - Kapacitet**

**Notes iz PDF-a:**
_"What is the actual production capacity available?"_

**Što reći studentima (8 min):**

"Sada dolazimo do **ključnog pitanja:**
> Koliki je STVARNI kapacitet tima?

**Vizualizacija:**

Zamislite da imate sve kartice poredane po vrijednosti (najvrijednije lijevo):

```
[100] [40] [20] [13] [8] [5] [3] [2] [1]  ← Story Points
  │     │    │    │   │   │   │   │   │
  ████████████████░░░░░░░░░░░░░░░░░░░░░  ← KAPACITET
                  │
                  └── Ovdje se zaustavlja kapacitet!
```

**Što nam ovo govori?**
- Tim može napraviti kartice s ukupno **~175 Story Points** u sprintu
- To znači: funkcionalnosti s vrijednosti 100, 40, 20 i 13 points
- Ostalo (8, 5, 3, 2, 1) mora čekati sljedeći sprint

**Princip:**
> Radi prvo ono što ima NAJVIŠE VRIJEDNOSTI dok ne potrošiš kapacitet!

Ovo je core Agile principa - **maksimiziranje isporučene vrijednosti**."

📚 **FACILITATOR NOTES:**

**Vizualno:**
Nacrtaj horizontalnu liniju 'kapaciteta' i pokaži gdje se presijeca s karticama.

---

### **Slajd 35: Pareto dijagram**

**Notes iz PDF-a:**
_"And with a Pareto diagram [representation of the degree of influence of certain variables on a phenomenon] we get that..."_

**Što reći studentima (5 min):**

"Možda ste čuli za **Pareto princip** (80/20 pravilo)?

**U kontekstu backloga:**
- ~20% funkcionalnosti donosi ~80% vrijednosti
- Fokusiraj se na tih 20%!

**Pareto dijagram pokazuje:**
- Visoki stupci lijevo = visoka vrijednost
- Niski stupci desno = niska vrijednost
- Crveni krug označava 'sweet spot' - najviše vrijednosti za uloženi trud

**Praktična implikacija:**
Ako napraviš samo prvih nekoliko funkcionalnosti (najviše vrijednosti), korisnik će biti 80% zadovoljan. Ostalo je 'cherry on top'."

---

# ⏰ **10:00-10:15 - PAUZA ☕**

"Odlično! Imamo 15 minuta pauze. Do sada ste naučile zašto je capacity planning važan i kako procijeniti vrijednost/težinu. Nakon pauze ćemo izračunati Focus Factor i napraviti Release Plan!"

---

# ⏰ **10:15-11:00 - SEKCIJA 2: FOCUS FACTOR I RELEASE PLAN**

---

### **Slajd 36: Establishing a release plan**

**Notes iz PDF-a:**
_"Release Plan: set of activities aimed at transforming requests into tested and functioning outputs. How to proportion the backlog according to the team's production capacity? Capacity planning: optimising productivity by managing available resources and skills needed for the Sprint."_

**Što reći studentima (5 min):**

"Sada kada znamo vrijednosti i težine, idemo na **Release Plan**.

**Što je Release Plan?**
Set aktivnosti za transformaciju zahtjeva u **testirane i funkcionalne** isporuke.

**Ključno pitanje:**
> Kako proporcionirati backlog prema kapacitetu tima?

**Capacity Planning je:**
Optimizacija produktivnosti kroz upravljanje:
- Dostupnim resursima (ljudima, vremenom)
- Vještinama potrebnim za Sprint

Cilj: **Realna planiranje** umjesto wishful thinking."

---

### **Slajd 37: Release plan - Primjer kalkulacije**

**Notes iz PDF-a:**
_"Example: a team of 6 people is asked to complete a series of activities estimated at 200 hours in 5 days. 1. Activity weight: 200h 2. Sprint duration: 5 days 3. Duration of working day: 8h 4. Team size: 6 persons. Total working capacity: 5*8*6 = 240h. But why then do we often end up in overload?"_

**Što reći studentima (10 min):**

"Pogledajmo **konkretan primjer:**

**Situacija:**
- Tim od 6 osoba
- Procijenjeni posao: 200 sati
- Sprint traje: 5 dana
- Radni dan: 8 sati

**Naivna kalkulacija:**
```
Ukupni kapacitet = 5 dana × 8 sati × 6 osoba = 240 sati
```

Posao je 200 sati, kapacitet je 240 sati → **Super! Ima viška!** 🎉

**ALI... zašto onda timovi stalno kasne?**

Jer ova kalkulacija ignorira REALNOST!

**Faktori koji smanjuju kapacitet:**

1. **Neujednačeni timovi**
   - Netko je junior, netko senior
   - Različite vještine
   - Bolovanja, godišnji

2. **Više projekata istovremeno**
   - 'Samo brzo pogledaj ovo za drugi projekt...'
   - Context switching gubi vrijeme

3. **Bottlenecks (uska grla)**
   - Čekanje na code review
   - Čekanje na testiranje
   - Čekanje na odobrenje

4. **Emergentne aktivnosti**
   - Hitni bugovi u produkciji
   - Neplanirani sastanci
   - 'Možeš li brzo pomoći?'"

📚 **FACILITATOR NOTES:**

**Analogija:**
Ako auto može ići 200 km/h, ne znači da će prosječna brzina putovanja biti 200 km/h. Imamo semafore, gužve, pauze za gorivo...

**Pitanje za studentice:**
"Koliko vremena zapravo radite kad imate 8-satni radni dan? Računajući pauze, mailove, sastanke..."

---

### **Slajd 38-39: Rješenja za faktore koji limitiraju**

**Notes iz PDF-a:**
_"So what to do? 1. Define the team configuration in advance. 2. Limiting the number of open contexts. 3. Foresee validation times. 4. Establishing a Focus Factor."_

**Što reći studentima (8 min):**

"Kako se nositi s ovim faktorima?

**RJEŠENJE 1: Definiraj konfiguraciju tima unaprijed**
- Tko je dostupan ovaj sprint?
- Ima li tko godišnji/bolovanje?
- Koje su vještine potrebne?

**RJEŠENJE 2: Ograniči broj otvorenih konteksta**
- Fokus na JEDAN projekt
- Minimizirati multitasking
- WIP limiti (koliko kartica može biti 'In Progress')

**RJEŠENJE 3: Predvidi vremena validacije**
- Uračunaj vrijeme za code review
- Uračunaj vrijeme za QA testiranje
- Uračunaj vrijeme za stakeholder feedback

**RJEŠENJE 4: Uspostavi Focus Factor**
- Realna procjena koliko od teoretskog kapaciteta se može iskoristiti
- Ovo ćemo sad detaljno proći!"

---

### **Slajd 40: Focus Factor (FF)**

**Notes iz PDF-a:**
_"Focus Factor (FF): estimation of how focused the team is. Average = 70%. A lower FF may mean that the team anticipates many disturbing factors or assumes that they have made over-optimistic estimates."_

**Što reći studentima (12 min):**

"**Focus Factor** je ključni koncept za realno planiranje!

**Što je Focus Factor (FF)?**
Procjena koliko je tim **zapravo fokusiran** na posao.

**Prosječan FF = 70%**

To znači: Od 8 sati radnog dana, samo ~5.6 sati je produktivni rad.

**Zašto nije 100%?**
- Sastanci
- Emailovi i Slack
- Pauze
- Pomoć kolegama
- Administrativni poslovi
- Context switching

**Formula:**
```
Efektivni kapacitet = Teoretski kapacitet × Focus Factor
```

**Primjer:**
```
Teoretski kapacitet = 240 sati
Focus Factor = 0.70 (70%)
Efektivni kapacitet = 240 × 0.70 = 168 sati
```

**Sada vidimo problem!**
- Posao: 200 sati
- Efektivni kapacitet: 168 sati
- **Nedostaje 32 sata!** 😱

**Kako izračunati FF za svoj tim?**

```
FF = Efektivna brzina / Dostupni čovjek-dani
```

**Efektivna brzina** = zbroj težina svih dovršenih Stories u zadnjem sprintu

**Primjer:**
- Zadnji sprint: tim je završio Stories ukupno 85 Story Points
- Dostupno je bilo 120 čovjek-sati
- FF = 85/120 = 0.71 (71%)

**SAVJET:** Koristi prosijek zadnjih 3 sprinta za točniju procjenu."

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Focus Factor je kao 'koeficijent realnosti'. Uzima u obzir sve te 'nevidljive' aktivnosti koje jedu vrijeme.

**Česta pitanja:**
Q: "Može li FF biti veći od 100%?"
A: "Teoretski da, ako su procjene bile pesimistične. Ali ako je stalno >100%, tim podcjenjuje kompleksnost."

Q: "Što ako nemamo podatke za prošle sprinte?"
A: "Koristi industrisjki prosjek 70% i prilagodi nakon prvog sprinta."

---

✏️ **VJEŽBA: Izračunaj efektivni kapacitet (10 min)**

**Zadatak:**

Koristeći podatke iz PDF-a, izračunaj efektivni radni kapacitet:

```
- Težina aktivnosti: 200h
- Trajanje sprinta: 5 dana
- Trajanje radnog dana: 8h
- Veličina tima: 6 osoba
- Focus Factor: 0.7
```

**Pitanja:**
1. Koji je teoretski kapacitet?
2. Koji je efektivni kapacitet?
3. Može li tim završiti posao od 200h?

**Rješenje:**
```
1. Teoretski kapacitet = 5 × 8 × 6 = 240h
2. Efektivni kapacitet = 240 × 0.7 = 168h
3. NE! Nedostaje 32h (200 - 168 = 32)
```

**Što napraviti?**
- Smanjiti opseg posla na 168h
- Produljiti sprint
- Dodati resurse (ne preporučuje se kasno u projektu)

📚 **FACILITATOR NOTES:**
Neka studentice same izračunaju, onda prođi rješenje. Ovo je fundamentalna vještina!

---

### **Slajd 41: What have we learnt?**

**Notes iz PDF-a:**
_"1. Renegotiating EFFORT based on SHARED UNDERSTANDING of VALUE (outcome-oriented) and according to PRODUCTIVITY of the TEAM. 2. Assess EFFECTIVE IMPACT of any ADDITIONAL RESOURCES. 3. Give PRIORITY to the backlog through a COHERENT RELEASE PLAN. 4. Understand if and when to add any EMERGING FEATURES to the backlog."_

**Što reći studentima (5 min):**

"Prije pauze, sumirajmo **4 ključna naučena principa:**

**1. Pregovaranje o trudu na temelju DIJELJENOG RAZUMIJEVANJA VRIJEDNOSTI**
- Tim i klijent se slažu što je najvažnije
- Fokus na ishode (outcomes), ne aktivnosti

**2. Procijeni EFEKTIVNI UTJECAJ dodatnih resursa**
- 'Dodaj više ljudi' nije magično rješenje
- Brooks's Law: 'Adding people to a late project makes it later'

**3. Daj PRIORITET backlogu kroz KOHERENTAN RELEASE PLAN**
- Logičan slijed isporuka
- Ovisnosti su uzete u obzir

**4. Razumij KADA i AKO dodati EMERGENTNE FUNKCIONALNOSTI**
- Novi zahtjevi će se pojaviti
- Imaj proces za evaluaciju: ide li u ovaj sprint ili čeka?"

---

# ⏰ **11:00-11:15 - PAUZA ☕**

"Odlična pauza! Nakon pauze slijedi **praktični workshop** - gradite vlastitu Agile ploču!"

---

# ⏰ **11:15-12:15 - SEKCIJA 3: PRAKTIČNI WORKSHOP**

---

### **Slajd 42-43: Praktični workshop - Scenarij**

**Notes iz PDF-a:**
_"EduTrack is an initiative to create a web-based classroom management platform... The web solution must be intuitive, scalable, and secure, focusing on user-friendly design and continuous adaptability through iterative feedback from teachers and students."_

**Što reći studentima (3 min):**

"Vrijeme je za **praktični rad**!

Koristimo već poznati **EduTrack scenarij**:
- Web platforma za upravljanje učionicom
- Praćenje prisutnosti, zadaće, ocjene, komunikacija
- Korisnici: učitelji, učenici, (roditelji)

**Vaš zadatak:**
Izgraditi **kompletnu Agile ploču** s:
- Definiranim workflowom
- User Stories i Tasks karticama
- Ispravnom strukturom i labelama

Radite u grupama, možete koristiti:
- **Fizički:** Papir, post-it-i, markeri
- **Digitalno (preporučeno):** Trello ili Miro

Ako radite digitalno, link za Miro board: [facilitator upisuje link]"

---

### **Slajd 44-45: Workshop upute**

**Notes iz PDF-a:**
_"Exercise: Now you're ready to try to set up an Agile board! Based on the EduTrack scenario: Define workflows, Write user stories and tasks on cards, Manage work effectively."_

✏️ **WORKSHOP: Izgradnja Agile ploče (45 min)**

**Cilj:** Primijeniti SVE naučene koncepte u praktičnom radu

**Faza 1: Setup ploče (10 min)**
1. Kreirajte ploču (Trello, Miro ili papir)
2. Definirajte stupce (workflow):
   ```
   📋 BACKLOG | 📝 TO DO | 🔄 IN PROGRESS | 👀 REVIEW | ✅ DONE
   ```
3. Opcionalno dodajte: BLOCKED stupac

**Faza 2: Kreiranje backloga (15 min)**
1. Napišite **3 Epica** za EduTrack
2. Za svaki Epic, napišite **2-3 User Stories**
3. Za JEDNU Story, napišite **3-4 Taska**

**Primjer strukture:**
```
📦 EPIC: Upravljanje prisutnosti
├── 📝 STORY: Kao učitelj, želim označiti prisutnost
│   ├── ✅ Task: Dizajnirati UI za unos prisutnosti
│   ├── ✅ Task: Kreirati backend API
│   └── ✅ Task: Povezati frontend i backend
└── 📝 STORY: Kao učitelj, želim vidjeti izvještaj prisutnosti
```

**Faza 3: Prioritizacija i labele (10 min)**
1. Primijenite **MoSCoW** na Stories (M/S/C/W labele)
2. Dodajte **procjene** (Story Points: 1, 2, 3, 5, 8...)
3. Pomaknite neke kartice u TO DO (simulacija sprint planiranja)

**Faza 4: Prezentacija (10 min)**
- Svaka grupa ima 2-3 min za prezentaciju svoje ploče
- Objasnite:
  - Koji workflow ste odabrali i zašto?
  - Kako ste prioritizirali?
  - Što bi išlo u prvi sprint?

📚 **FACILITATOR NOTES:**

**Kako voditi workshop:**

1. **Setup (prvih 5 min):**
   - Ako digitalno: podijeli linkove, provjeri da svi imaju pristup
   - Ako fizički: podijeli materijale (papiri, post-it-i, markeri)

2. **Tijekom rada (obilazi grupe):**
   - Provjeravaj da Stories imaju ispravan format
   - Pomaži ako netko zapne
   - Izazivaj: "Zašto je ovo Must Have?"

3. **Ako grupa završi prije vremena:**
   - Neka dodaju Acceptance Criteria za Stories
   - Neka simuliraju Daily Stand-up (što je u IN PROGRESS, ima li blocker?)

4. **Prezentacija:**
   - Pohvali kreativnost
   - Daj konstruktivan feedback
   - Naglasi što je dobro napravljeno

**Česti problemi i rješenja:**

| Problem | Rješenje |
|---------|----------|
| "Ne znamo što su Epici za EduTrack" | Predloži: Prisutnost, Ocjene, Komunikacija, Zadaće |
| "Stories su prevelike" | Pomozi razbiti na manje |
| "Taskovi su previše detaljni" | Objasni da Tasks ne moraju biti granularni kao kod |
| "Sve je Must Have" | Izazivaj: "Ako možeš napraviti samo 3 stvari, koje?" |

**Ako koristite Trello:**
- Kreiraj jedan board unaprijed kao template
- Podijeli link za kopiranje
- Power-up za Labels nije nužan (built-in labels su dovoljni)

**Ako koristite Miro:**
- Pripremi template s predefiniranim stupcima
- Koristi Sticky Notes za kartice
- Različite boje za Epice, Stories, Tasks

---

## ⏰ **12:15-12:30 - RECAP MODULA + ZAVRŠNE RIJEČI**

---

### **RECAP CIJELOG AGILE MODULA (10 min)**

**Što reći studentima:**

"Čestitam! Završile ste **Agile Methodologies modul**!

Pogledajmo što sve sada znate:

**DAN 1 - Agile Fundamentals:**
- ✅ Povijest i potreba za Agileom
- ✅ Agile Manifest i 4 vrijednosti
- ✅ 12 principa
- ✅ MVP i iterativni razvoj

**DAN 2 - Kanban vs Scrum:**
- ✅ Kanban principi i ploča
- ✅ WIP limiti
- ✅ Scrum framework i sprintevi
- ✅ Kada koristiti koji pristup

**DAN 3 - Scrum uloge i rituali:**
- ✅ Product Owner, Scrum Master, Tim
- ✅ Sprint Planning, Daily Stand-up, Review, Retrospektiva
- ✅ Scrum Master certifikacije

**DAN 4 - Product Backlog:**
- ✅ Što je backlog i 5 komponenti
- ✅ User Story format
- ✅ Epic → Story → Task hijerarhija
- ✅ MoSCoW prioritizacija

**DAN 5 - Capacity Planning + Workshop:**
- ✅ Focus Factor i efektivni kapacitet
- ✅ Release planning
- ✅ Praktična izgradnja Agile ploče

**Što dalje?**
- Ove vještine ćete koristiti u skoro svakoj IT tvrtki
- Agile nije samo za developere - koristi se u marketingu, HR-u, dizajnu...
- Ako vas zanima Scrum Master karijera, razmislite o certifikaciji!"

---

### **ZAVRŠNE RIJEČI (5 min)**

**Što reći studentima:**

"Nekoliko završnih misli:

**1. Agile je MINDSET, ne samo proces**
- Prihvaćanje promjena
- Fokus na vrijednost
- Kontinuirano učenje

**2. Ne postoji 'savršeni' Agile**
- Svaki tim adaptira
- Počnite jednostavno, poboljšavajte iterativno
- Isprobajte, naučite, prilagodite

**3. Vaše prvo iskustvo s Agileom**
- Može biti zbunjujuće
- To je normalno!
- S praksom dolazi razumijevanje

**Za one koji žele više:**
- Pročitajte Agile Manifesto opet
- Isprobajte Trello za osobne projekte
- Pratite Agile zajednicu online

**Hvala na sudjelovanju!** Imate li pitanja o bilo čemu iz cijelog modula?"

---

## ❓ **PITANJA ZA PROVJERU RAZUMIJEVANJA**

**Osnovni level:**
1. Što je Focus Factor?
2. Zašto teoretski kapacitet nije jednak efektivnom kapacitetu?
3. Koji je prosječan Focus Factor?

**Srednji level:**
4. Izračunaj efektivni kapacitet za tim od 4 osobe, 2-tjedni sprint, 8h radni dan, FF 0.65
5. Što znači ako je FF manji od 70%?
6. Kako MoSCoW pomaže u capacity planning?

**Viši level:**
7. Koji faktori utječu na Focus Factor tima?
8. Kako bi se nosili s klijentom koji zahtijeva više nego što tim može?
9. Kada bi dodali nove ljude u tim, a kada ne?

**Odgovori:**
4. Efektivni kapacitet = 10 dana × 8h × 4 osobe × 0.65 = 208h

---

## 🔄 **BACKUP AKTIVNOSTI**

### **BACKUP AKTIVNOST 1: Sprint Planning simulacija (15 min)**

**Cilj:** Simulirati stvarni Sprint Planning sastanak

**Upute:**
1. Grupa glumi Scrum tim (6 osoba)
2. Daj im backlog s 10 prioritiziranih Stories
3. Kapacitet sprinta: 40 Story Points
4. Tim mora odlučiti koje Stories ulaze u sprint

**Dodatni twist:** 
- Jedna story ima ovisnost o drugoj
- Jedan član tima je na pola radnog vremena

📚 **FACILITATOR NOTES:**
Potiče diskusiju i pregovaranje - core Agile skill!

---

### **BACKUP AKTIVNOST 2: Focus Factor anketa (10 min)**

**Cilj:** Reflektirati o vlastitoj produktivnosti

**Upute:**
1. Svaka osoba razmisli o tipičnom radnom danu
2. Procijeni koliko vremena zapravo produktivno radi
3. Izračunaj osobni Focus Factor
4. Anonimna razmjena rezultata

**Diskusija:**
- Što 'krade' vaše vrijeme?
- Kako bi povećali svoj FF?

---

### **BACKUP AKTIVNOST 3: Release Plan izrada (15 min)**

**Cilj:** Kreirati Release Plan za 3 sprinta

**Upute:**
1. Koristi backlog iz workshopa
2. Kapacitet po sprintu: 30 Story Points
3. Rasporedi Stories u 3 sprinta
4. Uzmi u obzir ovisnosti i prioritete

**Format:**
```
Sprint 1 (30 SP): Story A, B, C
Sprint 2 (30 SP): Story D, E
Sprint 3 (30 SP): Story F, G, H
```

---

### **BACKUP AKTIVNOST 4: "Što može poći po zlu?" (10 min)**

**Cilj:** Identificirati rizike u sprintu

**Upute:**
1. Grupe dobiju scenarij: "Sprint je počeo s planom za 5 Stories"
2. Liste faktore koji mogu poremetiti plan
3. Za svaki faktor, predloži mitigaciju

**Primjeri faktora:**
- Ključna osoba se razboli
- Klijent mijenja zahtjeve
- Otkriveni su kritični bugovi u produkciji

---

### **BACKUP AKTIVNOST 5: Velocity tracking vježba (10 min)**

**Cilj:** Razumjeti kako velocity (brzina) pomaže planiranju

**Upute:**
1. Daj podatke za 4 prošla sprinta:
   - Sprint 1: 25 SP završeno
   - Sprint 2: 30 SP završeno
   - Sprint 3: 22 SP završeno
   - Sprint 4: 28 SP završeno
2. Izračunaj prosječnu velocity
3. Koliko SP tim može planirati za Sprint 5?

**Rješenje:**
- Prosječna velocity = (25+30+22+28)/4 = 26.25 SP
- Za Sprint 5 planiraj ~26 SP

---

### **BACKUP AKTIVNOST 6: Agile jeopardy (15 min)**

**Cilj:** Zabavna provjera znanja iz cijelog modula

**Kategorije:**
- Agile Fundamentals (100-500 bodova)
- Scrum (100-500 bodova)
- Kanban (100-500 bodova)
- Backlog (100-500 bodova)
- Capacity Planning (100-500 bodova)

**Primjeri pitanja:**
- (100) Koliko vrijednosti ima Agile Manifest? (4)
- (300) Što znači WIP u Kanbanu? (Work In Progress)
- (500) Kako se računa Focus Factor? (Efektivna brzina / Dostupni čovjek-dani)

📚 **FACILITATOR NOTES:**
Koristi whiteboard za bodove. Timovi se natječu.

---

### **BACKUP AKTIVNOST 7: Refleksija modula (10 min)**

**Cilj:** Osobna refleksija i action items

**Upute:**
Svaka osoba odgovara na:
1. **Što sam naučila?** (3 ključne stvari)
2. **Što me iznenadilo?**
3. **Što ću primijeniti?** (konkretna akcija)
4. **O čemu želim znati više?**

Opcionalno: dijeljenje u parovima ili malim grupama.

---

## 📚 **DODATNI RESURSI ZA FACILITATORA**

**Prije predavanja, pregledaj:**
1. [Capacity Planning in Scrum - Scrum.org](https://www.scrum.org/resources/blog/capacity-based-sprint-planning)
2. [Focus Factor Explained - AgileSherpas](https://www.agilesherpas.com/blog/focus-factor)
3. [Release Planning Guide - Atlassian](https://www.atlassian.com/agile/project-management/release-planning)

**Za tvoje dalje učenje:**
- [Velocity vs Capacity - Mountain Goat](https://www.mountaingoatsoftware.com/blog/know-the-difference-between-velocity-and-capacity)
- [Sprint Planning Tips - Scrum Alliance](https://www.scrumalliance.org/community/articles)

**Alati za workshop:**
- [Trello](https://trello.com) - besplatna Agile ploča
- [Miro](https://miro.com) - besplatni whiteboard (do 3 ploče)
- [Jira](https://www.atlassian.com/software/jira) - profesionalni alat (kompliciraniji)

**Pripremna lista:**
- [ ] Pripremi Trello/Miro template ako radite digitalno
- [ ] Testiraj pristup svim studentima
- [ ] Pripremi fizičke materijale (post-it-i, markeri) kao backup
- [ ] Imaj spremne backup aktivnosti ako završite ranije
- [ ] Pripremi "certifikat" ili pohvalnicu za završetak modula (opciono)

---

## 🏆 **ZAKLJUČAK MODULA**

**Agile Methodologies modul završen!**

Studentice sada imaju:
- ✅ Razumijevanje Agile mindset-a
- ✅ Praktično znanje Scrum i Kanban frameworka
- ✅ Sposobnost pisanja User Stories
- ✅ Vještine prioritizacije i planiranja
- ✅ Iskustvo izgradnje Agile ploče

**Sljedeći koraci za studentice:**
1. Isprobati Agile na osobnom projektu
2. Razmisliti o Scrum certifikaciji
3. Pratiti Agile zajednicu i učiti dalje

---

**KRAJ SINOPSISA - DAN 5 (ZAVRŠNI DAN AGILE MODULA)** ✅
