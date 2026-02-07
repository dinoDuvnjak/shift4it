# 🎓 UDEMY RESOURCES USAGE - VODIČ ZA KORIŠTENJE

## 🎯 SVRHA DOKUMENTA

Ovaj dokument objašnjava **kako i kada koristiti Udemy resurse** pri generiranju sinopsisa za SHIFT4IT program.

**Cilj:** Maksimalno iskoristiti Udemy tečaj kao dopunski izvor materijala i vježbi.

---

## 📚 ŠTO SU UDEMY RESURSI?

### **Definicija:**
Za svaki modul SHIFT4IT programa postoji **Udemy tečaj** koji služi kao:
- Referentni materijal za facilitatora
- Izvor dodatnih vježbi
- Alternativna objašnjenja koncepata
- Dopuna za nedostatke u PDF prezentacijama

### **External Resources PDF:**
Uz svaki Udemy tečaj dolazi **External Resources PDF** koji sadrži:
- Linkove na tools i resources
- Web članke i tutoriale
- Design inspiraciju (Dribbble, Behance...)
- Reference materijale

---

## 🎓 UDEMY TEČAJEVI PO MODULIMA

### **UX/UI DESIGN:**
```
Tečaj: "Complete Web Designer + Mobile Designer: Zero to Mastery"
Instruktor: [Ime]
Platforma: Udemy
External Resources: websites-and-resources-by-section.md
```

**Relevantne sekcije za SHIFT4IT:**
1. **Sketching** - Section X
2. **Inspiration** - Section X
3. **User Flows** - Section X
4. **Sitemaps** - Section X
5. **Wireframes** - Section X
6. **Prototyping** - Section X
7. **Design Systems** - Section X
8. **Mobile Design** - Section X
9. **Visual Design** - Section X

### **AGILE METHODOLOGIES:**
```
Tečaj: [Dodati naziv kad bude dostupan]
Instruktor: [Ime]
Platforma: Udemy
External Resources: [PDF naziv]
```
[TBD - Update kad Agile modul postane aktivan]

### **PROJECT MANAGEMENT:**
```
Tečaj: [Dodati naziv kad bude dostupan]
Instruktor: [Ime]
Platforma: Udemy
External Resources: [PDF naziv]
```
[TBD - Update kad PM modul postane aktivan]

---

## 📤 UPLOADANJE UDEMY RESURSA

### **OPCIJA A: Upload JEDNOM na početku chata (PREPORUČENO)**

#### **Prednosti:**
✅ Claude ima **stalni pristup** resursima
✅ Može **referencirati kroz cijelo generiranje**
✅ Ne moraš pamtiti uploadati svaki put
✅ Konzistentno korištenje resursa kroz sve sinopsise

#### **Mane:**
❌ Povećava **context length** (više tokena)
❌ Može sporiti generiranje (minimalno)

#### **Kako:**
```
1. Otvori novi Claude chat
2. Upload PRVO:
   - External Resources PDF
   - Ostali materijali (raspored, guidelines...)
3. Zatim upload PDF za Dan 1
4. Copy-paste master prompt
5. Dodaj: "Koristi Udemy resurse iz External Resources PDF-a gdje ima smisla"
```

#### **Kada uploadaš više dana:**
```
Dan 1:
- Upload: External Resources (jednom)
- Upload: Dan_1_prezentacija.pdf
- Generate sinopsis

Dan 2:
- External Resources je već tu!
- Upload samo: Dan_2_prezentacija.pdf
- Generate sinopsis

Dan 3:
...itd.
```

---

### **OPCIJA B: Upload External Resources za svaki dan posebno**

#### **Prednosti:**
✅ Manji **context** (brže generiranje)
✅ Fokusiraniji pristup

#### **Mane:**
❌ Moraš **uploadati svaki put**
❌ Lako zaboraviti
❌ Inconsistency između dana

#### **Kako:**
```
Za svaki dan:
1. Otvori novi chat (ili nastavi postojeći)
2. Upload: 
   - External Resources PDF
   - Dan_X_prezentacija.pdf
3. Copy-paste prompt
4. Generate sinopsis
```

---

### **🏆 PREPORUKA: OPCIJA A**

