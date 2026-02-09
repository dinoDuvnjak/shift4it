# 📘 DAN 8 - POMIRENJE WATERFALL-A I AGILE-A

## **PREDAVANJE: Koegzistencija metodologija i upravljanje višestrukim timovima**
**TRAJANJE:** 9:00-12:30 (3.5 sata, s pauzama)  
**PDF MATERIJAL:** AGILE_4_v2.pdf (Sekcija 4.3)  
**BROJ STUDENTICA:** 8-30  
**MODUL:** Agile Methodologies (ZAVRŠNI DAN)  
**PRETHODNI DAN:** Dan 7 - Kako izbjeći neuspjeh  

---

## 🎯 **CILJEVI UČENJA:**

Na kraju ovog predavanja, studentice će moći:

1. **Kreirati** Gantt dijagram iz Agile kartica
2. **Koristiti** digitalne alate za Agile projektno upravljanje (TeamGantt, EleGantt, OpenProject)
3. **Pratiti** ukupni napredak projekta pomoću Sprint Goals
4. **Objasniti** koncept Scrum of Scrums i kada ga primijeniti
5. **Organizirati** rad više Scrum timova na istom projektu
6. **Upravljati** geografski distribuiranim timovima
7. **Primijeniti** Scrum Master checklist za svakodnevni rad
8. **Integrirati** Agile prakse s tradicionalnim Waterfall okruženjem

---

## ⏰ **RASPORED PREDAVANJA:**

```
9:00-10:00   SEKCIJA 1: Kreiranje Gantta iz Agile kartica + Alati (60 min)
10:00-10:15  PAUZA ☕
10:15-11:00  SEKCIJA 2: Scrum of Scrums & Koordinacija (45 min)
11:00-11:15  PAUZA ☕
11:15-12:00  SEKCIJA 3: Upravljanje višestrukim Scrum timovima (45 min)
12:00-12:30  SEKCIJA 4: Scrum Master Checklist & Završni Recap modula (30 min)
```

**Ukupno efektivno vrijeme:** 180 min (3h)

---

## 📋 **PREGLED SLAJDOVA I PRIORITETI:**

**PDF sadrži ~30 slajdova za sekciju 4.3:**

**PRIORITET 1 - MUST COVER (150 min):**
- Slajd 1-2: Kreiranje Gantta iz kartica ✅
- Slajd 3-8: Digitalni alati (TeamGantt, EleGantt, OpenProject) ✅
- Slajd 9-10: Praćenje napretka sa Sprint Goals ✅
- Slajd 11-15: Scrum of Scrums ✅
- Slajd 16-22: Multiple Scrums ✅
- Slajd 23-25: Scrum Master Checklist ✅

**PRIORITET 2 - NICE TO HAVE (30 min):**
- Virtualni timovi i geografska distribucija
- Dodatne diskusije o praktičnim izazovima

---

## ⏰ **9:00-10:00 - SEKCIJA 1: KREIRANJE GANTTA IZ AGILE KARTICA + ALATI**

### **Uvodni dio (5 min)**

**Što reći studentima:**

"Dobro jutro i dobrodošle na **posljednji dan** našeg Agile modula! 🎉

Tijekom proteklih dana naučile ste:
- Osnove Agile-a i Scruma
- User Stories i estimaciju
- Planiranje sprintova i releasea
- Mjerenje performansi
- Kako izbjeći neuspjeh

Danas ćemo **zatvoriti krug** i naučiti:
- Kako spojiti Agile s 'tradicionalnim' svijetom (Gantt, izvještaji)
- Kako koordinirati kada imate VIŠE Agile timova
- Praktične alate i checklistove

**Zašto je ovo važno?**
U stvarnom svijetu, rijetko radite u 'čistom' Agile okruženju. Vaši klijenti, manageri, ili drugi odjeli vjerojatno koriste Waterfall. Morate znati **prevesti** između dva svijeta."

---

### **Slajd 1-2: Creating the Gantt from cards**

**Notes iz PDF-a:**
_"Regardless of the approach taken, we are often asked to produce a project Gantt. With respect to Agile, we can try to do this by starting with the very cards on the board."_

**Što reći studentima (15 min):**

"**Gantt dijagram** - svi ste ga vidjele. One vodoravne trake koje pokazuju trajanje zadataka kroz vrijeme.

**Problem:**
- Management traži Gantt
- Klijent traži Gantt
- Drugi odjeli trebaju Gantt za koordinaciju
- ALI vi radite Agile s karticama i sprintovima!

**Rješenje: Kreirajte Gantt IZ vaših kartica**

**Kako?**

**KORAK 1: Grupirajte kartice po Epicima**
```
Epic 1: Registracija korisnika
├── Kartica 1.1: Login stranica (5 SP)
├── Kartica 1.2: Registracijski form (8 SP)
└── Kartica 1.3: Email verifikacija (3 SP)

Epic 2: Dashboard
├── Kartica 2.1: Home widget (5 SP)
├── Kartica 2.2: Statistike (8 SP)
...
```

