# 📘 DAN 14 - METRIKE I GA4 - NAPREDNE FUNKCIJE I PRAKSA

## **PREDAVANJE: Goals, Events, HEART Framework & GA4 Vježbe**
**TRAJANJE:** 9:00-12:30 (3.5 sata, s pauzama)  
**PDF MATERIJAL:** 9-metrics.pdf (slajdovi 26-53)  
**BROJ STUDENTICA:** 8-30  
**PRETHODNI DAN:** Dan 13 - Uvod u metrike i Google Analytics

---

## 🎯 **CILJEVI UČENJA:**

Na kraju ovog predavanja, studentice će moći:

1. **Razlikovati** mikro-konverzije od makro-konverzije
2. **Identificirati** ključne e-commerce evente u GA4
3. **Koristiti** Campaign URL Builder za kreiranje UTM linkova
4. **Objasniti** HEART Framework i njegovih 5 dimenzija
5. **Analizirati** podatke u GA4 koristeći različite filtere i dimenzije
6. **Kreirati** custom audience u GA4
7. **Izgraditi** purchase funnel u GA4 Explore
8. **Interpretirati** metrike za donošenje poslovnih odluka

---

## ⏰ **RASPORED PREDAVANJA:**

```
9:00-10:00   SEKCIJA 1: Goals & Events u GA4
             - Slajdovi 26-31: Konverzije, e-commerce eventi, custom eventi
             
10:00-10:15  ☕ PAUZA

10:15-11:00  SEKCIJA 2: Traffic Sources & HEART Framework
             - Slajdovi 32-36: Kampanje, UTM, HEART metodologija
             
11:00-11:15  ☕ PAUZA

11:15-12:15  SEKCIJA 3: GA4 Praktične vježbe
             - Slajdovi 37-51: Extensive hands-on vježbe u GA4
             
12:15-12:30  SEKCIJA 4: Summary & Diskusija
             - Slajdovi 52-53: Recap, open discussion
```

**Ukupno efektivno vrijeme:** 180 min (3h)

---

## 📊 **PREGLED SLAJDOVA PO PRIORITETU:**

**PRIORITET 1 - MUST COVER (150 min):**
- Slajdovi 26-28: Goals i konverzije ✅
- Slajdovi 32-33: Traffic sources i UTM ✅
- Slajdovi 35-36: HEART Framework ✅
- Slajdovi 37-41: Core GA4 vježbe ✅

**PRIORITET 2 - NICE TO HAVE (30 min, ako ima vremena):**
- Slajdovi 29-31: Game eventi, custom eventi
- Slajdovi 42-50: Dodatne vježbe (odaberi 2-3)

**PRIORITET 3 - SELF-STUDY/HANDOUT:**
- Slajd 34: Time commitment detalji
- Slajdovi 51-53: Završne vježbe i resursi

---

# ⏰ **9:00-10:00 - SEKCIJA 1: GOALS & EVENTS**

## **Uvodni dio (5 min)**

**Što reći studentima:**

"Dobro jutro! Jučer smo naučili osnove Google Analytics-a - što su metrike, kako radi tracking, GDPR...

Danas idemo dublje:
- **Ciljevi i konverzije** - Kako pratimo uspjeh
- **Eventi** - Akcije koje korisnici poduzimaju
- **HEART Framework** - Metodologija za mjerenje UX-a
- I naravno - **puno praktičnog rada** u GA4!

Spremni? Krenimo!"

---

### **Slajd 26: Setting Goals - Konverzije**

**Notes iz PDF-a:**
_"100% of events can become conversions. MIC = Micro-conversions are all actions by your users that lead to a macro-conversion. MAC = Macro conversions are all actions taken by your users that earn you a profit."_

**Što reći studentima (12 min):**

"**Ciljevi (Goals)** u analytics-u su akcije koje želimo da korisnici naprave.

U GA4, svaki **event** (događaj) može postati **conversion** (konverzija).

**Dvije vrste konverzija:**

**1. MAKRO-KONVERZIJE (MAC)**
Glavne akcije koje donose profit:
- Kupnja proizvoda 💰
- Slanje upita za ponudu
- Registracija za plaćeni plan
- Booking rezervacija

**2. MIKRO-KONVERZIJE (MIC)**
Manje akcije koje vode do makro-konverzije:
- Dodavanje u košaricu 🛒
- Prijava na newsletter
- Preuzimanje kataloga
- Gledanje video prezentacije
- Klik na 'Kontakt' stranicu

**Zašto pratimo mikro-konverzije?**

Zamislite funnel (lijevak):
```
        Posjet stranici (1000)
              ↓
       Pregled proizvoda (500)
              ↓
      Dodavanje u košaricu (100)
              ↓
         Checkout (50)
              ↓
         Kupnja (25)
```

Ako pratimo samo kupnje, vidimo da imamo 25 kupnji. Ali NE znamo GDJE gubimo korisnike!

S mikro-konverzijama vidimo:
- 500/1000 pregledava proizvode (OK)
- Samo 100/500 dodaje u košaricu (PROBLEM! 80% odustaje)
- 25/50 završi kupnju (Checkout je solidan)

