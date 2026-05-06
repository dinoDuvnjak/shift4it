# 📘 DAN 12 - ACCESSIBILITY IMPLEMENTATION: TESTIRANJE I PRIMJENA

## **PREDAVANJE: Accessibility u praksi - Auditing, Testing i Alati**
**TRAJANJE:** 9:00-12:30 (3.5 sata, s pauzama)  
**PDF MATERIJAL:** 8-accessibility.pdf (Slajdovi 49-80+)  
**BROJ STUDENTICA:** 8-30

---

## 📋 **SADRŽAJ PDF-a I RASPODJELA:**

**Nastavak od Dana 11:**

### **DAN 11 (PRETHODNI):**
- ✅ Uvod u Accessibility (a11y)
- ✅ ROI of Accessibility
- ✅ Legislation

### **DAN 12 - OVAJ SINOPSIS (Slajdovi 49-80+):**
- ✅ Auditing/Testing - Slajdovi 49-70
- ✅ Manage - Slajdovi 71-78
- ✅ Conclusions - Slajdovi 79-80+
- ✅ Praktične vježbe s alatima

---

## 🎯 **CILJEVI UČENJA:**

Na kraju ovog predavanja, studentice će moći:

1. **Koristiti** automatske alate za accessibility testiranje (WAVE, Lighthouse, axe)
2. **Provesti** ručno testiranje pristupačnosti (keyboard, contrast)
3. **Razlikovati** automatsko od ručnog testiranja i objasniti zašto je potrebno oboje
4. **Identificirati** najčešće accessibility probleme na web stranicama
5. **Primijeniti** WCAG kriterije na Figma dizajn
6. **Kreirati** accessibility checklist za svoje projekte
7. **Koristiti** Figma pluginove za provjeru kontrasta i pristupačnosti
8. **Planirati** accessibility kao dio design workflow-a

---

## ⏰ **9:00-9:15 - RECAP I UVOD**

### **Recap jučerašnjeg dana (8 min):**

**Što reći studentima:**

"Dobro jutro! Prije nego krenemo s praktičnim dijelom, ponovimo ključne točke od jučer:

❓ **Pitanja za grupu:**
1. Što znači a11y? (accessibility)
2. Koja su 4 POUR principa? (Perceivable, Operable, Understandable, Robust)
3. Kada EAA stupa na snagu za privatni sektor? (lipanj 2025)
4. Zašto je Google 'najpoznatiji slijepac'? (crawler ne vidi, ne čuje, ne koristi miš)

✅ **Jučer:** Zašto je accessibility važan (ROI, zakoni)
✅ **Danas:** KAKO testirati i implementirati accessibility"

---

### **Uvod u testiranje (7 min):**

**Što reći studentima:**

"Postoje 3 načina testiranja accessibility-ja:

### **1. AUTOMATED TESTING**
- Alati: Lighthouse, WAVE, axe
- Brzo, može skenirati cijelu stranicu
- **ALI:** hvata samo ~30% problema!

### **2. MANUAL TESTING**
- Tipkovnička navigacija
- Provjera kontrasta
- Pregled semantičke strukture
- Hvata ~50% problema

### **3. USER TESTING**
- Testiranje s osobama s invaliditetom
- Najvrijednije, ali i najskuplje
- Hvata preostalih ~20% problema

**Zaključak:** Trebamo KOMBINACIJU sva tri pristupa!"

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Automatski alati su odlični za brzu provjeru, ali ne mogu zamijeniti ljudsku procjenu. Npr., alat može provjeriti postoji li alt text, ali ne može procijeniti je li alt text KORISTAN.

---

## ⏰ **9:15-10:00 - SEKCIJA 1: AUTOMATED TESTING TOOLS**

### **Slajd 49: Auditing/Testing - Naslov**

**Što reći studentima (3 min):**

"Sada ulazimo u praktični dio - alati za testiranje.

Kao što smo rekli, automatski alati su prvi korak. Brzi su, besplatni, i mogu skenirati stranice u sekundama.

Ali zapamtite: **automatski alati hvate samo 30% problema!**

To je kao da imate spell-checker za tekst - pomoći će s pravopisom, ali neće uhvatiti ako ste napisali potpuno krivu rečenicu."

---

### **Slajd 50-51: Supports and Levels**

**Što reći studentima (5 min):**

"Prije nego uđemo u alate, ponovimo WCAG razine:

