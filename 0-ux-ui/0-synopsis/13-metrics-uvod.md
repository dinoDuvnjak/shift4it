# 📘 DAN 13 - UVOD U METRIKE I GOOGLE ANALYTICS

## **PREDAVANJE: Metrics & Analytics - Osnove**
**TRAJANJE:** 9:00-12:30 (3.5 sata, s pauzama)  
**PDF MATERIJAL:** 9-metrics.pdf (slajdovi 1-25)  
**BROJ STUDENTICA:** 8-30  
**NASTAVAK:** Dan 14 - Napredne funkcije i praksa

---

## 🎯 **CILJEVI UČENJA:**

Na kraju ovog predavanja, studentice će moći:

1. **Objasniti** zašto su metrike i analitika ključne za digitalni marketing i UX dizajn
2. **Identificirati** tracking tagove na web stranicama koristeći Chrome ekstenzije
3. **Razlikovati** sampling od thresholdinga u analitici
4. **Opisati** evoluciju Google Analytics-a od Urchin-a do GA4
5. **Razumjeti** kako funkcionira GA4 protokol i instalacija
6. **Objasniti** GDPR regulativu i njezin utjecaj na tracking
7. **Provjeriti** GDPR usklađenost bilo koje web stranice
8. **Koristiti** Google Analytics 4 demo account za pronalaženje osnovnih metrika

---

## ⏰ **RASPORED PREDAVANJA:**

```
9:00-10:00   SEKCIJA 1: Uvod u metrike i tracking tagove
             - Slajdovi 1-9: Zašto metrike, tracking rješenja, analytics osnove
             
10:00-10:15  ☕ PAUZA

10:15-11:00  SEKCIJA 2: Google Analytics - Povijest i instalacija
             - Slajdovi 10-17: GA povijest, instalacija, protokol
             
11:00-11:15  ☕ PAUZA

11:15-12:00  SEKCIJA 3: GDPR i privatnost podataka
             - Slajdovi 18-23: GDPR compliance, consent, praktična vježba
             
12:00-12:30  SEKCIJA 4: GA4 Demo Account - Prve vježbe
             - Slajdovi 24-25: Uvod u demo account, osnovne metrike
             - Recap dana
```

**Ukupno efektivno vrijeme:** 180 min (3h)

---

## 📊 **PREGLED SLAJDOVA PO PRIORITETU:**

**PRIORITET 1 - MUST COVER (180 min):**
- Slajdovi 1-9: Uvod u metrike, tracking tagovi ✅
- Slajdovi 10-14: GA povijest i instalacija ✅
- Slajdovi 18-22: GDPR compliance ✅
- Slajdovi 24-25: GA4 demo vježba ✅

**PRIORITET 2 - NICE TO HAVE (ako ima vremena):**
- Slajdovi 15-17: GA4 protokol detalji (brzi pregled)

**PRIORITET 3 - HANDOUT:**
- Slajd 23: Consent tehničke tablice (dati kao PDF)

---

# ⏰ **9:00-10:00 - SEKCIJA 1: UVOD U METRIKE I TRACKING**

## **Uvodni dio (5 min)**

**Što reći studentima:**

"Dobro jutro! Danas započinjemo s jednom od najvažnijih tema u digitalnom dizajnu i marketingu - **metrikama i analitikom**.

Vjerojatno ste čuli izraz 'You can't improve what you don't measure' - ne možeš poboljšati ono što ne mjeriš. Ovo je temeljna istina u digitalnom svijetu.

Danas ćemo naučiti:
- Zašto su metrike važne
- Kako web stranice prate korisnike
- Što je Google Analytics i kako funkcionira
- Kako GDPR utječe na tracking
- I na kraju ćemo praktično raditi u GA4 demo accountu"

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Metrics (metrike) su kvantitativni podaci koji nam govore što korisnici rade na webu. Analytics su alati koji te podatke prikupljaju i analiziraju. Zajedno čine temelj data-driven (podacima vođenog) dizajna i marketinga.

---

### **Slajd 1: Metrics - Uvod**

**Notes iz PDF-a:**
_"Objective: Introduction to key metrics and their role in digital marketing analysis. Why is this important? Understanding website traffic and user behavior is essential for optimizing digital performance. 'You can't improve what you don't measure' – data-driven decisions help businesses grow. Analytics tools are more than just counters; they provide deep insights into visitor behavior."_

**Što reći studentima (10 min):**

"Metrike su **brojevi koji nam govore priču** o našim korisnicima. Ali te brojeve ne čitamo samo tako - trebamo alate za analizu, koje zovemo **analytics tools**.

**Zašto su metrike važne?**

1. **Ne možeš poboljšati ono što ne mjeriš** - Ako ne znamo koliko ljudi napušta košaricu prije kupnje, ne možemo to popraviti

2. **Podaci su temelj za pametne odluke** - Umjesto da dizajniramo 'po osjećaju', imamo konkretne brojeve koji pokazuju što radi, a što ne

3. **Analytics alati nisu samo brojači** - Oni nam pokazuju:
   - Odakle dolaze posjetitelji (Google, Instagram, direktno...)
   - Što rade na stranici (koje stranice gledaju, koliko dugo ostaju)
   - Gdje 'odustaju' (npr. na checkout stranici)
   - Koji uređaji i preglednici se koriste

**Primjer iz stvarnog života:**
Zamislite da vodite online trgovinu. Analytics vam može pokazati da 70% korisnika na mobilnim uređajima napušta stranicu na checkout-u. To vam govori - imate problem s mobilnim checkout procesom! Bez analitike, nikada to ne biste znali."

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Analytics alati rade tako da postave mali kod (script) na web stranicu. Svaki put kada korisnik posjeti stranicu, taj kod šalje podatke na server (npr. Google server). Ti podaci se zatim analiziraju i prikazuju u dashboard-u.

**Česta pitanja:**
Q: "Je li ovo isto kao špijuniranje korisnika?"
A: "Analytics prikuplja anonimne podatke o ponašanju, ne osobne informacije. Vidimo 'Korisnik X je posjetio stranicu Y', ali ne znamo tko je ta osoba po imenu. Također, GDPR regulativa (o kojoj ćemo pričati kasnije) štiti korisnike i zahtijeva pristanak."

📖 **Reference:**
- Google Analytics Official Guide: https://support.google.com/analytics

---

### **Slajd 2: Tracking Tags - Lolaliza**