Sada znamo: **Problem je između pregleda i košarice!**"

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
- **Conversion rate** = broj konverzija / broj posjetitelja × 100
- Prosječan e-commerce conversion rate je 1-3%
- Ako imate 2%, to znači da od 100 posjetitelja, 2 kupe

**Česta pitanja:**
Q: "Koje mikro-konverzije su najvažnije?"
A: "Ovisi o poslovnom modelu. Za e-commerce: add to cart, begin checkout. Za SaaS: signup, activate trial. Za blog: newsletter signup, time on page."

---

### **Slajd 27-28: Events u GA4 - E-commerce**

**Notes iz PDF-a:**
_"List of e-commerce-specific events in Google Analytics: generate_lead, view_item_list, view_item, view_promotion, select_item, add_to_wishlist, add_to_cart, view_cart, remove_from_cart, begin_checkout, add_payment_info, add_shipping_info, purchase, refund..."_

**Što reći studentima (15 min):**

"GA4 ima **unaprijed definirane evente** za e-commerce. Ne morate ih sami izmišljati!

**E-commerce Event Flow:**

```
view_item_list    →  Korisnik gleda kategoriju proizvoda
       ↓
   view_item      →  Korisnik otvara proizvod
       ↓
  add_to_cart     →  Dodaje u košaricu
       ↓
   view_cart      →  Pregledava košaricu
       ↓
 begin_checkout   →  Počinje checkout
       ↓
add_payment_info  →  Unosi podatke o plaćanju
       ↓
add_shipping_info →  Unosi adresu dostave
       ↓
   purchase       →  Završava kupnju! 🎉
```

**Zašto su ovi eventi važni?**

1. **Standardizirani su** - GA4 ih automatski prepoznaje
2. **Povezani s izvještajima** - E-commerce reporti koriste ove evente
3. **Omogućuju analizu funnela** - Vidite gdje korisnici odustaju

**Dodatni korisni eventi:**

| Event | Kada se trigira |
|-------|-----------------|
| `generate_lead` | Korisnik pošalje upit |
| `add_to_wishlist` | Dodavanje na listu želja |
| `view_promotion` | Korisnik vidi promociju |
| `select_promotion` | Klikne na promociju |
| `refund` | Povrat novca |

**Napomena za developere:**
Ovi eventi se ne prate automatski! Developer mora implementirati tracking za svaki event. Ako GA4 ne pokazuje 'purchase' evente, vjerojatno nisu implementirani."

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Kao UX dizajner, nećeš implementirati evente, ali moraš razumjeti:
1. Koji eventi postoje
2. Što nam govore o user journey-u
3. Kako ih koristiti za poboljšanje dizajna

**Česta pitanja:**
Q: "Tko implementira ove evente?"
A: "Frontend developer u suradnji s analytics specijalistom. Ti kao dizajner možeš napraviti 'event tracking plan' - dokument koji kaže koje evente treba pratiti."

---

### **Slajd 29-30: Events za Igre (KRATKI PREGLED)**

**Notes iz PDF-a:**
_"List of game-specific events: earn_virtual_currency, join_group, level_end, level_start, level_up, post_score, spend_virtual_currency, tutorial_begin, tutorial_complete, unlock_achievement..."_

**Što reći studentima (5 min):**

"GA4 ima i evente specifične za **igre i aplikacije**:

**Gaming eventi:**
- `level_up` - Korisnik napreduje na sljedeći level
- `tutorial_complete` - Završio tutorial
- `unlock_achievement` - Otključao achievement
- `spend_virtual_currency` - Potrošio virtualnu valutu

**Zašto ovo spominjemo?**
Čak i ako ne radite igre, ovi koncepti se mogu primijeniti:
- `tutorial_complete` → Korisnik završio onboarding
- `unlock_achievement` → Korisnik postigao milestone

**Primjer:**
Duolingo (aplikacija za učenje jezika) koristi gaming evente iako nije igra:
- Level up = završio lekciju
- Achievement = 7 dana zaredom vježbanja
- Virtual currency = XP bodovi"

---

### **Slajd 31: Custom Events & Parameters**

**Notes iz PDF-a:**
_"500 custom events. 25 parameters per event. 25 User Properties per property. DIMENSIONS are the visitor (or his visit). METRICS account for the visitor's actions. 50 customized event dimensions. 50 custom metrics per property. 25 customized, user-oriented dimensions."_

**Što reći studentima (8 min):**

"Osim standardnih, možete kreirati **custom evente**!

**Limiti u GA4:**
- Do **500** custom evenata
- Do **25** parametara po eventu
- Do **25** user properties

**Razlika između DIMENSIONS i METRICS:**

| DIMENSIONS | METRICS |
|------------|---------|
| Opisuju KOGA | Mjere ŠTO |
| Kategorije | Brojevi |
| Browser, Land, Device | Sesije, Konverzije, Revenue |

**Primjer:**
- Dimension: `country = Croatia` (tko)
- Metric: `sessions = 5000` (koliko)