```
NAJBOLJA PRAKSA:
- Upload External Resources PDF JEDNOM na početku
- Reci Claude-u eksplicitno: "Koristi Udemy resurse gdje ima smisla"
- Claude će sam odlučiti kada su relevantni
```

**Razlog:** Konzistentnost i manje manualnog rada.

---

## 🕐 KADA KORISTITI UDEMY RESURSE

### **Situacija 1: PDF prezentacija nema dovoljno detalja**

#### **Primjer:**
```
PDF slajd kaže:
"User research methods"
[Bullet points, bez objašnjenja]
```

#### **Udemy dopuna:**
```markdown
📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
User research metode dijele se na qualitative i quantitative...

💡 **UDEMY DOPUNA:**
Za detaljnije objašnjenje user research metoda, pogledaj:
- Udemy tečaj: Section 3 - "User Research Basics"
- Lekcija 8: "Interview Techniques"
- Lekcija 9: "Survey Design"

Ove lekcije pokrivaju:
- Kako voditi user intervjue (step-by-step)
- Najbolje prakse za survey pitanja
- Analiza research findings
```

---

### **Situacija 2: Trebaju dodatne vježbe**

#### **Primjer:**
```
PDF ima samo 1 vježbu za wireframing, ali treba nam više prakse.
```

#### **Udemy dopuna:**
```markdown
✏️ **ZADATAK 1: Wireframing Homepage (iz PDF-a)**
[Osnovna vježba]

💡 **DODATNA VJEŽBA (iz Udemy-a):**

**ZADATAK 2: Wireframing Mobile App Screen**

**Izvor:** Udemy Section 7 - Exercise 3

**Cilj:** Primijeniti wireframing principe na mobilni layout

**Upute:**
1. Odaberi jedan screen iz popularne app (Instagram, Spotify...)
2. Wireframe taj screen u Figma (20 min)
3. Fokus na:
   - Layout hierarchy
   - Content placement
   - CTA pozicija

📖 **Reference:**
- Udemy Lekcija: "Mobile Wireframing Best Practices"
- Primjer iz tečaja: [screenshot link]
```

---

### **Situacija 3: Trebaju reference primjeri ili slike**

#### **Primjer:**
```
PDF objašnjava "design patterns" ali nema vizualnih primjera.
```

#### **Udemy dopuna:**
```markdown
**Što reći studentima (10 min):**

Design patterns su uobičajena rješenja za česte UX probleme...

**Primjeri:**
Pogledajte [Udemy Section 12 - Design Patterns Gallery] za:
- Navigation patterns (hamburger menu, tab bar, bottom sheet)
- Form patterns (multi-step, inline validation)
- Loading patterns (skeleton screens, progress bars)

📖 **Reference iz External Resources:**
- [Design Patterns Library](http://ui-patterns.com/patterns)
- [Mobbin - Pattern Examples](https://mobbin.com)

Ovi resursi pokazuju kako top apps koriste svaki pattern.
```

---

### **Situacija 4: Trebaju alternative objašnjenja**

#### **Primjer:**
```
PDF objašnjava "grid systems" tehnički, studentice ne razumiju.
```

#### **Udemy dopuna:**
```markdown
📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Grid system je kao sheet of paper s linijama...
[Basic objašnjenje]

**Ako studentice i dalje ne razumiju:**

💡 **ALTERNATIVNO OBJAŠNJENJE (iz Udemy-a):**
Udemy instruktor koristi odličnu analogiju:
"Grid je kao šahovska ploča - sve se postavlja po pravilima."

Pogledaj Udemy Section 9 - "Grid Systems Made Easy":
- Lekcija 15: "8pt Grid Introduction" (video 10 min)
- Lekcija 16: "Practical Grid Application" (demo)

Pokazuje kako grid olakšava:
- Alignment između elemenata
- Consistent spacing
- Faster design decisions
```

---

## 🔧 KAKO CLAUDE INTEGRIRA UDEMY RESURSE

### **Format dopune:**