### **WCAG RAZINE USKLAĐENOSTI:**

| Razina | Opis | Primjer |
|--------|------|---------|
| **A** | Minimum | Alt text postoji |
| **AA** | Standard (zakoni) | Kontrast 4.5:1 |
| **AAA** | Idealno | Kontrast 7:1 |

**Što testirati:**
- Za većinu projekata: **AA razina**
- Za specifične potrebe: pojedini AAA kriteriji

**Koliko kriterija ima WCAG 2.2?**
- 86 success criteria ukupno
- 32 na razini A
- 24 na razini AA
- 30 na razini AAA"

Europska direktiva o pristupačnosti (poput Direktive (EU) 2016/2102) ne zahtijeva izričito označavanje web-stranica oznakom ili „bedžom” pristupačnosti.
Međutim, zahtijeva da web-stranice i mobilne aplikacije javnog sektora objave javnu izjavu o pristupačnosti koja opisuje razinu usklađenosti, trenutačne napore i kontakt podatke za povratne informacije korisnika.
Drugim riječima, iako formalna oznaka ili certifikat nisu obvezni, transparentnost i informiranje o pristupačnosti jesu, kako bi korisnici mogli razumjeti razinu pristupačnosti i znati kome se obratiti za podršku.
Objava izjave o pristupačnosti dobar je način da organizacije i tvrtke pokažu koje napore ulažu, jer ona jasno prikazuje razinu usklađenosti, planirana poboljšanja i mogućnosti kontakta za korisnike.

## **Slajd 59: Odabir datoteka**

Sažetak:
Fokusirajte se na stranice s velikim prometom i ključne stranice
Obuhvatite različite vrste sadržaja i funkcionalnosti
Prioritet dajte ključnim točkama korisničkog putovanja
Ograničite se na upravljiv broj stranica koji je reprezentativan za cijelu web-stranicu
Ovakav pristup osigurava da je vaša revizija temeljita i učinkovita, pružajući točan uvid u stanje pristupačnosti vaše web-stranice.



Prilikom revizije pristupačnosti web-stranice, datoteke poput PDF-ova, Word dokumenata i drugog preuzimljivog sadržaja također su važni elementi za procjenu.

Sažetak:
Odaberite ključne i često korištene datoteke, osobito one koje pružaju važne informacije
Obuhvatite različite formate i razine složenosti sadržaja
Fokusirajte se na dokumente povezane s najposjećenijih stranica
Osigurajte da zadovoljavaju standarde pristupačnosti poput WCAG-a za PDF/Office datoteke
Uključivanje procjene sadržaja za preuzimanje osigurava cjelovit uvid u ukupnu pristupačnost vaše web-stranice i pomaže u učinkovitom određivanju prioriteta za poboljšanja.




---

### **Praktična vježba: Google Lighthouse (15 min)**

✏️ **ZADATAK: Lighthouse Audit**

**Što reći studentima:**

"Sada ćemo zajedno napraviti accessibility audit koristeći Google Lighthouse."

**Upute za studentice:**

1. Otvori **Chrome browser**
2. Idi na bilo koju web stranicu (npr. tvoj omiljeni news portal)
3. **Desni klik** → **Inspect** (ili F12)
4. Klikni tab **Lighthouse**
5. Označi samo **Accessibility**
6. Klikni **Analyze page load**
7. Čekaj rezultate (30-60 sekundi)

**Što dobivamo:**
- **Score** (0-100)
- **Lista problema** s prioritetom
- **Upute** kako popraviti svaki problem

**Zajedno analizirajmo:**
- Koji je score stranice?
- Koji su najčešći problemi?
- Koliko je jednostavno popraviti te probleme?

📚 **FACILITATOR NOTES:**

**Troubleshooting:**
- Ako Lighthouse ne radi, provjeri je li stranica potpuno učitana
- Lighthouse radi samo u Chrome-u
- Incognito mode može dati čišće rezultate

**Očekivani problemi na većini stranica:**
- Missing alt text
- Low contrast
- Missing form labels
- Missing document title

---

### **Praktična vježba: WAVE Extension (15 min)**

✏️ **ZADATAK: WAVE Analysis**

**Što reći studentima:**

"WAVE je vizualni alat koji označava probleme direktno na stranici."

**Upute za studentice:**