**Kada koristiti custom evente?**
Kada standardni eventi ne pokrivaju vašu potrebu:
- `video_50_percent` - Korisnik pogledao 50% videa
- `scroll_depth_75` - Scrollao 75% stranice
- `pricing_page_view` - Posjetio stranicu s cijenama

⚠️ **Upozorenje:** Ne pretjerujte s custom eventima! Više evenata = kompleksnije analize."

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Dimensions i Metrics su temeljni koncepti:
- **Dimensions** = kvalitativni podaci (tekstualne kategorije)
- **Metrics** = kvantitativni podaci (brojevi)

Svaki GA4 report koristi kombinaciju dimensions i metrics.

---

# ☕ **10:00-10:15 - PAUZA**

---

# ⏰ **10:15-11:00 - SEKCIJA 2: TRAFFIC SOURCES & HEART**

### **Slajd 32: Traffic Sources**

**Notes iz PDF-a:**
_"Direct traffic is by default - you can't do anything with it. UTM parameters can override traffic source for campaign tracking. Attribution models (last-click, first-click, data-driven) affect reporting."_

**Što reći studentima (10 min):**

"Odakle dolaze vaši posjetitelji? **Traffic sources** nam to govore!

**Glavne kategorije izvora prometa:**

1. **Organic Search** 🔍
   - Korisnici koji su vas našli preko Google/Bing pretrage
   - Besplatan promet, ali zahtijeva SEO

2. **Paid Search** 💰
   - Google Ads, Bing Ads
   - Plaćate po kliku (PPC)

3. **Social** 📱
   - Facebook, Instagram, LinkedIn, TikTok
   - Može biti organic ili paid

4. **Referral** 🔗
   - Linkovi s drugih stranica
   - Blog mentions, partner linkovi

5. **Email** ✉️
   - Newsletter kampanje
   - Transakcijski emailovi

6. **Direct** 🎯
   - Korisnik upisao URL direktno
   - ALI: Često je 'catch-all' kategorija!

**Problem s Direct trafficom:**
'Direct' znači da GA4 ne zna odakle je korisnik došao. To može biti:
- Stvarno direktan posjet
- Bookmark
- Link iz aplikacije (WhatsApp, Slack)
- Dark social
- Greška u trackingu

**Rješenje:** Koristite **UTM parametre** za sve što kontrolirate!"

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
'Direct' promet je često mystery bag. Ako imate puno direct prometa (>30%), vjerojatno nešto nije dobro tagirano.

---

### **Slajd 33: Campaign URL Builder**

**Notes iz PDF-a:**
_"When you want to force a source on a url (a click) you can use the URL constructor. It automatically adds UTM parameters to the final url."_

**Što reći studentima (10 min):**

"**Campaign URL Builder** je Google-ov alat za kreiranje UTM linkova.

**Zašto ga koristiti?**
Bez UTM-a, ako podijelite link na Instagram Storiju, GA4 će to prikazati kao 'Direct' (jer Instagram ne šalje referrer).

S UTM-om, možete točno pratiti odakle dolazi promet.

**Kako koristiti:**

1. Idite na: https://ga-dev-tools.google/campaign-url-builder/

2. Unesite:
   - **Website URL:** https://vaša-stranica.hr/proizvod
   - **Campaign Source:** instagram
   - **Campaign Medium:** social_story
   - **Campaign Name:** summer_2024

3. Alat generira:
```
https://vaša-stranica.hr/proizvod?
utm_source=instagram
&utm_medium=social_story
&utm_campaign=summer_2024
```

4. Koristite OVAJ link umjesto običnog!

**Best practices:**
- Budite konzistentni s imenovanjem (lowercase, underscore)
- Dokumentirajte sve kampanje u spreadsheet
- Ne koristite UTM za interne linkove (samo vanjske kampanje)"

---

✏️ **MINI ZADATAK: UTM Builder (5 min)**

**Cilj:** Kreirati UTM link za imaginarnu kampanju

**Zadatak:**
1. Idite na: https://ga-dev-tools.google/campaign-url-builder/
2. Kreirajte link za:
   - Newsletter kampanja za Valentine's Day
   - Stranica: https://shop.hr/valentines-gift
3. Odaberite logične source, medium, campaign
4. Generirajte i podijelite rezultat

📚 **FACILITATOR NOTES:**
Očekivani odgovor:
- source: newsletter ili email
- medium: email
- campaign: valentines_2024 ili slično

---

### **Slajd 34: Time Commitment (KRATKI PREGLED)**

**Notes iz PDF-a:**
_"When a user starts a new session, Google Analytics begins recording the duration of the session. Duration is sent when user moves application screen in background, exits the application screen, or the site freezes."_

**Što reći studentima (3 min):**

"Brzi pregled kako GA4 mjeri **vrijeme na stranici**:

GA4 počinje mjeriti kada korisnik dođe na stranicu. Vrijeme se šalje kada:
- Korisnik ode na drugu stranicu
- Minimizira browser
- Zatvori tab