**Notes iz PDF-a:**
_"How many marketing tracking tags can you find on the lolaliza.com homepage? Websites use multiple tracking tags to collect user data for marketing and analytics. Understanding how many and which tags are present helps assess tracking intensity."_

**Što reći studentima (5 min):**

"Sada ćemo vidjeti kako web stranice u stvarnosti koriste tracking.

**Tracking tagovi** su mali komadi koda koje web stranice instaliraju da bi pratile korisnike. Svaki tag šalje podatke nekom servisu - Google Analytics, Facebook, TikTok, itd.

Pogledajmo primjer: **lolaliza.com** (belgijska modna trgovina).

**Pitanje za vas:** Što mislite, koliko tracking tagova ima prosječna e-commerce stranica?"

*(Pauza za odgovore - vjerojatno će reći 5-10)*

"Zapravo, većina velikih stranica ima **20-50+ tagova**! Svaki za drugu svrhu:
- Google Analytics za analizu prometa
- Facebook Pixel za remarketing
- Hotjar za heatmape
- I mnogi drugi..."

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Tracking tag je JavaScript kod koji se učitava s web stranicom. Svaki tag "razgovara" sa svojim serverom i šalje podatke. Više tagova = više podataka koji se prikupljaju, ali i sporije učitavanje stranice.

**Kako provjeriti tagove:**
Koristit ćemo Chrome ekstenziju **Ghostery** koja pokazuje sve tagove na stranici.

---

### **Slajd 3: Tracking Tags - Reuters**

**Notes iz PDF-a:**
_"How many marketing tracking tags can you find on the reuters.com homepage? Take any website after first verifying that there are numerous trackers installed."_

**Što reći studentima (3 min):**

"Pogledajmo sada **reuters.com** - veliki news portal.

News stranice su poznate po velikom broju tagova jer:
- Žive od oglasa (trebaju ad trackere)
- Imaju partnere za sadržaj
- Trebaju detaljnu analitiku čitanosti

Reuters tipično ima **30-50+ tracking tagova**."

---

### **Slajd 4: Tracking Tags - Zalando**

**Notes iz PDF-a:**
_"How many tracking tags can you find on the Zalando homepage? Take any website after first verifying that there are numerous trackers installed."_

**Što reći studentima (3 min):**

"**Zalando** je veliki e-commerce - kod njih tracking je ključan za:
- Praćenje kupovnog ponašanja
- Remarketing (prikazivanje oglasa za proizvode koje ste gledali)
- Personalizaciju preporuka

Zalando vjerojatno ima **40-60+ tagova** zbog:
- Više platformi za oglašavanje (Google, Facebook, TikTok, Pinterest...)
- A/B testing alata
- Customer experience alata"

---

### **Slajd 5: Tracking Solutions - Pregled**

**Notes iz PDF-a:**
_"There are many tracking solutions available."_

**Što reći studentima (5 min):**

"Sada kada znamo da postoje tagovi, pogledajmo **tko su glavni igrači** u tracking industriji.

*(Pokažite slajd s logotipovima)*

**Kategorije tracking rješenja:**

1. **Analytics alati:**
   - Google Analytics (najpopularniji)
   - Hotjar (za heatmape i snimke sesija)

2. **Advertising platforme:**
   - Google Ads
   - Facebook/Meta Pixel
   - TikTok Pixel
   - Pinterest Tag

3. **Remarketing/Retargeting:**
   - Criteo
   - MediaMath
   - Rubicon Project

4. **Data management:**
   - Salesforce
   - Oracle MOAT

Svaki od ovih alata ima svoju svrhu i način prikupljanja podataka."

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
- **Analytics alati** prate ponašanje na stranici
- **Ad platforme** prate konverzije iz oglasa
- **Remarketing alati** omogućuju prikazivanje oglasa korisnicima koji su već posjetili stranicu
- **Data management** platforme centraliziraju sve podatke

**Česta pitanja:**
Q: "Zašto toliko različitih alata?"
A: "Svaka platforma (Google, Facebook, TikTok) želi svoje podatke. Ako oglašavate na sve tri platforme, trebate tag za svaku. Plus, neki alati rade specifične stvari (npr. Hotjar snima kako se korisnik kreće po stranici)."

---

### **Slajd 6: 200+ Tracking Solutions**

**Notes iz PDF-a:**
_"In 2024, there were more than 200 tracking solutions."_

**Što reći studentima (3 min):**

"Da, dobro ste vidjeli - postoji **više od 200 različitih tracking rješenja**!

Ovo pokazuje koliko je tracking industrija velika i kompleksna. Ne morate znati sve - fokusirat ćemo se na najvažniji: **Google Analytics**.

Zašto Google Analytics?
- Koristi ga **52% svih web stranica** u svijetu
- Besplatan je (s određenim ograničenjima)
- Najdetaljniji je analytics alat
- Industrija standard"

---

### **Slajd 7: Analytics - Definicija**

**Notes iz PDF-a:**
_"Analytics are tools for measuring and analyzing website traffic. They're not just a counter for visitor numbers, but truly powerful marketing tools for analyzing and understanding what visitors do on a site. 1. YOU CAN'T IMPROVE WHAT YOU DON'T MEASURE 2. GOOD DATA IS THE FOUNDATION FOR MAKING SMART DECISIONS. 3. DATA WITHOUT CONTEXT IS MEANINGLESS."_

**Što reći studentima (8 min):**

"Sada kada razumijemo tracking, definirajmo što su **analytics alati**.

**Analytics alati** su programi za mjerenje i analizu web prometa. Ali oni su puno više od brojača posjetitelja!

**Tri ključna principa analitike:**

**1. Ne možeš poboljšati ono što ne mjeriš**
Ako ne pratimo bounce rate (postotak korisnika koji odmah napuste stranicu), ne znamo imamo li problem s prvim dojmom.

**2. Dobri podaci su temelj za pametne odluke**
Umjesto 'Mislim da korisnici preferiraju plavi gumb', imamo 'A/B test pokazuje da plavi gumb ima 23% veći CTR'.

**3. Podaci bez konteksta su besmisleni**
Ako vam kažem '10.000 posjetitelja', je li to dobro ili loše? Ovisi o kontekstu! Za mali blog - odlično. Za Amazon - katastrofa.

