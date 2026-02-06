# 🔧 TROUBLESHOOTING - RJEŠAVANJE PROBLEMA

## 🎯 SVRHA DOKUMENTA

Ovaj dokument sadrži **najčešće probleme** pri generiranju sinopsisa i **konkretna rješenja**.

**Format:** Problem → Zašto se događa → Kako riješiti → Primjer

---

## 🚨 KRITIČNI PROBLEMI

### **PROBLEM 1: Claude dijeli sinopsis u više poruka**

#### **Simptomi:**
```
Claude piše:
"Evo početka sinopsisa..."
[dio teksta u chat-u]

"Sada nastavljam s vježbama..."
[dio teksta u artifact-u]

"I na kraju backup aktivnosti..."
[još teksta u chat-u]
```

#### **Zašto se događa:**
- Claude "misli" da olakšava čitanje
- Automatski split ako sinopsis prelazi određenu dužinu
- Nije jasno naglašeno u promptu da mora biti JEDAN artifact

#### **Rješenje:**

**✅ ODMAH reci:**
```
STOP. Molim te generiraj KOMPLETAN sinopsis kao JEDAN .md artifact.
NE dijeli sadržaj kroz chat poruke. 
SVE mora biti u artifact boxu.
```

**✅ PREVENCIJA - dodaj na kraj prompta:**
```
VAŽNO: Generiraj CIJELI sinopsis kao JEDAN .md artifact.
Ne dijeli sadržaj. Ne piši dio u chat, dio u artifact.
Kompletan Dan_XX.md mora biti u artifact boxu.
```

#### **Kako provjeriti da je riješeno:**
- Cijeli sinopsis vidiš u artifact boxu (lijevo)
- Chat poruka Claude-a sadrži samo potvrdu: "Generirao sam kompletan sinopsis..."
- Možeš kliknuti "Copy" i dobiti kompletan .md fajl

---

### **PROBLEM 2: Tekst je na engleskom umjesto hrvatskom**

#### **Simptomi:**
```markdown
**What to tell students (15 min):**
User research is the process of understanding user needs...

**Common questions:**
Q: "How many users should we interview?"
A: Ideally 5-8 users for qualitative research...
```

#### **Zašto se događa:**
- Claude je treniran primaries na engleskom
- Notes iz PDF-a su možda na engleskom
- Prompt nije dovoljno naglasio HRVATSKI

#### **Rješenje:**

**✅ Ako se već dogodilo:**
```
Molim te prevedi CIJELI sinopsis na hrvatski jezik.
Ostavi samo tehničke termine na engleskom (wireframe, prototype, user flow...).
Sve ostalo - objašnjenja, upute, rečenice - MORA biti na hrvatskom.
```

**✅ PREVENCIJA - dodaj na početak prompta:**
```
⚠️ JEZIK: HRVATSKI
- Sav tekst, objašnjenja, upute = HRVATSKI
- Engleski termini OK (wireframe, prototype, MVP...)
- NIKAD cijele rečenice ili paragrafi na engleskom
- Notes iz PDF-a prijevodi na hrvatski ako su na engleskom
```

#### **Specifični slučajevi:**

**Ako su Notes iz PDF-a na engleskom:**
```markdown
✅ DOBRO:
**Notes iz PDF-a:**
_"User research je proces razumijevanja korisničkih potreba kroz intervjue i testiranje."_

❌ LOŠE:
**Notes iz PDF-a:**
_"User research is the process of understanding user needs through interviews and testing."_
```

**Engleski termini koji su OK:**
- Wireframe, prototype, mockup
- User flow, user journey
- MVP (Minimum Viable Product)
- Sprint, backlog, standup
- Stakeholder, deliverable

**Što MORA biti na hrvatskom:**
- Sve rečenice, paragrafi, objašnjenja
- Upute za vježbe
- Facilitator notes
- Pitanja i odgovori

---

### **PROBLEM 3: Brojevi slajdova se ne podudaraju s PDF-om**

#### **Simptomi:**
```
PDF ima:
Slajd 1, 2, 3, 4, 5, 6, 7, 8 (ukupno 8)

Sinopsis ima:
Slajd 1, 2, 3, 5, 7, 8 (preskočeni 4 i 6)
```

