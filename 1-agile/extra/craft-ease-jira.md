# 🗂️ CraftEase – Jira Scrum Setup
## SHIFT4IT Bootcamp | Simulacija IT Projekta

---

## ⚙️ Osnovna Konfiguracija Projekta

**Projekt tip:** Scrum (ne Kanban)
**Naziv projekta:** CraftEase - SHIFT4IT Bootcamp

### Jira Accounti

| Account | Rola u Scrum-u | Tim |
|---|---|---|
| `craftease-business` | Business Team | 3 studentice |
| `craftease-design` | Design Team | 5 studentice |
| `facilitator` | **Product Owner** | Facilitatorica |

> **Napomena:** Facilitatorica je uvijek **Product Owner** — osoba koja definira što se gradi i zašto. Svaki tim ima **rotacijskog Scrum Mastera** — svaki sprint druga studentica vodi standup i Sprint Review za svoj tim.

### Što facilitatorica pripremi PRIJE Sprint 1 (do 22.04):

- [ ] Kreirati Jira projekt (tip: Scrum)
- [ ] Dodati 3 Epica (vidi dolje)
- [ ] Kreirati 3 sprinta s datumima (23.04 / 05.05 / 07.05)
- [ ] Pozvati studentice na oba account-a
- [ ] Kreirati početni backlog sa Stories za Sprint 1 (ili to rade studentice kao prvi zadatak u Sprint Planningu)
- [ ] Otvoriti Figma projekt sa zajedničkim workspace-om za Design tim

---

## 🗺️ Roadmap: 3 Sprinta = 3 Dana

```
SPRINT 1 (23.04) ──► Discovery & Kickoff
SPRINT 2 (05.05) ──► Research & UX Design
SPRINT 3 (07.05) ──► Hi-fi, Prototip & Pitch
```

> **Logika slijeda:** Business završava istraživanje i zahtjeve **prije** nego Design može dizajnirati navigaciju. Design završava wireframes **prije** Sprint 3. Dependencije su označene s ⚠️.

---

## 🏔️ Epici (Epics)

| Epic | Naziv | Aktivni u sprintovima |
|---|---|---|
| `EPIC-1` | 🔍 Product Discovery & Research | Sprint 1–2 |
| `EPIC-2` | 🎨 UX/UI Design | Sprint 1–3 |
| `EPIC-3` | 🚀 Testing, Pitch & Launch | Sprint 3 |

---

## 🏃 SPRINT 1 — Discovery & Kickoff (23.04)

> **Cilj sprinta:** Svi timovi postavljaju temelje. Rade **paralelno** — nema međuzavisnosti između timova u ovom sprintu.

### ⏰ Tijek dana

```
9:00– 9:10   Lean Startup/MVP briefing (facilitatorica — 10 min)
9:10– 9:25   Sprint Planning u Jiri (svaki tim dodaje tasks)
9:25–10:00   Rad na deliverablima
10:00–10:15  ☕ Pauza
10:15–11:00  Rad na deliverablima
11:00–11:15  ☕ Pauza
11:15–12:00  Rad na deliverablima
12:00–12:30  Sprint Review + Retrospektiva
```

### 📣 Lean Startup/MVP Briefing (9:00–9:10)

Facilitatorica uvodi ovaj koncept prije Sprint Planninga jer direktno objašnjava ZAŠTO radimo 3 mini-sprinta umjesto jedne "savršene" aplikacije:

> *"Umjesto da radimo 3 mjeseca i na kraju pokažemo gotov produkt, mi radimo Build → Measure → Learn. Svaki sprint je MVP — minimum koji možemo pokazati i dobiti feedback. CraftEase nije gotov nakon 3 sprinta, ali je dovoljno konkretan da ga možemo testirati s pravim korisnicima."*

Korisno pitanje za studentice: *"Koji je najmanji set screena koji bi pokazao ključnu vrijednost CraftEase platforme?"*

### 💼 Business Team

**STORY — Definirati problem i ciljnog korisnika** *(EPIC-1)*
- TASK — Desk research: Tko su DIY kupci? Što ih frustrira? (20 min)
- TASK — Formulirati 3 verzije problem statementa (15 min)
- TASK — Odabrati i dokumentirati finalni problem statement u Jiri (10 min)
- TASK — Identificirati primarne korisnike (kupac radionice) i sekundarne (instruktor) (10 min)

**STORY — Napisati draft User Stories** *(EPIC-1)*
- TASK — Draft User Stories za Workshop Registration
- TASK — Draft User Stories za Tutorial Browse
- TASK — Draft User Stories za Tool Availability

