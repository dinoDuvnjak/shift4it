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

## 🗺️ Roadmap: 5 Sprinta = 5 Dana

Svaki dan u razredu je jedan Sprint. Komprimirano od realnih 2-tjednih sprintova — ali za edukacijske svrhe savršeno jer svaki dan imaju konkretni deliverable i retrospektivu.

```
SPRINT 1 (Dan 15) ──► Discovery & Kickoff
SPRINT 2 (Dan 16) ──► Research & Requirements
SPRINT 3 (Dan 17) ──► UX Design
SPRINT 4 (Dan 18) ──► UI Design & Prototyping
SPRINT 5 (Dan 19) ──► Testing, Build & Pitch
```

> **Logika slijeda:** Business mora završiti istraživanje i zahtjeve **prije** nego Design može dizajnirati. Design mora završiti wireframes **prije** nego Dev može graditi komponente. Dependencije su označene s ⚠️.

---

## 🏔️ Epici (Epics)

4 Epica koja "žive" kroz sve sprintove:

| Epic | Naziv | Aktivni u sprintovima |
|---|---|---|
| `EPIC-1` | 🔍 Product Discovery & Research | Sprint 1–2 |
| `EPIC-2` | 🎨 UX/UI Design | Sprint 2–4 |
| `EPIC-3` | 💻 Frontend Development (React) | Sprint 1, 4–5 |
| `EPIC-4` | 🚀 Testing, Pitch & Launch | Sprint 5 |

---

## 🏃 SPRINT 1 — Discovery & Kickoff (Dan 15)
*Epics: EPIC-1 + EPIC-3*

> **Cilj sprinta:** Svi timovi postavljaju temelje. Rade **paralelno** — nema međuzavisnosti između timova u ovom sprintu.

### 💼 Business Team

**STORY — Definirati problem i poslovne ciljeve**
- TASK — Istražiti potrebe DIY kupaca
- TASK — Formulirati 3 verzije problem statementa
- TASK — Odabrati i dokumentirati finalni problem statement
- TASK — Identificirati primarne i sekundarne korisnike
- TASK — Napisati business goals dokument

### 🎨 Design Team

**STORY — Provesti benchmark analizu (3 konkurenta)**
- TASK — Analizirati Home Depot DIY
- TASK — Analizirati Leroy Merlin
- TASK — Analizirati Instructables.com
- TASK — Kreirati Competitive Feature Matrix u Figmi

### 💻 Dev Team

**STORY — Postaviti razvojno okruženje**
- TASK — Kreirati GitHub repozitorij
- TASK — Postaviti React projekt (Vite)
- TASK — Napisati README s opisom projekta
- TASK — Definirati folder strukturu komponenti

---

## 🏃 SPRINT 2 — Research & Requirements (Dan 16)
*Epics: EPIC-1 + EPIC-2*

> **Cilj sprinta:** Business završava sve zahtjeve i predaje ih Design timu. Design istražuje korisnika. Dev planira arhitekturu.
> ⚠️ **Dependencija:** Design ne može početi User Journey Map dok Business ne završi User Stories (poželjno do 10:30).

### 💼 Business Team

**STORY — Napisati User Stories za sve 3 core funkcionalnosti**
- TASK — User stories za Workshop Registration
- TASK — User stories za Tutorial Browse
- TASK — User stories za Tool Availability
- TASK — Definirati Acceptance Criteria za svaku story

**STORY — Pripremiti Information Architecture input dokument**
- TASK — Popisati sve stranice/sekcije aplikacije
- TASK — Definirati navigacijsku strukturu (glavni meni, footer)
- TASK — ➡️ Predati Design timu kao input za Sitemap (Sprint 3)

### 🎨 Design Team

**STORY — Kreirati Primary User Personu u Figmi**
- TASK — Definirati demografiju i ponašanje
- TASK — Identificirati ciljeve i frustracije
- TASK — Vizualizirati personu u Figmi

**STORY — Kreirati User Journey Map u Figmi**
- TASK — Mapirati korisnikov put od awareness do booking
- TASK — Identificirati touchpoints i pain points
- TASK — Vizualizirati journey u Figmi
- ⚠️ *Čeka: User Stories od Business tima*

### 💻 Dev Team

**STORY — Planirati komponentnu arhitekturu**
- TASK — Definirati listu React komponenti
- TASK — Kreirati komponentni dijagram
- TASK — Dogovoriti naming convention s Design timom

**STORY — Postaviti routing strukturu**
- TASK — Instalirati React Router
- TASK — Definirati URL strukturu svih stranica

---

## 🏃 SPRINT 3 — UX Design (Dan 17)
*Epic: EPIC-2*

> **Cilj sprinta:** Design tim prolazi kroz cijeli UX proces u logičnom slijedu — svaka story ovisi o prethodnoj. Business daje content i potvrđuje strukturu. Dev koristi sitemap za finalizaciju arhitekture.
> ⚠️ **Dependencija:** Ovaj sprint pretpostavlja da su User Stories i IA input dokument iz Sprinta 2 gotovi.

### 💼 Business Team

**STORY — Potvrditi strukturu aplikacije s Design timom**
- TASK — Pregledati IA input dokument iz Sprinta 2
- TASK — Uskladiti navigacijsku strukturu s Design timom (sync meeting)

**STORY — Pripremiti content za aplikaciju**
- TASK — Napisati copy za Homepage hero sekciju
- TASK — Kreirati 3 sample workshop opisa
- TASK — Kreirati 3 sample tutorial opisa s popisom materijala

### 🎨 Design Team

> ✏️ **Napomena za facilitatora:** Design tim prolazi 4 UX koraka **redom**. Svaki sljedeći korak ovisi o prethodnom — ne mogu se raditi paralelno.