#### **Zašto se događa:**
- Claude "misli" da su neki slajdovi nevažni (npr. naslovnice)
- Pogrešno brojanje tijekom generiranja
- PDF nije učitan pravilno

#### **Rješenje:**

**✅ Prvo PROVJERI PDF:**
```
1. Otvori PDF
2. Zbroji slajdove (dno desno u PDF readeru)
3. Provjeri: Ima li neki slajd koji je čisto naslovna stranica BEZ sadržaja?
```

**✅ Reci Claude-u:**
```
Provjeri PDF ponovno. 
Slajdovi u sinopsisu moraju TOČNO odgovarati brojkama u PDF-u.
Format: ### **Slajd X: [Točan naslov iz PDF-a]**

PDF ima [broj] slajdova. Sinopsis mora imati svih [broj].
```

**✅ Ako slajd JE prazan (samo naslov, bez sadržaja):**
```markdown
### **Slajd 2: Naslovna stranica modula**

_[Ovaj slajd služi samo kao vizualni separator. Nema dodatnog sadržaja za obradu.]_

**Što reći studentima (1 min):**
"Ovo je naslovna stranica našeg modula. Nastavljamo dalje."
```

#### **Kako provjeriti da je riješeno:**
- Otvori PDF i sinopsis side-by-side
- Prođi kroz redom: Slajd 1 ✅, Slajd 2 ✅, Slajd 3 ✅...
- Svaki slajd iz PDF-a mora biti u sinopsisu

---

### **PROBLEM 4: Timing ne ispada realan (previše/premalo)**

#### **Simptomi - PREVIŠE:**
```
Total timing: 4.5 sata
(Trebalo bi biti ~3h efektivnog rada)
```

#### **Simptomi - PREMALO:**
```
Total timing: 1.5 sat
(Nedostaje sadržaja za 3h predavanje)
```

#### **Zašto se događa:**
- Loša procjena koliko traje objašnjenje
- Vježbe su preambiciozne ili preskromne
- Previše backup aktivnosti računato u glavni timing

#### **Rješenje za PREVIŠE timinga:**

**✅ Identifikuj gdje je problem:**
```
1. Pregledaj sinopsis
2. Označuj stvari koje se čine predugim:
   - Objašnjenja > 15 min → Skrati na 10 min
   - Vježbe > 30 min → Razbij u 2 kraće vježbe ili skrati
   - Diskusije > 15 min → Skrati na 10 min
```

**✅ Reci Claude-u:**
```
Timing je preobiman (X sati ukupno). Trebam ~3h efektivnog rada.
Molim te skrati:
- [Slajd Y] s 20 min na 10 min
- [Vježbu Z] s 35 min na 25 min
Regeneriraj sinopsis s revidiranim timingom.
```

#### **Rješenje za PREMALO timinga:**

**✅ Dodaj sadržaja:**
```
Timing je prekratak (X sati ukupno). Treba mi punjih 3h.
Molim te dodaj:
- Više hands-on vježbi (15-20 min svaka)
- Discussion segmente nakon vježbi (10 min)
- Group activities između teorijskih sekcija
```

#### **PRAVILA ZA REALAN TIMING:**

```markdown
✅ DOBRI TIMINGS:
- Uvod u koncept: 5-10 min
- Duboko objašnjenje: 10-15 min
- Kratka vježba: 10-15 min
- Srednja vježba: 20-25 min
- Duga vježba: 30-40 min
- Diskusija/review: 10-15 min
- Backup aktivnost: 5-15 min

❌ SUMNJIVI TIMINGS:
- Objašnjenje: 25 min (predugo, studentice će se smučiti)
- Vježba: 5 min (prekratko, neće ništa napraviti)
- Vježba: 60 min (predugo, preambiciozno)
```

#### **FORMULA ZA PROVJERU:**
```
Start: 9:00
Pauza 1: 10:00-10:15 (15 min)
Pauza 2: 11:00-11:15 (15 min)
End: 12:30

UKUPNO: 3.5h - 30 min (pauze) = 3h efektivnog rada
```

---

### **PROBLEM 5: Reference linkovi ne rade**

