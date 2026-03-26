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
| `craftease-design` | Design Team | 3-4 studentice |
| `craftease-dev` | Dev Team | 3-4 studentice |
| `facilitator` | **Product Owner** | Facilitatorica |

> **Napomena:** Facilitatorica je uvijek **Product Owner** — osoba koja definira što se gradi i zašto. Svaki tim ima **rotacijskog Scrum Mastera** — svaki dan druga studentica vodi dnevni standup za svoj tim.

---

## 🗺️ Roadmap: 4 Sprinta = 4 Dana

Svaki dan u razredu je jedan Sprint. Komprimirano od realnih 2-tjednih sprintova — ali za edukacijske svrhe savršeno jer svaki dan imaju konkretni deliverable i retrospektivu.

```
SPRINT 1 (Dan 15) ──► Discovery & Research
SPRINT 2 (Dan 16) ──► UX Design
SPRINT 3 (Dan 17) ──► UI Design + Dev Setup
SPRINT 4 (Dan 18) ──► Prototype + Code + Pitch
```

---

## 🏔️ Epici (Epics)

4 Epica koja "žive" kroz sve sprintove:

| Epic | Naziv |
|---|---|
| `EPIC-1` | 🔍 Product Discovery & Research |
| `EPIC-2` | 🎨 UX/UI Design |
| `EPIC-3` | 💻 Frontend Development (React) |
| `EPIC-4` | 🚀 Testing, Pitch & Launch |

---

## 🏃 SPRINT 1 — Discovery & Research (Dan 15)
*Epic: EPIC-1 — Product Discovery & Research*

### 💼 Business Team

**STORY — Napisati Problem Statement za CraftEase**
- TASK — Istražiti potrebe DIY kupaca
- TASK — Formulirati 3 verzije problem statementa
- TASK — Odabrati finalnu verziju i dokumentirati

**STORY — Definirati target audience i poslovne ciljeve**
- TASK — Identificirati primarne i sekundarne korisnike
- TASK — Napisati business goals dokument

### 🎨 Design Team

**STORY — Provesti benchmark analizu (3 konkurenta)**
- TASK — Analizirati Home Depot DIY
- TASK — Analizirati Leroy Merlin
- TASK — Analizirati Instructables.com
- TASK — Kreirati Competitive Feature Matrix

**STORY — Kreirati Primary User Personu**
- TASK — Definirati demografiju i ponašanje
- TASK — Identificirati ciljeve i frustracije
- TASK — Vizualizirati personu u Figmi

### 💻 Dev Team

**STORY — Postaviti razvojno okruženje**
- TASK — Kreirati GitHub repozitorij
- TASK — Postaviti React projekt (Create React App / Vite)
- TASK — Napisati README s opisom projekta
- TASK — Definirati folder strukturu komponenti

---

## 🏃 SPRINT 2 — UX Design (Dan 16)
*Epic: EPIC-2 — UX/UI Design*

### 💼 Business Team

**STORY — Napisati User Stories za sve 3 core funkcionalnosti**
- TASK — User stories za Workshop Registration
- TASK — User stories za Tutorial Browse
- TASK — User stories za Tool Availability
- TASK — Definirati Acceptance Criteria za svaku story

**STORY — Kreirati Information Architecture dokument**
- TASK — Nacrtati sitemap aplikacije
- TASK — Definirati navigacijsku strukturu

### 🎨 Design Team

**STORY — Kreirati User Journey Map**
- TASK — Mapirati korisnikov put od awareness do booking
- TASK — Identificirati touchpoints i pain points
- TASK — Vizualizirati journey u Figmi / Miru

**STORY — Dizajnirati Low-fi Wireframes (5 ekrana)**
- TASK — Wireframe: Homepage
- TASK — Wireframe: Workshop listing page
- TASK — Wireframe: Tutorial detail page
- TASK — Wireframe: Tool availability checker
- TASK — Wireframe: Booking confirmation

### 💻 Dev Team

**STORY — Planirati komponentnu arhitekturu**
- TASK — Definirati listu React komponenti
- TASK — Kreirati komponentni dijagram
- TASK — Dogovoriti naming convention s Design timom

**STORY — Postaviti routing strukturu**
- TASK — Instalirati React Router
- TASK — Definirati URL strukturu svih stranica

---

## 🏃 SPRINT 3 — UI Design + Dev Setup (Dan 17)
*Epics: EPIC-2 nastavak + EPIC-3 početak*