**Zašto je ovo važno?**
Ako korisnik čita članak 10 minuta, ali zatim samo zatvori tab, GA4 možda neće registrirati tih 10 minuta!

To je jedan od razloga zašto podaci nisu 100% točni."

---

### **Slajd 35-36: HEART Framework**

**Notes iz PDF-a:**
_"The HEART Framework is a UX measurement methodology developed by Google's UX research team. It helps businesses assess and improve their digital products based on key user experience metrics. HEART: Happiness, Engagement, Adoption, Retention, Task Success."_

**Što reći studentima (15 min):**

"**HEART Framework** je metodologija za mjerenje UX-a koju je razvio Google-ov UX tim.

Umjesto da gledate samo 'page views', HEART vam daje holistički pogled na korisničko iskustvo.

**HEART = 5 dimenzija:**

**H - HAPPINESS (Sreća)** 😊
*Koliko su korisnici zadovoljni?*
- NPS (Net Promoter Score)
- CSAT (Customer Satisfaction)
- App Store rating
- Survey rezultati

*Primjer metrike:* 'Koliko je vjerojatno da biste preporučili našu aplikaciju prijatelju? (1-10)'

**E - ENGAGEMENT (Angažman)** 📊
*Koliko aktivno koriste proizvod?*
- Session duration
- Pages per session
- Feature usage
- Return visits

*Primjer metrike:* 'Prosječno vrijeme po sesiji = 8 minuta'

**A - ADOPTION (Usvajanje)** 🆕
*Koliko novih korisnika dolazi?*
- New signups
- First-time purchases
- Feature adoption rate
- Onboarding completion

*Primjer metrike:* 'Ovaj tjedan imamo 500 novih registracija'

**R - RETENTION (Zadržavanje)** 🔄
*Koliko korisnika se vraća?*
- Return rate
- Churn rate
- Subscription renewals
- DAU/MAU ratio

*Primjer metrike:* '30-day retention = 45%'

**T - TASK SUCCESS (Uspješnost zadatka)** ✅
*Koliko učinkovito korisnici postižu cilj?*
- Task completion rate
- Time on task
- Error rate
- Conversion rate

*Primjer metrike:* '78% korisnika uspješno završi checkout'

---

**Kako implementirati HEART:**

| Dimenzija | Goals | Signals | Metrics |
|-----------|-------|---------|---------|
| Happiness | Korisnici vole app | Pozitivni reviews | NPS > 50 |
| Engagement | Aktivno korištenje | Česte sesije | 3+ sesije/tjedan |
| Adoption | Rast korisnika | Novi signups | +10% mjesečno |
| Retention | Korisnici se vraćaju | Return visits | 40% retention |
| Task Success | Lako korištenje | Brzi checkout | <3 min checkout |

---

**Zašto HEART?**

1. **Strukturiran pristup** - Nije random odabir metrika
2. **Balansiran pogled** - Ne fokusirate se samo na jednu stvar
3. **UX fokusiran** - Dizajniran za UX timove
4. **Google koristi** - Provjereno u praksi"

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
HEART je framework, ne alat. Vi odlučujete koje konkretne metrike ćete pratiti u svakoj kategoriji.

**Česta pitanja:**
Q: "Moramo li pratiti sve 5 dimenzija?"
A: "Ne nužno. Odaberite 2-3 koje su najrelevantnije za vaš proizvod. Startup možda fokusira na Adoption i Retention, dok etablirana tvrtka možda na Happiness i Task Success."

📖 **Reference:**
- HEART Framework: https://www.heartframework.com/

---

# ☕ **11:00-11:15 - PAUZA**

---

# ⏰ **11:15-12:15 - SEKCIJA 3: GA4 PRAKTIČNE VJEŽBE**

### **Slajd 37: GA4 Demo - Uvod u vježbe**

**Notes iz PDF-a:**
_"Access to Google GA4 demo account. We're revisiting the exercise in Google's demo account on Google's shopping site."_

**Što reći studentima (3 min):**

"Sada prelazimo na **intenzivan praktičan rad** u GA4!

Pristupite demo accountu ako još niste:
https://support.google.com/analytics/answer/10993011

Radimo seriju vježbi koje pokrivaju ključne GA4 funkcionalnosti. Svaka vježba ima specifičan cilj i pitanje na koje trebate odgovoriti.

Radite u parovima. Pitajte ako zapnete!"

---

### **Slajd 38: Product Performance Analysis**

**Notes iz PDF-a:**
_"In the Google DEMO account (GA4), Product performance analysis with Explore (by September 2024). Which product category generated the most revenue on the demo site? Which product has the highest conversion rate? Identify the pages with the highest engagement rates. Which traffic channels generate the most new users?"_

---

✏️ **ZADATAK 1: Product Performance Analysis (15 min)**

**Cilj:** Analizirati performanse proizvoda i stranica

**Period:** Rujan 2024

**Pitanja:**
1. Koja kategorija proizvoda generira najviše prihoda?
2. Koji proizvod ima najvišu conversion rate?
3. Koje stranice imaju najviši engagement rate?
4. Koji traffic kanali donose najviše novih korisnika?