#### **Simptomi:**
```
📖 **Reference:**
- [Example](wrong-link.com) → 404 Error
- [Tool](http://tool.com) → Redirect loop
```

#### **Zašto se događa:**
- URL je outdated
- Typo u linku
- Website više ne postoji

#### **Rješenje:**

**✅ PRIJE SLANJA sinopsisa:**
```
Test svaki link:
1. CMD+Click (Mac) ili CTRL+Click (Windows) na link
2. Provjeri da se otvara
3. Provjeri da vodi na pravu stranicu
```

**✅ Ako link ne radi:**
```
1. Google search za alternativu
2. Provjeri External Resources PDF za backup link
3. Zamijeni u sinopsisu

Ili reci Claude-u:
"Link [X] ne radi. Pronađi alternativni resurs za [tema]."
```

**✅ PREVENCIJA:**
```
Koristi etablirane resurse iz External Resources PDF-a:
- Figma, Dribbble, Behance (sigurni linkovi)
- Nielsen Norman Group (rijetko mijenjaju URL-ove)
- Google Fonts, Coolors (stabilni toolovi)
```

#### **Backup ako link NE RADI u razredu:**
```markdown
📚 **FACILITATOR NOTES:**
**Ako link ne radi:**
- Screenshot alternative: Imam backup u `/resources/screenshots/`
- Ili live search: Google "[tema] example" zajedno sa studentima
- Ili improvise: "Zamislimo da ovaj website ima..."
```

---

### **PROBLEM 6: Nedostaju facilitator notes**

#### **Simptomi:**
```markdown
### **Slajd 5: User Personas**

**Notes iz PDF-a:**
_"User personas represent target users."_

**Što reći studentima (10 min):**
Persone su fikcionalni prikazi korisnika...

[NEMA FACILITATOR NOTES]
```

#### **Zašto se događa:**
- Claude zaboravi dodati
- Prompt nije dovoljno naglasio važnost

#### **Rješenje:**

**✅ Reci Claude-u:**
```
Slajd [X] nema facilitator notes. 
Molim te dodaj sekciju 📚 **FACILITATOR NOTES:** s:
- Objašnjenjem koncepta za facilitatora
- 2-3 česta pitanja i odgovora
- Troubleshooting savjetima
- Linkovima za dublje učenje
```

**✅ PREVENCIJA - dodaj u prompt:**
```
⚠️ OBVEZNO: Svaki slajd MORA imati sekciju 📚 FACILITATOR NOTES.
```

#### **Što ako SAMI pišeš facilitator notes:**
```markdown
📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
[Objasni koncept sebi - što je, zašto je važno, kako funkcionira]

**Česta pitanja:**
Q: "[Pitanje koje očekuješ]"
A: [Tvoj odgovor]

**Troubleshooting:**
- [Problem]: [Rješenje]

📖 **Linkovi za dublje razumijevanje:**
- [Resurs koji si našao]
```

---

### **PROBLEM 7: Backup aktivnosti nisu dovoljno detaljne**

#### **Simptomi:**
```markdown
### **BACKUP AKTIVNOST 1: Group Discussion (10 min)**

Diskutirajte o user research metodama.
```

#### **Zašto se događa:**
- Claude misli da je dovoljno kratko opisati
- Nije clear da facilitator treba step-by-step

#### **Rješenje:**

**✅ Reci Claude-u:**
```
Backup aktivnost [X] nije dovoljno detaljna.
Molim te dodaj:
- Jasan cilj aktivnosti
- Step-by-step upute (numbered)
- Facilitator notes (kako voditi, troubleshooting)
- Timing breakdown
```

**✅ Template za dobru backup aktivnost:**
```markdown
### **BACKUP AKTIVNOST 1: [Naziv] ([X] min)**

**Cilj:**
[Što studentice postižu - konkretan outcome]

**Kada koristiti:**
- [Situacija 1]
- [Situacija 2]

**Materijali:**
- [Lista svega što treba]

**Upute:**
1. [Korak 1 - detaljan]
2. [Korak 2 - detaljan]
3. [Korak 3 - detaljan]

**Timing breakdown:**
- Korak 1: X min
- Korak 2: Y min
- Korak 3: Z min

📚 **FACILITATOR NOTES:**
**Kako voditi:**
[Savjeti]

**Troubleshooting:**
- [Problem]: [Rješenje]
```