**Što sve možemo mjeriti?**
- Broj posjetitelja (po danu, tjednu, mjesecu)
- Odakle dolaze (Google search, social media, direktno)
- Što rade na stranici (koje stranice gledaju, koliko dugo)
- Konverzije (kupnje, prijave, download-i)
- Tehnički podaci (browser, uređaj, lokacija)"

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Analytics alati rade u dva koraka:
1. **Prikupljanje** - JavaScript kod na stranici šalje podatke
2. **Obrada** - Server agregira i analizira podatke
3. **Prikaz** - Dashboard prikazuje rezultate

**Česta pitanja:**
Q: "Zašto su podaci bez konteksta besmisleni?"
A: "Zamislite da vidite da je prosječno vrijeme na stranici 2 minute. Je li to dobro? Ako je blog post od 500 riječi - super, ljudi čitaju. Ako je checkout stranica - loše, traje predugo!"

📖 **Reference:**
- Google Analytics Support: https://support.google.com/analytics

---

### **Slajd 8: Analytics - Ograničenja**

**Notes iz PDF-a:**
_"These are not 100% accurate tools! Tracking 100% of data is impossible (Data Integrity problem). User leaves page too soon. The user uses AdBlockers. User blocks JS. Google Consent is enabled and the user has not accepted or refused cookies. Sampling or thresholding."_

**Što reći studentima (8 min):**

"⚠️ **Važno upozorenje:** Analytics alati NISU 100% točni!

**Zašto ne možemo pratiti sve korisnike?**

1. **Korisnik napusti stranicu prebrzo**
   - Ako korisnik klikne 'Back' u prvoj sekundi, tracking se možda nije stigao učitati

2. **AdBlockeri**
   - Ekstenzije poput uBlock Origin, AdBlock Plus blokiraju tracking skripte
   - ~25-40% korisnika koristi neki oblik ad blockera

3. **Onemogućen JavaScript**
   - Neki korisnici (iz sigurnosnih razloga) isključe JavaScript
   - Bez JS-a, analytics ne radi

4. **Cookie consent**
   - GDPR zahtijeva pristanak za tracking
   - Ako korisnik odbije cookies, ne možemo ga pratiti

5. **Sampling i thresholding**
   - Google Analytics ponekad koristi uzorke umjesto svih podataka
   - O tome više na sljedećem slajdu

**Što to znači za nas?**
Analytics brojevi su **trendovi i indikatori**, ne apsolutne istine. Ako GA kaže 10.000 posjetitelja, stvarni broj je možda 12.000-15.000.

Uvijek gledajte relativne promjene: 'Promet je porastao 20%' je pouzdanije od 'Imali smo točno 10.543 posjetitelja'."

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
"Data Integrity" problem znači da nikada nećemo imati 100% točne podatke. To je OK! Analitika nam i dalje daje vrijedne uvide - samo trebamo biti svjesni ograničenja.

**Česta pitanja:**
Q: "Ako podaci nisu točni, čemu uopće analytics?"
A: "Trendovi i relativne usporedbe su još uvijek vrlo korisni. Ako vidite pad od 50% u tjednu, to je stvaran problem - čak i ako ne znate točan broj posjetitelja."

---

### **Slajd 9: Sampling vs Threshold**

**Notes iz PDF-a:**
_"Sampling is a method that allows Google Analytics to generate reports by examining only a representative portion of the data. Data Thresholding allows Google to withhold data in situations where the algorithm detects a potential risk of identifying a real-world person."_

**Što reći studentima (7 min):**

"Dva važna koncepta koja mogu utjecati na vaše podatke u GA4:

**SAMPLING (Uzorkovanje)**
Kada imate PUNO podataka, Google Analytics ne analizira sve - uzima **reprezentativni uzorak**.

*Primjer:* Imate 10 milijuna posjetitelja mjesečno. GA možda analizira samo 1 milijun i onda ekstrapolira rezultate.

- ✅ Brže generiranje izvještaja
- ❌ Manje precizni podaci

**THRESHOLDING (Pragovi)**
Google skriva podatke kada postoji rizik identificiranja stvarne osobe.

*Primjer:* Imate 2 posjetitelja iz malog sela u dobi 18-24. Google može sakriti te podatke jer bi bilo lako identificirati te osobe.

- ✅ Štiti privatnost korisnika
- ❌ Nedostaju neki podaci

**Kada se ovo događa?**
- Sampling: Veliki skupovi podataka (milijuni redaka)
- Thresholding: Mali, specifični segmenti (posebno demografija)

Za većinu malih/srednjih stranica, ovo neće biti veliki problem."

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
- **Sampling** = Google gleda dio podataka i pretpostavlja ostatak
- **Thresholding** = Google namjerno skriva podatke radi privatnosti

Ako radite s GA4 i vidite poruku "(other)" ili prazna polja, to je vjerojatno thresholding.

---

# ☕ **10:00-10:15 - PAUZA**

**Facilitator:** Najavi 15-minutnu pauzu. Podsjeti studentice da se vrate na vrijeme.

---

# ⏰ **10:15-11:00 - SEKCIJA 2: GOOGLE ANALYTICS**

### **Slajd 10: Google Analytics - Tržišni lider**

**Notes iz PDF-a:**
_"52% Sites around the world are tracked with Google Analytics. Facebook > 18%. Hotjar > 3%. Is it really free? From 25 million events per month, 50.000€ PER YEAR! When things are free and too good to be true, it's usually because you're the product."_

**Što reći studentima (10 min):**

"**Google Analytics** je apsolutni tržišni lider:

📊 **Tržišni udio:**
- Google Analytics: **52%** svih web stranica
- Facebook Analytics: ~18%
- Hotjar: ~3%
- Ostali: ~27%

**Je li stvarno besplatan?**

Google Analytics je besplatan za većinu korisnika, ALI:

1. **Plaćate s podacima** - Google koristi vaše podatke za poboljšanje svojih proizvoda i oglašavanja

2. **Enterprise verzija je skupa** - GA360 (za velike tvrtke) košta od **50.000€+ godišnje**

3. **Skriveni troškovi:**
   - Potrebno znanje za korištenje
   - Vrijeme za analizu
   - Možda treba konzultant/agencija

**Zlatno pravilo:**
'Ako je proizvod besplatan, vi ste proizvod.'

Google Analytics prikuplja podatke o milijardama korisnika. Ti podaci pomažu Google-u prodavati bolje ciljane oglase. Vaša 'cijena' za besplatni GA je dijeljenje tih podataka.