**Gdje tražiti:**

| Pitanje | Location u GA4 |
|---------|----------------|
| 1. Revenue by category | Monetization → Ecommerce purchases → Filter by Item category |
| 2. Conversion rate | Monetization → Ecommerce purchases → Sort by "Purchase-to-view rate" |
| 3. Engagement rate | Engagement → Pages and screens → Sort by "Engagement rate" |
| 4. New users by channel | Acquisition → Traffic acquisition → "New users" column |

📚 **FACILITATOR NOTES:**

**Hints:**
1. Za kategorije, možda trebate dodati "Item category" dimension
2. Conversion rate = purchases / views
3. Engagement rate je postotak engaged sessions
4. "New users" kolona je različita od "Users"

**Tipični odgovori:**
- Kategorija: Apparel obično vodi
- Engagement: Homepage i product pages
- Traffic: Organic Search obično dominira

---

### **Slajd 39: Audience Creation**

**Notes iz PDF-a:**
_"Create an audience of users who have added a product to the shopping cart, but haven't finalized their purchase. Create an audience of users who have visited a product page without adding it to the shopping cart."_

---

✏️ **ZADATAK 2: Kreiranje Custom Audience (15 min)**

**Cilj:** Naučiti kreirati segmente korisnika za remarketing

**Zadatak:**
Kreirajte dvije audience grupe:

**Audience 1: Cart Abandoners**
- Dodali proizvod u košaricu ✅
- NISU kupili ❌

**Audience 2: Browsers Without Action**
- Posjetili product page ✅
- NISU dodali u košaricu ❌

**Koraci:**

1. Idite na **Admin** → **Audiences** → **New audience**
2. Kliknite **Create a custom audience**
3. Definirajte uvjete:
   - Include: `event = add_to_cart`
   - Exclude: `event = purchase`
4. Imenujte audience (npr. "Cart Abandoners Sept 2024")
5. Spremite

📚 **FACILITATOR NOTES:**

**Zašto su ove audience važne?**
- **Cart abandoners** = Remarketing cilj! Ovi korisnici su već pokazali interes
- **Browsers** = Mogu trebati više informacija o proizvodu

**Korak po korak za Cart Abandoners:**
1. Admin (gear icon) → Data display → Audiences
2. New audience → Create a custom audience
3. Add new condition → Event → add_to_cart
4. Add group to exclude → Event → purchase
5. Name: "Cart Abandoners"
6. Save

---

### **Slajd 40: Creating Funnels in Explore**

**Notes iz PDF-a:**
_"Creation of a purchase funnel (from session start to purchase). How can this funnel be compared to check whether mobiles are as efficient as desktops?"_

---

✏️ **ZADATAK 3: Purchase Funnel Analysis (15 min)**

**Cilj:** Vizualizirati user journey kroz funnel

**Zadatak:**
1. Kreirajte purchase funnel u Explore
2. Usporedite desktop vs mobile performanse

**Koraci:**

1. Idite na **Explore** (lijevi menu)
2. Kliknite **Funnel exploration** template
3. Postavite korake funnela:
   - Step 1: `session_start`
   - Step 2: `view_item`
   - Step 3: `add_to_cart`
   - Step 4: `begin_checkout`
   - Step 5: `purchase`
4. Pogledajte drop-off rates između koraka
5. Dodajte **Breakdown** → Device category
6. Usporedite desktop vs mobile

**Pitanja za analizu:**
- Gdje je najveći drop-off?
- Jesu li mobilni korisnici manje efikasni?
- Koji korak ima najveću razliku desktop vs mobile?

📚 **FACILITATOR NOTES:**

**Što očekivati:**
- Najveći drop-off obično: view_item → add_to_cart
- Mobile često ima veći drop-off na checkoutu (manji ekran, teže unositi podatke)

**Ako studentice zapnu:**
Explore može biti zbunjujući. Pokažite na svom ekranu!

---

### **Slajd 41: Open Discussion**

**Notes iz PDF-a:**
_"A customer wants to know why sales have fallen over the last 30 days. What do you check? Conversion tracking is not working properly, how can I identify the problem? You need to improve the engagement rate on a key page. What do you measure and how?"_

---

✏️ **DISKUSIJA: Poslovni scenariji (10 min)**

**Cilj:** Primijeniti znanje na realne probleme

**Scenarij 1:**
*"Klijent pita zašto su prodaje pale u zadnjih 30 dana. Što provjeravate?"*

**Što diskutirati:**
- Usporedi s prethodnim periodom (YoY, MoM)
- Provjeri traffic - je li pao?
- Provjeri conversion rate - je li pao?
- Provjeri po kanalima - koji je izvor problema?
- Provjeri mobile vs desktop
- Ima li tehničkih problema? (greške na checkoutu)

**Scenarij 2:**
*"Conversion tracking ne radi. Kako identificirati problem?"*

**Što diskutirati:**
- Provjeri DebugView u GA4
- Koristi browser developer tools
- Provjeri je li script instaliran
- Provjeri consent - jesu li cookies blokirani?
- Testiraj s GA Debugger ekstenzijom

