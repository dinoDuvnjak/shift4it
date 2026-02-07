# 📘 DAN 3 - PSYCHOLOGY PRINCIPLES IN DESIGN

## **PREDAVANJE: UX Psychology Laws & Gestalt Principles**
**TRAJANJE:** 9:00-12:30 (3.5 sata, s pauzama)
**PDF MATERIJAL:** 2 & 3.Principles of design and ergonomics-1.pdf (nastavak)
**BROJ STUDENTICA:** 8-30

---

## 🎯 **CILJEVI UČENJA:**

Na kraju ovog predavanja, studentice će moći:
1. Primijeniti Hick's Law za smanjenje cognitive loada u dizajnu (limitiranje izbora)
2. Prepoznati i koristiti Gestalt principe za organiziranje vizualnih elemenata (proximity, similarity, closure, continuity)
3. Koristiti Von Restorff Effect za isticanje ključnih elemenata u interfaceu
4. Primijeniti Fitts' Law za optimizaciju veličine i pozicije interaktivnih elemenata
5. Razumjeti F i Z reading patterns i dizajnirati sukladno s njima
6. Evaluirati postojeće interfacee kroz prizmu psiholoških principa
7. Identificirati loš UX dizajn i artikulirati zašto ne funkcionira
8. Kreirati wireframe koji primjenjuje sve naučene psihološke principe

---

## ⏰ **RASPORED PREDAVANJA:**

```
9:00-10:00   Psychology Laws (Hick, Fitts, Von Restorff)
10:00-10:15  PAUZA ☕
10:15-11:00  Gestalt Principles (Dio 1)
11:00-11:15  PAUZA ☕
11:15-12:15  Gestalt Principles (Dio 2) + Eye-tracking Patterns
12:15-12:30  User Inyerface Game & Recap
```

---

## ⏰ **9:00-9:10 (10 min) - UVOD U PSYCHOLOGY PRINCIPLES**

### **Slajd 67: The Psychology Principles in UI/UX Design**

**Notes iz PDF-a:**
_"Psychology has an important role in designing the user experience. By understanding how different psychology principles influence human behaviour, you can design your products to elicit specific responses and actions from your users."_

**Što reći studentima (10 min):**

"Dobro jutro! Jučer smo učile o vizualnim principima dizajna - alignment, contrast, colors, typography.

Danas idemo **dublje u PSIHOLOGIJU** - kako ljudski mozak procesira informacije i kako to utječe na dizajn.

**Zašto je ovo važno?**

Ljudi ne koriste interfacee na način kako mi dizajneri mislimo da će ih koristiti. Oni:
- Skenirate sadržaj, ne čitaju svaku riječ
- Traže najlakši put do cilja
- Donose odluke na temelju vizualnih cue-ova
- Imaju limitiranu working memory

**Ako razumijete kako mozak funkcionira, možete dizajnirati interfacee koji su intuitivni i prirodni za korištenje.**

Danas učimo:
1. **UX Laws** - Hick's Law, Fitts' Law, Von Restorff Effect
2. **Gestalt Principles** - Kako mozak grupira vizualne elemente
3. **Reading Patterns** - F i Z patterns
4. **Practical Application** - User Inyerface game (frustrirajući dizajn)

Spremne za malo psihologije? Let's go!"

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
UX dizajn je 50% psihologija, 50% vizualni dizajn. Ne možeš kreirati dobar UX bez razumijevanja kako ljudi misle i percipiraju informacije.

**Ključni koncept:**
Ljudi koriste **dva sistema razmišljanja** (Daniel Kahneman - "Thinking, Fast and Slow"):
- **System 1:** Brzo, automatsko, intuitivno (većina UI interakcija)
- **System 2:** Sporo, deliberate, analitičko (složeni taskovi)

Dobar UX dizajn radi sa System 1 - automatizam, ne prisiljava korisnika da previše razmišlja.

**Česta pitanja:**
Q: "Zar ovo nisu samo 'trikovi' za manipuliranje korisnika?"
A: "Ne, ako ih koristiš etički. Ovi principi pomažu korisnicima postići njihove ciljeve lakše. Manipulacija bi bila koristiti ih da tjerate ljude na akcije koje NE žele."

**Troubleshooting:**
- **Studentice misle da je ovo previše teorijski**: Naglasi da će sve biti praktično primijenjeno - svaki princip ima konkretne design implikacije.

