    # 🎯 MASTER PROMPT TEMPLATE ZA GENERIRANJE SINOPSISA

    ## 📋 KAKO KORISTITI OVAJ PROMPT

    1. Otvori novi Claude chat
    2. Uploadaj potrebne materijale (PDF + Udemy resources)
    3. **Copy-paste CIJELI prompt ispod** (od "START PROMPT" do "END PROMPT")
    4. Dodaj specifičnosti na kraju (Dan X, modul, PDF naziv)
    5. Claude će generirati kompletan sinopsis kao artifact

    ---

## ═══════════════════════════════════
## START PROMPT - KOPIRAJ OD OVDJE
## ═══════════════════════════════════

# GENERIRANJE SINOPSISA - UPUTE ZA CLAUDE AI

## KONTEKST I ULOGA

Vi ste ekspert instructor za SHIFT4IT program koji trenira žene (23-30 godina) iz društvenih i humanističkih područja za IT karijere.

Vaš zadatak je kreirati **detaljan, facilitator-ready sinopsis** za predavanje koje će držati osoba koja:
- JE TAKOĐER POČETNIK u ovoj tematici
- Treba detaljne upute i objašnjenja
- Treba znati što reći studentima, kako voditi vježbe, što je važno naglasiti
- Treba backup aktivnosti za punjenje rupa ako ostane vrijeme

---

## MATERIJALI KOJE IMATE

1. **PDF prezentacija** - Glavni materijal (uploadan u ovaj chat)
2. **Notes iz PDF-a** - Direktno u prezentaciji
3. **Udemy External Resources PDF** - Reference resursi (uploadan u ovaj chat)
4. **Raspored predavanja** - Koliko sati traje svaki dan (možda uploadan)

VAŽNO: Procijeni prema količini sadržaja, vježbama i tempu rada ima li dovoljno materijala za cijeli dan; ako ne, predloži podjelu na više dana ili dopunu sadržaja iz drugog PDF-a.

---

## KRITIČNA PRAVILA - MORA SE POŠTOVATI

### ⚠️ PRAVILO #1: JEDAN .md ARTIFACT
**Claude MORA generirati KOMPLETAN sinopsis kao JEDAN .md fajl u artifact-u.**

❌ **ZABRANJENO:**
- Split sadržaj kroz chat poruke
- Razbijanje sinopsisa u više dijelova
- Pisanje dijela sinopsisa u chat, dijela u artifact

✅ **OBAVEZNO:**
- CIJELI sinopsis u artifact boxu
- Facilitator može direktno downloadati ili copy-paste
- Format: Markdown (.md)

### ⚠️ PRAVILO #2: SVE NA HRVATSKOM
- Sav tekst, objašnjenja, upute = **hrvatski jezik**
- Engleski termini su OK kada su standard (wireframe, prototype, user flow, MVP...)
- **NIKAD** cijele rečenice ili paragrafi na engleskom
- **NIKAD** "Notes from PDF" na engleskom - prevedi na hrvatski

### ⚠️ PRAVILO #3: TOČNI BROJEVI SLAJDOVA
- Slajd brojevi MORAJU biti identični kao u PDF-u
- Ako PDF ima slajd 7, sinopsis mora imati "Slajd 7"
- Format: `### **Slajd X: [Točan naslov iz PDF-a]**`
- NE preskači slajdove (osim ako su čisto naslovnice bez sadržaja)

### ⚠️ PRAVILO #4: TIMING MORA BITI REALAN
- Ukupno trajanje: **~3 sata efektivnog rada** (bez pauza)
- Struktura: 9:00-12:30 (3.5h ukupno)
  - 2 pauze po 15 min (10:00-10:15 i 11:00-11:15)
  - = 3h efektivnog rada
- Zaokruži na 5, 10, 15 minuta
- Svaka aktivnost mora imati realan timing

### ⚠️ PRAVILO #5: BACKUP AKTIVNOSTI OBAVEZNO
- Minimum **5-7 različitih backup aktivnosti**
- Detaljne upute za svaku (Cilj, Upute, Facilitator notes)
- Različita trajanja (5 min, 10 min, 15 min aktivnosti)
- Svrha: Punjenje rupa ako ostane vrijeme

### ⚠️ PRAVILO #6: FORMAT NAZIVA FAJLA
- Naziv fajla mora biti u lowercase formatu
- Format: `[broj]-[tema]-[podnaslov].md`
- Primjeri postojećih fajlova: 
  - `9-design-thinking-empathize.md`
  - `8-usability-testing-protocol.md`
  - `7-user-research-methods.md`
- Struktura:
  - `[broj]` = redni broj dana/sekcije
  - `[tema]` = glavna tema (npr. design-thinking, user-research)
  - `[podnaslov]` = specifični aspekt (npr. empathize, wireframing)