**Scenarij 3:**
*"Trebate poboljšati engagement rate na ključnoj stranici. Što mjerite?"*

**Što diskutirati:**
- Trenutni engagement rate
- Time on page
- Scroll depth
- Click events (CTA-ovi)
- Exit rate

📚 **FACILITATOR NOTES:**
Ovo je otvorena diskusija. Nema "točnih" odgovora - cilj je razviti analitičko razmišljanje.

---

### **Slajdovi 42-50: Dodatne GA4 vježbe (ODABERI 2-3)**

**Napomena za facilitatora:**
Slajdovi 42-50 sadrže dodatne vježbe. Ovisno o vremenu, odaberite 2-3 koje ćete raditi. Ostale mogu biti homework.

---

✏️ **VJEŽBA 4: New User Analysis (10 min)**
*(Slajd 42)*

**Period:** 1.-31. listopada 2024

**Pitanje:** Koliko novih korisnika je posjetilo stranicu?

**Lokacija:** Reports → Acquisition → User acquisition

---

✏️ **VJEŽBA 5: Best Traffic Source (10 min)**
*(Slajd 43)*

**Period:** 1.-15. studenog 2024

**Pitanje:** Koji izvor prometa je generirao najviše sesija?

**Lokacija:** Reports → Acquisition → Traffic acquisition

---

✏️ **VJEŽBA 6: Add to Cart Events (10 min)**
*(Slajd 44)*

**Period:** 1.-30. listopada 2024

**Pitanje:** Koliko puta je triggiran `add_to_cart` event?

**Lokacija:** Reports → Engagement → Events → Filter: add_to_cart

---

✏️ **VJEŽBA 7: Geographic Performance (10 min)**
*(Slajd 45)*

**Period:** 1. listopada - 15. studenog 2024

**Pitanje:** Koja regija SAD-a je generirala najviše prihoda?

**Lokacija:** Reports → User → Demographics → Geo → Add filter: Country = United States

---

✏️ **VJEŽBA 8: Secondary Dimension (10 min)**
*(Slajd 46)*

**Period:** 1.-30. rujna 2024

**Pitanje:** Za `add_to_cart` evente, koji izvor prometa je generirao najviše dodavanja?

**Lokacija:** 
1. Reports → Engagement → Events → add_to_cart
2. Dodaj secondary dimension: Session source

---

✏️ **VJEŽBA 9: Mobile Performance (10 min)**
*(Slajd 47)*

**Period:** 1.-31. kolovoza 2024

**Pitanje:** Koja stranica ima najviši CTR za mobilne korisnike?

**Lokacija:**
1. Reports → Engagement → Pages
2. Filter: Device category = mobile
3. Sort by relevant metric

---

✏️ **VJEŽBA 10: Paid Traffic Analysis (10 min)**
*(Slajd 48)*

**Period:** 1. listopada - 15. studenog 2024

**Pitanje:** Za korisnike iz paid search-a, koliko stranica u prosjeku pregledaju?

**Lokacija:**
1. Reports → Acquisition → Traffic acquisition
2. Nađi Paid Search red
3. Pogledaj "Pages / session" ili "Views per session"

---

✏️ **VJEŽBA 11: Session Duration by Country (10 min)**
*(Slajd 49)*

**Period:** 1.-31. kolovoza 2024

**Pitanje:** Koji izvor prometa ima najduže prosječno trajanje sesije za francuske posjetitelje?

**Lokacija:**
1. Reports → Acquisition → Traffic acquisition
2. Add filter: Country = France
3. Sort by "Average session duration"

---

✏️ **VJEŽBA 12: Conversions by Device (10 min)**
*(Slajd 50)*

**Period:** 1. rujna - 31. listopada 2024

**Pitanje:** Koja zemlja ima najviše konverzija s tableta?

**Lokacija:**
1. Reports → Acquisition ili custom explore
2. Dimensions: Country, Device category
3. Filter: Device = tablet
4. Sort by Conversions

---

# ⏰ **12:15-12:30 - RECAP & DISKUSIJA**

### **Slajd 52: Summary**

**Notes iz PDF-a:**
_"In this lesson, we explored how to quantify and evaluate user experience using data. You learned the difference between metrics, analytics, and tracking techniques. The goal is to move beyond assumptions – by collecting real user data, you can make informed design decisions. Key takeaway? What gets measured, gets improved."_

**Što reći studentima (10 min):**

"Vrijeme za **recap** svega što smo naučili u ova dva dana!

**Ključne poruke:**

1. **'What gets measured, gets improved'**
   - Bez podataka, samo nagađamo
   - S podacima, donosimo informirane odluke

2. **Metrike vs Analytics vs Tracking:**
   - **Metrike** = brojevi koje pratimo (sessions, conversions)
   - **Analytics** = alati za prikupljanje i analizu (GA4)
   - **Tracking** = tehnike za prikupljanje (cookies, events, pixels)

3. **GA4 ključne funkcionalnosti:**
   - Events i Conversions
   - Traffic sources
   - Audiences
   - Funnels
   - Explore za custom analize