> 💡 **Facilitator napomena:** User Stories u Sprint 1 su DRAFT — ne trebaju Acceptance Criteria još. To dolazi u Sprint 2. Format: *"Kao [tip korisnika], želim [akciju], kako bih [cilj]."*

### 🎨 Design Team

**STORY — Benchmark analiza (3 konkurenta)** *(EPIC-1)*
- TASK — Analizirati Home Depot / Hornbach (screenshoti + komentari u Figmi)
- TASK — Analizirati Leroy Merlin ili Bauhaus
- TASK — Analizirati Instructables.com ili sličan DIY portal
- TASK — Kreirati Competitive Feature Matrix u Figmi (tablica: Feature × Konkurent)

**STORY — Kreirati Primary User Personu u Figmi** *(EPIC-2)*
- TASK — Definirati demografiju: dob, zanimanje, iskustvo s DIY projektima
- TASK — Identificirati 3 cilja i 3 frustracije korisnika
- TASK — Vizualizirati personu u Figmi (koristiti Figma Community template)

> 💡 **Facilitator napomena:** Persona treba biti konkretna osoba, ne apstrakcija. Primjer: "Ana, 34, marketingaška menadžerica, živi u stanu, hobi je DIY dekoracija, frustrira je kad nema upute za početnike."

### ✅ Definition of Done — Sprint 1

| Deliverable | Business | Design |
|---|---|---|
| Problem statement | Dokumentiran u Jiri (story description) | — |
| Draft User Stories | Min. 3 stories (po jedna po funkcionalnosti) | — |
| Benchmark | — | Competitive matrix u Figmi |
| Persona | — | Vizualizirana u Figmi |

---

## 🏃 SPRINT 2 — Research & UX Design (05.05)

> **Cilj sprinta:** Business finalizira sve zahtjeve. Design prolazi UX proces redom — svaki korak ovisi o prethodnom.
> ⚠️ **Ključna dependencija:** Design ne može početi User Journey Map dok Business ne završi User Stories. **Cilj: Business predaje Stories do 10:30.**

### ⏰ Tijek dana

```
9:00– 9:15   Sprint Planning u Jiri
9:15–10:30   Rad na deliverablima (Business: finalizira Stories + IA | Design: čeka do 10:30)
10:00–10:15  ☕ Pauza
10:15–10:30  Business predaje IA input dokument Design timu (sync 5 min)
10:30–11:00  Design počinje User Journey Map | Business nastavlja s IA dokumentom
11:00–11:15  ☕ Pauza
11:15–12:00  Design nastavlja Sitemap → User Flow → Lo-fi sketch
12:00–12:30  Sprint Review + Retrospektiva
```

### 💼 Business Team

**STORY — Finalizirati User Stories s Acceptance Criteria** *(EPIC-1)*
- TASK — User Stories za Workshop Registration + Acceptance Criteria (min. 2 kriterija po story)
- TASK — User Stories za Tutorial Browse + Acceptance Criteria
- TASK — User Stories za Tool Availability + Acceptance Criteria

**STORY — IA Input dokument** *(EPIC-1)*
- TASK — Popisati sve stranice/sekcije aplikacije (Home, Workshop List, Workshop Detail, Tutorial List, Tutorial Detail, Booking, Confirmation)
- TASK — Definirati navigacijsku strukturu (glavni meni, footer linkovi)
- TASK — ➡️ **Predati Design timu do 10:30** kao input za Sitemap

> 💡 **Facilitator napomena:** IA Input dokument može biti jednostavan — lista stranica u Jira komentaru ili Google Doc. Bitno je da Design tim zna koje sve stranice postoje prije nego crta Sitemap.

### 🎨 Design Team

> ✏️ **Napomena:** Design tim prolazi 4 UX koraka **redom**. Ne mogu se raditi paralelno — svaki sljedeći korak ovisi o prethodnom.

**STORY — User Journey Map u Figmi** *(EPIC-2)*
- TASK — Mapirati korisnikov put od discovery (čuje za CraftEase) do booking confirmation
- TASK — Identificirati touchpoints (gdje korisnik dolazi u kontakt s platformom)
- TASK — Označiti pain points i opportunities na svakom koraku
- ⚠️ *Čeka: User Stories od Business tima (do 10:30)*

**STORY — Sitemap u Figmi** *(EPIC-2)*
- TASK — Kreirati vizualni sitemap s parent/child strukturom svih stranica
- TASK — Validirati s IA input dokumentom od Business tima
- ⚠️ *Čeka: završen User Journey Map*