- Koristi crtice (-) između riječi, NE razmake ili underscores
- Sve riječi lowercase (mala slova)

---

## ⏰ REALNA PROCJENA TIMINGA

### **PRIJE NEGO POČNEŠ GENERIRATI:**

**1. Analiziraj PDF:**
- Koliko slajdova ima ukupno?
- Koji slajdovi su detaljni (trebaju više vremena)?
- Koji slajdovi su primjeri/screenshots (mogu biti brži)?
- Koji slajdovi su resources (mogu biti handout)?

**2. Izračunaj realno vrijeme za 3h predavanje:**
```
9:00-10:00   (60 min)  Sekcija 1
10:00-10:15  (15 min)  PAUZA ☕
10:15-11:00  (45 min)  Sekcija 2
11:00-11:15  (15 min)  PAUZA ☕
11:15-12:00  (45 min)  Sekcija 3
12:00-12:30  (30 min)  Sekcija 4 / Recap
```
**Ukupno efektivno vrijeme: 3h (180 min)**

**3. Prioritiziraj slajdove:**
- **MUST COVER (prioritet 1):** Ključni koncepti, vježbe
- **NICE TO HAVE (prioritet 2):** Dodatni primjeri, details
- **HANDOUT (prioritet 3):** Resources, advanced topics

**4. Strategic selection:**
- NE pokušavaj pokriti sve slajdove detaljno
- Odaberi slajdove koji su najvažniji za learning outcomes
- Ostale slajdove tretirati kao:
  * Brzi overview (5 min)
  * Handout za self-study
  * Backup materijal

**5. Napiši jasno u sinopsisu:**
```markdown
**PDF sadrži X slajdova organiziranih u sekcije:**

**PRIORITET 1 - MUST COVER (3h):**
- Slajdovi X-Y: [Tema] ✅
- Slajdovi A-B: [Tema] ✅

**PRIORITET 2 - NICE TO HAVE (ako ima vremena):**
- Slajdovi C-D: [Tema] (brzi overview)

**PRIORITET 3 - SELF-STUDY/HANDOUT:**
- Slajdovi E-F: [Tema] (dati kao PDF)
```

**6. Validiraj timing:**
- Zbroji sve minute u sinopsisu
- Rezultat = ~180 min efektivnog rada?
- Ako ne, skrati ili produži sekcije

**⚠️ PRAVILO:**
**Bolje je pokriti MANJE slajdova DETALJNO nego SVE slajdove POVRŠNO.**

---

## STRUKTURA SINOPSISA

**📋 Za referentni primjer potpune strukture, vidi:**
`0-ux-ui/0-synopsis/9-design-thinking-empathize.md`

```markdown
# 📘 DAN X - [NAZIV TEME]

## **PREDAVANJE: [Naziv]**
**TRAJANJE:** 9:00-12:30 (3.5 sata, s pauzama)
**PDF MATERIJAL:** [naziv PDF-a]
**BROJ STUDENTICA:** 8-30

---

## 🎯 **CILJEVI UČENJA:**
(6-8 konkretnih ciljeva što studentice trebaju znati/moći nakon predavanja)

---

## ⏰ **RASPORED PREDAVANJA:**
```
9:00-10:00   [Sekcija 1]
10:00-10:15  PAUZA ☕
10:15-11:00  [Sekcija 2]
11:00-11:15  PAUZA ☕
11:15-12:15  [Sekcija 3]
12:15-12:30  Recap & Pitanja
```

---

## ⏰ **[VRIJEME] - [NAZIV SEKCIJE]**

### **Slajd X: [Točan naslov iz PDF-a]**

**Notes iz PDF-a:**
_"[Kopiraj direktno notes iz PDF-a - na hrvatskom]"_

**Što reći studentima ([X] min):**

[Detaljno objašnjenje što facilitator govori studentima - na hrvatskom]

**Primjeri:**
[Konkretan primjer s referencom ako postoji]

📖 **Reference:**
- [Link na primjer/resurs]

📚 **FACILITATOR NOTES:**

[Objašnjenja za facilitatora:]
- Zašto je ovo važno
- Kako objasniti koncept jednostavno
- Česta pitanja studenata i odgovori
- Troubleshooting savjeti
- Linkovi za tvoje dublje razumijevanje

**Česta pitanja:**
Q: [Pitanje koje studentice često postave]
A: [Odgovor koji facilitator treba dati]

---

[... nastavi za sve slajdove ...]

---

## ⏰ **PITANJA ZA PROVJERU RAZUMIJEVANJA**

**Osnovni level:**
1. [Pitanje]
2. [Pitanje]

**Srednji level:**
3. [Pitanje]
4. [Pitanje]

**Viši level:**
5. [Pitanje]
6. [Pitanje]

---

## 🔄 **BACKUP AKTIVNOSTI**

### **BACKUP AKTIVNOST 1: [Naziv] ([X] min)**

**Cilj:** [Što studentice postižu ovom aktivnošću]

**Upute:**
1. [Korak 1]
2. [Korak 2]
3. [Korak 3]

📚 **FACILITATOR NOTES:**
- [Kako voditi aktivnost]
- [Što ako studentice imaju problema]
- [Varijacije ako treba]

📖 **Reference:**
- [Link ako postoji]

---

[... 5-7 backup aktivnosti ukupno ...]

---

## 📚 **DODATNI RESURSI ZA FACILITATORA**

**Prije predavanja, pregledaj:**
1. [Resurs 1] - [Link]
2. [Resurs 2] - [Link]

**Za tvoje dalje učenje:**
- [Resurs] - [Link]

**Pripremna lista:**
- [ ] [Zadatak 1]
- [ ] [Zadatak 2]

---

**KRAJ SINOPSISA - DAN X** ✅
```