**Preporuka industrije:**
Oko **10% marketing budžeta** bi trebalo ići na analitiku i učenje iz podataka."

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Google Analytics ima checkbox u postavkama koji kaže "Share your data with Google to improve products". Većina ljudi to ima uključeno a da ni ne znaju. To omogućuje Google-u korištenje vaših podataka.

**Česta pitanja:**
Q: "Postoje li alternative Google Analytics-u koje ne dijele podatke?"
A: "Da! Matomo (ex-Piwik) je open-source alternativa koju možete hostati sami. Fathom i Plausible su privacy-focused alternative. Ali imaju manju zajednicu i manje tutoriala."

---

### **Slajd 11: Google Analytics - Povijest**

**Notes iz PDF-a:**
_"Today, we're talking about Google Analytics 4. It's the latest version of analytics offered by Google. It's a blend between the classic universal analytics and Firebase analytics. Now, everything is interconnected within one tool."_

**Što reći studentima (8 min):**

"Kratka povijest Google Analytics-a:

**2005: Urchin** 🦔
- Google kupuje tvrtku Urchin
- Urchin postaje 'Urchin from Google'
- Ovdje dolazi skraćenica **UTM** (Urchin Tracking Module)

**2012: Universal Analytics**
- Nova verzija s boljim trackingom
- Session-based model (pratimo sesije korisnika)

**2019: Google Analytics 4 (GA4)**
- Potpuno novi pristup
- Event-based model (pratimo događaje, ne sesije)
- Integracija s Firebase (za mobile apps)

**Zašto je GA4 drugačiji?**

| Universal Analytics | Google Analytics 4 |
|---------------------|---------------------|
| Session-based | Event-based |
| Samo web | Web + Mobile apps |
| Cookies-fokusiran | Machine learning za praznine |
| Ugašen 2024 | Trenutna verzija |

Od **srpnja 2024**, Universal Analytics više ne postoji. Svi moraju koristiti GA4!"

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
- **Session-based** = pratimo 'posjete' (sesije). Jedna sesija = jedno posjećivanje stranice.
- **Event-based** = pratimo 'događaje' (klikove, scrollove, kupnje). Fleksibilnije i detaljnije.

GA4 je kompleksniji od stare verzije, ali i moćniji. Većina online tutoriala iz 2020-2023 još uvijek pokazuje Universal Analytics - pazite da tražite GA4 specifične resurse!

---

### **Slajd 12: UTM Parametri**

**Notes iz PDF-a:**
_"UTM (Urchin Tracking Module) allows businesses to track marketing campaign performance. Different UTM parameters include: utm_source, utm_medium, utm_campaign, utm_term, utm_content."_

**Što reći studentima (10 min):**

"**UTM parametri** su način da pratimo odakle dolaze posjetitelji kada kliknu na naše linkove.

**Što je UTM?**
UTM = Urchin Tracking Module (naslijeđe iz Urchin-a!)

Kada šaljete link u email kampanju ili objavljujete na društvenim mrežama, želite znati koliko klikova je došlo odatle.

**5 UTM parametara:**

1. **utm_source** - Izvor prometa
   - Primjer: `google`, `facebook`, `newsletter`

2. **utm_medium** - Tip prometa
   - Primjer: `cpc` (cost per click), `email`, `social`

3. **utm_campaign** - Naziv kampanje
   - Primjer: `summer_sale_2024`, `black_friday`

4. **utm_term** - Ključna riječ (za plaćene oglase)
   - Primjer: `running_shoes`

5. **utm_content** - Verzija oglasa (za A/B testiranje)
   - Primjer: `blue_button`, `red_button`

**Primjer kompletnog UTM linka:**
```
https://mojashop.hr/proizvod?
utm_source=facebook
&utm_medium=paid_social
&utm_campaign=summer_sale_2024
&utm_content=video_ad_1
```

Kada korisnik klikne ovaj link, GA4 zna:
- Došao je s Facebook-a
- Kroz plaćeni oglas
- U sklopu Summer Sale 2024 kampanje
- Na verziju oglasa 'video_ad_1'"

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
UTM parametri se dodaju na kraj URL-a. Korisnik ih ne mora vidjeti ili razumjeti - oni su za analytics.

**Česta pitanja:**
Q: "Moram li ručno pisati UTM parametre?"
A: "Ne! Postoji Google Campaign URL Builder koji to radi automatski. Kasnije ćemo vidjeti kako se koristi."

📖 **Reference:**
- Google Campaign URL Builder: https://ga-dev-tools.google/campaign-url-builder/

---

### **Slajd 13: GA4 Instalacija - Kod**

**Notes iz PDF-a:**
_"GA4 script (gtag.js) must be added to web pages. Data is processed with a 72-hour delay for complex insights. GA4 focuses on event-based tracking rather than session-based."_

**Što reći studentima (7 min):**

"Kako se GA4 instalira na web stranicu?

**Osnovni kod:**
```html
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXX');
</script>
```

**Gdje se stavlja ovaj kod?**
U `<head>` sekciju svake stranice na webu.

**Što se događa nakon instalacije?**
1. Korisnik posjeti stranicu
2. Script se učita
3. Podaci se šalju na Google server
4. Google obrađuje podatke (može trajati do **72 sata** za kompleksne podatke!)
5. Podaci su dostupni u GA4 dashboardu

**Zašto 72 sata?**
Google radi kompleksne kalkulacije - machine learning modele, fraud detection, data validation. To zahtijeva vrijeme.

Za **real-time podatke**, GA4 ima poseban 'Realtime' report koji pokazuje aktivnost u zadnjih 30 minuta."

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Kao UX dizajner, vjerojatno nećete sami instalirati GA4 - to radi developer ili marketinški tim. Ali dobro je razumjeti kako funkcionira.

**Česta pitanja:**
Q: "Trebam li ja kao dizajner znati kodirati?"
A: "Ne nužno! Ali razumijevanje kako tracking radi pomaže u komunikaciji s developerima i u interpretaciji podataka."

---

### **Slajd 14: GA4 Instalacija - Dijagram**

**Notes iz PDF-a:**
_"The installation of Google Analytics is done through a script added to your pages, which is then processed by Google's servers. After that, the data is analyzed and available on a dashboard. Google takes 72 hours to process complex data."_

**Što reći studentima (5 min):**