---

### **PROBLEM 8: Claude "dijeli" sinopsis - copy-paste kvari formatiranje**

#### **Simptomi:**
```
Kopirao/la si iz artifact-a u VS Code:
- Emoji se ne prikazuju pravilno
- Heading razine su krivo
- Liste su razbijene
```

#### **Zašto se događa:**
- Copy-paste iz browsera ponekad kvari Markdown
- Encoding problema s emoji
- VS Code extension nije instaliran

#### **Rješenje:**

**✅ NAČIN 1 - Download direktno:**
```
1. U artifact boxu, klikni ikonu "..." (gore desno)
2. "Download"
3. Spremi kao Dan_XX.md
4. Otvori u VS Code
```

**✅ NAČIN 2 - Copy-paste pravilno:**
```
1. Klikni "Copy" button u artifact boxu (NE ručno selektiraj tekst)
2. VS Code → New File
3. CMD+V (Mac) ili CTRL+V (Windows)
4. Save As → Dan_XX.md
5. Provjeri Markdown preview (CMD+K V)
```

**✅ NAČIN 3 - Ako još uvijek ne radi:**
```
1. Copy sadržaj iz artifact-a
2. Paste u plain text editor (Notepad, TextEdit)
3. Copy iz plain text editora
4. Paste u VS Code
```

#### **Provjera da je formatiranje OK:**
```
1. VS Code: Otvori Markdown preview (CMD+K V ili CTRL+K V)
2. Provjeri:
   - [ ] Emoji se vide
   - [ ] Headinzi su pravilni (H1, H2, H3)
   - [ ] Liste su formatirane
   - [ ] Linkovi rade
```

---

### **PROBLEM 9: PDF nije pravilno uploadan ili Claude ga ne vidi**

#### **Simptomi:**
```
Claude kaže:
"Ne vidim PDF u ovom chatu. Molim te uploadaj PDF prezentaciju."

Ili:

"Na temelju uploadanog PDF-a..." [ali reference su krivi/generički]
```

#### **Zašto se događa:**
- Upload je failao (internet connection)
- PDF je prevelik (>10 MB može biti problem)
- PDF je korumpiran

#### **Rješenje:**

**✅ Provjeri da je PDF uploadan:**
```
1. Scroll gore u chatu
2. Vidiš li attachment s PDF ikonom?
3. Možeš li kliknuti i vidjeti PDF?
```

**✅ Re-upload ako treba:**
```
1. Zatvori postojeći chat ili otvori novi
2. Upload PDF PRVO (prije copy-paste prompta)
3. Pričekaj da se upload završi (loading bar)
4. ONDA copy-paste prompt
```

**✅ Ako je PDF prevelik:**
```
1. Otvori PDF u Preview (Mac) ili Adobe (Windows)
2. Export → Reduce File Size
3. Re-upload manji PDF
```

**✅ Test da Claude vidi PDF:**
```
Upload PDF, zatim pitaj:
"Koliko slajdova ima ovaj PDF? Koji je naslov prvog slajda?"

Ako Claude točno odgovori → PDF je OK
Ako ne → Re-upload
```

---

## 🔄 ITERATIVNO POBOLJŠAVANJE

### **Scenario: Sinopsis je OK, ali želiš poboljšati nešto specifično**

#### **Problem: Jedan slajd nema dovoljno detalja**
```
Rješenje:
"Slajd 7 treba više detalja. Molim te dodaj:
- Detaljnije objašnjenje wireframing procesa
- Konkretan primjer wireframe-a (link)
- Još 2 česta pitanja"
```

#### **Problem: Vježba je prejednostavna**
```
Rješenje:
"Vježba 2 je prejednostavna za 30 min. Molim te:
- Dodaj extension: Nakon osnovnog zadatka, studentice dodaju još X
- Dodaj peer review fazu (10 min)
- Povećaj complexity malo"
```

#### **Problem: Fali primjera**
```
Rješenje:
"Slajdovi 5-8 nemaju konkretne primjere. Molim te dodaj:
- Slajd 5: Link na dobar primjer [tema]
- Slajd 6: Screenshot ili opis primjera
- Slajd 7: Reference link na Dribbble/Behance"
```