4. **HEART Framework:**
   - Happiness, Engagement, Adoption, Retention, Task Success
   - Strukturiran pristup UX metrikama

5. **GDPR:**
   - Privatnost korisnika je prioritet
   - Consent je obavezan
   - Podaci nikad nisu 100% kompletni

**Vaš sljedeći korak:**
Otvorite GA za bilo koju stranicu na kojoj radite (ili vaš projekt) i primijenite ovo znanje!

**Pitanja?"

---

### **Slajd 53: Resursi**

**Što reći studentima (5 min):**

"Evo korisnih resursa za nastavak učenja:

📖 **Linkovi:**
- GA4 Measurement Protocol Cheatsheet: https://www.thyngster.com/ga4-measurement-protocol-cheatsheet/
- GDPR Info (BE): https://www.autoriteprotectiondonnees.be/citoyen/themes/internet/cookies
- GA4 Limits: https://support.google.com/analytics/table/13948007
- Campaign URL Builder: https://ga-dev-tools.google/campaign-url-builder/
- HEART Framework: https://www.heartframework.com/

📺 **Učenje:**
- Google Analytics Academy (besplatno): https://analytics.google.com/analytics/academy/

Ove resurse ćete dobiti i kao PDF."

---

## ❓ **PITANJA ZA PROVJERU RAZUMIJEVANJA**

**Osnovni level:**
1. Koja je razlika između mikro i makro konverzije?
2. Nabroji 3 e-commerce eventa u GA4.
3. Što znači HEART?

**Srednji level:**
4. Zašto bi kreirali "Cart Abandoners" audience?
5. Kako UTM parametri pomažu u trackingu?
6. Koja je razlika između Dimensions i Metrics?

**Viši level:**
7. Kako bi dizajnirao/la HEART metrički plan za novu mobile app?
8. Klijent ima visok bounce rate na checkoutu. Koje metrike bi analizirao/la i zašto?

---

## 🔄 **BACKUP AKTIVNOSTI**

### **BACKUP AKTIVNOST 1: HEART Framework za Vašu App (15 min)**

**Cilj:** Primijeniti HEART na konkretni primjer

**Upute:**
1. Odaberite poznatu aplikaciju (Spotify, Instagram, Uber...)
2. Za svaku HEART dimenziju:
   - Definirajte jedan cilj
   - Predložite signal
   - Predložite metriku

**Primjer za Spotify:**
| H | Goal: Korisnici uživaju u glazbi | Signal: Playliste kreirane | Metric: NPS |
| E | Goal: Aktivno slušanje | Signal: Daily listening | Metric: Minutes/day |
...itd.

📚 **FACILITATOR NOTES:**
Ova aktivnost povezuje teoriju s praksom. Može se raditi u grupama.

---

### **BACKUP AKTIVNOST 2: UTM Naming Convention (10 min)**

**Cilj:** Kreirati konzistentan sustav imenovanja UTM parametara

**Upute:**
Kreirajte "UTM Style Guide" za imaginarnu tvrtku:
1. Kako ćete pisati source? (lowercase, camelCase, itd.)
2. Koje medium kategorije ćete koristiti?
3. Kako ćete strukturirati campaign imena?
4. Napravite 5 primjera

**Primjer:**
```
Convention:
- source: lowercase, no spaces (facebook, google, newsletter)
- medium: underscore (paid_social, organic_search, email)
- campaign: YYYYMM_name (202402_valentines)

Examples:
?utm_source=facebook&utm_medium=paid_social&utm_campaign=202402_valentines
```

📚 **FACILITATOR NOTES:**
Konzistentno imenovanje je ključno za čiste podatke. Ako svaki put drugačije napišete "Facebook" (Facebook, facebook, FB, fb), imat ćete kaos u reportima.

---

### **BACKUP AKTIVNOST 3: Conversion Rate Calculation (10 min)**

**Cilj:** Vježbati izračun conversion rate-a

**Zadaci:**

1. Stranica ima 10.000 posjetitelja i 150 kupnji.
   - CR = ?
   - *Odgovor: 1.5%*

2. Landing page ima 5.000 views i 250 form submissions.
   - CR = ?
   - *Odgovor: 5%*

3. Povećali ste CR s 2% na 2.5%. Koliko je to % povećanje?
   - *Odgovor: 25% relativno povećanje*

4. Imate 50.000€ revenue s CR od 2%. Ako povećate CR na 3%, koliki je očekivani revenue?
   - *Odgovor: 75.000€*

📚 **FACILITATOR NOTES:**
Conversion rate formula: `CR = (Conversions / Total visitors) × 100`

---

### **BACKUP AKTIVNOST 4: Event Mapping Exercise (15 min)**

**Cilj:** Definirati koje evente bi trebalo pratiti za danu stranicu

**Scenarij:**
Radite za booking.com konkurenta. Definirajte event tracking plan.

**Zadatak:**
Popunite tablicu:

| User Action | Event Name | Category | Parameters |
|-------------|------------|----------|------------|
| Pretraga | search | engagement | destination, dates, guests |
| ... | ... | ... | ... |