### 💼 Business Team

**STORY — Pregledati i odobriti wireframes (Design Review)**
- TASK — Provjeriti pokrivaju li wireframes sve user stories
- TASK — Dati pisani feedback Design timu putem Jira komentara

**STORY — Pripremiti content za aplikaciju**
- TASK — Napisati copy za Homepage hero sekciju
- TASK — Kreirati 3 sample workshop opisa
- TASK — Kreirati 3 sample tutorial opisa s popisom materijala

### 🎨 Design Team

**STORY — Kreirati Design System u Figmi**
- TASK — Definirati color palette (primary, secondary, neutral)
- TASK — Odabrati tipografiju (heading + body font)
- TASK — Kreirati button komponentu (primary, secondary, disabled)
- TASK — Kreirati card komponentu (workshop card, tutorial card)

**STORY — Dizajnirati High-fi mockupe (5 ekrana)**
- TASK — High-fi: Homepage
- TASK — High-fi: Workshop listing
- TASK — High-fi: Tutorial detail
- TASK — High-fi: Tool availability
- TASK — High-fi: Booking confirmation

### 💻 Dev Team

**STORY — Izgraditi bazne React komponente**
- TASK — Header & Navigation komponenta
- TASK — Footer komponenta
- TASK — WorkshopCard komponenta
- TASK — TutorialCard komponenta

**STORY — Postaviti mock data**
- TASK — Kreirati `workshops.json` s 3 sample radionice
- TASK — Kreirati `tutorials.json` s 3 sample tutoriala
- TASK — Kreirati `tools.json` s dostupnosti materijala

---

## 🏃 SPRINT 4 — Prototype + Code + Pitch (Dan 18)
*Epics: EPIC-3 završetak + EPIC-4*

### 💼 Business Team

**STORY — Kreirati Pitch prezentaciju**
- TASK — Slide: Problem & rješenje
- TASK — Slide: Target audience i persona
- TASK — Slide: Ključne funkcionalnosti
- TASK — Slide: Što smo naučili (retrospektiva)

**STORY — Definirati Success Metrics**
- TASK — Identificirati KPI-eve za CraftEase (npr. broj bookinga, retention)

### 🎨 Design Team

**STORY — Kreirati interaktivni Figma prototip**
- TASK — Povezati sve ekrane u flow
- TASK — Definirati interakcije i tranzicije
- TASK — Testirati prototip s kolegicama (usability test)
- TASK — Dokumentirati design odluke

**STORY — Prezentirati dizajn**
- TASK — Pripremiti Figma walkthrough za pitch

### 💻 Dev Team

**STORY — Finalizirati React aplikaciju**
- TASK — Implementirati Workshop Listing stranicu s mock datom
- TASK — Implementirati Tutorial Detail stranicu
- TASK — Implementirati Tool Availability checker
- TASK — Implementirati Booking flow (forma + potvrda)

**STORY — Deploy aplikacije**
- TASK — Deploy na GitHub Pages ili Netlify
- TASK — Testirati responzivnost (mobile + desktop)

---

## 🔄 Scrum Ceremonije u Razredu

### Svako jutro (9:00–9:15) — Daily Standup

Svaki tim ima 5 minuta. Svaka studentica odgovara na 3 pitanja:

1. Što sam radila jučer?
2. Što ću raditi danas?
3. Imam li blocker?

### Kraj svakog dana (12:15–12:30) — Sprint Review + Retro

- Svaki tim prikazuje što je završio (**Demo**)
- 3 pitanja za retro:
  - Što je išlo dobro?
  - Što je išlo loše?
  - Što mijenjamo?
- Facilitatorica kao PO **"prihvaća"** ili **"vraća"** stories

---

## 👁️ Što Studenti Vide u Jiri

| View | Sadržaj |
|---|---|
| **Roadmap view** | 4 sprinta s Epicima na vremenskoj liniji |
| **Board view** | `To Do → In Progress → In Review → Done` |
| **Backlog** | Sve stories raspoređene po sprintovima |
| **Epic panel** | Postotak završenosti svakog Epica |

> **Napomena:** U Jira free tieru roadmap postoji, ali je ograničen — vidjet ćeš sprintove na timeline-u, što je sasvim dovoljno za edukacijske svrhe.

---

*SHIFT4IT Program | CraftEase Završni Projekt | Dani 15–18*