---

## ✅ VALIDACIJSKI CHECKLIST

### **Prije nego finaliziraš sinopsis:**

#### **STRUKTURA I FORMAT:**
- [ ] Cijeli sinopsis je u JEDNOM artifact-u
- [ ] H1 samo za naslov dana
- [ ] H2 za glavne sekcije, H3 za slajdove
- [ ] Emoji na početku naslova

#### **SADRŽAJ:**
- [ ] Sav tekst na hrvatskom (osim termina)
- [ ] Svi brojevi slajdova odgovaraju PDF-u
- [ ] Svaki slajd ima facilitator notes
- [ ] 5-7 backup aktivnosti s detaljnim uputama

#### **TIMING:**
- [ ] Ukupno ~3h efektivnog rada
- [ ] 2 pauze po 15 min (10:00-10:15 i 11:00-11:15)
- [ ] Timing je zaokružen na 5/10/15 min
- [ ] Realan timing (provjereno)

#### **REFERENCE:**
- [ ] Linkovi su working linkovi (provjereno)
- [ ] Reference formatirani kao [tekst](url)
- [ ] Ima smislene reference gdje treba

#### **FACILITATOR SUPPORT:**
- [ ] Svaki slajd: objašnjenje koncepta
- [ ] Svaki slajd: česta pitanja (2-4)
- [ ] Svaki slajd: troubleshooting
- [ ] Backup aktivnosti: detaljne upute

#### **PRAKTIČNOST:**
- [ ] Vježbe imaju jasne korake
- [ ] Materijali su navedeni
- [ ] Može se izvesti s resursima koji postoje

---

## 🆘 KADA SVI RJEŠENJA FAILAJU

### **Nuclear Option 1: Novi chat**
```
1. Zatvori postojeći chat
2. Otvori NOVI Claude chat
3. Upload sve materijale PONOVNO
4. Copy-paste CIJELI prompt (provjeravaj da si kopirao SVE)
5. Dodaj: "Generiraj kompletan sinopsis kao JEDAN .md artifact"
```

### **Nuclear Option 2: Simplifikacija prompta**
```
Umjesto cijelog prompta, pojednostavi:

"Claude, kreiraj sinopsis za Dan X - [Tema] prema uploadanom PDF-u.

PRAVILA:
1. Cijeli sinopsis u JEDNOM .md artifact-u
2. Sav tekst na hrvatskom
3. Slajd brojevi moraju biti identični PDF-u
4. Svaki slajd mora imati facilitator notes
5. Dodaj 5 backup aktivnosti

Format:
- Uvod (ciljevi, raspored)
- Slajdovi (svaki s notesima iz PDF-a)
- Backup aktivnosti
- Resursi

Trajanje: ~3h efektivnog rada (9:00-12:30 s 2 pauze)"
```

### **Nuclear Option 3: Manual fix**
```
Ako Claude stalno faila s nekim dijelovima:
1. Generiraj što može
2. Manualno dodaj/popuni dijelove koji nedostaju
3. Use template iz drugih sinopsisa
4. Copy-paste facilitator notes struktura iz prošlih dana
```

---

## 📞 GDJE TRAŽITI POMOĆ

### **Interna pomoć:**
1. Provjeri ostale sinopsise u `/uxui/lectures/` za reference
2. Pitaj druge facilitatore
3. Check SHIFT4IT Slack kanal

### **External resursi:**
- Claude documentation: [claude.ai/docs](https://claude.ai/docs)
- Markdown guide: [markdownguide.org](https://www.markdownguide.org/)
- Figma community: Za template pomoć

---

## 🔗 POVEZANI DOKUMENTI

- **Format:** Vidi `02_FORMATTING_GUIDE.md`
- **Best practices:** Vidi `03_BEST_PRACTICES.md`
- **Udemy:** Vidi `05_UDEMY_RESOURCES_USAGE.md`
- **Master prompt:** Vidi `01_PROMPT_TEMPLATE.md`

---

**VERZIJA:** 1.0  
**ZADNJE AŽURIRANO:** 2025-02-06  
**STATUS:** Aktivno korištenje