# 📐 FORMATTING GUIDE - PRAVILA FORMATIRANJA SINOPSISA

## 🎯 SVRHA DOKUMENTA

Ovaj dokument definira **točna pravila** za Markdown formatiranje sinopsisa u SHIFT4IT programu.

**Cilj:** Konzistentno formatiranje svih sinopsisa bez obzira na modul ili dan.

---

## ⚠️ KRITIČNO PRAVILO #1: JEDAN ARTIFACT

### **PRAVILO:**
Claude **MORA** generirati kompletan sinopsis kao **JEDAN .md fajl u artifact boxu**.

### **ZAŠTO?**
- Facilitator može direktno downloadati ili copy-paste
- Nema potrebe za složenim cut-paste operacijama
- GitHub commit je jednostavan (jedan fajl)
- VS Code preview radi odmah

### **ŠTO TO ZNAČI:**

✅ **DOBRO:**
```
Claude generira:
┌─────────────────────────────┐
│  ARTIFACT BOX               │
│                             │
│  # 📘 DAN 1 - UX UVOD      │
│  ## CILJEVI...             │
│  ## SLAJD 1...             │
│  ...                       │
│  [KOMPLETAN SINOPSIS]      │
│                             │
└─────────────────────────────┘
```

❌ **LOŠE:**
```
Claude piše u chat:
"Evo početka sinopsisa..."
# DAN 1 - UX UVOD
[dio sinopsisa]

"A sad dio 2 u artifact-u..."
[ARTIFACT s ostatkom]
```

### **KAKO SPRIJEČITI SPLIT:**
Ako Claude počne dijeliti sadržaj, **odmah reci:**
```
"STOP. Generiraj CIJELI sinopsis u JEDNOM artifact-u. 
Ne dijeli kroz chat poruke."
```

---

## 📝 MARKDOWN HIJERARHIJA

### **Naslovi:**

```markdown
# 📘 DAN X - NAZIV TEME
↑ H1 - SAMO za glavni naslov dana (1x po fajlu)

## 🎯 **CILJEVI UČENJA:**
↑ H2 - Za glavne sekcije (Ciljevi, Raspored, Backup aktivnosti...)

### **Slajd 7: Naziv Slajda**
↑ H3 - Za pojedinačne slajdove

#### Podsekcija (rijetko korišteno)
↑ H4 - Samo ako je nužno za strukturu
```