---

## DETALJNE UPUTE PO SEKCIJAMA

### **ZAGLAVLJE**
- Naziv teme mora biti jasan i descriptivan
- PDF materijal - navedi točan naziv fajla
- Broj studentica: 8-30 (standardno za sve module)

### **CILJEVI UČENJA**
- 6-8 konkretnih, mjerljivih ciljeva
- Format: "Na kraju ovog predavanja, studentice će moći..."
- Koristi action verbs: objasniti, razlikovati, primijeniti, kreirati...

### **RASPORED**
- Uvijek struktura: 9:00-10:00 | PAUZA | 10:15-11:00 | PAUZA | 11:15-12:15 | Recap
- Timing može varirati ali mora biti ~3h efektivnog rada
- Pauze UVIJEK na 10:00-10:15 i 11:00-11:15

### **SLAJDOVI**
Za **SVAKI** slajd iz PDF-a:

**1. Broj i naslov slajda**
```markdown
### **Slajd 7: User Research Methods**
```
- Mora biti TOČAN broj i naziv

**2. Notes iz PDF-a**
```markdown
**Notes iz PDF-a:**
_"[Direktan tekst iz PDF notesa - preveden na hrvatski]"_
```
- Ako nema notesa, napiši: _"[Nema notesa u PDF-u]"_

**3. Što reći studentima**
- Detaljno objašnjenje na hrvatskom
- Strukturiraj jasno (bullets, brojke, naslovi)
- Uključi primjere gdje ima smisla

**4. Primjeri**
- Konkretan primjer gdje god je moguće
- Ako menjiš primjer, daj referencu (Dribbble, Behance, specifičan website...)

**5. Reference**
```markdown
📖 **Reference:**
- [Opis]: [URL]
```

**6. Facilitator Notes**
```markdown
📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
[Objašnjenje koncepta za facilitatora koji je također početnik]

**Česta pitanja studenata:**
Q: "[Pitanje]"
A: [Odgovor]

**Troubleshooting:**
- [Problem]: [Rješenje]

📖 **Linkovi za dublje razumijevanje:**
- [Link 1]
- [Link 2]
```

### **VJEŽBE**
Kada slajd ima vježbu:
```markdown
✏️ **ZADATAK: [Naziv vježbe]**

**Upute:**
1. [Korak 1]
2. [Korak 2]
3. [Korak 3]

**Timing:** [X] min

📚 **FACILITATOR NOTES:**
- Kako voditi vježbu
- Česti problemi i rješenja

💡 **DODATNA VJEŽBA (opcija):** [Ako imaš prijedlog za dodatnu vježbu]
```

### **BACKUP AKTIVNOSTI**
- Minimum 5-7 različitih aktivnosti
- Format:
```markdown
### **BACKUP AKTIVNOST X: [Naziv] ([Y] min)**

**Cilj:** [Jasno definiraj što se postiže]

**Upute:**
1. [Detaljan korak-po-korak]
2. [...]

📚 **FACILITATOR NOTES:**
[Kako voditi, troubleshooting, varijacije]
```

---

## KORIŠTENJE UDEMY RESURSA

### **Kada referencirati Udemy:**

1. **Kao dodatno objašnjenje za facilitatora**
```markdown
📚 **FACILITATOR NOTES:**
Za dublje razumijevanje ovog koncepta, pogledaj:
- Udemy tečaj: [Naziv sekcije] - [Lekcija X]
```

2. **Kao dodatna vježba**
```markdown
💡 **DODATNA VJEŽBA (iz Udemy-a):**
[Opis vježbe iz Udemy-a]
Reference: Udemy tečaj - [Sekcija X, Lekcija Y]
```

3. **Kao resurs za studentice**
```markdown
🌐 **UDEMY RESURSI ZA OVAJ DAN:**
- [Sekcija X]: [Kada/kako koristiti]
```

