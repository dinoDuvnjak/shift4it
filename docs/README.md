# 📚 DOKUMENTACIJA ZA GENERIRANJE SINOPSISA - PREGLED

## 🎯 SVRHA DOKUMENTACIJE

Ova dokumentacija sadrži **kompletne upute za Claude AI** kako generirati detaljne sinopsise predavanja za SHIFT4IT program.

**Moduli:**
- UX/UI Design (50h)
- Agile Methodologies (30h)
- Project Management (30h)

Svaki modul dijeli **istu strukturu** - razlikuje se samo sadržaj i referentni Udemy tečaj.

---

## 📁 STRUKTURA DOKUMENTACIJE

### **01_PROMPT_TEMPLATE.md** ⭐ NAJVAŽNIJE
Master prompt koji se koristi za generiranje svakog sinopsisa.
- Kompletne upute za Claude
- Copy-paste u svaki novi chat
- Generički - radi za sve module

### **02_FORMATTING_GUIDE.md**
Pravila formatiranja Markdown dokumenata.
- Struktura sinopsisa
- Korištenje emojija
- Hijerarhija naslova
- Timing format

### **03_BEST_PRACTICES.md**
Najbolje prakse za pisanje kvalitetnih sinopsisa.
- Kako pisati facilitator notes
- Kreiranje vježbi
- Backup aktivnosti
- Primjeri i reference

### **04_TROUBLESHOOTING.md**
Česte greške i njihova rješenja.
- Problem: Brojevi slajdova se ne podudaraju
- Problem: Engleski tekst umjesto hrvatskog
- Problem: Nedostaju backup aktivnosti
- Itd.

### **05_UDEMY_RESOURCES_USAGE.md**
Detaljne upute kako koristiti Udemy resurse u procesu.
- Kada uploadati
- Kako integrirati u sinopsis
- Format referenci

---

## 🚀 BRZI START

### **Za hitno generiranje:**

1. **Otvori novi Claude chat**
2. **Upload:** PDF prezentacija + Udemy External Resources PDF
3. **Copy-paste:** Kompletan prompt iz `01_PROMPT_TEMPLATE.md`
4. **Dodaj:** "Kreiraj sinopsis za Dan X - [Naziv]"
5. **Download:** Artifact koji Claude generira

➡️ **Detaljne upute:** Vidi `01_PROMPT_TEMPLATE.md`

---

## ⚠️ KRITIČNA PRAVILA

### **1. JEDAN .md FAJL = JEDAN ARTIFACT**
Claude **MORA** generirati kompletan sinopsis kao **JEDAN .md artifact**.
- ❌ **NE** split sadržaj kroz chat poruke
- ❌ **NE** razbijaj sinopsis u više dijelova
- ✅ **DA** - kompletan Dan_XX.md u artifact boxu
- ✅ **DA** - facilitator može direktno downloadati ili copy-paste

### **2. SVE NA HRVATSKOM**
- Tekst, objašnjenja, upute = hrvatski
- Engleski termini OK (wireframe, prototype...)
- **NIKAD** cijele rečenice ili paragrafi na engleskom

### **3. TOČNI BROJEVI SLAJDOVA**
- Slajd brojevi MORAJU odgovarati PDF-u
- Ako PDF ima 18 slajdova, sinopsis mora imati svih 18
- Format: `### **Slajd X: Naslov**`

### **4. TIMING MORA BITI REALAN**
- Ukupno ~3h efektivnog rada (bez pauza)
- 2 pauze po 15 min (10:00-10:15 i 11:00-11:15)
- Zaokruživanje na 5, 10, 15 min

### **5. BACKUP AKTIVNOSTI SU OBAVEZNE**
- Minimum 5-7 različitih aktivnosti
- Detaljne upute za svaku
- Različita trajanja (5-15 min)

---

## 📊 WORKFLOW

```
START
  ↓
Pripremi materijale (PDF + Udemy resources)
  ↓
Otvori novi Claude chat
  ↓
Upload materijale
  ↓
Copy-paste prompt iz 01_PROMPT_TEMPLATE.md
  ↓
Claude generira artifact
  ↓
Download/copy-paste artifact
  ↓
Spremi kao Dan_XX_Naziv.md
  ↓
Commit na GitHub
  ↓
END
```

---

## 🎓 ZA RAZLIČITE MODULE

### **UX/UI Design:**
- Udemy: "Complete Web Designer + Mobile Designer"
- PDF: 1.Intro UX-orange.pdf, 2 & 3.Principles...pdf, itd.
- Trajanje: 15 dana x 3.5h = 52.5h

### **Agile Methodologies:**
- Udemy: [naziv tečaja - dodati kasnije]
- PDF: [lista PDF-ova - dodati kasnije]
- Trajanje: [dane x sati]

### **Project Management:**
- Udemy: [naziv tečaja - dodati kasnije]
- PDF: [lista PDF-ova - dodati kasnije]
- Trajanje: [dane x sati]

---

## 📞 PODRŠKA

Ako Claude ne generira sinopsis kako treba:
1. Provjeri jesi li uploadao sve materijale
2. Provjeri jesi li kopirao kompletan prompt
3. Podsjeti Claude-a na kritična pravila
4. Vidi `04_TROUBLESHOOTING.md` za specifične probleme

---

## 📝 VERZIONIRANJE

- **Verzija:** 1.0
- **Datum:** 2025-02-06
- **Autor:** SHIFT4IT Tim
- **Status:** Aktivno korištenje

---

## 🔄 AŽURIRANJE DOKUMENTACIJE

Kada otkriješ poboljšanje ili grešku:
1. Editiraj relevantni .md fajl u `/docs`
2. Dodaj bilješku u CHANGELOG sekciju
3. Updateaj verziju

---

**⚡ BRZI LINKOVI:**
- [Master Prompt](01_PROMPT_TEMPLATE.md) ← Počni ovdje
- [Formatting Guide](02_FORMATTING_GUIDE.md)
- [Best Practices](03_BEST_PRACTICES.md)
- [Troubleshooting](04_TROUBLESHOOTING.md)
- [Udemy Resources](05_UDEMY_RESOURCES_USAGE.md)

---

**🎯 CILJ:** Generirati konzistentne, kvalitetne, detaljne sinopsise za sve module SHIFT4IT programa.