**STORY — User Flow u Figmi** *(EPIC-2)*
- TASK — User Flow za Workshop Registration (happy path + što ako nema mjesta?)
- TASK — User Flow za Tutorial Browse (filtriranje + detalj tutoriala)
- ⚠️ *Čeka: završen Sitemap*

**STORY — Lo-fi Wireframes (3–4 screena, Figma)** *(EPIC-2)*
- TASK — Wireframe: Homepage (hero, istaknute radionice, search)
- TASK — Wireframe: Workshop listing (kartice, filter)
- TASK — Wireframe: Workshop detail + Booking forma
- ⚠️ *Čeka: završeni User Flows*

> 💡 **Facilitator napomena:** Lo-fi wireframes su crno-bijele skice — bez boja, bez fontova. Samo layout i struktura. Cilj je brzina, ne ljepota. Ako ne stignu sva 4 screena, 3 su dovoljna za Sprint 3.

### ✅ Definition of Done — Sprint 2

| Deliverable | Business | Design |
|---|---|---|
| User Stories | Sve 3 s Acceptance Criteria u Jiri | — |
| IA Input dokument | Predan Design timu do 10:30 | — |
| User Journey Map | — | U Figmi, s pain points |
| Sitemap | — | U Figmi, validiran s IA doc |
| User Flow | — | Min. 2 flowa u Figmi |
| Lo-fi Wireframes | — | Min. 3 screena u Figmi |

---

## 🏃 SPRINT 3 — Hi-fi, Prototip & Pitch (07.05)

> **Cilj sprinta:** Design vizualizira i prototypira. Business daje brzi feedback i priprema pitch. Na kraju zajednička prezentacija.
> ⚠️ **Ključna dependencija:** Design čeka business feedback (do 9:45) prije nego počne Hi-fi.

### ⏰ Tijek dana

```
9:00– 9:15   Sprint Planning u Jiri
9:15– 9:45   Business pregledava Lo-fi wireframes i piše feedback u Jiru (30 min)
             | Design priprema DaisyUI komponente dok čeka feedback
9:45–10:00   Sync 5 min: Business verbalno prezentira feedback Design timu
10:00–10:15  ☕ Pauza
10:15–11:00  Design radi Hi-fi mockupe (DaisyUI) | Business radi Pitch prezentaciju
11:00–11:15  ☕ Pauza
11:15–11:30  Design spaja screene u Figma prototip
11:30–11:50  Usability test: Design testira prototip s 2 kolegice iz Business tima
11:50–12:00  Priprema za Pitch (svaki tim 2 min)
12:00–12:30  🎤 PITCH + Sprint Review + Retrospektiva
```

### 💼 Business Team

**STORY — Review Lo-fi wireframes i feedback** *(EPIC-2)*
- TASK — Provjeriti pokrivaju li wireframes sve User Stories iz Sprint 2 (checkbox po story)
- TASK — Dati pisani feedback u Jira komentarima (što nedostaje, što je nejasno) — do 9:45
- TASK — Potvrditi ili tražiti izmjene: Design iterira na osnovu feedbacka

**STORY — Kreirati Pitch prezentaciju** *(EPIC-3)*
- TASK — Slide: Problem statement + "Zašto CraftEase postoji"
- TASK — Slide: Naš korisnik (Persona iz Sprint 1)
- TASK — Slide: Ključne funkcionalnosti (3 User Stories, kratko)
- TASK — Slide: Što smo naučili (1 insight iz procesa)

> 💡 **Facilitator napomena:** Pitch je max 5 minuta za svaki tim. Business priča o problemu i korisniku, Design pokazuje prototip u Figmi. Zajedno = jedan produkt.

### 🎨 Design Team

**STORY — Hi-fi Mockupi (3 screena, DaisyUI)** *(EPIC-2)*
- TASK — Primijeniti color palette i tipografiju (orange/antracit/bijela — vidi CraftEase dizajn vodič)
- TASK — Hi-fi: Homepage (hero CTA + istaknute radionice)
- TASK — Hi-fi: Workshop listing (kartice s DaisyUI card komponentom)
- TASK — Hi-fi: Workshop detail + Booking (DaisyUI form + button)
- ⚠️ *Čeka: feedback od Business tima (do 9:45)*

**STORY — Kreirati Figma interaktivni prototip** *(EPIC-2)*
- TASK — Povezati 3 screena u flow (Home → Listing → Detail → Booking)
- TASK — Definirati hover/click interakcije na CTA gumbovima
- ⚠️ *Čeka: završeni Hi-fi mockupi*