```markdown
💡 **UDEMY DOPUNA:**
[Opis što se nalazi u Udemy tečaju i zašto je korisno]

**Relevantne lekcije:**
- Section X: [Naziv sekcije]
- Lekcija Y: [Naziv lekcije]

**Što pokriva:**
- [Point 1]
- [Point 2]

📖 **Linkovi iz External Resources PDF-a:**
- [Resource 1]: [URL] - [Kada koristiti]
- [Resource 2]: [URL] - [Kada koristiti]
```

### **Primjer u praksi:**

```markdown
### **Slajd 10: Typography Basics**

**Notes iz PDF-a:**
_"Typography is important for readability and hierarchy."_

**Što reći studentima (10 min):**

Typography (tipografija) je art i znanost postavljanja teksta...
[Osnovno objašnjenje]

💡 **UDEMY DOPUNA:**

Udemy tečaj ima odličan deep-dive u typography:
- **Section 11:** "Typography for Web and Mobile"
- **Lekcija 22:** "Font Pairing Principles"
- **Lekcija 23:** "Hierarchy with Type"

**Što pokriva:**
- Kako odabrati fontove koji rade zajedno
- Creating visual hierarchy s veličinom i težinom fonta
- Accessibility considerations (font size, line height)

📖 **Tools iz External Resources:**
- [Google Fonts](https://fonts.google.com) - Free web fonts
- [Font Pair](https://fontpair.co) - Font pairing suggestions
- [Type Scale Calculator](https://type-scale.com) - Typography scales

**Kada koristiti:**
- Prije vježbe dizajniranja
- Ako studentice pitaju "Koji font da koristim?"
- Za tvoje dodatno učenje prije predavanja
```

---

## 📝 PRAVILA ZA KORIŠTENJE UDEMY RESURSA

### **✅ KORISTI Udemy resurse:**

1. **Kada PDF nema dovoljno detalja**
   - Kratak opis → Udemy ima dublje objašnjenje
   
2. **Kada trebaju dodatne vježbe**
   - PDF ima 1 vježbu → Udemy ima 3-4 exercises
   
3. **Kada trebaju vizualni primjeri**
   - PDF je text-heavy → Udemy ima screenshots/demos
   
4. **Kada trebaju linkovi na tools**
   - External Resources PDF ima kuriranu listu
   
5. **Za facilitatorovo učenje**
   - Facilitator Notes: "Za dublje razumijevanje, pogledaj..."

### **❌ NE koristi Udemy resurse:**

1. **Kada PDF već ima sve što treba**
   - Ne dupliciraj sadržaj
   
2. **Kada Udemy nije relevantan za taj specifični slajd**
   - Ne forciraj reference
   
3. **Kada bi overwhelmalo facilitatora**
   - Ne preopterećuj s linkovovima
   
4. **Kada nema direktne veze s temom**
   - Stay focused

### **⚖️ BALANS:**

```
Preporučeni omjer:
70% PDF sadržaj (primary)
30% Udemy dopuna (supplementary)

Ne zamijeni PDF s Udemy-om.
Udemy je DODATAK, ne zamjena.
```

---

## 🗂️ FORMATIRANJE UDEMY REFERENCI

### **U Facilitator Notes:**

```markdown
📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
[Osnovno objašnjenje]

💡 **UDEMY DOPUNA:**
Za dodatne detalje, pogledaj:
- Udemy tečaj: "Complete Web Designer"
- Section 5: "Wireframing Fundamentals"
- Lekcija 12: "Low-Fidelity vs High-Fidelity"

📖 **Linkovi za dublje razumijevanje:**
- [Link 1 iz External Resources]
- [Link 2 iz External Resources]
```

### **U Vježbama:**

```markdown
✏️ **ZADATAK: [Naziv]**

[Osnovne upute iz PDF-a]

💡 **DODATNA VJEŽBA (opcija iz Udemy-a):**

**Izvor:** Udemy Section X - Exercise Y

**Cilj:** [Specifičan cilj]

**Upute:**
[Step-by-step iz Udemy-a]

📖 **Reference:**
- Udemy demo: [Link ili opis gdje naći]
```

### **U External Resources sekciji:**