**KORAK 2: Procijenite trajanje Epica**
- Velocity tima: 20 SP/sprint
- Epic 1 = 16 SP ≈ 1 sprint
- Epic 2 = 25 SP ≈ 1.5 sprinta

**KORAK 3: Mapiranje na timeline**
```
Sprint 1: Epic 1 (100%)
Sprint 2: Epic 2 (66%)
Sprint 3: Epic 2 (završetak) + Epic 3 (početak)
...
```

**KORAK 4: Kreirajte Gantt s Epicima kao taskovima**

**Važno:**
- Gantt iz Agile-a je **procjena**, ne obećanje
- Revidirajte svaki sprint na temelju velocity-a
- Komunicirajte da su datumi **okvirni**"

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
U tradicionalnom Waterfallu, Gantt se kreira na početku i rijetko se mijenja. U Agile-u, Gantt se **stalno ažurira** na temelju stvarnog napretka.

**Česta pitanja:**
Q: "Ako se Gantt stalno mijenja, čemu služi?"
A: "Za komunikaciju s ostatkom organizacije. Stakeholderi trebaju vidjeti 'big picture'. Gantt im je poznat format. Vi prevodite vaš Agile napredak u njihov jezik."

---

### **Slajd 3-4: A digital tool: TeamGantt**

**Notes iz PDF-a:**
_"TeamGantt is a digital tool that allows you to: create, share, update Gantt; reorganise tasks; display all projects in one view; manage resources, control budget and make sure to avoid overload; create reports; check progress against plan and make projections; list tasks and schedule them; track activities."_

**Što reći studentima (10 min):**

"**TeamGantt** je alat specifično dizajniran za spajanje Agile-a i Gantt dijagrama.

**Glavne funkcionalnosti:**

| Funkcija | Opis |
|----------|------|
| Kreiranje Gantta | Drag-and-drop sučelje |
| Dijeljenje | Tim i stakeholderi vide isti view |
| Ažuriranje | Real-time promjene |
| Resursi | Vidite tko je preopterećen |
| Budget | Praćenje troškova po tasku |
| Izvještaji | Automatski reports |
| Projekcije | Predikcije na temelju napretka |

**Kada koristiti TeamGantt?**
- Kad radite s klijentima koji trebaju Gantt
- Kad koordinirate s Waterfall timovima
- Kad management traži 'klasične' izvještaje

**Demo walkthrough:**
[Ako imate pristup, pokažite sučelje]
1. Kreirate projekt
2. Dodajete Epice kao 'parent tasks'
3. User Stories kao 'subtasks'
4. Dodijelite ljude
5. TeamGantt automatski crta Gantt"

