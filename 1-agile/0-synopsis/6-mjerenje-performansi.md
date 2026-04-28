# 📘 DAN 6 - MJERENJE PERFORMANSI U AGILE-U

## **PREDAVANJE: Kako mjeriti performanse Agile tima**
**TRAJANJE:** 9:00-12:30 (3.5 sata, s pauzama)  
**PDF MATERIJAL:** AGILE_4_v2.pdf (Sekcija 4.1)  
**BROJ STUDENTICA:** 8-30  
**MODUL:** Agile Methodologies  
**PRETHODNI DAN:** Dan 5 - Capacity Planning & Workshop  

---

## 📋 Sadržaj

- [🎯 Ciljevi učenja](#-ciljevi-učenja)
- [⏰ Raspored predavanja](#️-raspored-predavanja)
- [📋 Pregled slajdova](#-pregled-slajdova-i-prioriteti)
- [⏰ Sekcija 1: Velocity — Ključna metrika (9:00–10:00)](#️-900-1000---sekcija-1-velocity---ključna-metrika)
- [⏰ Pauza (10:00–10:15)](#️-1000-1015---pauza-)
- [⏰ Sekcija 2: Burndown & Burnup Charts (10:15–11:00)](#️-1015-1100---sekcija-2-burndown--burnup-charts)
- [⏰ Pauza (11:00–11:15)](#️-1100-1115---pauza-)
- [⏰ Sekcija 3: CFD, Epic Burndown & Control Chart (11:15–12:00)](#️-1115-1200---sekcija-3-cfd-epic-burndown--control-chart)
- [⏰ Sekcija 4: Ostale metrike & Recap (12:00–12:30)](#️-1200-1230---sekcija-4-ostale-metrike--recap)
- [❓ Pitanja za provjeru razumijevanja](#-pitanja-za-provjeru-razumijevanja)
- [🔄 Backup aktivnosti](#-backup-aktivnosti)
- [📚 Dodatni resursi za facilitatora](#-dodatni-resursi-za-facilitatora)
- [🌐 Eksterni resursi](#-eksterni-resursi)

---

## 🎯 **CILJEVI UČENJA:**

Na kraju ovog predavanja, studentice će moći:

1. **Objasniti** što je velocity i zašto je ključna metrika u Agile-u
2. **Izračunati** velocity tima na temelju završenih user storija
3. **Interpretirati** velocity chart i prepoznati trendove
4. **Razlikovati** burndown i burnup chart te njihove primjene
5. **Analizirati** Cumulative Flow Diagram (CFD) i identificirati uska grla
6. **Opisati** Epic burndown chart i koncept scope creep-a
7. **Koristiti** Control chart za praćenje cycle time-a
8. **Primijeniti** kombinaciju kvantitativnih i kvalitativnih metrika

---

## ⏰ **RASPORED PREDAVANJA:**

```
9:00-10:00   SEKCIJA 1: Velocity - Ključna metrika (60 min)
10:00-10:15  PAUZA ☕
10:15-11:00  SEKCIJA 2: Burndown & Burnup Charts (45 min)
11:00-11:15  PAUZA ☕
11:15-12:00  SEKCIJA 3: CFD, Epic Burndown & Control Chart (45 min)
12:00-12:30  SEKCIJA 4: Ostale metrike & Recap (30 min)
```

**Ukupno efektivno vrijeme:** 180 min (3h)

---

## 📋 **PREGLED SLAJDOVA I PRIORITETI:**

**PDF sadrži ~27 slajdova za sekciju 4.1:**

**PRIORITET 1 - MUST COVER (170 min):**
- Slajd 1-2: Uvod u mjerenje performansi ✅
- Slajd 3-6: Velocity (ključna metrika) ✅
- Slajd 7-16: Burndown charts ✅
- Slajd 17: Burnup charts ✅
- Slajd 18-21: Cumulative Flow Diagram ✅
- Slajd 22-23: Epic burndown ✅
- Slajd 24-25: Control chart ✅
- Slajd 26-27: Ostale metrike ✅

**PRIORITET 2 - BACKUP (ako ima vremena):**
- Dodatne diskusije o praktičnim primjerima
- Vježba izrade metrika za hipotetski projekt

---

## ⏰ **9:00-10:00 - SEKCIJA 1: VELOCITY - KLJUČNA METRIKA**

### **Uvodni dio (5 min)**

**Što reći studentima:**

"Dobro jutro! Danas ulazimo u iznimno praktičnu temu - **mjerenje performansi** u Agile timu. Zašto je ovo važno?

Zamislite da trenirate za maraton. Kako znate napredujete li? Mjereći vrijeme, udaljenost, otkucaje srca. Isto tako, Agile tim treba **objektivne podatke** da bi znao:
- Koliko posla može završiti u sprintu?
- Jesmo li na dobrom putu za isporuku?
- Gdje su uska grla?

Danas ćemo naučiti **ključne metrike** koje svaki Agile tim koristi."

---

### **Slajd 7: Velocity - Ključna metrika (definicija)**

**Notes iz PDF-a:**
_"Velocity: measure of the amount of work a team manages to complete during a single cycle/sprint. It is calculated for each cycle, summing up the effort (in hours or points) expended to complete the 'done' cards."_

**Što reći studentima (10 min):**

"**Velocity** (brzina) je **najvažnija metrika** u Scrum-u. Jednostavno rečeno:

> **Velocity = Koliko posla tim završi u jednom sprintu**

Kako se mjeri?
- Na kraju svakog sprinta zbrojimo **story pointe** (ili sate) svih kartica koje su potpuno **DONE**
- Ključna riječ je **DONE** - kartica koja je 90% gotova NE broji se!

**Primjer:**
- Sprint 1: Tim završi kartice od 8 + 5 + 3 = **16 story pointa**
- Sprint 2: Tim završi kartice od 5 + 5 + 8 = **18 story pointa**
- Sprint 3: Tim završi kartice od 8 + 8 + 5 = **21 story point**

Prosječna velocity = (16 + 18 + 21) / 3 = **~18 story pointa po sprintu**"

**Primjeri iz stvarnog života:**
- Ako tim ima velocity 20 pointa, a projekt ima 100 pointa ukupno → trebat će ~5 sprintova
- Velocity pomaže odgovoriti na pitanje: "Kada ćemo biti gotovi?"

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Velocity nije fiksna - varira iz sprinta u sprint. To je normalno! Bolest člana tima, praznici, kompleksni zadaci... sve utječe. Zato koristimo **prosjek zadnjih 3-5 sprintova** za planiranje.

**Česta pitanja:**
Q: "Zašto se kartica koja je 90% gotova ne broji?"
A: "Zato što u Agile-u cijenimo **isporučenu vrijednost**. Ako korisnik ne može koristiti feature, feature ne postoji. To nas tjera da razbijamo posao na manje dijelove koje možemo **potpuno završiti**."

Q: "Možemo li uspoređivati velocity između timova?"
A: "NE! Story pointi su subjektivni - svaki tim ima svoju 'kalibaciju'. Tim A s velocity 30 nije bolji od Tima B s velocity 20. Velocity uspoređujemo samo s **istim timom** kroz vrijeme."

**Troubleshooting:**
- Ako studentice zbuni koncept story pointa, podsjeti ih na Dan 4/5 gdje su to učili
- Ako nemaju taj background, objasni kratko: "Story point je relativna mjera složenosti, ne vrijeme"

---

### **Slajd 8: Velocity - Dijagram procesa**

**Notes iz PDF-a:**
_"The team pulls their desired number of stories into the current sprint. Each user story includes an estimated number of 'points' as a measure of effort required to complete. User stories that are not completely done at the end of the sprint do not count toward velocity, and are carried into the next sprint. Teams can also pull stories from the top of the product backlog if they finish the full sprint backlog early."_

**Što reći studentima (10 min):**

"Pogledajmo kako velocity funkcionira u praksi:

**POČETAK SPRINTA:**
1. Product Backlog ima kartice s procjenama: 8, 5, 5, 3, 5 pointa...
2. Tim uzima kartice u Sprint Backlog prema svojoj velocity
3. **Estimated velocity = 26 pointa** (koliko planiraju završiti)

**KRAJ SPRINTA:**
4. Pregledavamo što je DONE:
   - Kartica 8 pointa - Done! ✅
   - Kartica 5 pointa - Done! ✅
   - Kartica 5 pointa - Done! ✅
   - Kartica 3 pointa - Almost done ❌ (ne broji se!)
   - Kartica 5 pointa - Not started ❌

5. **Actual velocity = 18 pointa** (samo potpuno završene)

**Što se događa s nedovršenim karticama?**
- Vraćaju se na vrh Product Backloga
- Ulaze u sljedeći sprint
- Procjena se može revidirati

**Što ako završimo ranije?**
- Tim može 'povući' dodatne kartice s vrha Product Backloga
- To je bonus - povećava velocity tog sprinta!"

📚 **FACILITATOR NOTES:**

**Vizualni primjer:**
Nacrtaj na ploči jednostavan primjer:
```
Product Backlog → Sprint Backlog → Done
    [8]              [8] ✓         [8]
    [5]              [5] ✓         [5]  
    [3]              [3] ✗         
    [5]              [5] ✗
```

**Česta pitanja:**
Q: "Što ako tim uvijek uzima premalo posla da bi imao visoku velocity?"
A: "To je gaming the system! Velocity nije za natjecanje. Product Owner i Scrum Master prate da tim uzima realan izazov. Cilj je **konzistentnost**, ne inflacija."

---

### **Slajd 9: Velocity Chart**

**Notes iz PDF-a:**
_"Shows workflow speed and team workload per sprint. Allows you to do forecasts for the future."_

**Što reći studentima (10 min):**

"**Velocity chart** je grafički prikaz velocity-a kroz više sprintova.

Pogledajmo primjer:

| Sprint | Commitment | Delivered |
|--------|------------|-----------|
| Sprint 1 | 4 | 2.5 |
| Sprint 2 | 4.3 | 3 |
| Sprint 3 | 4.5 | 3.5 |
| Sprint 4 | 5 | 4.5 |

**Što vidimo?**
1. **Commitment** (plavo) - koliko je tim planirao
2. **Delivered** (zeleno) - koliko je stvarno isporučio

**Analiza ovog primjera:**
- Tim **konstantno precjenjuje** svoje mogućnosti (commitment > delivered)
- ALI - **oba trenda idu gore** = tim se poboljšava
- Gap između commitment i delivered **se smanjuje** = bolje planiranje

**Zašto je ovo korisno?**
- Vidimo trend - tim postaje bolji/lošiji?
- Možemo **predvidjeti** buduće sprintove
- Identificiramo probleme - ako velocity naglo padne, nešto nije u redu"

✏️ **MINI VJEŽBA: Analiza Velocity Charta (8 min)**

**Upute:**
1. U parovima, pogledajte imaginarni velocity chart:
   - Sprint 1: Commitment 20, Delivered 15
   - Sprint 2: Commitment 18, Delivered 17
   - Sprint 3: Commitment 17, Delivered 18
   - Sprint 4: Commitment 18, Delivered 12
   
2. Odgovorite:
   - Koji trend vidite u prva 3 sprinta?
   - Što se dogodilo u Sprintu 4?
   - Što biste kao Scrum Master istražili?

**Rješenje:**
- Trend: Tim se poboljšava (commitment = delivered u S3)
- Sprint 4: Nešto je pošlo po zlu (delivered pao za 33%)
- Istražiti: Bolest? Praznici? Kompleksan task? Tehnički dug?

📚 **FACILITATOR NOTES:**

**Ključna poruka:**
Velocity chart nije za kažnjavanje tima! To je **alat za razgovor**. Ako velocity padne, pitamo "Što se dogodilo?" - ne "Zašto ste loši?"

---

### **Slajd 10: Velocity Chart - Requirements & Tips**

**Notes iz PDF-a:**
_"Requirements: Definition of work units (effort) for each task and duration of sprints. Continuous communication between team members on completed/to-be-completed tasks. At the end of each sprint, analysis of the number of completed work units. Note: An actual velocity lower than the estimated one may denote: FF too high, Optimistic estimates. Tip: to increase team velocity, start the retrospective from the 'blocked' cards."_

**Što reći studentima (7 min):**

"Da bi velocity chart bio koristan, trebamo:

**PREDUVJETI:**
1. ✅ Definirane jedinice rada (story pointi ili sati)
2. ✅ Fiksno trajanje sprintova (npr. uvijek 2 tjedna)
3. ✅ Kontinuirana komunikacija u timu
4. ✅ Analiza na kraju svakog sprinta

**KADA JE DELIVERED < COMMITTED?**
Dva najčešća razloga:
1. **Focus Factor previsok** - planiramo kao da nema meetinga, bolesti, prekida
2. **Optimistične procjene** - podcjenjujemo složenost zadataka

**PRO TIP za povećanje velocity:**
> Na retrospektivi, počnite od **blokiranih kartica**!

Pitajte:
- 'Zašto je ova kartica bila blokirana?'
- 'Što možemo napraviti da se to ne ponovi?'
- 'Tko je trebao pomoć, a nije je dobio?'

Blokirane kartice su **zlato za poboljšanje** - pokazuju gdje sustav ne radi."

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Focus Factor (FF) smo učili Dan 5. Podsjetnik: FF je postotak vremena koje tim stvarno radi na sprint taskovima (tipično 60-70%). Ako planiraš s FF 100%, uvijek ćeš imati nizak delivered.

**Primjer iz prakse:**
"Zamislite tim od 5 ljudi, 2-tjedni sprint. Teorijski: 5 × 10 dana × 8h = 400 sati. Ali stvarno: meetingi (40h), bolest (16h), support (30h)... Realno: ~250 sati. FF = 62.5%"

> 💡 **Ako ostane vremena:** [BACKUP AKTIVNOST 5: Brainstorming - Što utječe na Velocity? (10 min)](#backup-aktivnost-5-brainstorming---što-utječe-na-velocity-10-min) — timski brainstorming dok je velocity tema svježa, odmah nakon što su razumjeli Focus Factor kao jednog od faktora.

---

## ⏰ **10:00-10:15 - PAUZA ☕**

---

## ⏰ **10:15-11:00 - SEKCIJA 2: BURNDOWN & BURNUP CHARTS**

### **Slajd 11: Burndown Chart - Definicija**

**Notes iz PDF-a:**
_"Graphical representation of the work required to complete a project. Usually the remaining work (or backlog) is indicated on the vertical axis and the time on the horizontal axis. The diagram represents a time series of tasks to be completed. It is useful for predicting when the work will be completed."_

**Što reći studentima (8 min):**

"**Burndown chart** je najpoznatiji Agile grafikon. Pokazuje:

> **Koliko posla preostaje i idemo li prema cilju?**

**Kako čitati burndown:**
- **Y os (vertikalna):** Preostali posao (sati, pointi, taskovi)
- **X os (horizontalna):** Vrijeme (dani sprinta)
- **Idealna linija:** Ravna dijagonala od početka do nule
- **Stvarna linija:** Vaš stvarni napredak

**Analogija:**
Zamislite da imate 100 km do cilja i 10 dana. Idealno bi bilo prolaziti 10 km/dan (ravna linija). Burndown pokazuje vašu stvarnu rutu - jeste li ispred, iza, ili na planu.

**Zašto je korisno?**
1. Vidimo **u realnom vremenu** jesmo li na putu
2. Možemo **predvidjeti** hoćemo li završiti na vrijeme
3. Daje **early warning** ako zaostajemo"

📖 **Reference:**
- Atlassian: [Burndown Charts Explained](https://www.atlassian.com/agile/tutorials/burndown-charts)

---

### **Slajd 8-10: Perfect Case - Iteracije 1, 2, 3**

**Notes iz PDF-a:**
_"[Vizualni primjer idealnog burndown charta kroz 3 iteracije]"_

**Što reći studentima (7 min):**

"Pogledajmo **idealan slučaj** - kako burndown izgleda kad sve ide po planu:

**ITERACIJA 1 (početak):**
- Backlog: 10 itema
- In Progress: 0
- Done: 0
- Burndown pokazuje: 10 na Y osi

**ITERACIJA 2:**
- Backlog: 8 itema
- In Progress: 1 (Item 2)
- Done: 1 (Item 1)
- Burndown: padamo s 10 na 9

**ITERACIJA 3:**
- Backlog: 7 itema
- In Progress: 1 (Item 3)
- Done: 2 (Item 1, 2)
- Burndown: padamo s 9 na 8

**Ključno:**
U idealnom slučaju, linija **ravnomjerno pada** prema nuli. To znači:
- Tim radi konstantnim tempom
- Nema iznenađenja
- Završit ćemo na vrijeme"

---

### **Slajd 11: Burndown Chart - Example 1**

**Notes iz PDF-a:**
_"[Primjer s projektom ABC, usporedba Planned Effort i Hours Remaining]"_

**Što reći studentima (8 min):**

"Pogledajmo stvarni primjer - **Projekt ABC, Sprint N**:

| Dan | Planirano | Stvarno |
|-----|-----------|---------|
| Day0 | 850h | 850h |
| 5-Jan | 600h | 490h |
| 9-Jan | 400h | 495h |
| 16-Jan | 50h | 50h |

**Što vidimo?**

1. **Početak (Day0):** Obje linije na 850h - OK!
2. **5-Jan:** Stvarno (490h) **ispod** planiranog (600h) = 🎉 Ispred smo!
3. **9-Jan:** Stvarno (495h) **iznad** planiranog (400h) = 😰 Zaostajemo!
4. **16-Jan:** Obje na 50h = ✅ Stigli smo!

**Analiza:**
- Tim je bio **prebrz** na početku
- Negdje između 5-9 Jan nešto se dogodilo (blokada? kompleksnost?)
- Na kraju su ipak **završili na vrijeme** (možda overtime?)

**Pouka:**
Burndown rijetko prati idealnu liniju. Cilj je da **završi na nuli** na kraju sprinta."

📚 **FACILITATOR NOTES:**

**Česta pitanja:**
Q: "Zašto je stvarna linija nekad IZNAD planirane?"
A: "Može značiti: (1) Dodali smo novi posao mid-sprint, (2) Podcijenjeni taskovi, (3) Blokade. Svaki od ovih zahtijeva drugačiju akciju."

> 💡 **Ako ostane vremena:** [BACKUP AKTIVNOST 4: Analiza stvarnog Burndown Charta (10 min)](#backup-aktivnost-4-analiza-stvarnog-burndown-charta-10-min) — studentice analiziraju Example 2 iz PDF-a odmah dok je burndown čitanje svježe.

---

### **Slajd 14-16: (Sad) Reality - Iteracije 1, 2, 3**

**Notes iz PDF-a:**
_"[Primjer kada stvarnost ne prati plan - scope creep]"_

**Što reći studentima (10 min):**

"A sada... **tužna stvarnost** koja se događa u većini projekata:

**ITERACIJA 1:**
- Počinjemo s 10 itema
- Burndown: ostaje na 10, 10, 10... NE PADA!
- Zašto? Tim radi, ali ništa nije **potpuno završeno**

**ITERACIJA 2:**
- 1 item je Done, ali...
- Backlog sada ima **11 itema** (netko je dodao Item 11!)
- Burndown: i dalje 10 (1 gotov - 1 dodan = 0 napretka)

**ITERACIJA 3:**
- 2 itema Done, ali...
- Backlog ima **12 itema** (dodan Item 12 - označen crveno!)
- Burndown: I DALJE NE PADA

**Ovo je SCOPE CREEP:**
> Kontinuirano dodavanje novog posla tijekom sprinta

**Zašto je ovo problem?**
- Tim radi, ali napredak se NE VIDI
- Morale pada ('koliko god radili, backlog je isti')
- Sprint cilj je nemoguće postići

**Kako se boriti:**
1. Sprint Backlog je **zaključan** nakon Sprint Planninga
2. Novi zahtjevi idu u **Product Backlog** za sljedeći sprint
3. Ako je nešto HITNO, nešto drugo mora izaći"

✏️ **DISKUSIJA (5 min):**
"Jeste li ikad bili u situaciji (posao, fakultet, privatno) gdje ste stalno dobivali nove zadatke dok ste radili na postojećima? Kako ste se osjećali? Što ste napravili?"

📚 **FACILITATOR NOTES:**

**Ključna poruka:**
Scope creep je **neprijatelj broj 1** za Agile timove. Burndown chart je **rani alarm** - ako linija ne pada, nešto nije u redu.

> 💡 **Ako ostane vremena:** [BACKUP AKTIVNOST 1: Crtanje vlastitog Burndown Charta (15 min)](#backup-aktivnost-1-crtanje-vlastitog-burndown-charta-15-min) — studentice sami nacrtaju sprint sa scope creepom, hands-on dok je "tužna stvarnost" upravo pokazana.

---

### **Slajd 17: Burnup Chart**

**Notes iz PDF-a:**
_"Are there alternatives to the unedifying 'flat' burndown charts? The burnup charts. Burnup charts answer the opposite question: how much work has been completed? Whereas a Burndown chart should always tend downwards, an ideal Burnup Chart moves upwards. But why don't we like burnup charts? They have no predictive utility. They do not push velocity up (I do not know how much effort is left to finish the job, so I do not 'speed up')."_

**Što reći studentima (5 min):**

"**Burnup chart** je 'obrnuti' burndown:

| Burndown | Burnup |
|----------|--------|
| Pokazuje: koliko preostaje | Pokazuje: koliko je završeno |
| Ide DOLJE | Ide GORE |
| Cilj: doći do 0 | Cilj: doći do vrha |

**Zašto se burnup manje koristi?**
1. **Nema prediktivnu moć** - ne vidimo koliko još treba
2. **Ne motivira ubrzanje** - ako ne znam koliko fali, ne žurim
3. Psihološki, 'brojanje preostalog' je motivirajuće

**Kada JE koristan?**
- Za prezentacije stakeholderima koji vole vidjeti 'napredak'
- Kad scope nije fiksiran pa je teško računati 'preostalo'

U praksi, većina timova koristi **burndown**."

---

## ⏰ **11:00-11:15 - PAUZA ☕**

---

## ⏰ **11:15-12:00 - SEKCIJA 3: CFD, EPIC BURNDOWN & CONTROL CHART**

### **Slajd 18-19: Cumulative Flow Diagram (CFD)**

**Notes iz PDF-a:**
_"Exceeds the limits of Burndown and Burnup. Adds some extra data. Displays data in a better way. Promotes more robust decision-making processes."_

**Što reći studentima (10 min):**

"**Cumulative Flow Diagram (CFD)** je napredni grafikon koji kombinira najbolje od burndown i burnup:

**Što pokazuje:**
- **Zelena zona (Done):** Završeni posao - raste prema gore
- **Siva zona (In Progress):** Posao u tijeku - WIP
- **Plava zona (Backlog):** Čeka na početak

**Kako čitati CFD:**
1. **Vertikalno:** Work in Progress (WIP) = debljina sive zone
2. **Horizontalno:** Cycle Time = koliko item provede od početka do kraja

**Zašto je CFD superioran:**
- Vidimo **trendove** za svaku fazu
- Identificiramo **uska grla** (ako zona raste = zagušenje)
- Vidimo **scope creep** (ako ukupna visina raste)

**Primjer čitanja:**
- Ako 'In Progress' zona postaje sve deblja → previše posla u tijeku, ništa se ne završava
- Ako 'Done' zona stagnira → tim ne isporučuje
- Ako 'Backlog' zona raste → dodajemo posao brže nego ga rješavamo"

📖 **Reference:**
- Kanbanize: [Understanding CFD](https://kanbanize.com/kanban-resources/kanban-analytics/cumulative-flow-diagram)

---

### **Slajd 21: CFD s više stanja**

**Notes iz PDF-a:**
_"A CFD can have as many 'coloured bands' as there are states into which the process is divided (the columns of our board)"_

**Što reći studentima (5 min):**

"CFD može imati **onoliko zona koliko imamo kolona na ploči**:

**Primjer kompleksnijeg procesa:**
- To Do (crveno)
- In Progress (plavo)
- Blocked (narančasto)
- Ready for Test (zeleno)
- Done (ljubičasto)

**Zašto je ovo korisno?**
Odmah vidimo:
- Ako 'Blocked' zona raste = problem s blokadama
- Ako 'Ready for Test' raste = QA je usko grlo
- Ako 'In Progress' je konstantno velik = previše WIP-a

**Pro tip:**
CFD je **rendgen za vaš proces**. Pokazuje gdje se stvari zaustavljaju."

---

### **Slajd 22-23: Epic and Release Burndown**

**Notes iz PDF-a:**
_"Track project progress over different sprints, highlighting the flow of work and any rework within an epic or version (even spread over several sprints). Scope creep: adding new requirements to an already defined project. Note: If scope creep between several epic is a problem during the sprint, it is a natural consequence of Agile development (the client can decide to accept or not accept the work done based on what emerges during the project)"_

**Što reći studentima (10 min):**

"**Epic Burndown** prati napredak **kroz više sprintova** za veće cjeline:

Iz primjera vidimo:
| Sprint | Work Remaining | Work Added | Work Completed |
|--------|----------------|------------|----------------|
| Original | 15 | - | - |
| Sprint 7 | 13 | 0 | -2 |
| Sprint 8 | 13 | +4 | 0 |
| Sprint 9 | 12 | +4 | -3 |
| Sprint 10 | 12 | 0 | -4 |

**Što vidimo:**
1. **Sprint 7:** Krenuli s 15, završili 2 = ostalo 13 ✅
2. **Sprint 8:** DODANO 4 nova pointa! Ostalo i dalje 13 ⚠️
3. **Sprint 9:** Opet dodano 4, završeno 3 = neto +1 ⚠️
4. **Sprint 10:** Konačno napredak, ostalo 12

**Scope Creep vizualiziran:**
- Svijetloplavi dijelovi = **dodani posao**
- Ako je puno svijetloplavog = scope creep problem

**Važna napomena:**
U Agile-u, scope creep NIJE uvijek loš! Klijent može promijeniti zahtjeve na temelju onoga što vidi. Ali moramo biti **svjesni** cijene."

📚 **FACILITATOR NOTES:**

**Česta pitanja:**
Q: "Kako razlikovati 'dobri' i 'loši' scope creep?"
A: "Dobar: Klijent vidi demo, ima bolju ideju, dodaje vrijednost. Loš: Klijent stalno mijenja mišljenje, dodaje 'nice to have' bez prioriteta. Razlika je u VRIJEDNOSTI koju novo donosi."

> 💡 **Ako ostane vremena:** [BACKUP AKTIVNOST 7: Kreiranje metrika za fiktivni projekt (15 min)](#backup-aktivnost-7-kreiranje-metrika-za-fiktivni-projekt-15-min) — grupe definiraju Epice i metrike za mobilnu app, direktna veza s Epic Burndown i scope creep konceptima koji su upravo obrađeni.

---

### **Slajd 18-19: Control Chart**

**Notes iz PDF-a:**
_"It highlights the cycle time of the cards, i.e. the time between 'doing' and 'done'. In an ideal situation, all cards/issues should be below the red line (average cycle time). In general: Short cycle time → High productivity. Constant cycle time → predictable delivery times. The ideal situation is therefore to have teams with short cycle times and constant cycle times."_

**Što reći studentima (10 min):**

"**Control Chart** prati **cycle time** - koliko vremena treba da kartica prođe od početka do kraja:

**Kako čitati:**
- **X os:** Kartice (redom kako su završene)
- **Y os:** Vrijeme (dani od 'In Progress' do 'Done')
- **Crvena linija:** Prosječni cycle time
- **Crne linije:** Gornja i donja granica 'normalnog'

**Što tražimo:**
1. **Kratki cycle time** = visoka produktivnost
2. **Konstantan cycle time** = predvidljiva isporuka
3. **Točke izvan granica** = 'Learning Opportunities' 💡

**Primjer:**
- Prosjek: 5 dana
- Većina kartica: 3-7 dana ✅
- Jedna kartica: 15 dana 🔴 → Zašto? Istraži!

**Outlieri su zlato:**
Svaka točka iznad gornje granice je prilika za učenje:
- Zašto je trajalo duže?
- Što možemo promijeniti?
- Je li bila blokada?"

✏️ **GRUPNA VJEŽBA: Analiza metrika (15 min)**

**Upute:**
1. Podijelite se u grupe od 3-4
2. Dobivate imaginarni scenarij:
   - Tim "Alpha" ima velocity chart koji pokazuje pad 3 sprinta zaredom
   - Njihov CFD pokazuje da 'In Progress' zona raste
   - Control chart ima 3 outliera u zadnjem sprintu

3. Diskutirajte (10 min):
   - Što je problem?
   - Koji je mogući uzrok?
   - Što biste predložili?

4. Svaka grupa dijeli zaključak (5 min)

**Moguća rješenja:**
- Previše WIP-a → uvedite WIP limite
- Blokade → Scrum Master ih mora rješavati prioritetno
- Preoptimistične procjene → Refinement sessioni

📚 **FACILITATOR NOTES:**
Potakni kreativnost. Nema jednog točnog odgovora - cilj je da studentice povežu metrike s akcijama.

> 💡 **Ako ostane vremena:** [BACKUP AKTIVNOST 2: Quiz - Prepoznaj Problem s Metrike (10 min)](#backup-aktivnost-2-quiz---prepoznaj-problem-s-metrike-10-min) — brzi natjecateljski kviz koji testira sve 5 naučenih metrika, idealan prijelaz prema Sekciji 4.

---

## ⏰ **12:00-12:30 - SEKCIJA 4: OSTALE METRIKE & RECAP**

### **Slajd 26-27: Other Metrics**

**Notes iz PDF-a:**
_"Quality: No. of reported defects (during the project, after release, from outside the team). No. of customers submitting support requests. % coverage of tests carried out automatically. Frequency, Speed and Difficulty of releases. Metrics are only one step in the process of building a team culture. They provide evidence of the team's performance and measurable objectives for its members but it is important to be able to collect feedback during retrospectives to increase the team's confidence, the quality of products/services and speed of execution of activities. Both quantitative and qualitative data are needed to drive change!"_

**Što reći studentima (10 min):**

"Velocity, burndown i CFD nisu jedine metrike. Evo još korisnih:

**METRIKE KVALITETE:**
- Broj prijavljenih bugova (tijekom projekta, nakon releasea)
- Broj korisničkih support zahtjeva
- Postotak pokrivenosti automatskim testovima

**METRIKE RELEASEA:**
- Učestalost releasea (dnevno? tjedno? mjesečno?)
- Brzina deploymenta
- Složenost release procesa

**VAŽNA PORUKA:**
> Metrike su samo JEDAN korak u izgradnji timske kulture!

**Kvantitativno + Kvalitativno:**
- Brojevi (velocity, bugs...) daju DOKAZE
- Retrospektive daju KONTEKST
- Oboje je potrebno za PROMJENU

**Primjer:**
Velocity pada. Brojevi kažu: 'Problem!' Retrospektiva kaže: 'Dva seniora su otišla na porodiljni. Normalizirat će se za 2 mjeseca.' Bez retrospektive, možda bismo krivili tim."

---

### **Recap & Završetak (15 min)**

**Što reći studentima:**

"Ponovimo što smo danas naučili:

**KLJUČNE METRIKE:**
1. **Velocity** - koliko tim završi po sprintu
2. **Burndown** - preostali posao vs. vrijeme
3. **Burnup** - završeni posao (manje korišten)
4. **CFD** - kompletan pregled procesa
5. **Epic Burndown** - praćenje kroz više sprintova
6. **Control Chart** - cycle time i outlieri

**ZLATNA PRAVILA:**
- ✅ Metrike su za RAZGOVOR, ne za kažnjavanje
- ✅ Velocity uspoređuj samo s ISTIM timom
- ✅ Outlieri su prilike za učenje
- ✅ Kvantitativno + kvalitativno = prava slika

**PITANJA?**"

> 💡 **Ako ostane vremena:** [BACKUP AKTIVNOST 3: Roleplay - Retrospektiva oko metrika (15 min)](#backup-aktivnost-3-roleplay---retrospektiva-oko-metrika-15-min) — tim simulira retrospektivu s konkretnim metrikama, savršeno zatvaranje dana.

---

## ❓ **PITANJA ZA PROVJERU RAZUMIJEVANJA**

**Osnovni level:**
1. Što je velocity i kako se računa?
2. Koja je razlika između burndown i burnup charta?

**Srednji level:**
3. Zašto se kartica koja je 90% gotova ne računa u velocity?
4. Što nam govori debljina 'In Progress' zone na CFD-u?

**Viši level:**
5. Kako biste reagirali ako velocity pada 3 sprinta zaredom?
6. Zašto je opasno uspoređivati velocity između različitih timova?

---

## 🔄 **BACKUP AKTIVNOSTI**

### **BACKUP AKTIVNOST 1: Crtanje vlastitog Burndown Charta (15 min)**

**Cilj:** Praktično razumijevanje burndown charta kroz vlastiti primjer

**Upute:**
1. Na papiru nacrtajte koordinatni sustav (X = dani 1-10, Y = story pointi 0-50)
2. Nacrtajte idealnu liniju od (0, 50) do (10, 0)
3. Simulirajte sprint:
   - Dan 1: Završili 3 pointa → crtate točku na 47
   - Dan 2: Završili 5 pointa → crtate točku na 42
   - Dan 3: Dodano 8 pointa! → crtate točku na 50 (42 + 8)
   - ... nastavite improvizirati
4. Povežite točke i analizirajte

📚 **FACILITATOR NOTES:**
- Ovo je hands-on aktivnost koja pomaže vizualnim učenicima
- Može se raditi individualno ili u parovima
- Poanta je doživjeti kako scope creep utječe na grafikon

---

### **BACKUP AKTIVNOST 2: Quiz - Prepoznaj Problem s Metrike (10 min)**

**Cilj:** Povezivanje metrika s problemima u timu

**Upute:**
Pročitajte scenarij i odgovorite koja metrika bi pokazala problem:

1. "Tim radi, ali ništa se ne završava potpuno" → ?
2. "Kartice čekaju predugo na review" → ?
3. "Stalno dodajemo novi posao tijekom sprinta" → ?
4. "Ne znamo kada ćemo završiti epic" → ?
5. "Neke kartice traju puno duže od prosjeka" → ?

**Odgovori:**
1. Burndown (ravna linija)
2. CFD (debela 'In Review' zona)
3. Epic Burndown (scope creep)
4. Velocity + Backlog veličina
5. Control Chart (outlieri)

📚 **FACILITATOR NOTES:**
- Može se igrati kao natjecanje između grupa
- Svaki točan odgovor = 1 bod

---

### **BACKUP AKTIVNOST 3: Roleplay - Retrospektiva oko metrika (15 min)**

**Cilj:** Simulirati kako tim koristi metrike na retrospektivi

**Upute:**
1. Jedna osoba je Scrum Master, ostale su tim
2. Scrum Master prezentira:
   - "Velocity je pao s 25 na 18 ovaj sprint"
   - "CFD pokazuje rast 'Blocked' zone"
   - "Imamo 3 outliera na Control Chartu"
3. Tim diskutira:
   - Što se dogodilo?
   - Koji su mogući uzroci?
   - Koje akcije predlažemo?

📚 **FACILITATOR NOTES:**
- Potakni otvorenu diskusiju
- Ne postoji točan odgovor - cilj je prakticirati korištenje metrika

---

### **BACKUP AKTIVNOST 4: Analiza stvarnog Burndown Charta (10 min)**

**Cilj:** Analiza stvarnog primjera

**Upute:**
1. Projicirajte Example 2 iz PDF-a (Sample Burndown Chart)
2. U parovima, odgovorite:
   - U kojem trenutku je tim bio najviše "iza" plana?
   - Kada su "uhvatili" plan?
   - Koliko je stvarni završetak odstupao od idealnog?

📚 **FACILITATOR NOTES:**
- Fokus je na čitanju grafa, ne na matematici
- Prihvatljive su približne procjene

---

### **BACKUP AKTIVNOST 5: Brainstorming - Što utječe na Velocity? (10 min)**

**Cilj:** Razumijevanje faktora koji utječu na tim

**Upute:**
1. Na ploči napišite: "ŠTO POVEĆAVA VELOCITY?" i "ŠTO SMANJUJE VELOCITY?"
2. Timski brainstorming - svaka studentica daje barem 1 ideju
3. Grupirajte ideje po temama

**Mogući odgovori:**
POVEĆAVA: Jasni zahtjevi, Nema prekida, Automatizirani testovi, Dobra komunikacija, Iskusan tim
SMANJUJE: Scope creep, Blokade, Bolesti, Nejasni zahtjevi, Tehnički dug

---

### **BACKUP AKTIVNOST 6: "Metric Bingo" (5 min)**

**Cilj:** Brzo ponavljanje pojmova

**Upute:**
1. Svaka studentica nacrta 3x3 grid
2. U svako polje upiše jedan pojam s predavanja (velocity, burndown, CFD, cycle time, scope creep, outlier, WIP, story point, sprint)
3. Facilitator čita definicije nasumično
4. Tko prvi ima 3 u nizu - viče "BINGO!"

📚 **FACILITATOR NOTES:**
- Energetska aktivnost za kraj predavanja
- Možete imati malu nagradu (slatkiš, dodatni bod...)

---

### **BACKUP AKTIVNOST 7: Kreiranje metrika za fiktivni projekt (15 min)**

**Cilj:** Primjena znanja na novi kontekst

**Upute:**
1. Zamislite da radite na projektu: "Mobilna aplikacija za naručivanje kave"
2. U grupama definirajte:
   - Koja 3 Epica bi projekt imao?
   - Procjena story pointa za svaki Epic?
   - Koje metrike biste pratili i zašto?
3. Prezentirajte ostalima (2 min po grupi)

📚 **FACILITATOR NOTES:**
- Potiče kreativnost i primjenu
- Nema krivih odgovora dok je logika ispravna

---

## 📚 **DODATNI RESURSI ZA FACILITATORA**

**Prije predavanja, pregledaj:**
1. Velocity u Scrum-u - [Scrum.org](https://www.scrum.org/resources/blog/agile-metrics-velocity)
2. Burndown Charts - [Atlassian Guide](https://www.atlassian.com/agile/tutorials/burndown-charts)
3. CFD objašnjen - [Kanbanize](https://kanbanize.com/kanban-resources/kanban-analytics/cumulative-flow-diagram)

**Za tvoje dalje učenje:**
- Jira tutorial za metrike - [Jira Software](https://www.atlassian.com/software/jira/guides/reports/overview)
- Advanced Agile Metrics - [AgileAlliance](https://www.agilealliance.org/glossary/velocity/)

**Pripremna lista:**
- [ ] Projector/ekran za prikaz PDF-a
- [ ] Papir i olovke za vježbu crtanja
- [ ] Flipchart ili ploča za brainstorming
- [ ] Timer za vježbe
- [ ] Opcionalno: Slatkiši za Bingo nagradu

> 💡 **Ako ostane vremena:** [BACKUP AKTIVNOST 6: "Metric Bingo" (5 min)](#backup-aktivnost-6-metric-bingo-5-min) — brza, energetska aktivnost za kraj predavanja, pojmovi iz cijelog dana.

---

## 🌐 **EKSTERNI RESURSI**

**Tools za praćenje metrika:**
- [Jira](https://www.atlassian.com/software/jira) - Najpopularniji Agile tool
- [Trello](https://trello.com) - Jednostavniji Kanban board
- [Azure DevOps](https://azure.microsoft.com/en-us/products/devops/) - Microsoft alternativa

**Članci za dublje razumijevanje:**
- [Velocity vs Story Points](https://www.mountaingoatsoftware.com/blog/know-exactly-what-velocity-means-to-your-scrum-team)
- [Why Burndown Charts Lie](https://www.agilealliance.org/resources/experience-reports/why-burndown-charts-lie/)

---

**KRAJ SINOPSISA - DAN 6** ✅