```markdown
## 🌐 **EKSTERNI RESURSI**

**Udemy tečaj preporuke za ovaj dan:**
- Section X: [Naziv] - Pogledaj prije predavanja
- Lekcija Y: [Naziv] - Koristi kao demo
- Exercise Z: [Naziv] - Dodatna vježba ako ima vremena

**Tools iz External Resources PDF-a:**
- [Tool 1]: [URL] - [Svrha]
- [Tool 2]: [URL] - [Svrha]

**Članci iz External Resources PDF-a:**
- [Article 1]: [URL] - [Kada pročitati]
- [Article 2]: [URL] - [Kada pročitati]
```

---

## 💻 WORKFLOW S UDEMY RESURSIMA

### **PRIJE GENERIRANJA SINOPSISA:**

```
KORAK 1: Pripremi materijale
├── External Resources PDF (za Udemy links)
├── PDF prezentacija za Dan X
└── Raspored predavanja (ako ima)

KORAK 2: Otvori Claude chat
└── Upload sve materijale

KORAK 3: Copy-paste master prompt
└── Dodaj liniju: "Koristi Udemy resurse iz External Resources PDF-a gdje ima smisla"

KORAK 4: Generate sinopsis
└── Claude automatski integrira Udemy gdje je relevantno
```

### **TIJEKOM GENERIRANJA:**

```
Ako Claude NE referencira Udemy dovoljno:

"Molim te dodaj više Udemy dopuna gdje je relevantno:
- Facilitator notes: Linkovi za dublje učenje
- Vježbe: Dodatne exercise opcije iz Udemy-a
- External resources sekcija: Kurirana lista Udemy lekcija za ovaj dan"
```

### **NAKON GENERIRANJA:**

```
PROVJERA:
- [ ] Je li Udemy referenciran gdje ima smisla?
- [ ] Jesu li Udemy reference konkretne? (Section X, Lekcija Y)
- [ ] Jesu li External Resources linkovi uključeni?
- [ ] Je li balans 70/30 (PDF / Udemy)?
```

---

## 🎯 SPECIFIČNI USE CASES

### **USE CASE 1: Facilitator je potpuni početnik u temi**

**Problem:** Facilitator ne razumije koncept dovoljno da ga objasni.

**Udemy rješenje:**
```markdown
📚 **FACILITATOR NOTES:**

**PRIJE PREDAVANJA, OBAVEZNO POGLEDAJ:**
- Udemy Section 4 - "User Flows Complete Guide"
- Lekcija 10: "What is a User Flow?" (8 min video)
- Lekcija 11: "Creating Your First User Flow" (12 min demo)

Ove lekcije će ti dati:
- Clear razumijevanje što je user flow
- Step-by-step kako ga kreirati
- Common mistakes to avoid

**Nakon gledanja, bit ćeš spreman/a objasniti studentima:**
[Onda ide objašnjenje]
```

---

### **USE CASE 2: PDF vježba je preskromna**

**Problem:** PDF ima samo "Kreiraj wireframe" bez detalja.

**Udemy rješenje:**
```markdown
✏️ **ZADATAK 1: Wireframing Homepage (iz PDF-a)**

**Upute:**
"Kreiraj wireframe za homepage."

💡 **ENHANCED VERSION (s Udemy guidance):**

**Izvor:** Udemy Section 7 - Wireframing Project

**Detaljne upute:**
1. Definiraj content hierarchy (5 min):
   - Header s navigation
   - Hero section s CTA
   - 3 feature sections
   - Footer

2. Sketch na papiru (10 min):
   - Low-fidelity
   - Focus na layout, ne detalje

3. Digital wireframe u Figmi (15 min):
   - Use Figma auto-layout
   - Keep it grayscale
   - Label sections

📖 **Reference:**
- Udemy demo: Section 7, Lekcija 15
- Example wireframes u Udemy Resources folderu
```

---

### **USE CASE 3: Studentice trebaju inspiraciju**

**Problem:** Studentice ne znaju gdje početi dizajn.

**Udemy rješenje:**
```markdown
**Prije vježbe (5 min exploration):**

Pogledajte Udemy inspiration gallery:
- Section 2 - "Design Inspiration Resources"
- Lekcija 4: "Where to Find Great Design"

📖 **Ili koristite External Resources:**
- [Dribbble - Mobile Design](https://dribbble.com/tags/mobile-design)
- [Behance - UX Projects](https://www.behance.net/search/projects?field=ux)
- [Mobbin - App Screenshots](https://mobbin.com)

**Zadatak:**
- 5 min browse
- Bookmark 2-3 dizajna koji vam se sviđaju
- Note što vam se sviđa (colors? layout? animations?)
- Use insights kao inspiration za svoju vježbu
```