**Očekivani eventi:**
- search
- view_listing
- select_dates
- add_to_wishlist
- begin_booking
- add_guest_info
- add_payment_info
- purchase

📚 **FACILITATOR NOTES:**
Ovo je praktična vježba za razumijevanje event tracking planiranja.

---

### **BACKUP AKTIVNOST 5: GA4 Scavenger Hunt (15 min)**

**Cilj:** Natjecateljski pronaći podatke u GA4

**Upute:**
Tko prvi pronađe sve odgovore, pobjeđuje!

**Pitanja:**
1. Koliki je bounce rate za homepage? (rujan 2024)
2. Koji browser ima najviše sesija?
3. Koliki je ukupni revenue za Q3 2024?
4. Koji grad ima najviše korisnika?
5. Koliko je ukupno pageviews u listopadu?

📚 **FACILITATOR NOTES:**
Gamifikacija učenja! Možete dati malu nagradu pobjedniku.

---

### **BACKUP AKTIVNOST 6: Privacy Policy Quiz (10 min)**

**Cilj:** Testirati znanje o GDPR i privatnosti

**Pitanja (True/False):**

1. GA4 podaci su 100% točni. → **False**
2. IP adresa je osobni podatak pod GDPR-om. → **True**
3. Pre-checked consent checkbox je validan. → **False**
4. Korisnik može zatražiti brisanje svojih podataka. → **True**
5. Analytics cookies se mogu postaviti prije pristanka. → **False**
6. GDPR se primjenjuje samo na EU tvrtke. → **False**
7. "Direct" traffic znači da su svi ti korisnici upisali URL ručno. → **False**

📚 **FACILITATOR NOTES:**
Brza provjera razumijevanja GDPR koncepta iz jučerašnjeg predavanja.

---

### **BACKUP AKTIVNOST 7: Dashboard Design (20 min)**

**Cilj:** Dizajnirati mockup GA4 dashboarda

**Scenarij:**
Vi ste UX dizajner za startup. CEO želi tjedni dashboard s najvažnijim metrikama.

**Zadatak:**
1. Odaberite 6-8 metrika koje bi prikazali
2. Skicirajte layout dashboarda (na papiru)
3. Objasnite zašto ste odabrali te metrike

**Hint - uključite:**
- Traffic overview
- Conversion metrics
- Top sources
- Mobile vs Desktop
- Jedna HEART metrika

📚 **FACILITATOR NOTES:**
Ovo povezuje UX dizajn s analytics znanjem. Dashboard je također proizvod koji zahtijeva dobar dizajn!

---

## 📚 **DODATNI RESURSI ZA FACILITATORA**

### **Prije predavanja:**

1. **Testiraj sve vježbe** - Odradi svaku vježbu u demo accountu
2. **Provjeri pristup** - Demo account ponekad ima ograničenja
3. **Pripremi backup** - Ako GA4 ne radi, imaj screenshots

### **Za tvoje dalje učenje:**

- Google Analytics Academy: https://analytics.google.com/analytics/academy/
- GA4 YouTube Channel: https://www.youtube.com/c/GoogleAnalytics
- Measure School (YouTube): Odlični GA4 tutoriali
- HEART Framework Paper: Search "HEART framework Google" za originalni paper

### **Pripremna lista:**

- [ ] Testiraj sve GA4 vježbe u demo accountu
- [ ] Provjeri Campaign URL Builder radi
- [ ] Pripremi HEART Framework printout (opcija)
- [ ] Imaj screenshots za fallback
- [ ] Provjeri Wi-Fi kapacitet (svi trebaju pristup)

---

## 🎓 **UDEMY RESURSI ZA OVAJ DAN**

**Napomena:**
Udemy tečaj "Complete Web Designer" ne pokriva direktno Google Analytics, ali za razumijevanje UX metrika možete referencirati:
- Bilo koja sekcija o User Testing
- Sekcije o Design Iteration based on feedback

Za dublje učenje GA4, preporučujem besplatni Google Analytics Academy umjesto Udemy resursa za ovu temu.

📖 **External Resources:**
- Google Analytics Academy: https://analytics.google.com/analytics/academy/
- HEART Framework: https://www.heartframework.com/
- GA4 Demo Account: https://support.google.com/analytics/answer/10993011
- Campaign URL Builder: https://ga-dev-tools.google/campaign-url-builder/

---

## 🎯 **HOMEWORK (Opcija)**

Ako želite dati domaću zadaću:

1. Pristupite GA4 demo accountu
2. Odradite vježbe koje nismo stigli na predavanju (slajdovi 42-50)
3. Napišite kratki izvještaj (max 1 stranica):
   - 3 najzanimljivija insight-a koje ste pronašli
   - 1 pitanje koje vam je ostalo nejasno

---

**KRAJ SINOPSISA - DAN 14** ✅

---

**ZAVRŠETAK MODULA:** Metrike i Google Analytics kompletiran!
**SLJEDEĆA TEMA:** [Prema planu SHIFT4IT programa]