**STORY — Mini Usability Test** *(EPIC-3)*
- TASK — Pripremiti 2 test scenarija (koristeći format iz Dana 8: kontekst + zadatak)
- TASK — Testirati prototip s 2 kolegice iz Business tima (5 min po osobi)
- TASK — Dokumentirati min. 3 findings (što je zbunjivalo / što je radilo glatko) u Jiri
- ⚠️ *Čeka: završen prototip*

> 💡 **Facilitator napomena:** Usability test je namjerno kratak — cilj nije savršen test nego da studentice DOŽIVE što je usability testing u praksi (znanje iz Dana 8). 2 sudionice × 5 minuta = 10 minuta testiranja.

### ✅ Definition of Done — Sprint 3

| Deliverable | Business | Design |
|---|---|---|
| Wireframe feedback | Pisani komentari u Jiri | — |
| Pitch prezentacija | 4 slidea, pripremljeno | — |
| Hi-fi mockupi | — | 3 screena s DaisyUI, u Figmi |
| Figma prototip | — | Klikabilni flow, min. 3 screena |
| Usability test findings | — | 3 findings dokumentirani u Jiri |

---

## 🎤 Finalni Pitch (12:00–12:30)

**Format:**
1. Business tim (5 min) — Problem, korisnik, User Stories
2. Design tim (5 min) — Figma prototip walkthrough, usability test insights
3. PO (facilitatorica) — Komentari, "prihvaćam" / "vraćam" stories (5 min)
4. Retrospektiva cijelog projekta (10 min)

**Individualni prikaz:**
Svaka studentica pokazuje **svoju Jira aktivnost** — koliko tasks je kreirala, komentirala, promijenila status. Ovo simulira PM izvještaj o individualnom doprinosu timu.

---

## 🔄 Scrum Ceremonije

### Sprint Planning (9:00–9:15, svaki sprint)

Svaki tim:
1. Pregleda Stories u backlogu za ovaj sprint
2. Procijeni može li sve završiti do 12:00
3. Podijeli Stories na Tasks i dodijeli ih članicama
4. Postavi Tasks na **"To Do"** u Jira boardu

### Sprint Review + Retro (12:00–12:30, svaki sprint)

**Demo (10 min):** Svaki tim prikazuje što je završio:
- Business: Jira board s dovršenim tasks + ključni dokument
- Design: Figma screen(s)

**PO Acceptance (5 min):** Facilitatorica kao PO "prihvaća" ili "vraća" svaku Story:
- ✅ Prihvaćeno: Story prelazi u Done
- 🔄 Vraćeno: Story ostaje otvorena s komentarom što nedostaje

**Retro (10 min):** 3 pitanja:
1. Što je išlo dobro?
2. Što je išlo loše?
3. Što mijenjamo u sljedećem sprintu?

---

## 👁️ Što Studentice Vide u Jiri

| View | Sadržaj |
|---|---|
| **Board view** | `To Do → In Progress → In Review → Done` |
| **Backlog** | Sve Stories raspoređene po sprintovima |
| **Epic panel** | Postotak završenosti svakog Epica |
| **Timeline / Roadmap** | 3 sprinta na vremenskoj liniji |

> **Napomena:** U Jira Free tieru roadmap postoji ali je ograničen — timeline s 3 sprinta je sasvim dovoljan za edukacijske svrhe.

---

## 📊 Individualni prikaz na kraju programa

Svaka studentica priprema kratki **PM summary** svoje aktivnosti:

- Screenshot Jira profila (broj completed tasks, komentara)
- Screenshot Figma screena koji je radila (Design tim)
- 1 rečenica: *"Moj doprinos ovom projektu bio je..."*

Ovo simulira **end-of-sprint report** koji PM studenti u stvarnom poslu pišu.

---

## 🎨 Dizajn smjernice

Za boje, tipografiju i preporučene screene vidi: [CraftEase dizajn vodič](../../0-ux-ui/extra/CraftEase-dizajn-guides.md)

**Kratki podsjetnik za Sprint 3 Hi-fi:**
- Primary: Narančasta / jantarna
- Neutral: Tamno siva / antracit
- Background: Bijela / off-white
- Font: Inter, Manrope ili DM Sans (Bold za naslove, Regular za body)
- DaisyUI komponente: `btn btn-primary`, `card`, `navbar`, `badge`

---

## 🔗 Resursi

User Flows Figma referenca: https://www.figma.com/design/WrlBzv2uB4q1PuRy5CIKvs/02.-User-Flows-Resource?node-id=59177-153&p=f&t=xXjGI1C2zlVqZl2t-0

---

*SHIFT4IT Program | CraftEase Završni Projekt | Sprintovi: 23.04 / 05.05 / 07.05*