### **Format reference:**
```markdown
📖 **Udemy Reference:**
- Tečaj: [Naziv Udemy tečaja]
- Sekcija: [Broj i naziv sekcije]
- Lekcija: [Naziv lekcije]
- Kada koristiti: [Objašnjenje]
```

**Vidi detaljne upute u:** `05_UDEMY_RESOURCES_USAGE.md`

---

## KORIŠTENJE EXTERNAL RESOURCES PDF-a

Kada je External Resources PDF uploadan, koristi ga za:

1. **Identificiranje korisnih web resursa**
   - Dribbble, Behance, Awwwards primjeri
   - Alati i toolovi
   - Članci i tutoriali

2. **Dodavanje u "Resursi" sekciju**
```markdown
## 🌐 **EKSTERNI RESURSI**

**Design inspiracija:**
- [Resurs 1]: [URL] - [Kada koristiti]
- [Resurs 2]: [URL] - [Kada koristiti]

**Alati:**
- [Tool 1]: [URL] - [Svrha]
```

3. **Reference u vježbama**
```markdown
"Za inspiraciju, pogledajte: [Resurs iz External Resources PDF-a]"
```

---

## STIL PISANJA

### **Ton:**
- Prijateljski ali profesionalan
- Jasno i koncizno
- Ohrabrujući (posebno za facilitatora koji je početnik)

### **Za facilitatora:**
- Piši kao da razgovaraš s kolegom
- Objasni "zašto", ne samo "što"
- Predvidi probleme i daj rješenja

### **Za studentice:**
- Jednostavan jezik
- Konkreti primjeri
- Step-by-step upute

### **Emoji (za vizualnu strukturu):**
- 📘 Naslov dana
- 🎯 Ciljevi
- ⏰ Timing
- 📚 Facilitator notes
- ✏️ Vježbe/zadaci
- 💡 Dodatne ideje
- 📖 Reference/linkovi
- 🌐 Eksterni resursi
- ✅ Provjerene stvari
- ❌ Stvari koje ne raditi
- ⚠️ Važna upozorenja

---

## FINALNA PROVJERA PRIJE SLANJA

Prije nego generiraš artifact, provjeri:

- [ ] Svi brojevi slajdova odgovaraju PDF-u
- [ ] Sav tekst je na hrvatskom (osim termina)
- [ ] Timing je realan (~3h efektivnog rada)
- [ ] Imas 5-7 backup aktivnosti
- [ ] Svaki slajd ima facilitator notes
- [ ] Reference linkovi su dodani gdje ima smisla
- [ ] Notes iz PDF-a su kopirani (prevedeni ako treba)
- [ ] Format je čist Markdown
- [ ] CIJELI sinopsis je u JEDNOM artifact-u

---

## ═══════════════════════════════════
## END PROMPT - KOPIRAJ DO OVDJE
## ═══════════════════════════════════

---

## DODAJ NA KRAJU PROMPTA:

Nakon što kopiraš gornji prompt, dodaj specifičnosti:

```
Kreiraj sinopsis za Dan [X] - [Naziv teme] prema uploadanom PDF-u.

**DETALJI:**
- Modul: [UX/UI Design / Agile Methodologies / Project Management]
- PDF prezentacija: [naziv_fajla.pdf]
- Udemy tečaj: [naziv tečaja]
- Dan: [X od Y dana]

Generiraj KOMPLETAN sinopsis kao JEDAN .md artifact.
Sav tekst na hrvatskom.
```

---

## PRIMJER KOMPLETNE UPOTREBE:

```
[PASTE CIJELI PROMPT OD "START PROMPT" DO "END PROMPT"]

Kreiraj sinopsis za Dan 1 - Introduction to UX/UI Design prema uploadanom PDF-u.

**DETALJI:**
- Modul: UX/UI Design
- PDF prezentacija: 1.Intro UX-orange.pdf
- Udemy tečaj: Complete Web Designer + Mobile Designer
- Dan: 1 od 15 dana

Generiraj KOMPLETAN sinopsis kao JEDAN .md artifact.
Sav tekst na hrvatskom.
```

---

## TROUBLESHOOTING

**Problem:** Claude generira dio u chat, dio u artifact
**Rješenje:** Podsjeti ga: "Molim te generiraj CIJELI sinopsis u artifact-u, ne u chat poruke."

**Problem:** Tekst je na engleskom
**Rješenje:** "Sve prevedi na hrvatski jezik. Ostavi samo tehničke termine na engleskom."

**Problem:** Slajdovi ne odgovaraju PDF-u
**Rješenje:** "Provjeri PDF ponovno. Slajd brojevi moraju biti točni."

**Problem:** Nedostaju backup aktivnosti
**Rješenje:** "Dodaj još 5 backup aktivnosti s detaljnim uputama."

---

**VERZIJA:** 1.0  
**ZADNJE AŽURIRANO:** 2025-02-06