"Vizualno prikazano, flow izgleda ovako:

```
[Vaše stranice] → [Google server] → [Data Processing] → [Dashboard]
     ↑                                                         ↓
  gtag.js                                              Vi gledate
  script                                               izvještaje
```

**Koraci:**
1. **Vaše stranice** imaju instaliran gtag.js script
2. Svaki pageview i event šalje podatke na **Google server**
3. **Data Processing** - Google obrađuje podatke (do 72h)
4. **Dashboard** - Vi vidite rezultate u GA4 sučelju

**Bitno za zapamtiti:**
- Nije instant! Kompleksni podaci trebaju vrijeme
- Realtime izvještaji pokazuju samo osnovne podatke
- Za detaljne analize, čekajte 24-72 sata"

---

### **Slajd 15-16: GA4 Protocol (BRZI PREGLED)**

**Što reći studentima (5 min):**

"Sljedeća dva slajda pokazuju tehnički detalj - **GA4 Measurement Protocol**.

Ovo je primjer kako zapravo izgleda podatak koji se šalje Google-u:

```
https://analytics.google.com/g/collect?
v=2&tid=G-ABC123XYZ&...
&dl=https://domaine.com/fr/
&dt=Naslov%20stranice
&en=page_view
```

**Ključni elementi:**
- `tid` = Tracking ID (vaš GA4 property)
- `dl` = Document Location (URL stranice)
- `dt` = Document Title (naslov stranice)
- `en` = Event Name (npr. page_view, purchase)

**Ne morate ovo pamtiti!** Ovo je za tehničke ljude. Vi ćete koristiti GA4 sučelje koje sve ovo prikazuje lijepo formatiran."

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Ovaj slajd je tu da pokaže da iza lijepog GA4 sučelja postoji tehnički protokol. Ako studentice pitaju detalje, možete reći da je to za advanced korisnike i developere.

---

### **Slajd 17: Cookies - Kolačići**

**Notes iz PDF-a:**
_"All Google Analytics information is stored in a cookie on your computer (browser). On YOUR domain name, or on the doubleclick domain name (e.g. remarketing)."_

**Što reći studentima (5 min):**

"Gdje se čuvaju vaši analytics podaci? U **cookies** (kolačićima)!

**Što je cookie?**
Cookie je mala tekstualna datoteka koju web stranica sprema u vaš browser. Koristi se za:
- Pamćenje prijave
- Pamćenje postavki
- **Tracking** (analitika, oglasi)

**GA4 cookies:**
Google Analytics sprema cookie na vašu domenu. Taj cookie sadrži:
- Jedinstveni ID korisnika
- Vrijeme prvog posjeta
- Broj sesija

**Zašto je ovo važno za GDPR?**
Cookies su 'personal data' pod GDPR-om. Zato stranice moraju tražiti pristanak prije postavljanja analytics cookies.

Ovo nas dovodi do sljedeće velike teme - **GDPR compliance**!"

---

# ☕ **11:00-11:15 - PAUZA**

**Facilitator:** Najavi 15-minutnu pauzu.

---

# ⏰ **11:15-12:00 - SEKCIJA 3: GDPR I PRIVATNOST**

### **Slajd 18: GDPR Compliance**

**Notes iz PDF-a:**
_"The General Data Protection Regulation (GDPR) is an EU law effective since May 2018. It aims to protect personal data and privacy of EU citizens. Key principles include: data minimization, explicit user consent, transparency, and the right to be forgotten."_

**Što reći studentima (10 min):**

"**GDPR** - General Data Protection Regulation je europski zakon koji štiti privatnost korisnika.

**Što je GDPR?**
- EU zakon na snazi od **svibnja 2018.**
- Štiti osobne podatke građana EU
- Primjenjuje se na SVE koji obrađuju podatke EU građana (čak i tvrtke izvan EU!)

**Ključni principi GDPR-a:**

1. **Data Minimization** - Prikupljaj samo podatke koji su ti potrebni

2. **Explicit Consent** - Korisnik mora **aktivno** pristati na tracking
   - ❌ Pre-checked checkbox
   - ✅ Korisnik sam označi checkbox

3. **Transparency** - Jasno objasni što prikupljate i zašto

4. **Right to be Forgotten** - Korisnik može zatražiti brisanje svih svojih podataka

**Zašto je GDPR problem za Google Analytics?**

1. **Podaci idu u SAD** - Google serveri su u SAD-u, gdje EU zakoni ne vrijede

2. **IP adresa = osobni podatak** - Čak i anonimizirana IP može se smatrati osobnim podatkom

3. **Consent** - Mnoge stranice ne traže pravilno pristanak

Europski regulatori (npr. francuski **CNIL**) su presudili da korištenje GA bez jakih zaštita **nije usklađeno s GDPR-om**!"

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
GDPR je ozbiljan zakon. Kazne za nepoštivanje mogu biti do **20 milijuna eura** ili **4% globalnog godišnjeg prihoda** (što god je veće).

Kao dizajner, trebate razumjeti GDPR jer utječe na:
- Cookie bannere koje dizajnirate
- Forme za prikupljanje podataka
- Privacy policy stranice

**Česta pitanja:**
Q: "Ako sam mala tvrtka, hoće li me kazniti?"
A: "Manje tvrtke obično dobiju upozorenja prije kazni. Ali dobra praksa je biti usklađen od početka."

---

### **Slajd 19: Personal Identifying Information**

**Notes iz PDF-a:**
_"Any information that could identify a single person, even if encrypted, cannot be imported into Google Analytics. The GDPR requires Prior consent. Example: 122.195.25.144"_

**Što reći studentima (5 min):**

"**Što su osobni podaci (PII)?**

PII = Personally Identifiable Information = bilo koja informacija koja može identificirati osobu.

**Primjeri:**
- Ime i prezime
- Email adresa
- IP adresa (da, čak i IP!)
- Broj telefona
- Adresa

**IP adresa primjer:**
`122.195.25.144` - Ovo je IP adresa. Sama po sebi ne znači ništa, ali u kombinaciji s drugim podacima može identificirati osobu.

**Što NE smijete slati u Google Analytics:**
- Emailove korisnika
- Imena
- Bilo koje PII

Google Analytics **zabranjuje** unos PII-a u sustav! Ako to radite, kršite uvjete korištenja."

---

### **Slajd 20: Što je Consent?**