1. Instaliraj **WAVE browser extension**:
   - [Chrome](https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh)
   - [Firefox](https://addons.mozilla.org/en-US/firefox/addon/wave-accessibility-tool/)

2. Idi na istu stranicu kao prije

3. Klikni **WAVE ikonu** u browseru

4. Analiziraj rezultate:
   - 🔴 **Errors** - moraju se popraviti
   - 🟡 **Alerts** - treba provjeriti
   - 🟢 **Features** - accessibility features koje postoje
   - 🔵 **Structural** - heading struktura
   - 💜 **Contrast** - problemi s kontrastom

**Usporedba s Lighthouse:**
- Je li WAVE našao iste probleme?
- Je li našao dodatne probleme?
- Koji alat daje korisnije informacije?

📖 **Reference:**
- [WAVE Web Accessibility Evaluator](https://wave.webaim.org/)

📚 **FACILITATOR NOTES:**

**Prednosti WAVE:**
- Vizualno pokazuje gdje su problemi
- Detaljnija objašnjenja
- Contrast checker built-in

**Mane WAVE:**
- Može biti overwhelming za početnike
- Ponekad označi "false positives"

---

### **Alat 3: axe DevTools (5 min - demo)**

**Što reći studentima:**

"Još jedan popularan alat je **axe DevTools** od Deque-a.

**Zašto axe:**
- Koriste ga veliki timovi (Microsoft, Google)
- Manje false positives
- Integrira se s development workflow-om

**Kako instalirati:**
1. Chrome Web Store → 'axe DevTools'
2. Instaliraj extension
3. Otvori DevTools (F12)
4. Novi tab 'axe DevTools'
5. Scan page

**Za danas:** Fokusirajte se na Lighthouse i WAVE - axe je 'bonus' alat."

📖 **Reference:**
- [axe DevTools](https://www.deque.com/axe/browser-extensions/)

---

## ⏰ **10:00-10:15 - PAUZA ☕**

**Facilitator notes:**
- Studentice mogu nastaviti eksperimentirati s alatima
- Pripremi se za manual testing sekciju

---

## ⏰ **10:15-11:00 - SEKCIJA 2: MANUAL TESTING**

### **Uvod u ručno testiranje (5 min):**

**Što reći studentima:**

"Automatski alati su odlični za početak, ali ne mogu sve provjeriti.

**Primjeri što automatski alati NE MOGU provjeriti:**

1. **Je li alt text KORISTAN?**
   - Alat može vidjeti da postoji alt='slika1.jpg'
   - Ali to nije koristan alt text!

2. **Je li fokus VIDLJIV?**
   - Alat može vidjeti da je element fokusibilan
   - Ali ne može vidjeti je li fokus vidljiv korisniku

3. **Je li redoslijed logičan?**
   - Alat može vidjeti tab order
   - Ali ne može procijeniti ima li smisla

Zato trebamo **ručno testiranje**!"

---

### **Praktična vježba: Keyboard Navigation (15 min)**

✏️ **ZADATAK: Navigacija tipkovnicom**

**Što reći studentima:**

"Sada ćemo testirati možemo li koristiti stranicu BEZ MIŠA."

**Upute za studentice:**

1. Idi na bilo koju web stranicu
2. **Makni ruke s miša** - koristit ćeš samo tipkovnicu!
3. Testiraj ove akcije:

| Tipka | Akcija |
|-------|--------|
| **Tab** | Idi na sljedeći element |
| **Shift+Tab** | Idi na prethodni element |
| **Enter** | Aktiviraj link/button |
| **Space** | Aktiviraj checkbox/button |
| **Arrow keys** | Navigiraj unutar komponente |
| **Escape** | Zatvori modal/dropdown |

**Pitanja za evaluaciju:**
- [ ] Možeš li doći do SVIH interaktivnih elemenata?
- [ ] Vidiš li JASNO koji element ima fokus?
- [ ] Je li redoslijed LOGIČAN?
- [ ] Možeš li zatvoriti modal/popup?
- [ ] Možeš li ispuniti formu?

**Zabilježi probleme koje pronađeš!**

📚 **FACILITATOR NOTES:**

**Česti problemi:**
- Focus nije vidljiv (outline: none u CSS-u)
- Skip to content link ne postoji
- Modal trap (ne možeš izaći tipkovnicom)
- Custom komponente nisu keyboard accessible

---

### **Praktična vježba: Contrast Checker (10 min)**

✏️ **ZADATAK: Provjera kontrasta**

**Što reći studentima:**

"Kontrast boja je jedan od najčešćih accessibility problema. WCAG zahtijeva:

- **AA standard:** 4.5:1 za normalan tekst, 3:1 za veliki tekst
- **AAA standard:** 7:1 za normalan tekst, 4.5:1 za veliki tekst"

**Upute za studentice:**

1. Otvori [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/)

2. Testiraj ove kombinacije:
   - Bijela pozadina (#FFFFFF) + svijetlo sivi tekst (#999999)
   - Bijela pozadina + tamno sivi tekst (#333333)
   - Plava pozadina (#0066CC) + bijeli tekst (#FFFFFF)

3. Za svaku kombinaciju zabilježi:
   - Contrast ratio
   - Prolazi li AA?
   - Prolazi li AAA?

**Bonus:** Koristi Color Picker u DevTools da dobiješ boje s bilo koje stranice.

📖 **Reference:**
- [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/)
- [Coolors Contrast Checker](https://coolors.co/contrast-checker)

📚 **FACILITATOR NOTES:**

**Kako koristiti Color Picker u Chrome:**
1. DevTools (F12)
2. Elements tab
3. Klikni na boju u Styles
4. Koristi eyedropper za pick boje sa stranice

---

### **WCAG kriteriji koje dizajneri moraju znati (10 min)**

**Što reći studentima:**

"Kao dizajneri, ne morate znati svih 86 WCAG kriterija. Ali ovih 10 MORATE znati:

### **TOP 10 WCAG KRITERIJA ZA DIZAJNERE:**

1. **1.1.1 Non-text Content** (A)
   - Sve slike trebaju alt text

2. **1.4.3 Contrast (Minimum)** (AA)
   - Tekst: 4.5:1, veliki tekst: 3:1

3. **1.4.4 Resize Text** (AA)
   - Tekst mora biti čitljiv pri 200% zoom

4. **1.4.11 Non-text Contrast** (AA)
   - UI komponente: 3:1 kontrast

5. **2.1.1 Keyboard** (A)
   - Sve mora biti dostupno tipkovnicom

6. **2.4.3 Focus Order** (A)
   - Logičan redoslijed fokusa

7. **2.4.7 Focus Visible** (AA)
   - Fokus mora biti vidljiv

8. **2.5.5 Target Size** (AAA → AA u 2.2)
   - Touch targets min 44x44px

9. **3.2.1 On Focus** (A)
   - Fokus ne smije uzrokovati promjenu konteksta

10. **3.3.2 Labels or Instructions** (A)
    - Forme moraju imati jasne labele"

📖 **Reference:**
- [WCAG 2.2 Quick Reference](https://www.w3.org/WAI/WCAG22/quickref/)

---

## ⏰ **11:00-11:15 - SIMULATION ☕**

## SLAJD 68

U kontekstu ciljeva pristupačnosti, simulacije poput NVDA, VoiceOver, Zoom i drugih alata koriste se za simuliranje načina na koji korisnici s različitim vrstama invaliditeta doživljavaju digitalni sadržaj.
Ovi alati pomažu developerima, dizajnerima i testerima da razumiju koliko je web-stranica ili aplikacija pristupačna, oponašajući perspektivu korisnika s vizualnim, slušnim ili motoričkim poteškoćama.

NVDA (NonVisual Desktop Access): besplatni čitač zaslona za Windows koji čita sadržaj naglas, pomažući u provjeri kako slabovidne osobe navigiraju i razumiju stranicu.
VoiceOver: Appleov ugrađeni čitač zaslona za macOS i iOS uređaje, koristi se za testiranje iskustva korisnika s oštećenjem vida na Apple uređajima.
Zoom: značajka pristupačnosti koja povećava sadržaj, korisna za osobe sa slabijim vidom kako bi se osiguralo da su tekst i elementi čitljivi pri različitim razinama uvećanja.
Ostali alati: uključuju TalkBack (Android), ZoomText (uvećanje i čitanje) te sustave za sintezu govora.

Njihova uloga u ciljevima pristupačnosti:
Procjena upotrebljivosti: omogućuju provjeru je li sadržaj uočljiv, upravljiv i razumljiv korisnicima s invaliditetom.
Identifikacija problema: pomažu u otkrivanju nedostajućih podrški, lošeg kontrasta, elemenata kojima se ne može navigirati ili zbunjujućih rasporeda.
Unaprjeđenje dizajna: usmjeravaju prilagodbe kako bi se osigurala kompatibilnost i upotrebljivost za sve korisnike, posebno one koji ovise o pomoćnim tehnologijama.
Zaključak:
Korištenje ovih simulacija kao dijela procesa testiranja pomaže osigurati da digitalni sadržaj zaista zadovoljava standarde pristupačnosti, čineći proizvode inkluzivnima i upotrebljivima za sve, bez obzira na njihove sposobnosti.

…<img width="1113" height="241" alt="image" src="https://github.com/user-attachments/assets/81fb4e92-b1c6-40a0-8e93-dab4082bb27a" />


---

## ⏰ **11:15-12:00 - SEKCIJA 3: ACCESSIBILITY U FIGMI**

### **Figma Pluginovi za Accessibility (10 min)**

**Što reći studentima:**

"Figma ima odlične pluginove za accessibility provjeru TIJEKOM dizajniranja.

### **PREPORUČENI PLUGINOVI:**

**1. Stark**
- Contrast checker
- Color blindness simulator
- Focus order visualization
- [Instaliraj Stark](https://www.figma.com/community/plugin/732603254453395948)

**2. A11y - Color Contrast Checker**
- Jednostavan contrast check
- Besplatan
- [Instaliraj A11y](https://www.figma.com/community/plugin/733159460536249875)

**3. Contrast**
- WCAG contrast checker
- Predlaže alternative
- [Instaliraj Contrast](https://www.figma.com/community/plugin/748533339900865323)

**4. Able**
- Simulira color blindness
- [Instaliraj Able](https://www.figma.com/community/plugin/734693888346260052)"

✏️ **ZADATAK: Instaliraj plugin**

1. Otvori Figma
2. Community → Plugins
3. Traži "Stark" ili "A11y"
4. Instaliraj jedan od pluginova
5. Testiraj na svom projektu

---

### **Praktična vježba: Accessibility Audit u Figmi (20 min)**

✏️ **ZADATAK: Audit vašeg dizajna**

**Što reći studentima:**

"Sada ćemo primijeniti sve što smo naučili na VAŠ dizajn u Figmi."

**Upute za studentice:**

1. Otvori svoj Figma projekt (ili koristi template)

2. **Provjeri kontrast:**
   - Pokreni Stark/A11y plugin
   - Provjeri SVE text/background kombinacije
   - Zabilježi probleme

3. **Provjeri touch targets:**
   - Buttoni: min 44x44px
   - Linkovi: dovoljan razmak između

4. **Provjeri fokus:**
   - Ima li svaki interaktivni element jasno definiran focus state?

5. **Provjeri hijerarhiju:**
   - Jesu li headingi logično strukturirani? (H1 → H2 → H3)
   - Je li vizualna hijerarhija jasna?

6. **Provjeri color blindness:**
   - Koristi Able plugin za simulaciju
   - Je li informacija prenosiva bez boje?

**Zabilježi:**
- 3 problema koje si pronašla
- Kako bi ih popravila

📚 **FACILITATOR NOTES:**

**Ako studentice nemaju svoj projekt:**
- Koristi Figma Community template
- Ili napravi jednostavan landing page mockup (30 min)

---

### **Accessibility Checklist za dizajnere (10 min)**

**Što reći studentima:**

"Na kraju, evo checkliste koju možete koristiti za SVAKI projekt:

### **🎨 ACCESSIBILITY CHECKLIST ZA DIZAJNERE:**

#### **BOJE I KONTRAST:**
- [ ] Text/background kontrast ≥ 4.5:1 (AA)
- [ ] Veliki text kontrast ≥ 3:1
- [ ] UI komponente kontrast ≥ 3:1
- [ ] Informacija se ne prenosi SAMO bojom

#### **TYPOGRAPHY:**
- [ ] Base font size ≥ 16px
- [ ] Line height ≥ 1.5
- [ ] Tekst se može povećati do 200%
- [ ] Izbjegavaj justified text

#### **TOUCH/CLICK TARGETS:**
- [ ] Minimalna veličina 44x44px
- [ ] Dovoljan razmak između targeta

#### **FOCUS STATES:**
- [ ] Svaki interaktivni element ima focus state
- [ ] Focus je JASNO vidljiv
- [ ] Focus order je logičan

#### **FORME:**
- [ ] Sva polja imaju labele
- [ ] Error states su jasni
- [ ] Required polja su označena

#### **SLIKE:**
- [ ] Sve slike imaju prostor za alt text
- [ ] Dekorativne slike su označene

#### **NAVIGACIJA:**
- [ ] Jasna, konzistentna navigacija
- [ ] Breadcrumbs gdje ima smisla
- [ ] Skip links u wireframe"

📖 **Reference:**
Spremi ovu checklist - koristit ćeš je za svaki projekt!

---

## ⏰ **12:00-12:30 - MANAGE, CONCLUSIONS, RECAP**

### **Slajd 71-78: Managing Accessibility (10 min)**

**Notes iz PDF-a:**
_"Accessibility is an ongoing process, not a one-time fix."_

**Što reći studentima:**

"Accessibility nije 'check and forget'. To je kontinuirani proces.

### **ACCESSIBILITY MANAGEMENT:**

**1. INTEGRIRAJ U WORKFLOW:**
- Design review uključuje accessibility check
- Dev review uključuje automated testing
- QA uključuje manual testing

**2. DOKUMENTIRAJ:**
- Accessibility guidelines za vaš tim
- Component library s accessible komponentama
- Testing procedure

**3. EDUCIRAJ:**
- Cijeli tim treba razumjeti osnove
- Accessibility champions u timu

**4. TESTIRAJ KONTINUIRANO:**
- Automated tests u CI/CD pipeline
- Redoviti manual auditi
- User testing s osobama s invaliditetom

**5. POBOLJŠAVAJ:**
- Accessibility statement s planom poboljšanja
- Prioritiziraj po impact/effort"

---

### **Slajd 79-80: Conclusions (5 min)**

**Što reći studentima:**

"Zaključimo ova dva dana o accessibility-ju:

### **KLJUČNE PORUKE:**

1. **Accessibility je za SVE, ne samo za osobe s invaliditetom**
   - Curb cut effect
   - 100% korisnika u nekom trenutku

2. **Accessibility je poslovna odluka, ne trošak**
   - ROI: tržište, SEO, troškovi, reputacija
   - EAA zakon od 2025

3. **Accessibility počinje u dizajnu**
   - Shift-left pristup
   - Kontrast, touch targets, fokus

4. **Automatski alati su početak, ne kraj**
   - 30% problema hvata automatika
   - Manual + user testing za ostatak

5. **Accessibility je state of mind**
   - Pitanje 'može li svatko ovo koristiti?'
   - Dio svakog design review-a"

---

### **Final Recap i Q&A (15 min)**

**Što reći studentima:**

"Ponovimo sve iz ova dva dana:

### **DAN 11 - ZAŠTO:**
- a11y = accessibility
- ROI: 1.3B korisnika, SEO, troškovi, brand
- POUR principi: Perceivable, Operable, Understandable, Robust
- EAA: lipanj 2025, WCAG 2.2 AA

### **DAN 12 - KAKO:**
- Automated tools: Lighthouse, WAVE, axe
- Manual testing: keyboard, contrast
- Figma plugins: Stark, A11y
- Checklist za svaki projekt

### **VAŠI SLJEDEĆI KORACI:**

1. Instaliraj WAVE extension - koristi na svakoj stranici
2. Instaliraj Stark plugin u Figmi
3. Nauči keyboard shortcuts za navigaciju
4. Dodaj accessibility check u svoj design process

**Imate li pitanja?**"

---

## ❓ **PITANJA ZA PROVJERU RAZUMIJEVANJA**

### **Osnovni level:**
1. Koji postotak accessibility problema automatski alati mogu otkriti? (~30%)
2. Koje tipke koristimo za navigaciju tipkovnicom? (Tab, Enter, Space, Arrow keys)
3. Koji je minimalni contrast ratio za normalan tekst po WCAG AA? (4.5:1)

### **Srednji level:**
4. Zašto automatski alati nisu dovoljni za accessibility testiranje?
5. Navedi 3 WCAG kriterija koje dizajneri moraju znati.
6. Koji Figma plugin bi koristila za provjeru kontrasta?

### **Viši level:**
7. Dizajniraš button na tamno plavoj pozadini (#003366). Koje boje teksta bi prošle WCAG AA?
8. Kako bi organizirala accessibility workflow u timu od 5 ljudi?
9. Klijent kaže "Nemamo budget za accessibility testing s korisnicima". Kako bi argumentirala?

---

## 🔄 **BACKUP AKTIVNOSTI**

### **BACKUP AKTIVNOST 1: Competitive Accessibility Audit (15 min)**

**Cilj:** Usporediti accessibility 3 konkurentskih stranica.

**Upute:**
1. Odaberi 3 stranice u istoj industriji (npr. 3 banke, 3 e-commercea)
2. Pokreni Lighthouse na svakoj
3. Usporedi:
   - Accessibility score
   - Najčešće greške
   - Tko je "pobjednik"?
4. Prezentiraj findings grupi

📚 **FACILITATOR NOTES:**
- Zanimljivo je usporediti velike vs male tvrtke
- Često manje poznate stranice imaju lošiji accessibility

---

### **BACKUP AKTIVNOST 2: Fix the Design (15 min)**

**Cilj:** Identificirati i predložiti popravke za accessibility probleme.

**Upute:**
1. Facilitator dijeli screenshot dizajna s accessibility problemima
2. Studentice identificiraju probleme
3. Predlažu rješenja
4. Diskusija o prioritetima

📚 **FACILITATOR NOTES:**
**Primjer problematičnog dizajna:**
- Svijetlo sivi tekst na bijeloj pozadini
- Mali buttoni bez padding-a
- Forme bez labela
- Slike bez alt text prostora

---

### **BACKUP AKTIVNOST 3: Accessibility Personas (10 min)**

**Cilj:** Razviti empatiju kroz persone.

**Upute:**
1. Kreiraj 3 persone s različitim potrebama:
   - Ana, 28, koristi screen reader (slijepa)
   - Marko, 45, koristi samo tipkovnicu (tremor)
   - Ivana, 32, color blind (protanopia)
2. Za svaku personu napiši:
   - Kako koriste web?
   - Koje su njihove frustracije?
   - Što bi im pomoglo?

---

### **BACKUP AKTIVNOST 4: Screen Reader Demo (10 min)**

**Cilj:** Iskustvo korištenja screen readera.

**Upute:**
1. Uključi VoiceOver (Mac) ili NVDA (Windows)
2. Zatvori oči
3. Pokušaj navigirati jednostavnu stranicu
4. Podijeli iskustvo s grupom

📚 **FACILITATOR NOTES:**
**VoiceOver shortcuts (Mac):**
- Cmd+F5: Uključi/isključi
- VO+Right/Left: Navigiraj
- VO+Space: Aktiviraj

**NVDA (Windows):**
- Besplatan download: nvaccess.org
- Insert+Down: Read all
- Tab: Interactive elements

---

### **BACKUP AKTIVNOST 5: Accessibility Statement Draft (15 min)**

**Cilj:** Razumjeti što accessibility statement treba sadržavati.

**Upute:**
1. Draftiraj accessibility statement za fiktivnu stranicu
2. Uključi:
   - Razinu usklađenosti
   - Poznate probleme
   - Plan poboljšanja
   - Kontakt informacije

📚 **FACILITATOR NOTES:**
**Template:**
```
Accessibility Statement for [Naziv stranice]

Commitment: [Izjava o posvećenosti accessibility-ju]

Conformance status: [Partially conformant with WCAG 2.2 AA]

Known limitations:
- [Problem 1]
- [Problem 2]

Planned improvements:
- [Mejora 1] - [Datum]
- [Mejora 2] - [Datum]

Feedback: [Email/forma za prijavu problema]
```

---

### **BACKUP AKTIVNOST 6: Color Blindness Challenge (10 min)**

**Cilj:** Dizajnirati UI bez oslanjanja na boju.

**Upute:**
1. Dizajniraj status indicator (success/error/warning)
2. Mora biti razumljiv u grayscale
3. Koristi: ikone, tekst, oblike - ne samo boju
4. Testiraj s Able pluginom

📚 **FACILITATOR NOTES:**
**Primjeri dobrih rješenja:**
- ✅ Zelena kvačica + tekst "Success"
- ❌ Crveni X + tekst "Error"
- ⚠️ Žuti trokut + tekst "Warning"

**Loše rješenje:**
- Samo zeleni/crveni krug bez ikone ili teksta

---

### **BACKUP AKTIVNOST 7: Accessibility Quick Wins (10 min)**

**Cilj:** Identificirati brze poboljšanja.

**Upute:**
1. Odaberi stranicu koju često koristiš
2. Napravi WAVE scan
3. Identificiraj 5 "quick wins" - probleme koji se mogu brzo popraviti:
   - Missing alt text
   - Missing form labels
   - Low contrast links
4. Procijeni effort (1-5) za svaki

📚 **FACILITATOR NOTES:**
Quick wins su obično:
- Alt text: 1 minuta po slici
- Form labels: 2 minute po formi
- Link contrast: 5 minuta (CSS promjena)

---

## 📚 **DODATNI RESURSI ZA FACILITATORA**

### **Alati koje smo koristili danas:**

1. **Google Lighthouse**
   - Built-in u Chrome DevTools
   - Accessibility + Performance + SEO

2. **WAVE**
   - [wave.webaim.org](https://wave.webaim.org/)
   - Browser extension

3. **axe DevTools**
   - [deque.com/axe](https://www.deque.com/axe/)
   - Professional tool

4. **WebAIM Contrast Checker**
   - [webaim.org/resources/contrastchecker](https://webaim.org/resources/contrastchecker/)

### **Figma Pluginovi:**

1. **Stark** - [Figma Community](https://www.figma.com/community/plugin/732603254453395948)
2. **A11y** - [Figma Community](https://www.figma.com/community/plugin/733159460536249875)
3. **Able** - [Figma Community](https://www.figma.com/community/plugin/734693888346260052)

### **Za tvoje dalje učenje:**

1. **Deque University** (besplatni tečajevi)
   - [dequeuniversity.com](https://dequeuniversity.com/)

2. **WebAIM Articles**
   - [webaim.org/articles](https://webaim.org/articles/)

3. **A11y Coffee** (newsletter)
   - [a11y.coffee](https://a11y.coffee/)

### **Pripremna lista:**

- [ ] Testiraj Lighthouse na svom laptopu
- [ ] Instaliraj WAVE extension
- [ ] Instaliraj Stark u Figmu
- [ ] Pripremi screenshot dizajna s problemima za backup aktivnost
- [ ] Provjeri da NVDA/VoiceOver rade (za demo)

---

## 🌐 **EKSTERNI RESURSI**

### **Checkliste:**
- [WebAIM WCAG Checklist](https://webaim.org/standards/wcag/checklist)
- [A11y Project Checklist](https://www.a11yproject.com/checklist/)

### **Testiranje:**
- [Pa11y](https://pa11y.org/) - Command line tool
- [Accessibility Insights](https://accessibilityinsights.io/) - Microsoft

### **Učenje:**
- [MDN Accessibility Guide](https://developer.mozilla.org/en-US/docs/Learn/Accessibility)
- [Google Web Fundamentals - Accessibility](https://developers.google.com/web/fundamentals/accessibility)

---

## 💡 **UDEMY DOPUNA**

### **Preporučene lekcije:**
Za dodatne vježbe s accessibility alatima, pogledaj:
- Udemy tečaj: "Complete Web Designer"
- Sekcija o accessibility testing (ako postoji)

### **External Resources iz Udemy PDF-a:**
Koristi linkove za:
- Dodatne accessibility alate
- Case studies
- Design system primjere

---

**KRAJ SINOPSISA - DAN 12** ✅

---

## 📝 **NAPOMENE ZA FACILITATORA:**

1. **Ovaj dan je PRAKTIČAN** - studentice rade s alatima
2. **Provjeri laptope** - trebaju Chrome + internet
3. **Instaliraj pluginove UNAPRIJED** na prezentacijskom računalu
4. **Backup plan** ako internet ne radi: offline demo s screenshotovima
5. **Handout:** Accessibility Checklist za studentice

---

## 📋 **HANDOUT ZA STUDENTICE:**

### **ACCESSIBILITY TOOLKIT:**

**Browser Extensions:**
- WAVE: [chrome.google.com/webstore/detail/wave](https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh)
- axe: [chrome.google.com/webstore/detail/axe](https://chrome.google.com/webstore/detail/axe-devtools-web-accessib/lhdoppojpmngadmnindnejefpokejbdd)

**Figma Plugins:**
- Stark
- A11y - Color Contrast Checker
- Able - Friction free accessibility

**Contrast Checkers:**
- webaim.org/resources/contrastchecker
- coolors.co/contrast-checker

**Keyboard Shortcuts:**
- Tab: Next element
- Shift+Tab: Previous
- Enter: Activate
- Space: Toggle
- Arrows: Navigate within component

**WCAG Quick Reference:**
- w3.org/WAI/WCAG22/quickref

---

**Sljedeće u modulu:** [Nastavak UX/UI tema]