### **PRAVILA:**
- **H1** (#) - Samo 1x na vrhu fajla
- **H2** (##) - Za glavne sekcije
- **H3** (###) - Za slajdove i backup aktivnosti
- **H4** (####) - Izbjegavaj ako nije neophodno

---

## 🎨 EMOJI KONVENCIJE

### **OBVEZNI EMOJI:**

| Emoji | Gdje | Značenje |
|-------|------|----------|
| 📘 | H1 naslov | Dan/tema |
| 🎯 | Ciljevi | Learning outcomes |
| ⏰ | Timing | Vrijeme/raspored |
| 📚 | Facilitator notes | Upute za facilitatora |
| ✏️ | Vježbe/zadaci | Praktična aktivnost |
| 💡 | Dodatne ideje | Opcije/alternative |
| 📖 | Reference | Linkovi/resursi |
| 🌐 | Eksterni resursi | Web resursi |
| ✅ | Pozitivni primjeri | Što raditi |
| ❌ | Negativni primjeri | Što NE raditi |
| ⚠️ | Upozorenja | Važno! |
| 🔄 | Backup aktivnosti | Alternative |
| ☕ | Pauze | Odmor |

### **KORIŠTENJE:**

✅ **DOBRO:**
```markdown
## 🎯 **CILJEVI UČENJA:**
```

✅ **DOBRO:**
```markdown
📚 **FACILITATOR NOTES:**
```

❌ **LOŠE:**
```markdown
## Ciljevi učenja 🎯
```
(Emoji ide NA POČETAK)

❌ **LOŠE:**
```markdown
🎯🎯🎯 **CILJEVI UČENJA:** 🎯🎯🎯
```
(Previše emojija)

### **UMJERENOST:**
- **1 emoji** po naslovu/sekciji
- **NE** koristi emoji u svakoj rečenici
- **NE** koristi emoji u objašnjenjima (samo u naslovima/sekcijama)

---

## ⏰ FORMATIRANJE TIMINGA

### **Format:**
```
[START]-[END] ([TRAJANJE] min)
```

### **PRIMJERI:**

✅ **DOBRO:**
```markdown
## ⏰ **9:00-9:15 (15 min) - UVOD U TEMU**
```

✅ **DOBRO:**
```markdown
**Što reći studentima (10 min):**
```

✅ **DOBRO:**
```markdown
### **BACKUP AKTIVNOST 1: Empathy Mapping (15 min)**
```

❌ **LOŠE:**
```markdown
9:00 do 9:15 - UVOD (15 minuta)
```
(Nedosljedan format)

### **ZAOKRUŽIVANJE:**
- Uvijek zaokruži na **5, 10, ili 15 minuta**
- NE: 7 min, 13 min, 22 min
- DA: 5 min, 10 min, 15 min, 20 min

### **RASPORED TEMPLATE:**
```markdown
## ⏰ **RASPORED PREDAVANJA:**

```
9:00-10:00   [Sekcija 1]
10:00-10:15  PAUZA ☕
10:15-11:00  [Sekcija 2]
11:00-11:15  PAUZA ☕
11:15-12:15  [Sekcija 3]
12:15-12:30  Recap & Pitanja
```
```

---

## 📑 STRUKTURA SLAJDA

### **TEMPLATE:**

```markdown
### **Slajd 7: User Research Methods**

**Notes iz PDF-a:**
_"[Tekst iz PDF notesa - hrvatski]"_

**Što reći studentima (15 min):**

[Objašnjenje za studentice - hrvatski]
- Bullet point 1
- Bullet point 2

**Primjeri:**
- Primjer 1: [Opis] - [URL]
- Primjer 2: [Opis]

📖 **Reference:**
- [Naziv resursa]: [URL]
- [Drugi resurs]: [URL]

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
[Objašnjenje za facilitatora]

**Česta pitanja:**
Q: "[Pitanje studentice]"
A: [Odgovor facilitatora]

**Troubleshooting:**
- [Problem]: [Rješenje]

📖 **Linkovi za dublje razumijevanje:**
- [Link 1]
- [Link 2]
```

### **OBVEZNI ELEMENTI PO SLAJDU:**
1. ✅ Broj i naslov slajda
2. ✅ Notes iz PDF-a (ili "_[Nema notesa u PDF-u]_")
3. ✅ Što reći studentima (s timingom)
4. ✅ Facilitator notes

### **OPCIONALNI ELEMENTI:**
- Primjeri (ako ima smisla)
- Reference (ako ima smisla)
- Vježbe (ako slajd ima vježbu)

---

## 📚 FACILITATOR NOTES FORMAT

### **STRUKTURA:**

```markdown
📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
[Objašnjenje koncepta za facilitatora koji je početnik]

**Zašto je ovo važno:**
[Kontekst i relevantnost]

**Česta pitanja:**
Q: "[Pitanje]"
A: [Odgovor]

Q: "[Drugo pitanje]"
A: [Odgovor]

**Troubleshooting:**
- [Problem]: [Rješenje]
- [Drugi problem]: [Rješenje]

📖 **Linkovi za dublje razumijevanje:**
- [Resurs 1]: [URL]
- [Resurs 2]: [URL]
```

### **KADA DODATI:**
- ✅ Svaki slajd MORA imati facilitator notes
- ✅ Svaka vježba MORA imati facilitator notes
- ✅ Svaka backup aktivnost MORA imati facilitator notes

### **ŠTO UKLJUČITI:**
1. Objašnjenje koncepta (za facilitatora početnika)
2. Zašto je važno
3. Česta pitanja (2-4 pitanja)
4. Troubleshooting (2-3 problema)
5. Linkovi za dublje učenje

---

## ✏️ FORMATIRANJE VJEŽBI

### **TEMPLATE:**

```markdown
✏️ **ZADATAK: [Naziv vježbe]**

**Cilj:**
[Što studentice trebaju postići ovom vježbom]

**Trajanje:** [X] min

**Materijali:**
- [Što je potrebno]
- [Alat 1]
- [Alat 2]

**Upute:**
1. [Korak 1 - detaljan]
2. [Korak 2 - detaljan]
3. [Korak 3 - detaljan]

**Primjer rezultata:**
[Opis ili screenshot rezultata ako postoji]

📚 **FACILITATOR NOTES:**

**Kako voditi vježbu:**
- [Savjet 1]
- [Savjet 2]

**Česti problemi:**
- [Problem]: [Rješenje]
- [Problem]: [Rješenje]

**Varijacije (ako ima vremena):**
- [Dodatna opcija]

📖 **Reference:**
- [Resurs ako postoji]
```

### **OBVEZNI ELEMENTI:**
1. ✅ Jasna upute (step-by-step)
2. ✅ Timing
3. ✅ Facilitator notes

---

## 🔄 BACKUP AKTIVNOSTI FORMAT

### **TEMPLATE:**

```markdown
### **BACKUP AKTIVNOST 1: [Naziv] ([X] min)**

**Cilj:**
[Što se postiže ovom aktivnošću]

**Kada koristiti:**
- [Situacija 1]
- [Situacija 2]

**Materijali:**
- [Što je potrebno]

**Upute:**
1. [Korak 1]
2. [Korak 2]
3. [Korak 3]

📚 **FACILITATOR NOTES:**

**Kako voditi:**
[Detaljne upute za facilitatora]

**Troubleshooting:**
- [Problem]: [Rješenje]

**Varijacije:**
- [Opcija A]: [Opis]
- [Opcija B]: [Opis]

📖 **Reference:**
- [Resurs ako postoji]
```

### **KOLIČINA:**
- **Minimum:** 5 backup aktivnosti
- **Optimalno:** 7 backup aktivnosti
- **Trajanja:** Mix 5 min, 10 min, 15 min

---

## 📖 FORMATIRANJE REFERENCE LINKOVA

### **INLINE REFERENCE:**

✅ **DOBRO:**
```markdown
Pogledajte [Dribbble](https://dribbble.com) za inspiraciju.
```

✅ **DOBRO:**
```markdown
Koristi [Figma](https://figma.com) za wireframing.
```

❌ **LOŠE:**
```markdown
Pogledajte Dribbble (https://dribbble.com) za inspiraciju.
```

### **SEKCIJA REFERENCI:**

✅ **DOBRO:**
```markdown
📖 **Reference:**
- [Dribbble - Mobile Design](https://dribbble.com/tags/mobile-design)
- [Behance - UX Projects](https://behance.net/search/projects?field=ux)
```

✅ **DOBRO:**
```markdown
🌐 **EKSTERNI RESURSI:**
- [Color Contrast Checker](https://webaim.org/resources/contrastchecker/) - Provjera kontrasta boja
- [Google Fonts](https://fonts.google.com) - Free fontovi
```

❌ **LOŠE:**
```markdown
Reference:
Dribbble: https://dribbble.com
Behance: https://behance.net
```
(Bez emoji, loše formatiranje linkova)

---

## 📋 LISTE I BULLET POINTS

### **KADA KORISTITI:**

✅ **Koristi liste za:**
- Naštimavanje točaka
- Korake u uputama
- Ciljeve učenja
- Materijale potrebne za vježbu
- Facilitator notes bullet points

❌ **NE koristi liste za:**
- Cijele paragrafe teksta
- Objašnjenja koncepata (koristi prozu)
- Kratke rečenice (umjesto toga piši kao normalan tekst)

### **FORMAT:**

✅ **DOBRO:**
```markdown
**Koraci:**
1. Otvori Figma
2. Kreiraj novi fajl
3. Dodaj frame
```

✅ **DOBRO:**
```markdown
**Ciljevi:**
- Razumjeti UX proces
- Primijeniti design thinking
- Kreirati wireframe
```

❌ **LOŠE:**
```markdown
- Studentice će razumjeti UX proces, što znači da će moći objasniti sve korake, primijeniti ih u praksi i kreirati svoj prvi prototip
```
(Bullet point je prekratak ili predugačak)

### **PRAVILA:**
- Bullet point = 1-2 rečenice max
- Numbered list = za korake (1, 2, 3...)
- Unnumbered list = za točke bez redoslijeda

---

## 🎨 FORMATIRANJE NAGLASAKA

### **BOLD (masno):**

✅ **Koristi za:**
- Naslove sekcija unutar slajda
- Ključne termine prvi put
- Upozorenja

```markdown
**Što reći studentima:**
**VAŽNO:** Uvijek spremaj rad!
```

### **ITALIC (kurziv):**

✅ **Koristi za:**
- Notes iz PDF-a
- Citati
- Naglasak na pojedinim riječima

```markdown
**Notes iz PDF-a:**
_"User research je temelj dobrog UX dizajna."_
```

### **CODE BLOCKS:**

✅ **Koristi za:**
- Primjere koda
- File paths
- Tehničke termine koji su točni nazivi

```markdown
Otvori `File > New` u Figmi.
```

```markdown
Instaliraj preko terminala:
```
npm install figma-plugin
```
```

❌ **NE koristi:**
- Za normalan tekst
- Za naglašavanje (koristi **bold**)

---

## 📦 CODE BLOCKS

### **KADA KORISTITI:**
- Timing raspored (```text)
- Primjeri koda
- Terminal komande
- JSON strukture

### **RASPORED:**

```markdown
## ⏰ **RASPORED PREDAVANJA:**

```text
9:00-10:00   Sekcija 1
10:00-10:15  PAUZA ☕
10:15-11:00  Sekcija 2
```
```

### **KOD:**

```markdown
```javascript
function pozdrav() {
  console.log("Bok!");
}
```
```

### **TERMINAL:**

```markdown
```bash
npm install
```
```

---

## ✅ CHECKLIST FORMATIRANJA

Prije nego pošalješ sinopsis, provjeri:

### **STRUKTURA:**
- [ ] H1 samo za naslov dana
- [ ] H2 za glavne sekcije
- [ ] H3 za slajdove i backup aktivnosti
- [ ] Emoji na početku naslova/sekcija
- [ ] Svi slajd brojevi odgovaraju PDF-u

### **TIMING:**
- [ ] Format: `9:00-9:15 (15 min)`
- [ ] Zaokruženo na 5/10/15 min
- [ ] Ukupno ~3h efektivnog rada
- [ ] 2 pauze po 15 min

### **FACILITATOR NOTES:**
- [ ] Svaki slajd ima facilitator notes
- [ ] Svaka vježba ima facilitator notes
- [ ] Svaka backup aktivnost ima facilitator notes

### **REFERENCE:**
- [ ] Linkovi formatirani kao [tekst](url)
- [ ] Reference sekcije imaju 📖 emoji
- [ ] URL-ovi su working linkovi

### **JEZIK:**
- [ ] Sav tekst na hrvatskom
- [ ] Engleski termini OK (wireframe, prototype...)
- [ ] NIKAD cijeli paragraf na engleskom

### **ARTIFACT:**
- [ ] CIJELI sinopsis u JEDNOM artifact-u
- [ ] NE split kroz chat poruke
- [ ] Copy-paste ready

---

## 🚨 ČESTE GREŠKE

### **GREŠKA 1: Split u više poruka**
❌ **Loše:** Dio u chat, dio u artifact
✅ **Rješenje:** Sve u JEDAN artifact

### **GREŠKA 2: Engleski tekst**
❌ **Loše:** "Let's discuss user research methods"
✅ **Rješenje:** "Razgovarajmo o metodama user researcha"

### **GREŠKA 3: Netočni brojevi slajdova**
❌ **Loše:** Slajd 5, Slajd 6, Slajd 9 (preskočen 7 i 8)
✅ **Rješenje:** Provjeri PDF i uključi SVE slajdove

### **GREŠKA 4: Nerealan timing**
❌ **Loše:** 9:00-9:03 (3 min)
✅ **Rješenje:** 9:00-9:05 (5 min)

### **GREŠKA 5: Previše emojija**
❌ **Loše:** 🎯🎯🎯 **CILJEVI** 🎯🎯🎯
✅ **Rješenje:** 🎯 **CILJEVI**

---

## 🔗 POVEZANE UPUTE

- **Sadržaj i struktura:** Vidi `03_BEST_PRACTICES.md`
- **Troubleshooting:** Vidi `04_TROUBLESHOOTING.md`
- **Udemy resursi:** Vidi `05_UDEMY_RESOURCES_USAGE.md`
- **Master prompt:** Vidi `01_PROMPT_TEMPLATE.md`

---

**VERZIJA:** 1.0  
**ZADNJE AŽURIRANO:** 2025-02-06  
**STATUS:** Aktivno korištenje