**Notes iz PDF-a:**
_"Your consent must be obtained prior to the insertion or reading of cookies. Your consent must be informed. Your consent is valid only if you can exercise a real choice. Your consent must be specific. You must be able to withdraw your consent."_

**Što reći studentima (8 min):**

"**Consent** (pristanak) ima specifična pravila pod GDPR-om:

**5 uvjeta za validan pristanak:**

1. **Prior** (Prethodni)
   - Morate pitati PRIJE postavljanja cookies
   - ❌ Ne smijete trackati pa onda pitati

2. **Informed** (Informiran)
   - Korisnik mora znati što pristaje
   - Jasno objašnjenje, ne pravnički žargon

3. **Real Choice** (Stvarni izbor)
   - Mora biti jednako lako odbiti kao i prihvatiti
   - ❌ 'Accept' gumb velik i zelen, 'Decline' siv i malen

4. **Specific** (Specifičan)
   - Odvojeni pristanci za različite svrhe
   - Analytics ≠ Marketing ≠ Personalizacija

5. **Withdrawable** (Opoziv)
   - Korisnik mora moći promijeniti odluku
   - Omogućite opciju 'Manage cookies' kasnije

**Primjer lošeg cookie bannera:**
'Korištenjem ove stranice pristajete na cookies' - NIJE validan pristanak!

**Primjer dobrog cookie bannera:**
'Koristimo cookies za analitiku i marketing. [Prihvati sve] [Odbij sve] [Prilagodi]'"

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Kao UX dizajner, možda ćete dizajnirati cookie banner. Zapamtite - 'dark patterns' (dizajn koji tjera korisnike da pristanu) su ILEGALNI pod GDPR-om!

---

### **Slajd 21: Pros and Cons GDPR Consent**

**Notes iz PDF-a:**
_"Pros: You comply with GDPR laws, Users are protected. Cons: If users refuse - you have no tracking info, No traffic sources, No links to paid ads, No conversion tracking, You can't compare periods easily."_

**Što reći studentima (5 min):**

"Poštivanje GDPR-a ima **prednosti i nedostatke**:

**✅ PREDNOSTI:**
- Zakonska usklađenost (izbjegavate kazne)
- Korisnici su zaštićeni (gradite povjerenje)
- Bolji imidž tvrtke

**❌ NEDOSTACI (ako korisnici odbiju):**
- Nema tracking podataka za te korisnike
- Ne znate izvore prometa
- Ne možete pratiti konverzije iz oglasa
- Usporedba perioda je nepouzdana

**Realnost:**
Otprilike **30-50%** korisnika odbije analytics cookies. To znači da vaši podaci pokrivaju samo dio posjetitelja.

**Što možemo učiniti?**
- Koristiti aggregirane podatke gdje je moguće
- Kombinirati više izvora podataka
- Prihvatiti da nikada nećemo imati 100% podataka"

---

### **Slajd 22: GDPR Praktična vježba**

**Notes iz PDF-a:**
_"Take a random site and check if it's GDPR compliant for your EU country. 15' + Debrief. Use Chrome. Addon: Analytics Debugger. Addon: EditThisCookie."_

**Što reći studentima (2 min uvod):**

"Sada ćemo **praktično provjeriti** je li neka stranica GDPR compliant!

Za ovo nam trebaju dvije Chrome ekstenzije:
1. **Analytics Debugger** - pokazuje GA tracking info
2. **EditThisCookie** - pokazuje sve cookies

Ovu vježbu radimo zajedno kao demonstraciju, a vi ćete imati priliku sami isprobati."

---

✏️ **ZADATAK: GDPR Provjera (15 min)**

**Cilj:** Provjeriti GDPR usklađenost web stranice

**Priprema (3 min):**
1. Otvorite Chrome browser
2. Instalirajte ekstenzije:
   - Analytics Debugger: https://chromewebstore.google.com/detail/analytics-debugger
   - EditThisCookie: https://chromewebstore.google.com/detail/editthiscookie-v3

**Zadatak (10 min):**
1. Odaberite bilo koju web stranicu (npr. web shop)
2. Očistite sve cookies za tu stranicu (EditThisCookie → Clear all)
3. Osvježite stranicu
4. **PRIJE** nego kliknete na cookie banner:
   - Otvorite EditThisCookie - ima li već cookies?
   - Ako da - stranica NIJE compliant!
5. Kliknite "Odbij" na cookie banneru
6. Provjerite ponovo - ima li analytics cookies?
7. Uključite Analytics Debugger - šalje li se još uvijek tracking?

**Pitanja za razmišljanje:**
- Je li cookie banner dao stvarni izbor?
- Jesu li opcije "Prihvati" i "Odbij" jednako vidljive?
- Postoji li opcija za detaljne postavke?

📚 **FACILITATOR NOTES:**

**Kako voditi vježbu:**
1. Prvo demonstriraj na jednoj stranici (npr. neki poznati web shop)
2. Zatim neka studentice probaju same
3. Debrief: Koja je stranica bila compliant, koja ne?

**Česti problemi:**
- Ekstenzija se ne instalira → Provjerite je li Chrome ažuriran
- Ne vide cookies → Osvježite stranicu nakon instalacije

**Što tražiti:**
- ❌ Cookies postoje PRIJE pristanka = Nije compliant
- ❌ "Odbij" je skriveno ili teško za naći = Nije compliant
- ❌ Tracking nastavlja nakon odbijanja = Nije compliant
- ✅ Nema cookies prije pristanka = Compliant
- ✅ Jasne opcije = Compliant

---

### **Slajd 23: Consent Technical Details (HANDOUT)**

**Notes iz PDF-a:**
_"Google Consent Status (G1xx) - G100: Consent for both ad_storage and analytics_storage is denied... etc."_

**Što reći studentima (2 min):**

"Ovaj slajd pokazuje tehničke detalje o consent statusima u GA4.

Ne morate ovo pamtiti! Ovo je referenca za developere.

Ukratko, Google ima kodove:
- G100 = Sve odbijeno
- G111 = Sve prihvaćeno
- G1-- = Stranica ne traži consent (problematično!)

Ovaj slajd ćete dobiti kao PDF za referencu."

---

# ⏰ **12:00-12:30 - SEKCIJA 4: GA4 DEMO**

### **Slajd 24: GA4 Demo Account - Uvod**

**Notes iz PDF-a:**
_"Access to Google GA4 demo account. Here's an introduction to Google's demo case, which is available to everyone and involves the analytics of Google's online store."_