---

## 📊 TRACKING UDEMY USAGE

### **Per sinopsis:**
```markdown
## 🎓 **UDEMY RESURSI ZA OVAJ DAN**

**Preporučene lekcije za facilitatora:**
1. Section X - Lekcija Y: [Naziv] (watch before class)
2. Section A - Lekcija B: [Naziv] (optional deep dive)

**Preporučene lekcije za studentice:**
1. Section C - Lekcija D: [Naziv] (after class review)
2. Section E - Exercise F: [Naziv] (additional practice)

**Tools i resursi korišteni:**
- [Tool 1] - Used in Exercise 2
- [Tool 2] - Referenced in Facilitator Notes
- [Article 1] - Linked in Additional Resources
```

### **Aggregate view (sve dane):**
```markdown
# UDEMY RESOURCE MAP - UX/UI MODULE

Dan 1: Sections 1-3 (Intro to UX, Sketching)
Dan 2: Sections 4-5 (User Flows, Sitemaps)
Dan 3: Sections 6-7 (Wireframing)
...itd.

TOOLS USED:
- Figma (primary tool - all days)
- Coolors (Day 8 - Color theory)
- Google Fonts (Day 9 - Typography)

REFERENCE SITES USED:
- Dribbble (Days 2, 5, 10)
- Behance (Days 3, 7)
- Mobbin (Days 11-15 - Mobile design)
```

---

## ⚠️ POTENTIAL ISSUES & SOLUTIONS

### **Issue 1: Udemy tečaj se updateao, sekcije su drugačije**

**Problem:** Reference "Section 5" više ne postoji ili se zove drugačije.

**Rješenje:**
```
1. Otvori Udemy tečaj
2. Prođi kroz curriculum
3. Find equivalent sekciju
4. Update reference u sinopsisu
5. Note promjenu u verzijskom zapisu
```

### **Issue 2: External Resources PDF ima dead linkove**

**Problem:** Link više ne radi.

**Rješenje:**
```
1. Google search za alternativu
2. Provjeri Udemy tečaj - možda ima novi link
3. Update External Resources PDF
4. Commitaj novu verziju
5. Regeneriraj sinopsise ako treba
```

### **Issue 3: Previše Udemy referenci - overwhelming**

**Problem:** Svaki slajd ima 5+ Udemy linkova.

**Rješenje:**
```
Streamline:
- Keep SAMO najrelevantnije 1-2 linka
- Ostale stavi u "Additional Resources" sekciju na kraju
- Prioritize quality over quantity
```

---

## 📖 BEST PRACTICES RECAP

### **DO:**
✅ Upload External Resources PDF na početku
✅ Reci Claude-u eksplicitno da koristi Udemy resurse
✅ Integriraj Udemy kao DOPUNU, ne zamjenu
✅ Konkretne reference (Section X, Lekcija Y)
✅ Balans 70/30 (PDF/Udemy)

### **DON'T:**
❌ Pretpostavljaj da Claude zna za Udemy bez upute
❌ Copy-paste cijele Udemy lekcije u sinopsis
❌ Zamijeni PDF sadržaj s Udemy sadržajem
❌ Reference Udemy bez konteksta ("Section 5" - za što?)
❌ Overload s linkovima

---

## 🔗 POVEZANI DOKUMENTI

- **Format:** Vidi `02_FORMATTING_GUIDE.md`
- **Best practices:** Vidi `03_BEST_PRACTICES.md`
- **Troubleshooting:** Vidi `04_TROUBLESHOOTING.md`
- **Master prompt:** Vidi `01_PROMPT_TEMPLATE.md`

---

**VERZIJA:** 1.0  
**ZADNJE AŽURIRANO:** 2025-02-06  
**STATUS:** Aktivno korištenje

---

## 📝 CHANGELOG

### Version 1.0 (2025-02-06)
- Initial documentation
- UX/UI module specifics documented
- Agile and PM modules marked as TBD
- External Resources integration guidelines