**STORY — Sketching: Brze idejne skice (Figma / papir)**
- TASK — Skicirati 5+ koncepata za Homepage layout
- TASK — Skicirati koncepte za Workshop listing i Tool checker
- TASK — Odabrati 1–2 koncepta za nastavak i dokumentirati razlog odabira

**STORY — User Flow: Mapirati navigacijske putanje (Figma)**
- TASK — Kreirati User Flow za Workshop Registration (happy path + alternativni put)
- TASK — Kreirati User Flow za Tutorial Browse
- TASK — Kreirati User Flow za Tool Availability Checker
- ⚠️ *Čeka: završen Sketching*

**STORY — Sitemap: Vizualizirati strukturu aplikacije (Figma)**
- TASK — Kreirati sitemap (parent/child struktura svih ekrana)
- TASK — Validirati sitemap s IA input dokumentom od Business tima
- ⚠️ *Čeka: završeni User Flows*

**STORY — Low-fi Wireframes: Dizajnirati 5 ekrana (Figma)**
- TASK — Wireframe: Homepage
- TASK — Wireframe: Workshop listing page
- TASK — Wireframe: Tutorial detail page
- TASK — Wireframe: Tool availability checker
- TASK — Wireframe: Booking confirmation
- ⚠️ *Čeka: završen Sitemap*

### 💻 Dev Team

**STORY — Postaviti mock data**
- TASK — Kreirati `workshops.json` s 3 sample radionice
- TASK — Kreirati `tutorials.json` s 3 sample tutoriala
- TASK — Kreirati `tools.json` s dostupnosti materijala

---

## 🏃 SPRINT 4 — UI Design & Prototyping (Dan 18)
*Epics: EPIC-2 + EPIC-3*

> **Cilj sprinta:** Design tim vizualizira i prototypira. Business daje feedback na wireframes iz Sprinta 3. Dev počinje graditi bazne komponente.
> ⚠️ **Dependencija:** Dev ne može graditi komponente dok nema Low-fi Wireframes iz Sprinta 3.

### 💼 Business Team

**STORY — Review wireframes i dati pisani feedback (Jira komentari)**
- TASK — Provjeriti pokrivaju li wireframes sve user stories iz Sprinta 2
- TASK — Dati pisani feedback Design timu putem Jira komentara
- TASK — Potvrditi ili tražiti izmjene — Design tim iterira na osnovu feedbacka

### 🎨 Design Team

**STORY — Kreirati Design System u Figmi**
- TASK — Definirati color palette (primary, secondary, neutral)
- TASK — Odabrati tipografiju (heading + body font)
- TASK — Kreirati button komponentu (primary, secondary, disabled)
- TASK — Kreirati card komponentu (workshop card, tutorial card)

**STORY — Dizajnirati High-fi Mockupe (5 ekrana, Figma)**
- TASK — High-fi: Homepage
- TASK — High-fi: Workshop listing
- TASK — High-fi: Tutorial detail
- TASK — High-fi: Tool availability
- TASK — High-fi: Booking confirmation
- ⚠️ *Čeka: završen Design System*

**STORY — Kreirati interaktivni Figma prototip**
- TASK — Povezati sve ekrane u flow
- TASK — Definirati interakcije i tranzicije
- TASK — Dokumentirati design odluke
- ⚠️ *Čeka: završeni High-fi Mockupi*

### 💻 Dev Team

**STORY — Izgraditi bazne React komponente**
- TASK — Header & Navigation komponenta
- TASK — Footer komponenta
- TASK — WorkshopCard komponenta
- TASK — TutorialCard komponenta
- ⚠️ *Čeka: Low-fi Wireframes iz Sprinta 3*

---

## 🏃 SPRINT 5 — Testing, Build & Pitch (Dan 19)
*Epics: EPIC-3 + EPIC-4*

> **Cilj sprinta:** Design testira prototip s pravim korisnicima i iterira. Dev implementira sve stranice i deploya. Business priprema pitch. Sve se spaja u finalnoj prezentaciji.

### 💼 Business Team

**STORY — Kreirati Pitch prezentaciju**
- TASK — Slide: Problem & rješenje
- TASK — Slide: Target audience i persona
- TASK — Slide: Ključne funkcionalnosti (demo iz Figme + live app)
- TASK — Slide: Što smo naučili (retrospektiva)

**STORY — Definirati Success Metrics**
- TASK — Identificirati KPI-eve za CraftEase (npr. broj bookinga, retention rate)

### 🎨 Design Team

**STORY — Provesti usability test prototipa**
- TASK — Pripremiti 3 task scenarija za testiranje
- TASK — Testirati prototip s 2–3 kolege iz Business ili Dev tima
- TASK — Dokumentirati findings (što je zbunjivalo, što je radilo glatko)

**STORY — Iterirati dizajn na osnovu feedbacka**
- TASK — Implementirati barem 2 izmjene u Figmi na temelju usability testa
- TASK — Ažurirati interaktivni prototip
- ⚠️ *Čeka: završen usability test*

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
| **Roadmap view** | 5 sprinta s Epicima na vremenskoj liniji |
| **Board view** | `To Do → In Progress → In Review → Done` |
| **Backlog** | Sve stories raspoređene po sprintovima |
| **Epic panel** | Postotak završenosti svakog Epica |

> **Napomena:** U Jira free tieru roadmap postoji, ali je ograničen — vidjet ćeš sprintove na timeline-u, što je sasvim dovoljno za edukacijske svrhe.

---

*SHIFT4IT Program | CraftEase Završni Projekt | Dani 15–19*



user flows figma - https://www.figma.com/design/WrlBzv2uB4q1PuRy5CIKvs/02.-User-Flows-Resource?node-id=59177-153&p=f&t=xXjGI1C2zlVqZl2t-0