**Što reći studentima (5 min):**

"Sada dolazimo do **praktičnog dijela** - radimo u pravom Google Analytics 4!

Google ima **demo account** koji je dostupan svima. To je stvarni analytics za **Google Merch Shop** - Google-ovu online trgovinu.

**Kako pristupiti:**
1. Idite na: https://support.google.com/analytics/answer/10993011
2. Kliknite na 'Access the GA4 Demo Account'
3. Prijavite se s Google računom

**Zašto je demo account odličan?**
- Pravi podaci (ne simulacija)
- Sigurno okruženje za učenje
- Ne možete ništa pokvariti!

**Google Merch Shop:**
https://shop.merch.google/

Ovo je stvarna trgovina gdje Google prodaje merchandise (majice, šalice, itd.). Demo account pokazuje analytics te trgovine."

📚 **FACILITATOR NOTES:**

**Priprema:**
Testiraj pristup demo accountu PRIJE predavanja! Ponekad Google mijenja linkove.

**Ako netko nema Google account:**
Neka se upare s kolegicom koja ima.

📖 **Reference:**
- GA4 Demo Account Access: https://support.google.com/analytics/answer/10993011

---

### **Slajd 25: GA4 Demo - Prva vježba**

**Notes iz PDF-a:**
_"In the Google DEMO account (GA4), get the following information (about September 2024): How many new users are there this month? The number of tablet purchases? How many sessions were generated by Organic Search? Which product was the most popular? What is the URL of the first page of the session? Most popular (after the homepage)? Looking at the traffic, what's the most popular source of traffic? What is the revenue of the product with the best add-to-cart rate per view? Which browser (and version) has a problematic engagement rate?"_

**Što reći studentima (3 min uvod):**

"Vaš prvi zadatak u GA4! Pronađite sljedeće podatke za **rujan 2024**:

1. Koliko je bilo novih korisnika ovaj mjesec?
2. Broj kupnji s tableta?
3. Koliko sesija je došlo iz Organic Search?
4. Koji proizvod je bio najpopularniji?
5. Koji je URL prve stranice sesije (najpopularniji nakon homepage-a)?

Radite u parovima. Imate 15 minuta!"

---

✏️ **ZADATAK: GA4 Demo - Osnovne metrike (15 min)**

**Cilj:** Naučiti navigirati GA4 i pronaći osnovne metrike

**Priprema:**
1. Pristupite GA4 demo accountu
2. Postavite vremenski period na rujan 2024

**Pitanja:**

| # | Pitanje | Gdje tražiti |
|---|---------|--------------|
| 1 | Koliko novih korisnika? | Reports → Acquisition → Overview |
| 2 | Kupnje s tableta? | Reports → Tech → Overview → Filter: Tablet |
| 3 | Sesije iz Organic Search? | Reports → Acquisition → Traffic acquisition |
| 4 | Najpopularniji proizvod? | Reports → Monetization → E-commerce purchases |
| 5 | Popularna landing page? | Reports → Engagement → Landing pages |

📚 **FACILITATOR NOTES:**

**Koraci za svako pitanje:**

**1. Novi korisnici:**
- Reports → Acquisition → User acquisition
- Kartica "New users" na vrhu

**2. Tablet kupnje:**
- Reports → Tech → Tech details
- Filter na "Device category" = "tablet"
- Pogledaj "Conversions" ili "Purchase" column

**3. Organic Search sesije:**
- Reports → Acquisition → Traffic acquisition
- Nađi red "Organic Search"
- Pogledaj "Sessions" column

**4. Najpopularniji proizvod:**
- Reports → Monetization → Ecommerce purchases
- Sortiraj po "Items viewed" ili "Items purchased"

**5. Landing pages:**
- Reports → Engagement → Landing page
- Ignoriraj "/" (homepage)
- Pogledaj drugu najpopularniju

**Ako netko zapne:**
GA4 ima search funkciju (🔍) - mogu utipkati "new users" i naći relevantni report.

---

## 🔄 **RECAP DANA (5 min)**

**Što reći studentima:**

"Brzi pregled što smo danas naučili:

1. **Metrike su temelj** - 'You can't improve what you don't measure'

2. **Tracking tagovi** - Web stranice koriste 20-50+ tagova za različite svrhe

3. **Google Analytics dominira** - 52% svih stranica, ali nije 100% točan

4. **GDPR je obavezan** - Morate tražiti pristanak, korisnici imaju prava

5. **GA4 je event-based** - Nova generacija analytics-a

**Sutra nastavljamo:**
- Ciljevi i događaji u GA4
- Traffic sources i kampanje
- HEART Framework
- Mnogo više praktičnih vježbi!

**Pitanja?"**

---

## ❓ **PITANJA ZA PROVJERU RAZUMIJEVANJA**

**Osnovni level:**
1. Što znači izraz 'You can't improve what you don't measure'?
2. Nabroj 3 razloga zašto analytics podaci nisu 100% točni.

**Srednji level:**
3. Koja je razlika između sampling-a i thresholding-a?
4. Zašto je Google Analytics potencijalno problematičan za GDPR?
5. Što je UTM parametar i čemu služi?

**Viši level:**
6. Kako bi provjerio/la je li neka web stranica GDPR compliant?
7. Zašto je GA4 prešao sa session-based na event-based model?

---

## 🔄 **BACKUP AKTIVNOSTI**

### **BACKUP AKTIVNOST 1: Tracking Tag Hunt (10 min)**

**Cilj:** Pronaći i usporediti broj tracking tagova na različitim stranicama

**Upute:**
1. Instalirajte Ghostery ekstenziju (ako već nemate)
2. Posjetite 3 različite stranice:
   - News portal (npr. index.hr)
   - E-commerce (npr. aboutyou.hr)
   - Corporate stranica (npr. neka lokalna tvrtka)
3. Za svaku zapišite broj trackera
4. Usporedite rezultate

**Pitanja za diskusiju:**
- Koja kategorija ima najviše trackera?
- Zašto mislite da je tako?

📚 **FACILITATOR NOTES:**
Ova aktivnost je odlična ako imate 10 min viška. Može se raditi individualno ili u parovima.

---

### **BACKUP AKTIVNOST 2: Cookie Banner Audit (15 min)**

**Cilj:** Analizirati UX cookie bannera na različitim stranicama