📖 **Reference:**
- [TeamGantt](https://www.teamgantt.com/) - 14 dana besplatno

---

### **Slajd 5-6: A digital tool: EleGantt**

**Notes iz PDF-a:**
_"EleGantt is a digital tool that allows you to: display the Gantt directly in each board starting from the cards present; automatically update the Gantt based on changes to cards, lists, assignees; display dependencies between cards; display deadlines and send automatic reminders to the team; group, filter or reorder cards."_

**Što reći studentima (10 min):**

"**EleGantt** je specifično dizajniran kao **Trello Power-Up**.

**Zašto je ovo cool?**
Ako već koristite Trello za vaš Kanban/Scrum board, EleGantt **automatski** generira Gantt iz vaših kartica!

**Glavne funkcionalnosti:**

| Funkcija | Opis |
|----------|------|
| Automatski Gantt | Generira se iz Trello kartica |
| Real-time sync | Promjena kartice = promjena Gantta |
| Dependencies | Vidite koje kartice ovise o drugim |
| Deadlines | Automatski reminderi |
| Filtriranje | Po assignee-u, labelu, listi... |

**Prednost nad TeamGantt:**
- Ne trebate dva alata
- Tim radi u Trellu, stakeholderi gledaju Gantt
- Nema duplog unosa

**Nedostatak:**
- Samo za Trello
- Manje napredno od TeamGantt-a"

📖 **Reference:**
- [EleGantt za Trello](https://elegantt.com/)

---

### **Slajd 7-8: A digital tool: OpenProject**

**Notes iz PDF-a:**
_"OpenProject is a project management digital tool that allows you to: create product and sprint backlogs; estimate activities in story points; use card templates; create burndown charts; track 'impediments' for sprints; assign and prioritise activities; display activities on calendar or board."_

**Što reći studentima (10 min):**

"**OpenProject** je **open-source** alternativa za Jiru i druge enterprise alate.

**Zašto OpenProject?**
- **Besplatan** (open source verzija)
- Kombinira **Agile i klasično** PM
- **Self-hosted** opcija (za privatnost podataka)

**Funkcionalnosti:**

| Kategorija | Funkcije |
|------------|----------|
| Agile | Product Backlog, Sprint Backlog, Burndown |
| Klasično PM | Gantt, WBS, Milestones |
| Timski rad | Assignees, Comments, Notifications |
| Praćenje | Impedimenti, Velocity, Reports |

**Kad koristiti OpenProject?**
- Kad nemate budget za Jiru ($$$)
- Kad trebate self-hosted rješenje
- Kad trebate i Agile i Waterfall u istom alatu

**Screenshot iz PDF-a pokazuje:**
- Kanban board s kolonama (New, In Progress, Closed, Rejected)
- Navigacija s Roadmap, Wiki, Meetings...
- Integracija s drugim modulima"

📖 **Reference:**
- [OpenProject](https://www.openproject.org/) - Community Edition je besplatna

✏️ **MINI VJEŽBA: Usporedba alata (5 min)**

**Upute:**
U parovima, popunite tablicu:

| Kriterij | TeamGantt | EleGantt | OpenProject |
|----------|-----------|----------|-------------|
| Cijena | ? | ? | ? |
| Integracija s Trellom | ? | ? | ? |
| Agile native | ? | ? | ? |
| Self-hosted | ? | ? | ? |

**Rješenje:**
| Kriterij | TeamGantt | EleGantt | OpenProject |
|----------|-----------|----------|-------------|
| Cijena | Plaćeno | Plaćeno | Free/Plaćeno |
| Integracija s Trellom | Ne | Da | Ne |
| Agile native | Djelomično | Ne | Da |
| Self-hosted | Ne | Ne | Da |

---

## ⏰ **10:00-10:15 - PAUZA ☕**

---

## ⏰ **10:15-11:00 - SEKCIJA 2: SCRUM OF SCRUMS & KOORDINACIJA**

### **Slajd 9-10: Monitor overall progress / Sprint Goals**

**Notes iz PDF-a:**
_"How to monitor the progress of activities? Define Sprint Goals (max 3 or 5) and ask the PM to indicate the % achievement of each one. Sprint Goals: sub-goals corresponding to sets of cards (≈ Epic). Use Agile as a tool for the micro-management of the team (also in waterfall projects): Organise team work by weekly sprints and hold regular meetings; Keep the team's velocity under control; Use goals as milestones and evaluate overall progress by % of their completion."_

**Što reći studentima (15 min):**

"Kako pratiti napredak na **visokoj razini** kad imate mnogo kartica?

**Odgovor: SPRINT GOALS**

**Što su Sprint Goals?**
- Sub-ciljevi koji odgovaraju grupi kartica (≈ Epic)
- Maksimalno **3-5 po sprintu**
- PM označava **% dovršenosti** svakog cilja

**Primjer:**

| Sprint 5 Goals | Status |
|----------------|--------|
| 1. Završiti login modul | 90% ✅ |
| 2. Implementirati dashboard | 60% 🔄 |
| 3. API integracija | 20% 🔄 |

**Zašto je ovo korisno?**
1. **Management** može vidjeti napredak bez čitanja 50 kartica
2. **Tim** ima jasan fokus za sprint
3. **Projekcije** - ako Goal 3 kasni, možemo reagirati

---

**KORIŠTENJE AGILE-A U WATERFALL PROJEKTIMA:**

Čak i ako organizacija radi Waterfall, možete koristiti Agile **interno u timu**:

- ✅ Organizirajte rad u **tjedne sprintove**
- ✅ Održavajte **daily standup** i **retrospektive**
- ✅ Pratite **velocity** tima
- ✅ Koristite **Sprint Goals kao milestones**

**Rezultat:**
- Bolja koordinacija tima
- Ranije prepoznavanje problema
- Waterfall management dobiva izvještaje koje razumije"

📚 **FACILITATOR NOTES:**

**Primjer iz prakse:**
"Radila sam na projektu gdje je klijent insistirao na Waterfall. Ali naš tim je interno radio Scrum. Svaki tjedan smo ažurirali Waterfall plan na temelju naše velocity. Klijent je bio sretan s izvještajima, mi smo bili sretni s načinom rada."

---

### **Slajd 11-13: Scrum of Scrums**

**Notes iz PDF-a:**
_"How to apply Agile to projects involving many people? Scrum of scrum (general meaning): technique for applying Agile to large organisations. Scrum of scrum (specific meaning): meeting held regularly between the SM of each team to share information."_

**Što reći studentima (15 min):**

"Što kad imate **veliki projekt** s više timova? Klasičan Scrum radi za tim od 5-9 ljudi. Što ako ih je 50?

**SCRUM OF SCRUMS**

**Generalno značenje:**
Tehnika za primjenu Agile-a u velikim organizacijama

**Specifično značenje:**
Redoviti sastanak **Scrum Mastera svih timova** za razmjenu informacija

---

**VIZUALIZACIJA:**

```
Proizvod A: 1 tim × 8 ljudi = 1 Scrum Master (S)
Proizvod B: 1 tim × 8 ljudi = 1 Scrum Master (S)
Proizvod C: 1 tim × 8 ljudi = 1 Scrum Master (S)
Proizvod D: 4 tima × 8 ljudi = 4 Scrum Mastera (S, S, S, S)

Total: 7 Scrum Mastera
```

---

**DVA NIVOA SCRUM OF SCRUMS:**

**1. CORPORATE SCRUM (svi SM svih proizvoda)**
- Svi Scrum Masteri se sastaju
- Dijele informacije na razini organizacije
- Frekvencija: Mjesečno ili kvartalno

**2. PRODUCT SCRUM (svi SM jednog velikog proizvoda)**
- Samo SM-ovi proizvoda D (koji ima 4 tima)
- Koordinacija između timova na istom proizvodu
- Frekvencija: Tjedno"

📚 **FACILITATOR NOTES:**

**Analogija:**
"Zamislite vojsku. Svaki vod ima vođu (Scrum Master). Voditelji vodova se sastaju s zapovjednikom satnije (Product Scrum). Zapovjednici satnija se sastaju s pukovnikom (Corporate Scrum). Informacije teku gore-dolje."

---

### **Slajd 14-15: Product/Project Scrum & Corporate Scrum**

**Notes iz PDF-a:**
_"Product/project scrum: 30-minute meeting, once a week where: 1. Each SM describes what the team did last week, what it will do in the current week and what obstacles it foresees. 2. SM share issues that affect all teams (e.g. related to integration). Corporate scrum: 15-30 minute plenary meeting, perhaps once a week where: 1. All team members receive news from the management. 2. 'Round-robin': in turn, one member reports what their team did last week, what they will do in the present week, and what problems they foresee. 3. Anyone else is free to add information or ask questions."_

**Što reći studentima (15 min):**

"Kako izgledaju ovi sastanci u praksi?

---

**PRODUCT/PROJECT SCRUM** (tjedno, 30 min)

**Tko sudjeluje:** Scrum Masteri svih timova na istom proizvodu

**Agenda:**
1. **Svaki SM izvještava (5 min po timu):**
   - Što je tim napravio prošli tjedan?
   - Što planira ovaj tjedan?
   - Koje prepreke predviđa?

2. **Zajedničke teme (10 min):**
   - Problemi koji utječu na SVE timove
   - Pitanja integracije između timova
   - Zavisnosti koje treba koordinirati

**Primjer problema za dijeljenje:**
- 'Tim A čeka API od Tima B - možemo li ubrzati?'
- 'Svi imamo problem s test environmentom'
- 'Klijent je promijenio prioritete - kako to utječe na vas?'

---

**CORPORATE SCRUM** (tjedno, 15-30 min)

**Tko sudjeluje:** Predstavnik svakog tima + management

**Agenda:**
1. **Novosti od managementa (5 min):**
   - Nadolazeći eventi
   - Organizacijske promjene
   - Strateške informacije

2. **Round-robin izvještaji (15 min):**
   - Jedan član svakog tima izvještava
   - Prošli tjedan / Ovaj tjedan / Problemi

3. **Otvorena diskusija (10 min):**
   - Pitanja
   - Dodatne informacije

**Savjet:**
> Rasporedite sastanke tako da oni koji sudjeluju u više razina ne moraju biti na svim sastancima isti dan!"

---

## ⏰ **11:00-11:15 - PAUZA ☕**

---

## ⏰ **11:15-12:00 - SEKCIJA 3: UPRAVLJANJE VIŠESTRUKIM SCRUM TIMOVIMA**

### **Slajd 16-17: Multiple Scrums - Osnovni principi**

**Notes iz PDF-a:**
_"What happens when several teams work on the same project? In general, the rule applies: more members = more complications. That is why it is essential to understand how many teams to use, how to allocate people between teams. As a rule, it is preferable not to have teams larger than 9 persons in order to avoid: Long meeting (>15 min), People who don't know what others do, Distractions, Tight deadlines to resolve unforeseen issues."_

**Što reći studentima (10 min):**

"Kada više timova radi na istom projektu, kompleksnost **eksponencijalno raste**.

**ZLATNO PRAVILO:**
> Više članova = Više komplikacija

**Zašto maksimalno 9 ljudi po timu?**

| Problem | Posljedica |
|---------|------------|
| Dugi sastanci | Daily standup > 15 min |
| Slaba koordinacija | Ljudi ne znaju što drugi rade |
| Distrakcije | Previše komunikacijskih kanala |
| Sporo rješavanje | Nepredviđeni problemi traju duže |

**Matematika komunikacije:**
- Tim od 5: 10 komunikacijskih kanala
- Tim od 9: 36 kanala
- Tim od 15: 105 kanala!

Formula: n(n-1)/2

**Preporuka:**
- Mali timovi (5-7) > Veliki timovi (10+)
- Radije 3 mala tima nego 1 veliki"

---

### **Slajd 18-20: Virtual teams**

**Notes iz PDF-a:**
_"Virtual teams: case 1 - You opt for one big team, but observing who talks to whom during the sprint, you notice a division into 2 sub-teams. Case 2 - Three smaller teams are used, noting however that while the first and second interact frequently, the third remains isolated. Does this mean that the team size is wrong? Yes, if they are permanent. No, if they are temporary."_

**Što reći studentima (10 min):**

"**VIRTUALNI TIMOVI** - fenomen koji morate prepoznati!

**SLUČAJ 1: Jedan veliki tim se 'raspada'**
- Formalno: 1 tim od 12 ljudi
- Stvarno: Dva pod-tima od 6 koji rijetko komuniciraju
- Dijagnoza: 'Virtualni' timovi su se formirali organski

**Što napraviti?**
Formalizirajte podjelu! Napravite 2 prava tima.

---

**SLUČAJ 2: Tri tima, ali treći je izoliran**
- Tim 1 i Tim 2: Česta komunikacija
- Tim 3: Rijetko komunicira s ostalima
- Dijagnoza: Tim 3 je 'virtualno' odvojen

**Je li to problem?**
- **DA**, ako je izolacija trajna → Tim 3 možda radi na krivom
- **NE**, ako je privremena → Možda rade na nezavisnom modulu

---

**KAKO PREPOZNATI VIRTUALNE TIMOVE:**
1. Promatrajte tko razgovara s kim
2. Gledajte tko se grupira na pauzama
3. Analizirajte code review-e i pull requeste
4. Pratite Slack/Teams komunikaciju

**Pro tip:**
Virtualni timovi NISU loši - oni pokazuju prirodnu strukturu. Formalizirajte ih ako imaju smisla!"

---

### **Slajd 21-22: Multiple Scrums - Sinkronizacija i Team Lead**

**Notes iz PDF-a:**
_"1. Synchronising Sprints: Advantages - Shared meetings, A single moment to redefine teams (between sprints), Fewer administrative tasks. 2. Appoint a Team Lead (Scrum Master of all teams): The Team Lead decides on the composition of the teams and their changes between several sprints. Note: before any change to the team, do not underestimate the so-called 'team gel' (bonds created by working in a team). What about part-time members? In general, a few full-time people are better than a larger team of part-time members."_

**Što reći studentima (10 min):**

"**KAKO KOORDINIRATI VIŠE TIMOVA?**

---

**1. SINKRONIZIRAJTE SPRINTOVE**

❌ **Loše:**
```
Tim A: Sprint A1 | Sprint A2 | Sprint A3
Tim B:    Sprint B1 | Sprint B2 | Sprint B3
Tim C:      Sprint C1 | Sprint C2 | Sprint C3
```
(Svaki tim ima drugačije datume - kaos!)

✅ **Dobro:**
```
Tim A: Sprint 1 | Sprint 2 | Sprint 3
Tim B: Sprint 1 | Sprint 2 | Sprint 3
Tim C: Sprint 1 | Sprint 2 | Sprint 3
```
(Svi sprintovi počinju i završavaju istog dana)

**Prednosti sinkronizacije:**
- Zajednički Sprint Planning, Review, Retro
- Lakše prebacivanje ljudi između timova (između sprintova)
- Manje administracije

---

**2. POSTAVITE TEAM LEAD-A**
- Scrum Master svih timova
- Odlučuje o sastavu timova
- Koordinira između timova

**UPOZORENJE: 'Team Gel'**
> Ne podcjenjujte veze stvorene radom u timu!

Premještanje ljudi između timova ima cijenu:
- Novi član treba vrijeme za onboarding
- Tim gubi dinamiku
- Moral može pasti

**Savjet:** Mijenjajte timove RIJETKO i samo kad je nužno.

---

**PART-TIME vs FULL-TIME:**
> Bolje je imati MANJE full-time ljudi nego VIŠE part-time!

Part-time članovi:
- Konstantno 'switchaju kontekst'
- Ne mogu pratiti sve
- Rijetko su na svim ceremonijama"

---

### **Slajd 23-24: Scrum Team & Fire Team + Distributed Teams**

**Notes iz PDF-a:**
_"How to maintain the balance between planned and emerging activities? One solution is to create 2 types of teams: Scrum Team and Fire Team. Scrum Team: under the guidance of the PM carries out activities trying to prevent emergencies. Fire Team: support team dedicated to resolving emergencies and protecting against other disruptive elements. How to manage geographically distributed teams? If the effectiveness of Agile depends a lot on the intensive and direct collaboration of the team it is necessary that this can also be done remotely."_

**Što reći studentima (10 min):**

"**KAKO BALANSIRATI PLANIRANI I HITNI POSAO?**

**Rješenje: SCRUM TEAM + FIRE TEAM**

| Scrum Team | Fire Team |
|------------|-----------|
| Radi planirane aktivnosti | Rješava hitne probleme |
| Slijedi Sprint Plan | Reagira na incidente |
| Fokusiran i zaštićen | Štiti Scrum Team od prekida |
| Predvidljiva velocity | Nepredvidljiv rad |

**Primjer:**
- Scrum Team razvija nove feature-e
- Fire Team rješava bugove u produkciji
- Kad Fire Team ima 'mirno razdoblje', pomaže Scrum Teamu

**Zašto ovo radi?**
Scrum Team može **fokusirano raditi** jer zna da netko drugi štiti od 'vatre'.

---

**GEOGRAFSKI DISTRIBUIRANI TIMOVI**

Agile ovisi o **intenzivnoj suradnji**. Kako to postići remote?

**Preduvjeti:**
- ✅ Rad u isto vrijeme (barem djelomično preklapanje)
- ✅ Sudjelovanje na daily meetinzima (video!)
- ✅ Direktni, spontani kontakti (Slack, Teams...)
- ✅ Vidljivost boarda i backloga (digitalni alati)

**Oprema:**
- Konferencijska soba s webcam i mikrofonom
- 'Remote windows' - ekrani koji pokazuju druge lokacije
- Collaboration software (Miro, Figma, Jira...)

**Zlatno pravilo:**
> Ako možete birati, bolje je imati JEDAN raspršeni tim nego VIŠE ko-lociranih timova.

Zašto? Jer 'mi vs oni' mentalitet je veći između timova nego unutar tima."

---

### **Slajd 25-26: Multiple Scrums - Alati za upravljanje**

**Notes iz PDF-a:**
_"Which tools should be used to manage multiple Scrums? Create a 'To Do List' board where, at each sprint, you move (or copy) cards from your personal boards. Create a 'board repository' to store project materials, resources (and cards) common to all members. If useful, create automatisms for recurring card movements (e.g. with Zapier or Butler)."_

**Što reći studentima (5 min):**

"**ALATI ZA UPRAVLJANJE VIŠE SCRUM TIMOVA**

**Struktura ploča:**

```
Individual Project Boards (svaki tim ima svoj)
         ↓
    To Do List Board (zajednički pregled)
         ↓
    Repository Board (zajednički resursi)
```

**1. INDIVIDUAL PROJECT BOARDS**
- Svaki tim ima svoj Trello/Jira board
- Radi po svom Sprint Backlogu

**2. TO DO LIST BOARD**
- Zajednički board za koordinaciju
- Kartice se kopiraju iz pojedinačnih ploča
- Management vidi 'big picture'

**3. REPOSITORY BOARD**
- Projektni materijali
- Zajednički resursi
- Dokumentacija

**Automatizacija:**
Koristite Butler (Trello) ili Zapier za automatsko kopiranje kartica!"

---

## ⏰ **12:00-12:30 - SEKCIJA 4: SCRUM MASTER CHECKLIST & ZAVRŠNI RECAP**

### **Slajd 27-29: Scrum Master Checklist**

**Notes iz PDF-a:**
_"At the beginning of each Sprint: After Sprint planning, create a Sprint information document, print it out and hang it on the team's most prominent wall. Send an e-mail to all stakeholders announcing that the new sprint has started. Update the information document with the sprint statistics. Every day: Ensure that the Daily Scrum is started and finished on time. Ensure that cards are added/removed from the backlog only when necessary and that the PM is informed. Ensure that the sprint backlog and burndown are kept up to date by the team. Ensure that problems are resolved or reported to the PM. At the end of each Sprint: Make a demo of the Sprint open to everyone and announcing it 1-2 days in advance. Do a retrospective of the Sprint with the whole team and the PM. Update the Sprint statistics document."_

**Što reći studentima (15 min):**

"Završavamo s **praktičnim checklistom** za Scrum Master (ili bilo koga tko vodi Agile tim):

---

**🚀 NA POČETKU SVAKOG SPRINTA:**

- [ ] Nakon Sprint Planninga, kreiraj **Sprint Info dokument**:
  - Estimirana velocity
  - Veličina tima
  - Trajanje sprinta
  - Sprint Goal
  
- [ ] **Isprintaj i objesi** na najvidljivije mjesto!

- [ ] Pošalji **email stakeholderima**:
  - 'Novi sprint je počeo'
  - Sprint cilj
  - Link na Sprint Info dokument

- [ ] Ažuriraj dokument sa **statistikama sprinta**

---

**📅 SVAKI DAN:**

- [ ] **Daily Scrum** počinje i završava na vrijeme (max 15 min)

- [ ] Kartice se dodaju/uklanjaju iz backloga **samo kad je nužno**
  - PM mora biti informiran o promjenama!

- [ ] Sprint backlog i burndown su **ažurirani**

- [ ] Problemi su **riješeni ili eskalirani** PM-u

---

**🏁 NA KRAJU SVAKOG SPRINTA:**

- [ ] **Sprint Demo** otvoren za sve
  - Najavi 1-2 dana unaprijed!
  - Pozovi stakeholdere, druge timove, management

- [ ] **Sprint Retrospektiva** s cijelim timom i PM-om
  - Što je bilo dobro?
  - Što poboljšati?
  - Akcije za sljedeći sprint

- [ ] Ažuriraj Sprint Info dokument:
  - Stvarna velocity
  - Ključne točke iz retrospektive"

✏️ **AKTIVNOST: Kreiranje vlastitog checklista (5 min)**

**Upute:**
Na temelju ovog predloška, dodajte 2-3 vlastite stavke koje mislite da bi bile korisne za vaš budući tim.

---

### **ZAVRŠNI RECAP CIJELOG AGILE MODULA (10 min)**

**Što reći studentima:**

"🎉 **Čestitam!** Završile ste Agile Methodologies modul!

**Ponovimo što smo naučile kroz 8 dana:**

**DAN 1-2: Osnove Agile-a**
- Agile Manifest i 12 principa
- Razlika Agile vs Waterfall
- MVP i iterativni razvoj

**DAN 3-4: Scrum u praksi**
- Uloge: Product Owner, Scrum Master, Tim
- Ceremonije: Planning, Daily, Review, Retro
- Artefakti: Product Backlog, Sprint Backlog

**DAN 5: Planiranje**
- User Stories i Story Points
- Velocity i Focus Factor
- Release Planning

**DAN 6: Mjerenje performansi**
- Velocity Chart
- Burndown/Burnup
- CFD, Control Chart

**DAN 7: Izbjegavanje neuspjeha**
- 7 uzroka neuspjeha
- Knoster model
- Adopcija vs Transformacija

**DAN 8 (danas): Integracija**
- Gantt iz Agile kartica
- Scrum of Scrums
- Upravljanje više timova
- Scrum Master Checklist

---

**KLJUČNE PORUKE ZA PAMĆENJE:**

1. **Agile je mindset**, ne samo alati
2. **Iteracija** je ključ - mali koraci, brzi feedback
3. **Tim** je jedinica - ne pojedinac
4. **Transparentnost** - problemi na vidjelo
5. **Kontinuirano poboljšanje** - uvijek može bolje

**SLJEDEĆI KORACI:**
- Primijenite ovo znanje na sljedećim projektima
- Eksperimentirajte - svaki tim je drugačiji
- Nastavite učiti - Agile se stalno razvija

**PITANJA?**"

---

## ❓ **PITANJA ZA PROVJERU RAZUMIJEVANJA**

**Osnovni level:**
1. Kako se kreira Gantt dijagram iz Agile kartica?
2. Što je Scrum of Scrums?

**Srednji level:**
3. Zašto je bolje imati više malih timova nego jedan veliki?
4. Koja je razlika između Product Scruma i Corporate Scruma?

**Viši level:**
5. Kako biste koordinirali 4 tima koji rade na istom proizvodu u 3 različite vremenske zone?
6. Koji su pros/cons uvođenja Fire Teama uz Scrum Team?

---

## 🔄 **BACKUP AKTIVNOSTI**

### **BACKUP AKTIVNOST 1: Simulacija Scrum of Scrums (15 min)**

**Cilj:** Iskustvo koordinacije više timova

**Upute:**
1. Podijelite se u 3 'tima' od 3-4 osobe
2. Svaki tim ima 'Scrum Mastera'
3. Timovi imaju 3 min da definiraju:
   - Što su 'napravili' prošli tjedan
   - Što planiraju ovaj tjedan
   - Koji problem imaju
4. Scrum Masteri se sastaju na 5-minutni Scrum of Scrums
5. Svaki SM izvještava (1.5 min)
6. Diskusija o zajedničkim problemima (2 min)

📚 **FACILITATOR NOTES:**
- Ovo je roleplay - timovi izmišljaju scenarij
- Cilj je iskusiti format, ne sadržaj

---

### **BACKUP AKTIVNOST 2: Dizajn Board strukture (10 min)**

**Cilj:** Praktična primjena koncepta višestrukih ploča

**Upute:**
1. U parovima, zamislite projekt s 3 tima
2. Dizajnirajte strukturu Trello ploča:
   - Koje ploče trebate?
   - Koje kolone ima svaka ploča?
   - Kako se kartice kreću između ploča?
3. Skicirajte na papiru

---

### **BACKUP AKTIVNOST 3: Scrum Master Roleplay (15 min)**

**Cilj:** Vježbanje svakodnevnih SM zadataka

**Upute:**
1. Jedna osoba je Scrum Master, ostale su tim
2. Scenarij: Daily Standup
   - Jedan član izvještava da je blokiran
   - Jedan član je završio više nego planirano
   - Jedan član izvještava da će zakasniti s taskom
3. Scrum Master mora moderirati i donijeti odluke
4. Diskusija: Što je SM napravio dobro/loše?

---

### **BACKUP AKTIVNOST 4: Quiz - Alati (5 min)**

**Cilj:** Provjera razumijevanja alata

**Pitanja:**
1. Koji alat je Trello Power-Up? → EleGantt
2. Koji alat je open-source? → OpenProject
3. Koji alat je najbolji za self-hosting? → OpenProject
4. Koji alat automatski generira Gantt iz Trello kartica? → EleGantt

---

### **BACKUP AKTIVNOST 5: Refleksija modula (10 min)**

**Cilj:** Osobna refleksija o naučenom

**Upute:**
Na papiru, odgovorite:
1. Koja 3 koncepta iz ovog modula su vam bila najkorisnija?
2. Što vas je iznenadilo?
3. Što biste htjele dalje naučiti o Agile-u?
4. Kako ćete primijeniti ovo znanje u praksi?

Opcionalno: Podijelite s grupom.

---

### **BACKUP AKTIVNOST 6: Kreiranje 'Agile Cheat Sheet' (15 min)**

**Cilj:** Sažimanje ključnih pojmova

**Upute:**
U grupama, kreirajte jednostrani 'cheat sheet' s:
- 10 ključnih pojmova i definicija
- 5 najvažnijih ceremonija
- 3 glavna alata
- 1 zlatno pravilo

Podijelite s ostalima - napravite 'master cheat sheet'!

---

### **BACKUP AKTIVNOST 7: Case Study - Koordinacija projekta (15 min)**

**Cilj:** Primjena svega naučenog

**Upute:**
Pročitajte scenarij:

*"StartupXY ima 20 developera koji rade na platformi za e-učenje. Trenutno su svi u jednom velikom timu. Daily standup traje 45 minuta. Nitko ne zna što drugi rade. Management traži Gantt i tjedne izvještaje."*

U grupama, predložite:
1. Kako podijeliti timove?
2. Kako organizirati Scrum of Scrums?
3. Koje alate koristiti?
4. Kako kreirati Gantt za management?

---

## 📚 **DODATNI RESURSI ZA FACILITATORA**

**Prije predavanja, pregledaj:**
1. TeamGantt demo - [YouTube](https://www.youtube.com/results?search_query=teamgantt+tutorial)
2. Scrum at Scale - [Scrum.org](https://www.scrum.org/resources/scaling-scrum)
3. LeSS (Large-Scale Scrum) - [Less.works](https://less.works/)

**Za tvoje dalje učenje:**
- SAFe (Scaled Agile Framework) - za enterprise
- Spotify Model - popularan pristup skaliranju

**Pripremna lista:**
- [ ] Projector/ekran za prikaz alata
- [ ] Papir za skiciranje board struktura
- [ ] Timer za roleplay aktivnosti
- [ ] Opcionalno: Pristup Trello/Jira za live demo

---

## 🌐 **EKSTERNI RESURSI**

**Alati:**
- [TeamGantt](https://www.teamgantt.com/)
- [EleGantt za Trello](https://elegantt.com/)
- [OpenProject](https://www.openproject.org/)
- [Jira](https://www.atlassian.com/software/jira)
- [Monday.com](https://monday.com/)

**Članci:**
- [Scrum of Scrums Guide](https://www.atlassian.com/agile/scrum/scrum-of-scrums)
- [Scaling Agile](https://www.scaledagileframework.com/)

**Videa:**
- [Spotify Engineering Culture Part 1](https://www.youtube.com/watch?v=4GK1NDTWbkY)
- [Spotify Engineering Culture Part 2](https://www.youtube.com/watch?v=X3rGdmoTjDc)

---

## 🎓 **CERTIFIKATI I DALJE UČENJE**

Za studentice koje žele nastaviti s Agile-om:

**Certifikati:**
- **PSM I** (Professional Scrum Master) - Scrum.org
- **CSM** (Certified Scrum Master) - Scrum Alliance
- **SAFe Agilist** - Za enterprise Agile

**Online tečajevi:**
- Coursera: Agile Development Specialization
- Udemy: Agile Crash Course
- LinkedIn Learning: Agile Foundations

---

**KRAJ SINOPSISA - DAN 8** ✅

---

## 🏆 **ZAVRŠETAK AGILE METHODOLOGIES MODULA**

Čestitamo na završetku modula! 

Ovaj modul pokrio je:
- Osnove Agile filozofije i Scrum frameworka
- Praktične vještine planiranja i estimacije
- Metrike za praćenje performansi
- Strategije za uspješnu implementaciju
- Skaliranje Agile-a za veće organizacije

Sretno u vašoj Agile karijeri! 🚀