📖 **Linkovi za dublje razumijevanje:**
- [Thinking Fast and Slow - Book Summary](https://fs.blog/thinking-fast-and-slow/)
- [Psychology for UX - Nielsen Norman Group](https://www.nngroup.com/topic/psychology-and-ux/)

---

## ⏰ **9:10-9:30 (20 min) - HICK'S LAW**

### **Slajd 68: Hick's Law**

**Notes iz PDF-a:**
_"Hick's Law states that the more stimuli (or choices) users face, the longer it will take them to make a decision. RT = a + b log2(n)"_

**Što reći studentima (8 min):**

"Počinjemo s **Hick's Law** - jedan od najvažnijih UX zakona.

**FORMULA:** RT = a + b log2(n)
- RT = Reaction Time (vrijeme odluke)
- n = broj opcija
- a, b = konstante

**U PRIJEVODU:**
Što više opcija daš korisniku, duže treba da odluči. Ovo se zove **'paradox of choice'**.

**PRIMJER - LOŠE:**
Zamislite restoran s 200 jela na meniju. Što se događa?
- Pregledaš cijeli meni 20 minuta
- Ne možeš se odlučiti
- Na kraju odabereš nešto random
- Možda čak odeš u drugi restoran jer je overwhelming

**PRIMJER - DOBRO:**
Restoran s 15-20 jela, organiziranih u kategorije (predjela, glavna jela, deserti).
- Brzo skeniraš kategorije
- Odabereš kategoriju (glavna jela)
- Odabereš iz 5-6 opcija
- Zadovoljan si s odlukom

**U UI DIZAJNU:**

**❌ LOŠE:**
- Navigation bar sa 20 linkova
- Form sa 30 polja
- Homepage sa 50 različitih buttona

**✅ DOBRO:**
- Navigation bar sa 5-7 glavnih kategorija (rest u dropdown)
- Form sa 5-10 esencijalnih polja (multi-step ako treba više)
- Homepage sa 1 primary CTA + 2-3 secondary actions

**PRAVILO: Limit choices gdje god je moguće.**"

**Primjeri:**
Prikaži Amazon homepage (mnogo opcija, ali organizirano u kategorije) vs Google homepage (jedna akcija - search).

📖 **Reference:**
- [Hick's Law - Laws of UX](https://lawsofux.com/hicks-law/)
- [The Paradox of Choice - TED Talk](https://www.ted.com/talks/barry_schwartz_the_paradox_of_choice)

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Hick's Law je logaritmičan, ne linearan - znači da svaka dodatna opcija povećava reaction time, ali ne u istom postotku. Prvih 5 opcija imaju veći impact nego opcija 50-55.

**Real-world primjeri:**
- **Netflix:** Preporučuje 5-10 filmova na top row, ne sve 10,000
- **McDonald's:** Ima "Featured Items" ili "Combo Meals" da smanje paralyzu choice-a
- **Apple:** Nudi 3-4 modela iPhonea, ne 50 kao neki Android brandovi

**Česta pitanja:**
Q: "Što ako korisnici TREBAJU sve te opcije?"
A: "Ponudi advanced filtering ili search. Primjer: Amazon ima milijune proizvoda, ali ti prikazuje 20-50 relevantnih. Filtering omogućava korisniku da SAM smanji opcije."

Q: "Koliko je previše opcija?"
A: "Psihologija kaže 7±2 itema je sweet spot za working memory. Za UI: 5-9 opcija po categoriji je optimalno."

**Troubleshooting:**
- **Studentice kažu: 'Ali ja volim imati puno izbora!'**: Objasni razliku između WANTING i NEEDING. Možda misliš da želiš 50 opcija, ali research pokazuje da su ljudi sretniji i brže odlučuju s manje opcija.

📖 **Linkovi za dublje razumijevanje:**
- [Hick's Law in UX - Interaction Design Foundation](https://www.interaction-design.org/literature/article/hick-s-law-making-the-choice-easier-for-users)

---

### **Slajd 69: Hick's Law in web design**

**Notes iz PDF-a:**
_"Visual showing on the left many options taking longer to decide, vs on the right fewer options. Best solution is to limit total number of options."_

**Što reći studentima (4 min):**

"Vizualno - što se događa:

**SLIKA LIJEVO:** 20 opcija → korisnik zbunjen, dugo traje
**SLIKA DESNO:** 5 opcija → brza odluka

**BEST PRACTICES:**

**1. Limit initial options**
- Ne prikazuj sve odjednom
- Progressive disclosure (pokažite više kako korisnik napreduje)

**2. Kategorize**
- Grupiraj slične opcije zajedno
- Primjer: E-commerce - kategorije (Muško, Žensko, Djeca) umjesto 500 proizvoda

**3. Use defaults/recommendations**
- Predloži najpopularniju opciju
- Netflix: 'Trending Now', 'Because you watched...'

**4. Filter & search**
- Za large datasets, omogući korisniku da filtrira opcije
- Amazon: Filters by price, rating, brand..."

📚 **FACILITATOR NOTES:**

**Progressive disclosure** = prikaži basic opcije first, advanced opcije na request. Primjer: Google Search - default je simple search bar, ali možeš kliknuti 'Advanced Search' za više filters.

---

### **Slajd 70: How to apply this law in UI/UX design**

**Notes iz PDF-a:**
_"1. Minimize choices when response times are critical. 2. Break down complex tasks into smaller steps. 3. Use filters for large numbers of products. 4. Take care not to simplify to the point of abstraction."_

**Što reći studentima (8 min):**

"Kako primijeniti Hick's Law u praksi:

**1. MINIMIZE CHOICES u kritičnim situacijama**
- Emergency actions: Jedan veliki button 'Call 911'
- Checkout: Jedan CTA 'Complete Purchase', ne 5 različitih payment opcija istovremeno

**2. BREAK DOWN complex tasks**
- Multi-step forms umjesto jednog dugog forma
- Primjer: Signup proces - korak 1 (email/password), korak 2 (profile info), korak 3 (preferences)
- Svaki korak = fewer choices = lakše

**3. USE FILTERS za large catalogs**
- E-commerce: Filter by category, price, rating, color...
- User sam sužava opcije do manageable seta

**4. DON'T OVER-SIMPLIFY**
- Balance između simplicity i functionality
- Previše simplificirano = korisnik ne može naći što traži
- Primjer: Ne reduciraj 'Settings' na 3 opcije ako korisnik treba 10 različitih settingsa

**REAL-WORLD APPLICATION:**

**Booking.com:**
- Step 1: Gdje, Kada (2 inputa)
- Step 2: Odaberi hotel iz 10-15 na prvoj stranici (može filtrirati)
- Step 3: Odaberi room type (2-4 opcije)
- Step 4: Checkout (1 akcija)

Razlomili complex task (booking vacation) u manageable korake s limitiranim opcijama u svakom."

📚 **FACILITATOR NOTES:**

**Balance je ključan:**
Ne želite eliminirati sve opcije - neki korisnici trebaju advanced features. Rješenje: Default simple, ali omogući advanced options za power users.

**Česta pitanja:**
Q: "Što ako moji korisnici ŽELE sve opcije odmah?"
A: "Pitaj ih! User research će pokazati. Ali obično 'wanting' i 'needing' nisu isto. Power users su manjina - dizajniraj za većinu, omogući advanced opcije za power users."

---

## ⏰ **9:30-9:50 (20 min) - GESTALT PRINCIPLES (INTRO + PROXIMITY + SIMILARITY)**

### **Slajd 71: Gestalt Principles of Visual Perception**

**Notes iz PDF-a:**
_"Gestalt psychology: 'the whole is greater than the sum of its parts.' Our brains naturally organize and interpret visual information to perceive meaningful patterns."_

**Što reći studentima (8 min):**

"Sada idemo u **Gestalt Principles** - kako naš mozak organizira vizualne informacije.

**Gestalt** = Njemački za 'unified whole'

**OSNOVNA IDEJA:**
Naš mozak NE vidi individualne elemente - vidi PATTERNS i GROUPS.

**Primjer:**
Kada vidite: • • • • •
Ne vidite '5 točaka' - vidite 'red točaka' ili 'grupu'

**Zašto je ovo važno za dizajn?**
Ako razumijete kako mozak grupira elemente, možete dizajnirati interfacee gdje je organizacija INTUITIVNA.

**Gestalt principi koje ćemo učiti:**
1. **Proximity** - Blizina
2. **Similarity** - Sličnost
3. **Common Regions** - Zajednička regija
4. **Symmetry** - Simetrija
5. **Figure-Ground** - Figura i pozadina
6. **Closure** - Zatvaranje
7. **Continuity** - Kontinuitet
8. **Common Fate** - Zajednička sudbina

**Svaki princip će vam pomoći odlučiti kako organizirati elemente u vašem dizajnu!**"

📖 **Reference:**
- [Gestalt Principles - Interaction Design Foundation](https://www.interaction-design.org/literature/topics/gestalt-principles)
- [Laws of UX - Gestalt Laws](https://lawsofux.com/)

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Gestalt psychology je osnovana 1920s u Njemačkoj. Founders: Max Wertheimer, Kurt Koffka, Wolfgang Köhler. Originally za razumijevanje percepcije, ali principles su univerzalni - primjenjuju se u art, design, photography, UI/UX.

**Ključna lekcija:**
Dizajn nije samo o individualnim elementima - o tome kako elementi INTERAGIRAJU i kako mozak ih percipira kao cjelinu.

**Česta pitanja:**
Q: "Moramo li koristiti SVE Gestalt principe u svakom dizajnu?"
A: "Ne! Ali znajući ih, možete SVJESNO odlučiti kako organizirati elemente. Ponekad ih koristite, ponekad namjerno breakate rules za efekt."

---

### **Slajd 72: Why Are Gestalt Principles Important in Design?**

**Notes iz PDF-a:**
_"Improve UX by making interfaces more intuitive. Enhance visual hierarchy and readability. Guide users' attention. Create cohesive layouts."_

**Što reći studentima (4 min):**

"Zašto trebate znati Gestalt principe?

**1. INTUITIVNI INTERFACEI**
- Korisnici odmah razumiju kako je sadržaj organiziran
- Ne moraju razmišljati gdje što pripada

**2. VIZUALNA HIJERARHIJA**
- Grouping pokazuje što je povezano
- Važnost se komunicira kroz spatial relationships

**3. VODITE PAŽNJU**
- Mozak automatski gleda patterns
- Možete dizajnirati 'flow' kroz interface

**4. COHESIVE LAYOUTS**
- Sve izgleda kao unified whole, ne chaos

**Gestalt principi su TEMELJ dobrog vizualnog dizajna u UI/UX, branding, graphic design!**"

📚 **FACILITATOR NOTES:**

Gestalt je subset vizualnog dizajna - kombinira se sa svim ostalim principima (alignment, contrast, itd.) koje su učile jučer.

---

### **Slajd 73: Law of Proximity**

**Notes iz PDF-a:**
_"Elements that are close to each other are perceived as related or grouped together."_

**Što reći studentima (10 min):**

"Prvi Gestalt princip: **LAW OF PROXIMITY (Zakon blizine)**

**PRAVILO:** Elementi koji su BLIZU jedni drugima percipiraju se kao POVEZANI.

**VIZUALNO:**
```
●  ●  ●     ●  ●  ●
```
Vidite 2 grupe od 3, ne 6 individualnih točaka.

**U UI DIZAJNU:**

**✅ DOBRO - Form sa groupingom:**
```
Personal Information
[First Name]
[Last Name]
[Date of Birth]

Contact Information  
[Email]
[Phone]
[Address]
```
Korisnik ODMAH vidi: "Ovo su dvije kategorije informacija"

**❌ LOŠE - Form bez groupinga:**
```
[First Name]
[Email]
[Last Name]
[Phone]
[Date of Birth]
[Address]
```
Korisnik se muči: "Koji fieldovi idu zajedno?"

**PRAKTIČNA PRIMJENA:**

**1. Group related elements**
- Navigation items - blizu jedan drugome
- Product image + price + title - close together
- Related buttons - grupiraj

**2. Use spacing to separate**
- VIŠE prostora = različite grupe
- Primjer: Navigation links blizu, ali dalje od main content

**3. Cards & Containers**
- Grupiraj related content u card
- Prostor oko carda = separation od drugih sadržaja

**PRAVILO: Spacing je komunikacija. Blizu = povezano. Daleko = odvojeno.**"

**Primjeri:**
Prikaži Medium.com članak - primijetite kako su related elementi blizu (author info, date, read time), dok su različite sekcije odvojene spacingom.

📖 **Reference:**
- [Law of Proximity - Laws of UX](https://lawsofux.com/law-of-proximity/)

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Proximity je najmoćniji Gestalt princip za organizaciju - ljudi će PRVO grupirati po blizini, pa onda po drugim faktorima (boja, shape).

**Praktični test:**
Ako elementirate dizajn, squintajte ili blur view - vidite li jasne grupe? Ako da = dobar proximity. Ako ne = loš spacing.

**Česta pitanja:**
Q: "Koliko prostora treba između grupa?"
A: "Minimum 1.5-2x više nego spacing UNUTAR grupe. Primjer: Ako je spacing unutar grupe 8px, između grupa treba biti barem 16-24px."

**Troubleshooting:**
- **Dizajn izgleda cluttered**: Vjerojatno nedovoljno spacinga između grupa.
- **Ne zna se što ide zajedno**: Proximity nije jasan - povećaj spacing između, smanji spacing unutar.

---

### **Slajd 74: Law of Proximity in web design**

**Notes iz PDF-a:**
_"Example showing grouped elements are perceived as related."_

**Što reći studentima (3 min):**

"Vizualni primjer:

Kada elementi su **close together** → percipiraju se kao SET
Kada elementi su **far apart** → percipiraju se kao ODVOJENI

**Web design aplikacija:**
- **Card components** - sve unutar carda = jedna group
- **Navigation menus** - items blizu = povezani (dropdown)
- **Footer sections** - grupiraj links po kategorijama s spacing"

📚 **FACILITATOR NOTES:**

Pokažite real website - analizirajte kako koriste proximity. Primjer: Airbnb homepage - every listing card ima sliku, title, price, rating blizu = jedna grupa.

---

### **Slajd 75: How to apply Law of Proximity in UI/UX**

**Notes iz PDF-a:**
_"Group related elements closely. Maintain consistent spacing between related elements. Avoid clutter. Group form fields by categories. Use proximity to create hierarchy."_

**Što reći studentima (5 min):**

"Kako primijeniti Law of Proximity:

**1. GROUP RELATED ELEMENTS**
- Buttons koje rade slične stvari - grupiraj
- Form fields iste kategorije - blizu
- Product info (image, title, price) - close together

**2. CONSISTENT SPACING**
- Svi related elementi = isti spacing (npr. 8px)
- Separation između grupa = veći spacing (npr. 24px)

**3. AVOID CLUTTER**
- Don't crowd sve na jednu stranicu
- Daj prostora između sections

**4. CATEGORIZE FORMS**
- Personal Info group
- Contact Info group
- Payment Info group
- Svaka grupa jasno separated

**5. CREATE HIERARCHY**
- Tight grouping = high relationship
- Loose grouping = low relationship

**QUICK TIP:**
Before you add border ili background color za grouping, PRVO probaj samo SPACING. Često je dovoljno!"

📚 **FACILITATOR NOTES:**

**Design principle:**
Manje je više - ne trebate border, background, shadow za svaku grupu. Samo dobar spacing radi posao.

---

## ⏰ **9:50-10:00 (10 min) - LAW OF SIMILARITY**

### **Slajd 76: Law of Similarity**

**Notes iz PDF-a:**
_"Objects that share similar characteristics (color, shape, size) are seen as belonging together."_

**Što reći studentima (8 min):**

"Sljedeći princip: **LAW OF SIMILARITY (Zakon sličnosti)**

**PRAVILO:** Elementi koji IZGLEDAJU SLIČNO percipiraju se kao POVEZANI.

**VIZUALNO:**
```
●  ●  ●  ■  ■  ■
```
Vidite: 3 kruga, onda 3 kvadrata - dvije grupe

**SLIČNOST može biti:**
- **Boja** - Svi plavni elementi = jedna grupa
- **Shape** - Svi kružni elementi = jedna grupa
- **Size** - Svi veliki elementi = jedna grupa
- **Style** - Svi boldni texti = jedna grupa

**U UI DIZAJNU:**

**✅ DOBRO - Consistent button styles:**
- Svi primary buttoni = plava boja + isti style
- Svi secondary buttoni = sivi outline + isti style
- Korisnik nauči: "Plavi button = glavna akcija"

**✅ DOBRO - Consistent links:**
- Svi linkovi = plava boja + underline
- Korisnik zna: "Plavo + underline = clickable"

**❌ LOŠE - Inconsistent styles:**
- Neki buttoni zeleni, neki crveni, neki žuti (no pattern)
- Neki linkovi underlined, neki nisu (confusion)

**PRIMJENA:**

**1. Style all similar elements the same way**
- Svi H1 naslovi = isti font, size, color
- Svi product cards = isti layout
- Svi error messages = crveni tekst + icon

**2. Use different styles for different functions**
- Primary actions = one style
- Secondary actions = different style
- Tertiary actions = third style

**3. Icons consistency**
- Svi ikoni isti stil (outlined ili filled, ne mix)

**PRAVILO: Ako izgleda isto, mora RADITI isto. Ako radi različito, mora IZGLEDATI različito.**"

**Primjeri:**
Prikaži Material Design - kako svi buttoni imaju consistent style across cijeli system.

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Similarity je temelj **Design Systems**. Companies kao Google, Apple, IBM kreiraju design systems gdje je SVE definirano - kako izgledaju buttons, links, forms, itd. Korisnici nauče patterns.

**Česta pitanja:**
Q: "Može li biti dosadno ako je sve isto?"
A: "Ne! Similarity se odnosi na FUNCTIONAL elemente (buttons, links). Creative content (slike, illustrations) može biti varied. Balance između consistency i variety."

Q: "Što ako trebam 10 različitih tipova buttona?"
A: "Red flag! Obično trebate 2-3 tipa (primary, secondary, tertiary). Ako trebate više, možda imate prekompliciran interface."

**Troubleshooting:**
- **Korisnici klikću na stvari koje nisu clickable**: Vjerojatno izgledaju slično kao clickable elementi. Promijeni style.

---

### **Slajd 77: Law of Similarity in web design**

**Notes iz PDF-a:**
_"When items share superficial characteristics, we perceive them as grouped. Seen in branding and design system guidelines."_

**Što reći studentima (2 min):**

"Primjeri gdje vidite Law of Similarity:

**1. Branding**
- Coca-Cola red + specific font = instant recognition
- Svi Coca-Cola proizvodi share iste karakteristike

**2. Design Systems**
- Google Material Design - svi Google apps share style
- Apple Human Interface Guidelines - svi iOS apps share patterns

**3. Web navigation**
- Svi navigation links ista boja/style = you know 'to su linkovi'

Similarity builds **familiarity** i **trust**."

📚 **FACILITATOR NOTES:**

Design systems su practical application of Law of Similarity - kreiraš library of reusable components koji svi izgledaju i rade isto.

---

### **Slajd 78: How to apply Law of Similarity**

**Notes iz PDF-a:**
_"Style similar functions the same way. Use same typography for related text. Repeat visual styles. Highlight differences with contrasting styles. Use visual cues consistently."_

**Što reći studentima (5 min):**

"Praktična primjena:

**1. STYLE SIMILAR FUNCTIONS IDENTICALLY**
- Svi 'Delete' buttoni = crveni
- Svi 'Edit' buttoni = plavi
- Svi 'Save' buttoni = zeleni

**2. TYPOGRAPHY CONSISTENCY**
- Svi H1 = 32px, Bold, Dark Gray
- Svi H2 = 24px, Semi-Bold, Dark Gray
- Svi Body = 16px, Regular, Gray

**3. REPEAT VISUAL STYLES**
- Colors, shapes, spacing - consistent across interface

**4. HIGHLIGHT DIFFERENCES**
- Ako element radi nešto RAZLIČITO = mora izgledati različito
- Primjer: 'Delete' button vs 'Save' button - različite boje

**5. CONSISTENT ICONS**
- Ako koristiš outlined icons, koristi SAMO outlined
- Ako koristiš filled icons, koristi SAMO filled
- Don't mix styles

**DESIGN SYSTEM APPROACH:**
Kreiraj 'component library':
- Button component (primary, secondary, tertiary styles defined)
- Input field component
- Card component
- itd.

Reuse components = automatic consistency!"

📚 **FACILITATOR NOTES:**

Figma ima excellent component system - možete kreirati master component i reusati across cijeli file. Promjena master componenta = update svih instanci.

---

## ⏰ **10:00-10:15 (15 min) - PAUZA ☕**

---

## ⏰ **10:15-10:45 (30 min) - GESTALT PRINCIPLES (DIO 2)**

### **Slajd 79: Law of Common Regions**

**Notes iz PDF-a:**
_"The tendency of brains to group elements when they are located within a shared boundary or enclosure."_

**Što reći studentima (8 min):**

"Sljedeći princip: **LAW OF COMMON REGIONS (Zakon zajedničke regije)**

**PRAVILO:** Elementi unutar ZAJEDNIČKE GRANICE percipiraju se kao GRUPA.

**VIZUALNO:**
```
┌─────────────┐
│  ●  ●  ●    │
└─────────────┘

┌─────────────┐
│  ■  ■  ■    │
└─────────────┘
```
Dvije grupe - jedna u prvom boxu, jedna u drugom.

**U UI DIZAJNU:**

**✅ CARDS:**
Svaki card = zajednička regija
- Pinterest pins - svaki pin u svom containeru
- Product listings - svaki product u cardu
- Blog posts - svaki post u svojoj regiji

**✅ SECTIONS:**
- Navigation bar = jedna regija (background color)
- Main content = druga regija
- Footer = treća regija

**KAKO KREIRATI COMMON REGION:**

**1. Borders**
```css
border: 1px solid #ccc;
```

**2. Background color**
```css
background: #f5f5f5;
```

**3. Shadows**
```css
box-shadow: 0 2px 8px rgba(0,0,0,0.1);
```

**4. Spacing** (implicit boundary)
- Dovoljan whitespace oko grupe = implicit region

**KADA KORISTITI:**

- **Mnogo informacija na stranici** - koristi cards da organiziraš
- **Complex forms** - svaka sekcija u svojoj regiji
- **Dashboards** - svaki metric/graph u svom containeru

**PRAVILO: Common region je JAČI od proximity - čak i ako elementi nisu blizu, ako su u istoj regiji, percipirani su kao grupa.**"

**Primjeri:**
Prikaži Pinterest - svaki pin je u svom implicit card containeru.

📖 **Reference:**
- [Law of Common Region - Laws of UX](https://lawsofux.com/law-of-common-region/)

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Common region overrides proximity - čak i ako su elementi daleko u regiji, mozak ih vidi kao grupu jer share boundary.

**Design trade-off:**
Previše borders/backgrounds = vizualno cluttered. Balance između common regions (clarity) i clean design (simplicity).

**Česta pitanja:**
Q: "Trebam li border ili background color?"
A: "Ovisi o context-u. Subtle background color je često dovoljno. Border dodaješ kada trebaš jači separation."

**Troubleshooting:**
- **Dizajn izgleda 'boxy'**: Previše borders. Koristi subtle shadows ili background colors umjesto hard borders.

---

### **Slajd 80: Law of Common Regions in web design**

**Notes iz PDF-a:**
_"Pinterest example - each pin separated in own region from others."_

**Što reći studentima (3 min):**

"Pinterest je ODLIČAN primjer Common Regions:

Svaki pin ima:
- Sliku
- Title
- Description
- Author info

Sve to u JEDNOJ regiji (card).

Korisnik odmah vidi: 'Ovo je jedan pin'. Clear separation od drugih pinova.

**Best practice:**
Koristi subtle containers - ne trebaju uvijek heavy borders. Shadow ili background color je često dovoljno."

📚 **FACILITATOR NOTES:**

Pinterest's Masonry layout - svaki pin je različite visine, ali svaki je u svojoj jasnoj regiji.

---

### **Slajd 81: How to apply Law of Common Regions**

**Notes iz PDF-a:**
_"Use containers or boxes. Leverage background colors. Apply borders and shadows. Create distinct sections. Organize information visually."_

**Što reći studentima (5 min):**

"Praktična primjena:

**1. USE CONTAINERS**
- Svaki logički set informacija = container
- Primjer: User profile card (avatar, name, bio, stats - sve u jednom cardu)

**2. BACKGROUND COLORS**
- Navigation = dark background
- Main content = white background
- Sidebar = light gray background

**3. BORDERS & SHADOWS**
```css
/* Subtle card */
border-radius: 8px;
box-shadow: 0 2px 4px rgba(0,0,0,0.1);
```

**4. DISTINCT SECTIONS**
- Header, Main, Footer - svaki ima svoj visual boundary
- Može biti color, border, ili samo spacing

**5. DASHBOARDS**
- Svaki metric u svom containeru
- Clear gdje jedan KPI ends, drugi starts

**DESIGN TIP:**
Start s minimum styling (samo spacing), onda dodaj borders/shadows/colors ako treba više definition."

📚 **FACILITATOR NOTES:**

**Modern trend:** Glassmorphism i neumorphism koriste subtle backgrounds i shadows za common regions bez heavy borders.

---

### **Slajd 82: Law of Symmetry**

**Notes iz PDF-a:**
_"Symmetrical elements are perceived as part of the same group."_

**Što reći studentima (6 min):**

"**LAW OF SYMMETRY (Zakon simetrije)**

**PRAVILO:** Elementi sa SIMETRIČNIM OSIMA lakše se percipiraju kao CJELINA.

**VIZUALNO:**
```
( )  { }  [ ]
```
Vidite 3 para, ne 6 individualnih simbola - jer je svaki par simetričan.

**U UI DIZAJNU:**

**✅ SYMMETRICAL LAYOUTS:**
- **Split-screen design** - lijeva strana = desna strana (mirror)
- **Centered content** - element centriran s jednakim spacing lijevo/desno
- **Modal dialogs** - centrirani na ekranu, simetrični layout

**KADA KORISTITI:**

**1. Formal/Professional websites**
- Corporate sites, banking, insurance
- Simetrija = stabilnost, pouzdanost

**2. Landing pages**
- Hero section - slika lijevo, tekst desno (ili obrnuto)
- Feature sections - alternating left/right layout

**3. Login/Signup pages**
- Form centriran
- Logo i branding simetrično raspoređeni

**KADA IZBJEĆI:**

**Asymmetry za dinamiku:**
- Magazine-style layouts
- Creative portfolios
- Blog layouts

**PRAVILO: Simetrija kreira balance i harmony. Koristi ju za formal/stable feeling. Break symmetry za dynamic/creative feeling.**"

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Symmetry = perceived stability. Asymmetry = perceived dynamism. Biraj prema brand tone-u i content-u.

**Česta pitanja:**
Q: "Mora li biti perfektly symmetrical?"
A: "Ne! Visual symmetry je dovoljno - izgleda balanced, ne mora biti pixel-perfect mirror."

---

### **Slajd 83: Law of Symmetry in web design**

**Notes iz PDF-a:**
_"Example showing symmetrical layouts."_

**Što reći studentima (2 min):**

"Primjeri simetrije:

**Apple.com** - često koriste symmetrical layouts
- Product centriran
- Tekst i image balanced left/right

**Banking websites** - skoro uvijek symmetrical
- Trust i stability = simetrija

**Asymmetrical primjer:**
- Wired.com, Vogue.com - magazine layouts, dynamic i editorial feel"

📚 **FACILITATOR NOTES:**

Pokažite usporedbu - Apple.com (symmetrical, stable) vs Awwwards winning site (asymmetrical, creative).

---

### **Slajd 84: How to apply Law of Symmetry**

**Notes iz PDF-a:**
_"Align elements symmetrically. Mirror design across screens. Maintain visual balance. Use symmetrical icons. Introduce asymmetry with caution."_

**Što reći studentima (4 min):**

"Praktična primjena:

**1. SYMMETRIC ALIGNMENT**
- Center važne elemente (logo, headline, CTA)
- Mirror layout (slika lijevo = tekst desno, onda obrnuto)

**2. BALANCE ACROSS SCREENS**
- Consistent layout na svakoj stranici
- Header, footer, sidebar - symmetrični

**3. ICONS & GRAPHICS**
- Symmetrical icons = professional look
- Primjer: Material Design icons - većina je symmetrical

**4. ASYMMETRY ZA EMPHASIS**
- Ako želiš breakati monotoniju ili kreirati focus
- Primjer: CTA button malo offset da se istakne

**5. RESPONSIVE DESIGN**
- Desktop: Symmetrical multi-column layout
- Mobile: Stack vertically (still centered = symmetry)"

📚 **FACILITATOR NOTES:**

Responsive design često breaka desktop symmetry na mobile - to je OK! Što je važno je da je svakom breakpoint-u design feels balanced.

---

### **Slajd 85: Figure and Ground**

**Notes iz PDF-a:**
_"The brain distinguishes between foreground and background elements."_

**Što reći studentima (8 min):**

"**FIGURE-GROUND PRINCIPLE (Figura i pozadina)**

**PRAVILO:** Mozak automatski ODVAJA foreground (figure) od background (ground).

**KLASIČNI PRIMJER:**
Rubin's Vase - vidite vazu ILI dva lica?

Ovo demonstrira da mozak mora odlučiti: što je figura, što je pozadina?

**U UI DIZAJNU:**

**✅ CLEAR FIGURE-GROUND:**
- Modal dialog (foreground) + dimmed background
- Card (figure) na colored background (ground)
- White text (figure) na tamnoj pozadini (ground)

**❌ AMBIGUOUS FIGURE-GROUND:**
- Low contrast - ne znaš što je foreground
- Primjer: Light gray text na bijeloj pozadini

**TEHNIKE ZA CLEAR FIGURE-GROUND:**

**1. CONTRAST**
- High contrast između figure i ground
- Tamno na svijetlom ili obrnuto

**2. SHADOWS**
```css
box-shadow: 0 4px 6px rgba(0,0,0,0.1);
```
- Shadow kreira depth = jasno što je foreground

**3. BLUR/DIM BACKGROUND**
- Modals - pozadina blurred ili dimmed
- Foreground element postaje obvious focus

**4. LAYERING**
- Z-axis - što je 'on top' = figura

**PRIMJER - Modal dialog:**
```
┌─────────────────────────┐
│   [Dimmed background]   │
│                         │
│   ┌───────────────┐     │
│   │ MODAL DIALOG  │ ← Figure
│   │ [Content]     │     │
│   │ [Button]      │     │
│   └───────────────┘     │
│                         │ ← Ground (dimmed)
└─────────────────────────┘
```

Jasno što je main focus (modal), što je pozadina (dimmed page).

**PRAVILO: Make it OBVIOUS što je main content (figure). Don't make users guess.**"

**Primjeri:**
Prikaži Basecamp.com - white foreground areas jasno se izdvajaju od background.

📖 **Reference:**
- [Figure-Ground Principle - Interaction Design Foundation](https://www.interaction-design.org/literature/article/figure-ground-gestalt-principle)

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Figure-ground je temelj visual hierarchy - users will focus on what stands out as figure, ignore what recedes as ground.

**Česta pitanja:**
Q: "Može li nešto biti i figura i ground?"
A: "Da - ovisi o focus-u. Primjer: Kad otvorite modal, modal je figura. Kad zatvorite modal, main page content postaje figura."

**Troubleshooting:**
- **Users ne vide važne elemente**: Vjerojatno nema jasnog figure-ground distinctiona. Dodaj contrast, shadow, ili color za separation.

---

## ⏰ **10:45-11:00 (15 min) - CLOSURE, CONTINUITY, COMMON FATE**

### **Slajd 88: Law of Closure**

**Notes iz PDF-a:**
_"The mind fills in gaps to complete a visual pattern or shape. Without this principle, we would only perceive discontinuous lines."_

**Što reći studentima (8 min):**

"**LAW OF CLOSURE (Zakon zatvaranja)**

**PRAVILO:** Mozak POPUNJAVA PRAZNINE da komplezira shapes.

**VIZUALNO:**
```
   ---
  /   \
 |     |
  \   /
   ---
```
Vidite KRUG, iako su linije discontinuous (isprekidane).

**ZAŠTO OVO RADI:**
Mozak preferira complete shapes, pa će mentalno 'zatvoriti' incomplete oblike.

**U UI DIZAJNU:**

**✅ MINIMALISTIČKI LOGOS:**
- IBM logo - horizontal linije, ali vidite slova
- WWF logo - negativan prostor kreira panda
- FedEx logo - arrow između E i x

**✅ ICONS:**
- Loading spinner - nije kompletan krug, ali vidite ga kao krug
- Hamburger menu - 3 linije, ali 'zatvarate' ga kao button

**✅ FORMS & BORDERS:**
- Ne trebate kompletne borders oko svakog elementa
- Implied boundaries - korisnici će 'zatvoriti' oblik mentalno

**PRAKTIČNA PRIMJENA:**

**1. CLEANER DESIGN**
- Koristi incomplete shapes - izgleda sofisticiranije
- Primjer: Border samo na dnu input fielda (ne oko cijelog)

**2. ICONS**
- Simplified icons - ne trebaju sve detalje
- Mozak će fill in missing parts

**3. LOADING ANIMATIONS**
- Incomplete circles/shapes = implies motion i completion

**4. NEGATIVE SPACE LOGOS**
- Kreativni logo design - space između elementa kreira drugu formu

**PRAVILO: Don't over-explain vizualno. Mozag će popuniti praznine. Koristi closure za minimalistički, clean design.**"

**Primjeri:**
Prikaži IBM logo, WWF panda logo, FedEx arrow.

📖 **Reference:**
- [Law of Closure - Laws of UX](https://lawsofux.com/law-of-closure/)

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Closure omogućava minimalistički dizajn - ne treba sve biti explicit. Users' brains will do some work, što kreira engaging experience.

**Famous primjeri:**
- **NBC logo** - 6 teardrop shapes, ali vidite peacock
- **Tour de France logo** - Yellow circle = sun & wheel, cyclist hidden u letters

**Česta pitanja:**
Q: "Koliko mogu 'hintati' prije nego postane unclear?"
A: "Test! Pokažite dizajn nekome tko ga nikad nije vidio. Ako vide što ste intended - works. Ako ne - previše ambiguous."

**Troubleshooting:**
- **Korisnici ne vide intended shape**: Too subtle. Dodajte više visual cues.

---

### **Slajd 89: Law of Closure in web design**

**Notes iz PDF-a:**
_"Examples of closure in icons and minimalist designs."_

**Što reći studentima (2 min):**

"Gdje vidite closure u dizajnu:

**ICONS:**
- Shopping cart icon - usually incomplete lines, ali vidite cart
- Cloud icon - outline koji nije fully closed

**LOADING INDICATORS:**
- Spinner - incomplete circle rotation

**LOGOS:**
- Minimalist logos koriste negative space

Closure omogućava **cleaner, simpler designs** without losing clarity."

📚 **FACILITATOR NOTES:**

Icon libraries (Material Icons, Font Awesome) often koriste closure - icons su simplified ali still recognizable.

---

### **Slajd 90: How to apply Law of Closure**

**Notes iz PDF-a:**
_"Use implied shapes. Create minimalist icons. Simplify complex forms. Use in loading animations. Engage users' imagination."_

**Što reći studentima (5 min):**

"Praktična primjena:

**1. IMPLIED SHAPES**
- Koristi partial borders - mozak će zatvoriti
- Primjer: Border samo lijevo side of element = still feels contained

**2. MINIMALIST ICONS**
- Simplified shapes koje mozak completes
- Less is more

**3. NEGATIVE SPACE**
- Use space between elementi da kreira drugu formu
- Creative logo design technique

**4. LOADING ANIMATIONS**
- Incomplete circles rotating = implies ongoing process

**5. PROGRESSIVE DISCLOSURE**
- Show hints of hidden content (blur, fade)
- Users know there's more = mental closure

**DESIGN TIP:**
When simplifying design, remove elements one by one i test - može li korisnik still razumjeti bez tog elementa? Ako da = remove it (closure će raditi)."

📚 **FACILITATOR NOTES:**

**Progressive enhancement approach:**
Start minimal, dodaj only ako users ne razumiju. Closure omogućava da manje je više.

---

### **Slajd 91: Law of Continuity**

**Notes iz PDF-a:**
_"The eye follows lines, curves, or patterns smoothly rather than seeing them as separate elements."_

**Što reći studentima (6 min):**

"**LAW OF CONTINUITY (Zakon kontinuiteta)**

**PRAVILO:** Oko prirodno PRATI LINIJE i CURVES.

**VIZUALNO:**
```
●━━●━━●━━●━━●
```
Vidite jednu kontinuiranu liniju, ne 5 odvojenih točaka.

**U UI DIZAJNU:**

**✅ VISUAL FLOW:**
- **Arrows** - vode oko kroz interface
- **Lines** - connectaju related elementi
- **Curves** - smooth transitions between sections

**✅ READING PATH:**
- Arrange elementi along path koji oko prirodno prati
- F-pattern, Z-pattern layouts

**PRIMJERI:**

**1. PROGRESS INDICATORS:**
```
Step 1 ━━━ Step 2 ━━━ Step 3 ━━━ Step 4
```
Linija kreira visual flow - vidiš progression

**2. TIMELINE:**
```
2020 ─── 2021 ─── 2022 ─── 2023
```
Horizontalna linija = temporal continuity

**3. NAVIGATION:**
- Breadcrumbs: Home > Category > Product
- Arrow pokazuje path koji ste prešli

**4. SCROLLING DESIGN:**
- Content flow top to bottom
- Sections blended s curves ili gradients = smooth continuity

**PRAVILO: Koristi lines, curves, arrows da VODITE oko korisnika kroz interface. Don't make them hunt for next step.**"

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Continuity je o reducing cognitive load - ako layout prirodno vodi oko, korisnik ne mora razmišljati gdje gledati sljedeće.

**Česta pitanja:**
Q: "Što ako ne želim da korisnik prati specific path?"
A: "Onda nemoj koristiti strong directional cues (arrows, lines). Ali većina tasks benefitaju od guided flow."

---

### **Slajd 92: Law of Continuity in web design**

**Notes iz PDF-a:**
_"Examples showing elements aligned along path creating smooth flow."_

**Što reći studentima (2 min):**

"Primjeri continuity:

**VOLKSWAGEN CAROUSELS:**
- Cards slide along horizontal path
- Smooth continuation - vidiš da ima more content

**PORTFOLIO SITES:**
- Scrolling design gdje svaka sekcija flows u sljedeću
- Curves ili diagonal layouts guide eye

**E-COMMERCE:**
- Product images arranged u grid, ali eye prati row-by-row
- Natural reading continuation"

📚 **FACILITATOR NOTES:**

Modern web često koristi parallax scrolling i animated transitions - sve to leverages continuity princip.

---

### **Slajd 93: How to apply Law of Continuity**

**Notes iz PDF-a:**
_"Use visual cues. Align elements along path. Create seamless navigation. Use gradients. Maintain visual hierarchy."_

**Što reći studentima (5 min):**

"Praktična primjena:

**1. VISUAL CUES**
- Arrows, lines, curves - guide users
- Primjer: Onboarding flow - arrow pokazuje 'Next'

**2. ALIGN ALONG PATH**
- Arrange CTA buttons along natural reading path
- Text i images flow together

**3. SEAMLESS NAVIGATION**
- Breadcrumbs
- Progress bars
- Steppers (1 → 2 → 3 → 4)

**4. GRADIENTS & FADES**
```css
background: linear-gradient(to bottom, #fff, #f0f0f0);
```
- Smooth transitions between sections

**5. SCROLLING ANIMATIONS**
- Elements appear kao što scrollaš
- Continuity of experience

**DESIGN TIP:**
When laying out content, think: 'Where does the eye naturally go next?' Position elementi along that path."

📚 **FACILITATOR NOTES:**

Scroll-triggered animations (AOS - Animate On Scroll libraries) leverage continuity - elementi appear along scroll path, krerajući guided experience.

---

### **Slajd 94: Common Fate**

**Notes iz PDF-a:**
_"Objects moving in the same direction or at the same speed are perceived as related."_

**Što reći studentima (4 min):**

"**COMMON FATE (Zajednička sudbina)**

**PRAVILO:** Elementi koji se KREĆU ZAJEDNO percipiraju se kao GRUPA.

**PRIMJER:**
Čopor ptica leti zajedno → vidite ih kao grupu, ne individualne ptice.

**U UI DIZAJNU:**

**✅ ANIMATED GROUPS:**
- Kada otvoriš dropdown menu - svi items slide down together
- Kada loadaš dashboard - svi cards appear together

**✅ CAROUSEL:**
- Cards koji scroll zajedno = one set of content

**✅ SCROLL EFFECTS:**
- Parallax - elementi u background kreću se sporije = different layer
- Elementi koji scroll zajedno = same layer

**PRAKTIČNA PRIMJENA:**

**1. ANIMATE RELATED ITEMS TOGETHER**
- Group reveal animation
- Primjer: List items fade in one-by-one, ali u sequence = related

**2. HOVER EFFECTS**
- Hover na card, cijeli card ima hover state
- Highlight all related elements zajedno

**3. DRAG & DROP**
- Items koji se mogu dragati zajedno = related set

**PRAVILO: Sync animations za related elements. Don't animate randomly - koordiniraj motions.**"

📚 **FACILITATOR NOTES:**

Common fate je najmanje korišten Gestalt princip u statičnom dizajnu, ali vrlo važan u animacijama i interactions.

---

## ⏰ **11:00-11:15 (15 min) - PAUZA ☕**

---

## ⏰ **11:15-11:45 (30 min) - VON RESTORFF EFFECT & FITTS' LAW**

### **Slajd 97: The Von Restorff Effect**

**Notes iz PDF-a:**
_"When multiple similar objects are present, the one that differs from the rest is most likely to be remembered. This is the main reason why all CTAs look different from other buttons."_

**Što reći studentima (10 min):**

"Sada idemo na **VON RESTORFF EFFECT** - također poznat kao **ISOLATION EFFECT**.

**PRAVILO:** Element koji je DRUGAČIJI od ostalih je najlakše ZAPAMTITI i privlači NAJVIŠE PAŽNJE.

**PRIMJER:**
```
●  ●  ●  ★  ●  ●  ●
```
Koja je forma najupečatljivija? Zvijezda! Jer je different.

**U UI DIZAJNU - CTA BUTTONS:**

Ovo je **GLAVNI RAZLOG** zašto CTA buttoni izgledaju drugačije od svih ostalih:

**✅ DOBRO:**
```
[Secondary]  [Secondary]  【PRIMARY CTA】
     ↑ Gray outline         ↑ Vibrant color, larger
```

Primary CTA se **IZDVAJA** - different color, možda shadow, možda veći.

**❌ LOŠE:**
```
[Button]  [Button]  [Button]  [Button]
```
Sve jednako = ništa ne privlači pažnju. Korisnik ne zna što kliknuti.

**PRAKTIČNA PRIMJENA:**

**1. PRIMARY CTA**
- Different color od brand colors
- Često: Complementary color (high contrast)
- Primjer: Spotify - zeleni CTA button na crnoj pozadini

**2. IMPORTANT NOTIFICATIONS**
- Red notification badge - different od ostalih elemenata
- Odmah privlači pažnju

**3. FEATURED PRODUCTS**
- 'Best Seller' badge - different color
- Highlighted background

**4. ERROR MESSAGES**
- Crvena boja - different od normalne text boje
- Icon + color = double emphasis

**PRAVILO:**

✅ **Use contrast wisely:**
- Make the TARGET highlight unique
- Different shape, color, or size

❌ **Don't overdo it:**
- Multiple prominent items = confusing
- Only ONE primary action should receive maximum emphasis

**BEST PRACTICE:**
- **1 Primary CTA** (most different)
- **2-3 Secondary actions** (medium emphasis)
- **Rest** (low emphasis)

Ako je SVE highlighted, NIŠTA nije highlighted!"

**Primjeri:**
Prikaži Medium.com - green 'Get Started' button jasno se izdvaja od ostalih elemenata.

📖 **Reference:**
- [Von Restorff Effect - Laws of UX](https://lawsofux.com/von-restorff-effect/)

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Von Restorff Effect = selective attention. Mozak automatski nota i remembers outliers. Ovo je moćan tool ali mora biti korišten strategically.

**Real-world primjeri:**
- **Spotify:** Zeleni CTA na crnoj pozadini
- **Netflix:** Crveni 'Get Started' button
- **Shopify:** Zeleni 'Start Free Trial' button

**Česta pitanja:**
Q: "Može li biti više primary CTA-ova?"
A: "Ne! Samo JEDAN primary CTA po screen/section. Ako imaš više, korisnik ne zna koji je najvažniji. Exception: Different sections of long page mogu imati different primary actions."

Q: "Koja boja je best za CTA?"
A: "Ovisi o brand colorima. Trebate high contrast. Često: Ako je brand plavi, CTA može biti narančasti (complementary). A/B testiraj different options."

**Troubleshooting:**
- **Low conversion rates**: Možda CTA ne stoji out dovoljno. Provjerite contrast, size, positioning.
- **Users klikću wrong button**: Možda sekundarni button izgleda previše prominent. Reduce emphasis.

📖 **Linkovi za dublje razumijevanje:**
- [CTA Button Design Best Practices](https://www.nngroup.com/articles/call-to-action-buttons/)

---

### **Slajd 98: Von Restorff Effect in web design**

**Notes iz PDF-a:**
_"Medium uses green CTA button contrasting with background to draw attention."_

**Što reći studentima (3 min):**

"**Medium.com primjer:**

Većina stranice = white/black/gray (neutral)
CTA button = green (vibrant, stands out)

Result: Oko odmah ide na zeleni button.

**Druge primjere:**
- **Dropbox:** Plavi CTA na bijeloj pozadini
- **Mailchimp:** Žuti CTA na light pozadini

**Pattern:**
CTA boja je uvijek RAZLIČITA od dominantnih brand colors na stranici. Ovo kreira isolation effect."

📚 **FACILITATOR NOTES:**

Von Restorff je jedan od najlakših principa za implementirati - samo make CTA different. Ali effective!

---

### **Slajd 99: How to apply Von Restorff Effect**

**Notes iz PDF-a:**
_"Use contrast wisely. The highlight should focus on one element. Test and optimize with A/B testing."_

**Što reći studentima (7 min):**

"Praktična primjena:

**1. USE CONTRAST WISELY**

Make CTA unique:
- **Different color** (complementary ili high contrast)
- **Different size** (larger than other buttons)
- **Different shape** (rounded corners vs sharp)

Example:
```css
/* Primary CTA */
background: #FF6B35; /* Vibrant orange */
padding: 16px 32px; /* Larger */
border-radius: 8px;
box-shadow: 0 4px 8px rgba(255,107,53,0.3);

/* Secondary buttons */
background: transparent;
border: 1px solid #ccc;
padding: 12px 24px; /* Smaller */
```

**2. FOCUS ON ONE ELEMENT**

❌ **Don't do this:**
Multiple attention-seeking elements on same screen.

✅ **Do this:**
ONE primary CTA + supporting secondary actions.

**3. TEST & OPTIMIZE**

A/B testing:
- Test different colors (is orange better than green?)
- Test different sizes
- Test different positioning
- Measure click-through rates

**4. HIERARCHY OF EMPHASIS**

Create 3 levels:
- **High emphasis:** Primary CTA (vibrant, large, shadow)
- **Medium emphasis:** Secondary actions (outlined, smaller)
- **Low emphasis:** Tertiary links (text links, subtle)

**5. CONTEXT MATTERS**

Different pages = different emphasis:
- **Homepage:** 'Get Started' = primary
- **Pricing page:** 'Buy Now' = primary
- **Product page:** 'Add to Cart' = primary

**DESIGN CHECKLIST:**

Before launching, ask:
- [ ] Je li primary CTA JASNO najistaknutiji element?
- [ ] Može li korisnik identificirati main action u 3 sekunde?
- [ ] Ima li previše competing elements za pažnju?
- [ ] Je li color contrast dovoljan?

**PRAVILO: One hero element per screen. Make it shine, reduce noise around it.**"

📚 **FACILITATOR NOTES:**

**A/B testing tools:**
- Google Optimize (free)
- Optimizely
- VWO (Visual Website Optimizer)

Test različite varijante CTA buttona i mjeri koji ima highest conversion rate.

**Česta pitanja:**
Q: "Što ako imam 2 equally important actions?"
A: "Razmisli jeste li SIGURNI da su equally important. Usually jedna akcija je important od druge. Ako stvarno jesu equal, koristi RAZLIČITE distinctive styles - ali rijetko je ovo best practice."

---

### **Slajd 100: Fitts' Law**

**Notes iz PDF-a:**
_"Fitts' Law proposes that the time taken to move to a target area is a function of the size of the target and distance to the target. T = k × log2(D/S + 0.5)"_

**Što reći studentima (10 min):**

"Sljedeći zakon: **FITTS' LAW**

**FORMULA:** T = k × log2(D/S + 0.5)
- T = Time to reach target
- D = Distance to target
- S = Size of target
- k = constant

**U PRIJEVODU:**
Što je target **VEĆI** i **BLIŽE**, brže ga možete kliknuti.

**REAL-WORLD PRIMJER:**

Zamislite klikneš button na ekranu:
- **Large button blizu cursora** = brzo klikneš (0.5 sec)
- **Tiny button daleko od cursora** = sporo klikneš (2 sec)

**U UI DIZAJNU:**

**✅ DOBRO - Large CTA:**
```css
button {
  padding: 16px 40px; /* Large click area */
  font-size: 18px;
}
```

**❌ LOŠE - Tiny CTA:**
```css
button {
  padding: 4px 8px; /* Tiny - teško kliknuti */
  font-size: 10px;
}
```

**PRAKTIČNA PRIMJENA:**

**1. SIZE MATTERS**

Minimum click target:
- **Desktop:** 44x44px
- **Mobile (touch):** 48x48px (thumb size)

Ovo je WCAG accessibility guideline također.

**2. DISTANCE MATTERS**

Frequent actions = close to expected cursor/touch location
- **Mobile:** Important buttons at BOTTOM (thumb reach)
- **Desktop:** Important buttons gdje cursor likely jest

**3. SPOTIFY EXAMPLE:**

Prikaži Spotify web player:
- **PLAY button** = HUGE, centered (most important action)
- **Skip, volume** = medium size (secondary)
- **Other controls** = smaller (tertiary)

Play button je largest jer je most frequent action.

**4. EDGE & CORNER PLACEMENT**

**Infinite size targets:**
- Screen edges i corners = easier to hit (cursor 'stops' at edge)
- Mac OS: Menu bar at TOP edge = infinitely tall target
- Windows: Start button at CORNER = easy to hit

**FITTS' LAW FOR TOUCH (MOBILE):**

**Thumb zone map:**
```
┌─────────────────┐
│  HARD TO REACH  │ ← Top corners
│                 │
│  EASY TO REACH  │ ← Middle/bottom
│  🖐️ THUMB ZONE  │ ← Bottom center = easiest
└─────────────────┘
```

Important actions = bottom center (natural thumb position).

**PRAVILO:**
- Make important targets LARGE
- Place frequent actions CLOSE to expected input location
- Use screen edges strategically"

**Primjeri:**
Prikaži Spotify - Play button je huge and centered.

📖 **Reference:**
- [Fitts' Law - Interaction Design Foundation](https://www.interaction-design.org/literature/article/fitts-s-law-the-importance-of-size-and-distance-in-ui-design)

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Fitts' Law je matematički principle iz 1954 (Paul Fitts). Originally za human movement, ali perfectly primjenjivo na UI design.

**Real-world primjeri:**
- **iOS:** Back button je large i top-left (predictable location)
- **Android:** Navigation at bottom = easier reach
- **Floating Action Button (FAB):** Large button, bottom-right corner = easy access

**Česta pitanja:**
Q: "Trebam li SVE buttone napraviti huge?"
A: "Ne! Size = importance. Primary actions = large. Secondary = medium. Tertiary = small. Balance između usability i vizualne čistoće."

Q: "Što ako imam 10 equally important actions?"
A: "Red flag! Vjerojatno nisu equally important. Prioritize. Ako stvarno jesu, organize u groups ili use different interaction pattern (menu, tabs)."

**Troubleshooting:**
- **Korisnici se muče kliknuti buttone**: Vjerojatno premaleni. Increase size ili padding.
- **Mobile users accidentally klik wrong button**: Buttons su preblizu. Increase spacing.

📖 **Linkovi za dublje razumijevanje:**
- [Fitts' Law Calculator](https://www.yorku.ca/mack/FittsLawSoftware/)

---

### **Slajd 101: Fitts' Law in web design**

**Notes iz PDF-a:**
_"Spotify example - Play button is much easier to press than any other button."_

**Što reći studentima (2 min):**

"**Spotify perfect primjer Fitts' Law:**

- **Play button:** Huge, centered → easiest to click
- **Next/Previous:** Medium size → secondary
- **Volume, settings:** Small → tertiary

Veličina = importance = ease of clicking.

**Lesson:** Size your buttons according to frequency of use i importance."

📚 **FACILITATOR NOTES:**

Live demo - otvori Spotify web player i pokažite kako je Play button dominantan.

---

### **Slajd 102: How to apply Fitts' Law**

**Notes iz PDF-a:**
_"Larger targets. Reduced distance. Edge & corner placement. Grouping. Feedback. Accessibility."_

**Što reći studentima (8 min):**

"Praktična primjena Fitts' Law:

**1. LARGER TARGETS**

Make clickable elements big enough:
```css
/* Minimum touch target */
button {
  min-width: 48px;
  min-height: 48px;
  padding: 12px 24px;
}
```

**2. REDUCED DISTANCE**

Place frequent controls close to main interaction area:

**Mobile:**
- Navigation = BOTTOM (thumb reach)
- Primary CTA = BOTTOM or CENTER

**Desktop:**
- CTA near expected cursor position
- Breadcrumbs near top (expected location)

**3. EDGE & CORNER PLACEMENT**

Use screen edges strategically:
- **Mac:** Menu always at top edge (infinite height)
- **Mobile:** FAB at bottom corner (easy thumb access)

**4. GROUPING**

Related elements = close together:
- Form submit button = end of form (expected)
- Modal actions = bottom of modal (grouped)

**5. FEEDBACK**

Immediate visual confirmation:
```css
button:hover {
  background: #darker-color;
  transform: scale(1.05); /* Subtle grow */
}

button:active {
  transform: scale(0.98); /* Subtle shrink */
}
```

**6. ACCESSIBILITY**

Ensure targets meet WCAG guidelines:
- Minimum 44x44px (Level AA)
- Adequate spacing between targets
- High contrast for visibility

**MOBILE-SPECIFIC:**

**Thumb Zone Heatmap:**
- **Green zone (easy):** Bottom 1/3 of screen, center
- **Yellow zone (ok):** Middle 1/3
- **Red zone (hard):** Top 1/3, especially corners

Place important actions in GREEN ZONE.

**RESPONSIVE DESIGN:**

```css
/* Desktop */
@media (min-width: 768px) {
  .cta-button {
    padding: 12px 32px;
  }
}

/* Mobile */
@media (max-width: 767px) {
  .cta-button {
    padding: 16px 40px; /* Larger for touch */
    width: 100%; /* Full width = easier to tap */
  }
}
```

**DESIGN CHECKLIST:**

- [ ] All interactive elements ≥ 44x44px?
- [ ] Primary actions close to expected input location?
- [ ] Adequate spacing between clickable elements?
- [ ] Hover/active states provide clear feedback?
- [ ] Mobile: Important actions in thumb zone?"

📚 **FACILITATOR NOTES:**

**Tools za testiranje:**
- Chrome DevTools → Mobile emulator (test thumb reach)
- Figma → Interactive prototype (test clickability)

**Common mistakes:**
- Tiny social media icons (Instagram, Facebook) - often < 30px
- Links with inadequate padding - text is clickable, but space around is not
- Hamburger menu icon too small on mobile

---

## ⏰ **11:45-12:05 (20 min) - EYE-TRACKING & READING PATTERNS**

### **Slajd 103: What Eye-Tracking reveals**

**Notes iz PDF-a:**
_"Eye tracking is a technique to track and analyze where users look on digital interface and for how long. The Nielsen Norman group F-pattern heat maps from eye tracking studies."_

**Što reći studentima (8 min):**

"Sada: **EYE-TRACKING** - kako ljudi ZAPRAVO gledaju web stranice.

**ŠTO JE EYE-TRACKING?**
Tehnologija koja prati gdje korisnik gleda na ekranu i koliko dugo.

**ZAŠTO JE VAŽNO?**
Većina ljudi NE čita web stranice word-by-word. Oni **SCAN** (skeniraju) sadržaj.

**ŠTO POKAZUJU STUDIJE:**

**Nielsen Norman Group** je napravio ekstenzivna eye-tracking istraživanja:

**F-PATTERN:**
```
═══════════════
═══════════
║
║
║══════
║══════
║
║
```

Users čitaju u F-shaped pattern:
1. **Horizontal movement** - top of page (headline)
2. **Second horizontal** - subheadline ili prvi paragraf
3. **Vertical scan** - left side of content

**Što ovo znači za dizajn:**
- **TOP of page:** Most important info (headlines, value proposition)
- **LEFT side:** Scannable (bullet points, subheadings, images)
- **RIGHT side:** Less attention (use for less critical info)

**Z-PATTERN:**
```
═══════════════
    ╲
      ╲
        ╲
═══════════════
```

For pages with MINIMAL text:
- Landing pages
- Ads
- Sign-up pages

Users scan:
1. Top-left → Top-right (header/logo)
2. Diagonal down
3. Bottom-left → Bottom-right (CTA)

**IMPLIKACIJE ZA DIZAJN:**

**F-Pattern pages:**
- Long-form content (blogs, articles, documentation)
- Important info on left side
- Use headings i bullet points

**Z-Pattern pages:**
- Minimal content
- Visual hierarchy (large headlines)
- CTA at bottom-right (end of Z)

**PRAVILO: Design sukladno s natural eye movement. Don't fight it!**"

**Primjeri:**
Prikaži heat map slike - F-pattern vrlo jasan na text-heavy stranama.

📖 **Reference:**
- [F-Shaped Pattern - Nielsen Norman Group](https://www.nngroup.com/articles/f-shaped-pattern-reading-web-content/)
- [Z-Pattern Layout](https://www.interaction-design.org/literature/article/the-z-shaped-layout-how-to-engage-readers-in-a-flash)

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Eye-tracking studies su pokazali da users tipično čitaju samo **20-28%** teksta na web stranici. Rest je scanning.

**F-pattern nije bug, it's a feature:**
Users su naučili biti efikasni. Skeniraju brzo da pronađu relevant info. Design mora podržati ovo ponašanje.

**Česta pitanja:**
Q: "Što ako želim da users čitaju SVE?"
A: "Make it scannable - koristi headings, bullet points, bold keywords. Lakše će skenirati, ali dobit će key info."

Q: "Je li F-pattern uvijek?"
A: "Većinom. Iznimka: landing pages s minimal text (Z-pattern). Mobile također često drugačije (scroll, ne scan horizontalno)."

**Troubleshooting:**
- **Users ne vide važne info**: Možda nije on 'hot' zone-u (top/left). Premjesti ili make more prominent.

---

### **Slajd 104: F Pattern**

**Notes iz PDF-a:**
_"F Pattern describes the most common scanning patterns of user's eye when it comes to content blocks. F for fast. This is how users read your content."_

**Što reći studentima (7 min):**

"Detaljnije o **F-PATTERN:**

**F = FAST**
Korisnici se kreću incredible speed preko stranice.

**Proces:**
1. **First horizontal:** Čitaju top content (headline, prvi paragraf)
2. **Second horizontal:** Skeniraju niže (subheading, bullet points)
3. **Vertical scan:** Left side - gledaju za keywords, links, images

**Heat map:**
```
🔴🔴🔴🔴🔴🔴  ← Highest attention
🔴🔴🔴🔴
🔴
🔴
🔴🔴🔴🔴      ← Medium attention
🔴🔴🔴
🔴
🔴
```

**KAKO DIZAJNIRATI ZA F-PATTERN:**

**1. FRONT-LOAD IMPORTANT INFO**
Prvo 2 paragrafa = critical info
- Who, What, Why → top of page

**2. USE HEADINGS & SUBHEADINGS**
Break up text s descriptive headings
- Users scan headings da nađu relevant sekciju

**3. BULLET POINTS**
- Easier to scan than paragraphs
- Left-aligned

**4. BOLD KEYWORDS**
Highlight important words u paragrafima
- User scan, vide bold keywords, odluče čitati ili ne

**5. LEFT-ALIGN TEXT**
Ne centeriraj long-form text
- Centered text = teško skenirati

**6. IMAGES ON LEFT**
Ako imaš images u content, pozicioniraj lijevo
- Privlače pažnju tijekom vertical scan

**PRIMJER - Blog post struktura:**

```
[Large Headline]                    ← F1: Horizontal read
[Subheadline / Author / Date]

[First paragraph with bold keywords] ← F2: Horizontal scan

[Subheading 1]                      ← Vertical scan na left
• Bullet point
• Bullet point
• Bullet point

[Subheading 2]                      ← Vertical scan continues
[Paragraph with bold keywords]

[Image aligned left]                ← Catches eye during scan
[Caption]

[Subheading 3]
...
```

**PRAVILO: Optimize left side i top of page. That's where attention goes.**"

📚 **FACILITATOR NOTES:**

**Inverted pyramid writing:**
Journalism concept - most important info first, detail later. Perfect za F-pattern.

**Mobile consideration:**
F-pattern manje primjenjivo na mobile - users više scrollaju vertically. Ali principle je isti - important info first.

**Česta pitanja:**
Q: "Je li F-pattern loš?"
A: "Ne! To je realnost. Prihvati ga i dizajniraj sukladno. Don't expect users da čitaju svaku riječ - make key info easy to scan."

---

### **Slajd 105: F vs Z patterns**

**Notes iz PDF-a:**
_"Visual showing F-pattern for text-heavy content vs Z-pattern for minimal text pages."_

**Što reći studentima (5 min):**

"**Kada koristiti F vs Z?**

**F-PATTERN:**
- **Content-heavy pages**
- Blogs, articles, documentation
- Multiple sections, headings
- Users scan for specific info

**Z-PATTERN:**
- **Minimal content pages**
- Landing pages, hero sections
- Ads, signup pages
- Clear single CTA

**DESIGN ACCORDINGLY:**

**F-Pattern page:**
```
[Headline]          → Horizontal read
[Subheadline]

[Body text]         → Vertical scan on left
[Heading]
[Body text]
[Heading]
[Body text]
```

**Z-Pattern page:**
```
[Logo]  [Nav] [CTA] → Top horizontal
        
    [Large visual]
    [Headline]      → Diagonal movement
    
[Benefits]     [CTA Button] → Bottom horizontal
```

**COMBINATION:**
Many pages koriste HYBRID - Z na hero section, F u content section."

📚 **FACILITATOR NOTES:**

Real-world example:
- **Apple.com:** Z-pattern na homepage hero, F-pattern u product detail pages
- **Medium.com:** F-pattern u article pages

---

### **Slajd 106: Heatmap - Attention Insight**

**Notes iz PDF-a:**
_"Attention Insight is a predictive analytics tool that evaluates how users visually perceive design before it goes live using AI."_

**Što reći studentima (3 min):**

"Cool tool: **ATTENTION INSIGHT**

**ŠTO JE:**
AI-powered tool koji PREDVIĐA gdje će users gledati prije nego launcha design.

**KAKO RADI:**
1. Uploadaš screenshot dizajna
2. AI generira heat map (gdje će attention ići)
3. Vidiš: hotspots (high attention) vs cold zones (low attention)

**ZAŠTO KORISTITI:**
- Test designs before building
- Validate da li CTA prima attention
- Optimize layouts

**LINK:** attentioninsight.com

**Chrome extension dostupan** - možete testirat any website!"

📖 **Reference:**
- [Attention Insight](https://attentioninsight.com/)

📚 **FACILITATOR NOTES:**

Free trial available - studentice mogu testirat svoje dizajne. Korisno za projekte.

---

## ⏰ **12:05-12:25 (20 min) - USER INYERFACE GAME & WRAP-UP**

### **Slajd 107: EXERCISE - User Inyerface**

**Notes iz PDF-a:**
_"User Inyerface is a hardcore and funny game where you have to fight through incredibly dumb and complicated interface. You will forever remember these mistakes in design."_

**Što reći studentima (3 min):**

"Vrijeme za **FUN (ali frustrirajući) EXERCISE!**

**USER INYERFACE** - najgori UI dizajn ikad napravljen... *namjerno*.

**ŠTO JE:**
Interaktivni game gdje morate popuniti form s najgorim mogućim UI decisions:
- Buttoni koji ne izgledaju kao buttoni
- Nejasne labele
- Confusing layouts
- Pop-ups koji blokiraju
- Misleading icons
- itd.

**CILJ:**
Completati form. Ali ćete se FRUSTRIRATI!

**ZAŠTO OVO RADIMO:**
Da zapamtite sve BAD DESIGN PRACTICES koje smo govorile danas. Kada radite dizajn, sjetit ćete se: 'Oh no, ne želim biti kao User Inyerface!'

**LINK:** userinyerface.com

Ready? Let's play!"

✏️ **ZADATAK: User Inyerface Game**

**Upute:**
1. Otvori [userinyerface.com](https://userinyerface.com/)
2. Pokušaj completati form
3. Zapamti: Koji design decisions te najviše frustriraju?
4. Screenshot svaki frustrating moment (optional)
5. Nakon što završiš (ili predaš 😅), diskutirat ćemo

**Timing:** 15 min

📚 **FACILITATOR NOTES:**

**Kako voditi:**
- Neka svaka studentica igra solo na svom laptopu
- Cirkuliraj po razredu - slušaj frustracije
- After 10-15 min, gather insights

**Česti problemi:**
- **Studentice se stvarno frustriraju**: To je POINT! Ali podsjeti ih da je ovo intentionally bad.
- **Ne mogu završiti**: Totally OK! Većina ljudi ne završi. Poenta je experience, ne completion.

**Što nakon game:**
Pitaj studentice:
- "Što vas najviše isfrustriralo?"
- "Koje principe smo govorile danas su bili violated?"
- "Što ćete zapamtiti za vlastiti dizajn?"

**Expected odgovori:**
- "Buttoni nisu izgledali kao buttoni" (affordance)
- "Previše opcija" (Hick's Law)
- "Tiny clickable elements" (Fitts' Law)
- "Sve je iste boje" (Von Restorff violated)
- "Ne znam gdje gledati" (Visual hierarchy, Gestalt)

**Lesson:**
Sve što je loše u User Inyerface = INVERSE of good UX principles. Zapamtite ovo!

📖 **Reference:**
- [User Inyerface - Official Site](https://userinyerface.com/)

---

## ⏰ **12:25-12:30 (5 min) - RECAP & CLOSURE**

**Što reći studentima (5 min):**

"Bravo! Završile smo User Inyerface (ili ste barem probale 😅).

**RECAP DANA:**

Naučile ste **psychology principles** koji objašnjavaju ZAŠTO neki dizajni rade, a neki ne:

**UX LAWS:**
✅ **Hick's Law** - Limit choices za brže odluke
✅ **Fitts' Law** - Veliki i bliži targets = lakše klikanje
✅ **Von Restorff** - Make important elementi different (stand out)

**GESTALT PRINCIPLES:**
✅ **Proximity** - Blizu = connected
✅ **Similarity** - Slično izgleda = connected
✅ **Common Regions** - Zajednička granica = group
✅ **Symmetry** - Balance i harmony
✅ **Figure-Ground** - Separate foreground od background
✅ **Closure** - Mozak popunjava praznine
✅ **Continuity** - Oko prati paths
✅ **Common Fate** - Kreću se zajedno = group

**READING PATTERNS:**
✅ **F-Pattern** - Text-heavy content (top + left side)
✅ **Z-Pattern** - Minimal content (landing pages)

**KEY TAKEAWAY:**
Dobar UX dizajn radi **SA** načinom kako mozak prirodno funkcionira, ne protiv njega.

**SUTRA:**
Nastavljamo s **Usability Heuristics** - Bastien & Scapin 8 kriterija za evaluiranje interfacea. Praktična primjena svega što smo učile!

Odlično ste danas radile! Vidimo se sutra! 🎉"

📚 **FACILITATOR NOTES:**

**Homework (optional):**
"Za praksu - analizirajte vaš omiljeni website kroz današnje principe:
- Koji Gestalt principles koriste?
- Je li F ili Z pattern?
- Kako koriste Von Restorff za CTA?

Donjeti insights sutra!"

**Pripremna lista za sutra (Dan 4):**
- [ ] Pripremi primjere websitea za heuristic evaluation
- [ ] Print heuristic evaluation checkliste (optional)
- [ ] Review Bastien & Scapin criteria

---

## 🔄 **BACKUP AKTIVNOSTI**

### **BACKUP AKTIVNOST 1: Gestalt Scavenger Hunt (15 min)**

**Cilj:** Identificirati Gestalt principle u real-world dizajnima

**Kada koristiti:**
- Gestalt sekcija završi prerano
- Trebaju hands-on primjere

**Upute:**
1. Otvori bilo koji popularan website (Medium, Airbnb, Spotify...)
2. Screenshot 3 primjera Gestalt principa:
   - Primjer proximity
   - Primjer similarity
   - Primjer figure-ground (ili drugi)
3. Annotate svaki screenshot - objasni koji princip i zašto
4. Share u Figma board ili chat

**Timing:** 15 min

📚 **FACILITATOR NOTES:**

**Evaluacija:**
Neka studentice prezentiraju svoje findings - diskutirajte jesu li ispravno identificirale principe.

---

### **BACKUP AKTIVNOST 2: CTA Button Comparison (10 min)**

**Cilj:** Analizirati Von Restorff Effect na različitim websiteima

**Kada koristiti:**
- Von Restorff sekcija ide brzo

**Upute:**
1. Otvori 3 različita websitea (e.g., Shopify, Stripe, Mailchimp)
2. Za svaki, identificiraj primary CTA button
3. Analiziraj:
   - Koja boja?
   - Koliko se razlikuje od ostalih elemenata?
   - Je li effective (stands out)?
4. Rate svaki CTA 1-10 (how well does it stand out?)

**Timing:** 10 min

📚 **FACILITATOR NOTES:**

Diskutirajte - koji website ima best CTA design? Zašto?

---

### **BACKUP AKTIVNOST 3: Fitts' Law Mobile Test (15 min)**

**Cilj:** Testirati thumb reachability na mobile device

**Kada koristiti:**
- Fitts' Law sekcija završi prerano

**Materijali:**
Mobile phone ili Figma mobile prototype

**Upute:**
1. Otvori mobile app (Instagram, Twitter, bilo što)
2. Pokušaj dosegnuti sve buttone samo thumbom (ne repositioning hand)
3. Mark zones:
   - Zelena = lako dosegnuti
   - Žuta = medium
   - Crvena = teško/nemoguće
4. Screenshot i share

**Timing:** 15 min

📚 **FACILITATOR NOTES:**

**Evaluacija:**
Koja apps imaju best thumb-friendly design? Koja ne?

---

### **BACKUP AKTIVNOST 4: F-Pattern Analysis (10 min)**

**Cilj:** Identificirati F-pattern na real website

**Kada koristiti:**
- Eye-tracking sekcija ide brzo

**Upute:**
1. Otvori blog post ili article (Medium, NY Times...)
2. Blur your eyes ili koristi Attention Insight
3. Gdje ide attention?
   - Top?
   - Left side?
   - F-shape?
4. Je li content organized za F-pattern?
   - Headings on left?
   - Important info at top?

**Timing:** 10 min

📚 **FACILITATOR NOTES:**

Diskutirajte - kako bi redesignali ako F-pattern nije jasan?

---

### **BACKUP AKTIVNOST 5: Bad Design Critique (15 min)**

**Cilj:** Identificirati violations of psychology principles

**Kada koristiti:**
- Kraj dana, recap aktivnost

**Upute:**
1. Find poorly designed website (r/badUIbattles, Reddit)
2. Lista sve violations:
   - Hick's Law violated? (previše opcija)
   - Fitts' Law violated? (tiny buttons)
   - Von Restorff violated? (ništa ne stands out)
   - Gestalt violated? (loš grouping)
3. Proposaj fixes

**Timing:** 15 min

📚 **FACILITATOR NOTES:**

**Resursi:**
- r/badUIbattles subreddit
- r/crappydesign
- Kolekcija bad designs na Behance

---

### **BACKUP AKTIVNOST 6: Quick Hick's Law Test (5 min)**

**Cilj:** Osjetiti Hick's Law u akciji

**Kada koristiti:**
- Brzi filler

**Upute:**
1. TASK 1: Prikaži 5 opcija (A, B, C, D, E) - studentice biraju jednu
   - Timer: Koliko brzo odlučuju?
2. TASK 2: Prikaži 20 opcija - studentice biraju jednu
   - Timer: Koliko brzo sad?
3. Compare times

**Timing:** 5 min

📚 **FACILITATOR NOTES:**

Demonstracija u live da Hick's Law works - više opcija = duže odlučivanje.

---

### **BACKUP AKTIVNOST 7: Design Psychology Kahoot (10 min)**

**Cilj:** Review kroz fun quiz

**Kada koristiti:**
- Kraj dana, recap

**Materijali:**
Kahoot quiz sa pitanjima o psychology principles

**Primjeri pitanja:**
1. "Što kaže Hick's Law?" (multiple choice)
2. "Koji Gestalt princip: elementi blizu = connected?" (Proximity)
3. "Von Restorff Effect kaže..." (element koji je different = zapamćen)

**Timing:** 10 min

📚 **FACILITATOR NOTES:**

Kreiraj Kahoot quiz prije ili koristi postojeći online UX quiz.

---

## 📚 **DODATNI RESURSI ZA FACILITATORA**

**Prije predavanja, pregledaj:**
1. [Laws of UX](https://lawsofux.com/) - Interactive guide za sve UX laws
2. [Gestalt Principles - Smashing Magazine](https://www.smashingmagazine.com/2014/03/design-principles-visual-perception-and-the-principles-of-gestalt/)
3. [F-Pattern Study - Nielsen Norman](https://www.nngroup.com/articles/f-shaped-pattern-reading-web-content/)

**Za tvoje dalje učenje:**
- [Thinking, Fast and Slow - Book by Daniel Kahneman](https://www.amazon.com/Thinking-Fast-Slow-Daniel-Kahneman/dp/0374533555)
- [Don't Make Me Think - Book by Steve Krug](https://www.amazon.com/Dont-Make-Think-Revisited-Usability/dp/0321965515)
- [The Design of Everyday Things - Book by Don Norman](https://www.amazon.com/Design-Everyday-Things-Revised-Expanded/dp/0465050654)

**Tools:**
- [Attention Insight](https://attentioninsight.com/) - AI heatmaps
- [User Inyerface](https://userinyerface.com/) - Bad UX game
- [Can't Unsee](https://cantunsee.space/) - Design detail game

**Pripremna lista:**
- [ ] Test User Inyerface game (poznaj kako funkcionira)
- [ ] Bookmarkaj primjere dobrih/loših designa
- [ ] Pripremi screenshots za demonstracije
- [ ] Provjeri da svi linkovi rade
- [ ] Download backup resources (ako WiFi ne radi)

---

**KRAJ SINOPSISA - DAN 3** ✅