**Upute:**
1. Posjetite 5 različitih web stranica
2. Za svaku analizirajte cookie banner:
   - Je li odmah vidljiv?
   - Koje opcije nudi? (Accept/Decline/Customize)
   - Jesu li opcije jednako istaknute?
   - Postoji li dark pattern?
3. Ocijenite svaki banner: 1-5 (1 = loš UX, 5 = odličan)

📚 **FACILITATOR NOTES:**
Ovo je odlična vježba za povezivanje GDPR-a s UX dizajnom. Cookie banner JE UX element!

---

### **BACKUP AKTIVNOST 3: UTM Builder Praksa (10 min)**

**Cilj:** Naučiti koristiti Google Campaign URL Builder

**Upute:**
1. Idite na: https://ga-dev-tools.google/campaign-url-builder/
2. Kreirajte UTM link za imaginarnu kampanju:
   - Stranica: https://mojshop.hr/proizvod
   - Source: instagram
   - Medium: social_organic
   - Campaign: spring_2024
3. Generirajte link i pogledajte rezultat
4. Razmislite: Kada bi koristili ovakav link?

📚 **FACILITATOR NOTES:**
Jednostavna hands-on aktivnost. Svi bi trebali uspjeti napraviti UTM link u nekoliko minuta.

📖 **Reference:**
- https://ga-dev-tools.google/campaign-url-builder/

---

### **BACKUP AKTIVNOST 4: Analytics Terminology Quiz (5 min)**

**Cilj:** Brza provjera razumijevanja pojmova

**Upute:**
Pročitaj definiciju, studentice pogađaju pojam:

1. "Postotak korisnika koji napuste stranicu bez interakcije" → **Bounce Rate**
2. "Vrijeme provedeno na stranici tijekom jednog posjeta" → **Session Duration**
3. "Broj stranica koje korisnik pregleda u jednom posjetu" → **Pages per Session**
4. "Posjetitelj koji se vraća na stranicu" → **Returning User**
5. "Posjetitelj koji je prvi put na stranici" → **New User**

📚 **FACILITATOR NOTES:**
Može se raditi kao natjecanje između grupa ili kao individualna aktivnost.

---

### **BACKUP AKTIVNOST 5: Real vs Fake Data (10 min)**

**Cilj:** Razviti kritičko razmišljanje o analytics podacima

**Upute:**
Prikaži ove scenarije i pitaj: "Je li ovo realno ili sumnjivo?"

1. **Stranica ima 100% bounce rate** - Sumnjivo (greška u trackingu)
2. **E-commerce ima 0.5% conversion rate** - Realno (industrija prosjek je 1-3%)
3. **Sav promet dolazi iz jedne zemlje** - Ovisi (lokalna tvrtka - OK, globalna - sumnjivo)
4. **Prosječna sesija traje 15 sekundi** - Sumnjivo (ili jako loš sadržaj)
5. **50% korisnika koristi Internet Explorer** - Sumnjivo (IE je ugašen)

📚 **FACILITATOR NOTES:**
Ova aktivnost uči studentice da budu kritične prema podacima. "Ako nešto izgleda čudno, vjerojatno i jest!"

---

### **BACKUP AKTIVNOST 6: Privacy Policy Scavenger Hunt (15 min)**

**Cilj:** Naučiti čitati privacy policy s GDPR perspektive

**Upute:**
1. Odaberite veliku stranicu (npr. Spotify, Netflix)
2. Pronađite njihovu Privacy Policy
3. Odgovorite na pitanja:
   - Koje podatke prikupljaju?
   - Koriste li Google Analytics?
   - Dijele li podatke s trećim stranama?
   - Kako možete zatražiti brisanje podataka?

📚 **FACILITATOR NOTES:**
Privacy policy-ji su dugi i komplicirani. Cilj je da studentice nauče tražiti ključne informacije, ne čitati cijeli dokument.

---

### **BACKUP AKTIVNOST 7: GA4 Exploration Challenge (15 min)**

**Cilj:** Slobodno istraživanje GA4 demo accounta

**Upute:**
1. Pristupite GA4 demo accountu
2. Imate 10 minuta za slobodno istraživanje
3. Napišite 3 stvari koje ste otkrili
4. Napišite 1 pitanje koje imate

📚 **FACILITATOR NOTES:**
Ova aktivnost funkcionira dobro jer studentice mogu istraživati vlastitim tempom. Na kraju napravite kratki debrief - što su pronašle?

---

## 📚 **DODATNI RESURSI ZA FACILITATORA**

### **Prije predavanja, pregledaj:**

1. **GA4 Demo Account** - Pristup i osnovna navigacija
   - https://support.google.com/analytics/answer/10993011

2. **Chrome Ekstenzije** - Testiraj instalaciju
   - Analytics Debugger
   - EditThisCookie
   - Ghostery

3. **GDPR Osnove** - Ako nisi siguran/na
   - https://gdpr.eu/what-is-gdpr/

### **Za tvoje dalje učenje:**

- Google Analytics Academy: https://analytics.google.com/analytics/academy/
- GA4 Measurement Protocol: https://www.thyngster.com/ga4-measurement-protocol-cheatsheet/
- HEART Framework: https://www.heartframework.com/

### **Pripremna lista:**

- [ ] Testiraj pristup GA4 demo accountu
- [ ] Instaliraj Chrome ekstenzije
- [ ] Provjeri rade li svi linkovi
- [ ] Pripremi backup stranicu ako neka ne radi
- [ ] Provjeri Wi-Fi u učionici (sve studentice trebaju pristup)

---

## 🎓 **UDEMY RESURSI ZA OVAJ DAN**

**Relevantne sekcije:**
Za ovu temu Udemy tečaj "Complete Web Designer" nema direktne lekcije o Google Analytics, ali za razumijevanje UX metrika pogledaj:
- Bilo koja sekcija o User Testing
- Sekcije o Design Critique

📖 **External Resources:**
- Google Analytics Support: https://support.google.com/analytics
- GA4 Demo Account: https://support.google.com/analytics/answer/10993011
- Campaign URL Builder: https://ga-dev-tools.google/campaign-url-builder/
- Ghostery (tracking checker): https://www.ghostery.com/

---

**KRAJ SINOPSISA - DAN 13** ✅

---

**NASTAVAK:** Dan 14 - Napredne GA4 funkcije, Goals & Events, HEART Framework, praktične vježbe
