# 📘 DAN 5 - INFORMATION ARCHITECTURE

## 🎯 **CILJEVI UČENJA:**

Na kraju ovog predavanja, studentice će moći:

1. Definirati što je Information Architecture (IA) i objasniti njenu ulogu u UX designu
2. Primijeniti 8 Dan Brown-ovih principa IA u praktičnom radu
3. Kreirati taxonomy za digitalni proizvod koristeći Post-it metodu
4. Organizirati sadržaj kroz hijerarhiju i navigation sustave
5. Dizajnirati sitemap koji prikazuje strukturu website-a ili aplikacije
6. Kreirati low-fidelity wireframe za homepage aplikacije
7. Razlikovati različite tipove navigacije (top, side, dropdown, breadcrumb...)
8. Provesti peer review wireframe-a s konstruktivnim feedbackom

---

## ⏰ **9:00-9:10 (10 min) - UVOD U DAN**

**Što reći studentima:**

"Dobro jutro! Danas ulazimo u svijet **Information Architecture** - disciplinu koja se bavi time kako organiziramo i strukturiramo sadržaj da korisnici lako pronađu ono što traže.

Zamislite biblioteku bez sustava - knjige bile bi raspršene, nema kategorija, nema načina da brzo nađete knjigu. IA je upravo taj sustav organizacije, ali za digitalne proizvode.

Danas ćemo raditi na vašem projektu **CraftEase** - web aplikaciji za DIY (Do-It-Yourself) radionice koja omogućuje korisnicima da se prijave na radionice, pregledavaju tutoriale i prate dostupnost alata i materijala u realnom vremenu."

**Pregled dana:**
- Prvo: Teorija - što je IA, principi, kako kreirati IA
- Drugo: Hands-on - taxonomy vježba s Post-it notesima
- Treće: Kreiranje sitemap-a i wireframe-a za vaš CraftEase projekt
- Četvrto: Peer review i finalizacija

---

## ⏰ **9:10-9:25 (15 min) - TEORIJA: UVOD U INFORMATION ARCHITECTURE**

### **Slajd 3: Summary**

Information Architecture (skraćeno **IA**) je praksa organiziranja i strukturiranja sadržaja na jasan i smislen način.

**Zašto je to važno?**
Zamislite da ulazite u shopping centar gdje nema znakova, nema plana, nema kategorija - sve je kaos. Nikad ne biste našli što tražite! IA osigurava da vaši korisnici mogu brzo i intuitivno navigirati kroz vaš website ili aplikaciju.

**Ključni elementi koje ćemo danas naučiti:**
- User flows (putanje korisnika)
- Sitemaps (mape strukture)
- Navigation menus (navigacijski izbornici)
- Content hierarchy (hijerarhija sadržaja)
- Labeling systems (sustavi označavanja)

Dobra IA poboljšava **usability** (upotrebljivost), smanjuje **frustraciju** korisnika i stvara pozitivno korisničko iskustvo.

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Information Architecture je kao tlocrt za kuću - prije nego počneš graditi, moraš znati gdje ide što. IA definira gdje će biti koji sadržaj, kako će korisnici navigirati između stranica, i kako će biti organizirani podaci.

Razlika između IA i UX design-a:
- **IA** = organizacija i struktura (gdje ide što)
- **UX design** = šire - cijelo korisničko iskustvo (kako se osjeća korisnik)

IA je **dio** UX procesa, ali fokusira se specifično na strukturu informacija.

**Česta pitanja:**

Q: "Zašto ne možemo samo dizajnirati bez IA?"
A: Možete, ali rizikujete da napravite app koji izgleda lijepo ali korisnici ne mogu pronaći ništa. IA osigurava da dizajn ima smisla za korisnike.

Q: "Koliko vremena treba posvetiti IA prije dizajna?"
A: Za manji projekt (5-10 stranica) možda 1-2 dana. Za veći projekt (50+ stranica) može biti i 1-2 tjedna. Pravilo: što je kompleksniji proizvod, više vremena treba IA.

**Troubleshooting:**
- **Problem**: Studentice misle da je IA samo "sitemap". 
  **Rješenje**: Objasni da sitemap je *dio* IA, ali IA uključuje i navigation, taxonomy, labeling, itd.

📖 **Linkovi za dublje razumijevanje:**
- [NN/g - Information Architecture Basics](https://www.nngroup.com/articles/information-architecture-sitemaps/)
- [Udemy teÄaj: Sekcija 4 - User Flows i Sitemaps](https://www.figma.com/templates/sitemap-generator/)

---

### **Slajd 4: Introduction to Information Architecture**

**Definicija IA:**
Information Architecture je proces kojim se sadržaj organizira i čini dostupnim korisnicima.

**IA uključuje:**
- Odlučivanje **gdje** će biti koji sadržaj
- Kreiranje **logičkih grupa** sadržaja
- Dizajniranje **navigacije** koja ima smisla

**Primjer:**
Netflix ima odličnu IA:
- Početna stranica → Kategorije (Akcija, Drama, Komedija)
- Svaka kategorija → Filmovi/serije
- Svaki film → Detalji, trailer, povezane preporuke

Sve je organizirano tako da brzo nađete što želite gledati.

**Razlika IA vs UX:**
- **IA** = struktura i organizacija (kosti kuće)
- **UX** = cijelo iskustvo (kako se kuća osjeća, izgleda, funkcionira)

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Najbolja analogija za IA je knjižnica:
- **IA librarian** odlučuje: koje kategorije će biti (Fikcija, Non-fikcija, Dječje knjige...)
- Gdje će biti svaka kategorija u prostoru
- Kako će biti označene police
- Kakav će biti sustav za traženje knjiga

Ista stvar za web: IA ekspert odlučuje gdje ide sadržaj, kako ga korisnici nalaze, kako je organiziran.

**Česta pitanja:**

Q: "Tko se bavi IA - UX designer ili netko drugi?"
A: U malim timovima, UX designer radi i IA. U velikim kompanijama postoje specijalizirani "Information Architects". Ali svaki UX designer mora znati IA basics.

Q: "Trebamo li raditi IA za svaki projekt?"
A: DA! Čak i za jednostavnu 3-page website. Možda ne treba detaljnog IA procesa, ali morate barem skicirati strukturu prije dizajna.

**Troubleshooting:**
- **Problem**: Studentice pitaju "Zašto se zove 'architecture'?"
  **Rješenje**: Jer gradimo strukturu - kao arhitekt gradi tlocrt kuće prije gradnje, IA gradi "tlocrt" sadržaja prije dizajna.

---

### **Slajd 5: Introduction to Information Architecture - 3 Pillars**

IA se temelji na **3 ključna elementa** (pokazati Venn dijagram na slajdu):

**1. USERS (Korisnici)** 🧑
- Tko će koristiti proizvod?
- Što su njihovi ciljevi?
- Što žele postići?

**2. CONTENT (Sadržaj)** 📄
- Koje informacije pružamo?
- Koliko sadržaja imamo?
- Kakve vrste sadržaja (tekst, slike, video)?

**3. CONTEXT (Kontekst)** 📱
- Gdje korisnici pristupaju sadržaju? (mobitel, desktop, tablet?)
- U kojoj situaciji? (doma, u pokretu, na poslu?)
- Koliko vremena imaju?

**Primjer - Netflix:**
- **Users**: Ljudi koji žele gledati filmove/serije (različite dobi, ukusi)
- **Content**: Tisuće filmova, serija, dokumentaraca
- **Context**: Gledaju na TV-u kod kuće, mobilnom u busu, tabletu u krevetu

Sva tri elementa moraju se balansirati za dobru IA!

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Ova 3 kruga (Users, Content, Context) su kao 3 noge stolice - sva tri moraju biti jaka da stolica stoji stabilno.

Primjer lošeg balansa:
- **Previše fokusa na Content**: Stavili ste sav sadržaj na web, ali korisnici ne mogu ništa pronaći jer nije organizirano.
- **Previše fokusa na Users**: Pokušavate zadovoljiti svaki mogući user scenario pa napravite prekompliciran sustav.

**Česta pitanja:**

Q: "Koji od 3 elementa je najvažniji?"
A: Sva tri su jednako važna! Ali ako moraš početi negdje, počni s **Users** - razumijevanje korisnika je temelj.

Q: "Kako saznajemo Context?"
A: User research! Intervjui, anketiranje, analytics (gdje pristupaju vašem siteu - desktop ili mobitel?).

**Troubleshooting:**
- **Problem**: Studentice ne razumiju razliku Content vs Context.
  **Rješenje**: Content = "ŠTO nudimo". Context = "GDJE i KADA korisnici to koriste".

📖 **Linkovi za dublje razumijevanje:**
- [User Context in UX Design](https://www.nngroup.com/articles/context-methods-study-guide/)

---

### **Slajd 6: Benefits of IA**

**Zašto ulagati vrijeme u IA? Evo 5 velikih benefita:**

**1. Povećanje conversion rate-a** 💰
- Korisnici lakše pronađu što trebaju → više kupnja/registracija
- Primjer: Amazon - lako pronađete proizvod → dodajete u košaricu → kupujete

**2. Jačanje kredibiliteta** ✅
- Čist, dobro organiziran website izgleda profesionalno
- Korisnici vam više vjeruju

**3. Poboljšanje produktivnosti** ⚡
- Zaposlenici znaju gdje dodati novi sadržaj
- Lakše održavanje website-a

**4. Boost SEO (optimizacija za tražilice)** 🔍
- Google voli dobro organizirane website-e
- Bolja struktura = bolji ranking u Google rezultatima

**5. Smanjenje troškova customer service-a** 💬
- Korisnici mogu sami riješiti probleme jer lako pronađu FAQ, Help sekciju, tutorial
- Manje poziva/emailova support timu

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Ovi benefiti pokazuju da IA nije samo "lijepo za imati" - direktno utječe na business rezultate.

Real-world primjer:
- **Loša IA**: E-commerce site gdje ne možete lako pronaći kategoriju "Muške cipele" → frustrirani korisnici odlaze → gubite novac
- **Dobra IA**: Jasna navigacija "Muško → Cipele → Sportske cipele" → korisnici brzo pronađu → kupuju

**Česta pitanja:**

Q: "Kako IA pomaže SEO-u?"
A: Google roboti ("crawlers") pregledavaju vaš website. Ako je dobro organiziran s jasnom strukturom i logičkim linkovima, Google lakše indeksira stranice → bolje rangiranje.

Q: "Je li IA jednokratni posao ili kontinuirani proces?"
A: **Kontinuirani proces**! Kako vaš business raste, dodaje se sadržaj, mijenjaju se user potrebe → IA se mora ažurirati.

**Troubleshooting:**
- **Problem**: Studentice pitaju "Kako dokazati vlasniku biznisa da IA vrijedi investiciju?"
  **Rješenje**: Fokusiraj se na conversion rate i customer service troškove - to su direktni $$$. Možeš pokazati A/B testove prije/poslije IA.

---

## ⏰ **9:25-9:45 (20 min) - TEORIJA: 8 PRINCIPA INFORMATION ARCHITECTURE**

### **Slajd 7: 8 Principles of IA - Introduction**

2010. godine, **Dan Brown** (osnivač EightShapes studija) kreirao je **8 principa Information Architecture** koji pomažu designerima donositi dobre odluke o organizaciji sadržaja.

Ovih 8 principa su kao "pravila igre" - pomoći će vam da ne napravite česte greške pri strukturiranju website-a ili aplikacije.

Idemo kroz svih 8!

---

### **Slajd 8: Principles 1-4**

**PRINCIP 1: OBJECTS (Objekti)** 🧩
_"Content should be treated as a living, breathing thing. It has lifecycles, behaviors, and attributes."_

Tretirajte sadržaj kao živi organizam:
- **Lifecycle**: Sadržaj se kreira, ažurira, arhivira, briše
- **Behaviors**: Sadržaj se može filtrirati, sortirati, tagirati
- **Attributes**: Svaki sadržaj ima properties (autor, datum, kategorija...)

**Primjer**: Blog post
- **Lifecycle**: Objavljen → Editiran → Arhiviran nakon godinu dana
- **Behaviors**: Može se filtrirati po kategoriji, pretraživati, sortirati po datumu
- **Attributes**: Naslov, autor, datum objave, kategorija, tagovi

---

**PRINCIP 2: CHOICES (Izbori)** ✂️
_"Less is more. Keep the number of choices to a minimum."_

**Manje je više!** Previše opcija paralizira korisnike.

**Primjer - LOŠE:**
Homepage s 20 linkova u glavnom menu → korisnik ne zna gdje kliknuti → odlazi

**Primjer - DOBRO:**
Homepage s 5-7 glavnih kategorija → jasno i jednostavno

**Pravilo:** 7±2 stavki u menu (psihološka granica za ljudsku memoriju)

---

**PRINCIP 3: DISCLOSURE (Otkrivanje)** 🔍
_"Show a preview of information that will help users understand what kind of information is hidden if they dig deeper."_

Dajte korisnicima **preview** što će pronaći ako kliknu dalje.

**Primjer - LOŠE:**
Link "Više informacija" (korisnik ne zna što će dobiti)

**Primjer - DOBRO:**
Link "Pogledaj galeriju (15 fotografija)" → korisnik točno zna što ga čeka

**Tehnike:**
- Tooltips (hover efekt s dodatnim info)
- Kratki descriptions ispod linkova
- Thumbnail slike prije full galerije

---

**PRINCIP 4: EXEMPLARS (Primjeri)** 💡
_"Show examples of content when describing the content of the categories."_

Kada opisujete kategoriju, **pokažite primjere** što je unutra.

**Primjer - LOŠE:**
Kategorija "Proizvodi" (korisnik ne zna što prodajete)

**Primjer - DOBRO:**
Kategorija "Proizvodi (npr. iPhone, MacBook, iPad)" → jasno

**Ili:**
Hover preko "Odjeća" → pojavi se mega-menu s thumbnail slikama: Majice, Hlače, Jakne...

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**

**Princip Objects** je o tome da shvatiš sadržaj kao dinamičnu stvar, ne statičnu. To znači da pri planiranju IA moraš misliti: "Hoće li ovaj content rasti? Hoće li korisnici moći filtrirati? Trebaju li tagovi?"

**Princip Choices** temelji se na Hick's Law (psihologija): što više opcija daš ljudima, duže im treba da odluče. Amazon ima tisuće proizvoda, ali homepage ima samo 10-ak glavnih kategorija.

**Princip Disclosure** je kao "trailer" za film - daš ljudima dovoljno info da znaju hoće li im se svidjeti, ali ne otkriva sve odmah.

**Princip Exemplars** pomaže korisnicima da brzo skeniraju i pronađu što traže. Posebno važno za e-commerce.

**Česta pitanja:**

Q: "Koliko je 'premalo' a koliko 'previše' choices?"
A: Pravilo 7±2: 5-9 glavnih opcija u navigaciji. Ako imaš više, grupiranje u podkategorije.

Q: "Što ako imam 100 kategorija proizvoda?"
A: Grupiranje! Npr. "Elektronika" → Mobiteli, Laptopi, Kamere... svaka s primjerima.

**Troubleshooting:**
- **Problem**: Studentice ne razumiju razliku Objects vs Content.
  **Rješenje**: Content = stvarni tekst/slike. Objects = način na koji tretiraš taj content (može li se tagirati? filtrirati? arhivirati?).

---

### **Slajd 9: Principles 5-8**

**PRINCIP 5: FRONT DOORS (Ulazna vrata)** 🚪
_"Assume that at least 50% of users will use a different entry point than the home page."_

**50% korisnika NEĆE doći na homepage!**

Doći će kroz:
- Google search → direktno na blog post
- Social media link → na specifičnu stranicu
- Email link → na proizvod

**Što to znači za IA:**
Svaka stranica mora biti self-contained:
- Jasna navigacija na svakoj stranici
- Logo link natrag na homepage
- Breadcrumbs (puteljak) da korisnik zna gdje je

---

**PRINCIP 6: MULTIPLE CLASSIFICATIONS (Višestruke klasifikacije)** 🗂️
_"Offer users several different classification schemes to browse the site's content."_

Ponudite **više načina** pretraživanja istog sadržaja.

**Primjer - Netflix:**
- Po žanru (Akcija, Drama, Komedija)
- Po godini (Novi naslovi, Klasici)
- Po popularity (Trending, Top 10)
- Po tvom watch history (Za tebe)

**Primjer - E-commerce odjeća:**
- Po kategoriji (Majice, Hlače, Cipele)
- Po brandu (Nike, Adidas, Puma)
- Po cijeni (Do 100kn, 100-500kn, 500+kn)
- Po boji, veličini, stilu...

---

**PRINCIP 7: FOCUSED NAVIGATION (Fokusirana navigacija)** 🎯
_"Keep navigation simple and never mix different things."_

**Navigacija mora biti jednostavna. Nemoj miješati različite stvari.**

**Primjer - LOŠE:**
Menu: O nama | Proizvodi | Blog | Prijava | Facebook | Newsletter

(Miješaš: informativne stranice + funkcije + social media + forms)

**Primjer - DOBRO:**
**Glavni menu**: O nama | Proizvodi | Blog  
**Sekundarni menu (gore desno)**: Prijava | Registracija  
**Footer**: Facebook, Instagram, Newsletter signup

---

**PRINCIP 8: GROWTH (Rast)** 📈
_"Assume that the content on the website will grow. Make sure the website is scalable."_

**Planiraj za budućnost!** Sadržaj će se povećavati.

**Pitanja koje si moraš postaviti:**
- Što ako umjesto 10 proizvoda imam 1000?
- Što ako umjesto 5 blog postova imam 500?
- Hoće li moja IA i dalje funkcionirati?

**Primjer:**
Ako danas imaš 3 kategorije proizvoda, ali za godinu dana možeš imati 20 → planiraj strukturu koja to može izdržati (filtering, search, subkategorije).

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**

**Princip Front Doors** je često zanemarivan! Ljudi misle da svi korisnici počinju na homepage. U stvarnosti, Google često dovodi korisnike direktno na "duboke" stranice. Zato svaka stranica mora imati context (breadcrumbs, clear navigation).

**Princip Multiple Classifications** temelji se na činjenici da različiti korisnici traže na različite načine. Neki traže po brandu, neki po cijeni, neki po kategoriji. Daj im sve opcije.

**Princip Focused Navigation** je važan jer confusion = abandonment. Ako je menu kaotičan, korisnici odlaze.

**Princip Growth** često se zaboravi - napraviš IA za trenutno stanje, ali za godinu dana imaš 10x više content-a i struktura se ruši. Uvijek planiraj scalability.

**Česta pitanja:**

Q: "Kako testirati da li moja IA može 'rasti'?"
A: Napravi simulaciju: "Što ako dodamo 50 novih proizvoda? Gdje bi oni išli? Može li trenutna struktura to izdržati?"

Q: "Koliko je 'previše' načina klasifikacije (princip 6)?"
A: Ponudi 3-5 načina filtriranja/klasifikacije. Više od toga postaje overwhelming.

**Troubleshooting:**
- **Problem**: Studentice pitaju "Kako znati hoće li content rasti?"
  **Rješenje**: Razgovaraj s klijentom/stakeholderima: "Planirate li dodavati proizvode? Koliko?" Uvijek pretpostavi da ĐćE rasti.

📖 **Linkovi za dublje razumijevanje:**
- [Dan Brown's 8 Principles - Medium Article](https://medium.com/@izharul/dan-browns-eight-useful-principles-of-information-architecture-b31bd019917d)

---

## ⏰ **9:45-10:00 (15 min) - TEORIJA: HOW TO CREATE IA**

### **Slajdovi 10-12: Step-by-Step Process**

Sada kada znate principe, idemo vidjeti **konkretni proces** kako napraviti IA za projekt.

**8 KORAKA:**

**KORAK 1: Definiraj ciljeve stakeholdera** 🎯
- Što klijent želi postići? (više prodaje? više registracija?)
- Tko je primarna publika?
- Koje funkcionalnosti su potrebne? (search? forms? download?)

**KORAK 2: Identificiraj user ciljeve** 👤
- Što korisnici žele postići na ovom siteu?
- User research: intervjui, ankete
- **Ključno**: Organiziraj content prema user potrebama, ne prema internoj strukturi kompanije!

**Primjer - LOŠE:** Organizacija prema odjelima kompanije (Marketing odjel, Sales odjel, HR odjel)  
**Primjer - DOBRO:** Organizacija prema user potrebama (Proizvodi, Podrška, O nama)

---

**KORAK 3: Definiraj content area-e** 📄
- Pregledaj postojeći content (ako redesign)
- Identificiraj novi content koji je potreban
- Odluči: što zadržati, što ažurirati, što izbaciti

---

**KORAK 4: Organiziraj content u grupe** 🗂️
- **Card sorting metoda**: Napiši svaki content na karticu, grupiraj povezane stvari
- Kreiraj široke kategorije i subkategorije

**Primjer:**
```
Proizvodi
├── Muška odjeća
│   ├── Majice
│   ├── Hlače
│   └── Jakne
└── Ženska odjeća
    ├── Haljine
    ├── Suknje
    └── Bluze
```

---

**KORAK 5: Kreiraj sitemap** 🗺️
- Vizualna reprezentacija strukture site-a (figma-template)[https://www.figma.com/community/file/1205181403296341187/sitemap]
- Prikaži parent-child odnose između stranica
- Osiguraj logičnu navigaciju

---

**KORAK 6: Outline navigation strukture** 🧭
- Horizontal ili vertical navigation?
- Koji main menu items?
- Trebaju li mega-menus?

---

**KORAK 7: Labeling - označi content jasno** 🏷️
- Koristi jasne, koncizne labele
- Testiraj s korisnicima: razumiju li što labela znači?

**Primjer - LOŠE:** "Solutions" (previše vague)  
**Primjer - DOBRO:** "Software Products"

---

**KORAK 8: Razvij wireframes** ✏️  (figma-template)[https://www.figma.com/community/file/900479694578549256/mobile-wireframe-ui-kit]
- Skiciraj page layout-e
- Definiraj gdje ide menu, header, footer
- Placeholderi za content

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Ovaj 8-step proces nije striktno linearan - često ćeš skakati naprijed-natrag. Npr. u koraku 7 (labeling) shvatiš da tvoja struktura iz koraka 5 (sitemap) ne funkcionira → vraćaš se i mijenjaj.

Real-world scenario:
- Klijent ti kaže "Želim website s 50 stranica."
- Počinješ s korak 1: razgovor s klijentom o ciljevima.
- Korak 2: user research (možda discovery workshop s korisnicima).
- Korak 3-4: Radiš content inventory i grupiranje (možda 2-3 dana posla).
- Korak 5: Kreiraš sitemap u tool-u kao Figma ili Miro.
- Korak 6-7: Definiraj navigation i labeling.
- Korak 8: Wireframes (to je već sljedeća faza projekta).

**Česta pitanja:**

Q: "Koliko dugo traje ovaj proces?"
A: Ovisi o veličini projekta. Mali site (10-20 stranica) = 1 tjedan. Veliki complex site (100+ stranica) = 3-4 tjedna ili više.

Q: "Trebam li raditi sve korake za svaki projekt?"
A: Za veće projekte DA. Za mali 5-page website možeš "preskočiti" formalni proces ali bi barem trebao skicirati sitemap.

**Troubleshooting:**
- **Problem**: Studentice u koraku 4 (organize content) ne znaju kako grupirati.
  **Rješenje**: Preporuči Post-it metodu (što ćemo raditi danas!) ili online tool kao Miro za card sorting.

---

## ⏰ **10:00-10:15 (15 min) - PAUZA ☕**

"Pauza 15 minuta! Odmorite se, popijte kavu. U 10:15 nastavljamo s hands-on vježbom!"

---

## ⏰ **10:15-10:20 (5 min) - KRATAK UVOD U TAXONOMY**

### **Slajd 13: Hierarchization**

**Information hierarchy** (informacijska hijerarhija) = organizacija sadržaja na način koji omogućuje korisnicima da lako navigiraju i razumiju.

Hijerarhija znači: **što je važnije = viša razina**.

**Primjer:**
```
Homepage (razina 1)
├── Proizvodi (razina 2)
│   ├── Laptopi (razina 3)
│   │   ├── Gaming laptopi (razina 4)
│   │   └── Business laptopi (razina 4)
```

**Pravilo:** Ne idi dublje od 3-4 razine (korisnici se izgube).

---

### **Slajd 14-15: Navigation Types**

Postoji **mnogo tipova navigacije**. Najčešći:

- **Top Navigation**: Horizontal menu na vrhu (za content-heavy websites)
- **Side Navigation**: Vertical menu lijevo/desno (za quick access)
- **Dropdown Navigation**: Menu se otvara na klik (za feature-rich apps)
- **Hamburger Menu**: 3 crte (☰) - za mobile apps
- **Bottom Bar Navigation**: Menu na dnu (mobilne app, brz pristup key features)
- **Breadcrumb Navigation**: Puteljak gdje si (Home > Proizvodi > Laptopi)

Nećemo ulaziti duboko u svaki tip, ali važno je da znate da postoje opcije!

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Navigation type ovisi o tome što gradiš:
- **Website s puno sadržaja** (news site) → Top Navigation + Breadcrumbs
- **Mobile app** → Bottom Bar ili Hamburger
- **Dashboard/SaaS app** → Side Navigation

**Česta pitanja:**

Q: "Koji navigation type je najbolji?"
A: Ovisi o kontekstu! Nema "najboljeg" - ovisi o uređaju (mobile vs desktop), količini sadržaja, user behavioru.

---

## ⏰ **10:20-11:00 (40 min) - HANDS-ON VJEŽBA: TAXONOMY & CLASSIFICATION**

### **Slajd 18: Taxonomy & Classification - Introduction**

**Taxonomy** = znanost klasifikacije. U UX-u, taxonomy znači grupiranje informacija u relevantne kategorije.

Zašto je važno?
- Korisnici brzo pronađu što traže
- Sadržaj je logično organiziran
- Scalable (može rasti)

**Primjer:**
```
Vehicles (root)
├── Shared (kategorija)
│   ├── Buses
│   ├── Trains
│   └── Planes
├── Personal (kategorija)
│   ├── Car
│   ├── Bicycle
│   └── Motorcycle
```

Danas ćete kreirati taxonomy za **CraftEase** projekt koristeći **Post-it metodu**!

---

### **CraftEase Projekt - Podsjetnik**

**Što reći studentima (2 min):**

**CraftEase** je web aplikacija za home improvement retailers (trgovine koje prodaju alate, materijale za DIY).

**Cilj aplikacije:**
- Omogućiti korisnicima da se prijave na DIY radionice (npr. "Kako položiti podne pločice", "Bojanje zidova 101")
- Pregledavaju project tutoriale (video, step-by-step upute)
- Provjere real-time dostupnost alata i materijala u trgovini

**Ciljna publika:** 
- Početnici u DIY-u (ljudi koji žele naučiti)
- Hobbyisti koji vole raditi sami

**Platforme:**
- Primarno web (desktop i mobitel)
- Možda kasnije app

---

### **VJEŽBA: Post-it Taxonomy za CraftEase**

**Trajanje:** 35 min (5 koraka)

**Materijali:**
- Post-it notes (različite boje ako imate)
- Whiteboard ili velika površina na zidu
- Markeri

---

### **KORAK 1: Brainstorm Content (7 min)**

**Upute za studentice:**

"U sljedećih 7 minuta, svaka od vas će **napisati po jedan topic na jedan Post-it note**.

**Teme mogu biti:**
- Materijali (npr. "Drvo", "Vijci", "Boja")
- Alati (npr. "Bušilica", "Čekić", "Ljestve")
- Radionice (npr. "Polaganje pločica", "Bojanje zidova")
- Tutoriali/Članci (npr. "Kako odabrati pravu boju", "10 DIY projekata za početnike")
- Funkcionalnosti (npr. "Prijava na radionicu", "Provjera dostupnosti")
- Kategorije sadržaja (npr. "Video tutoriali", "PDF vodiči")

**Pravila:**
- **Jedan topic = jedan Post-it**
- Pišite jasno (velim slovima)
- Ne razmišljajte previše - nabacajte ideje!
- Lijepi Post-it notes na whiteboard nasumično

**Cilj:** Prikupiti što više ideja (svatko barem 5-10 Post-it notes)."

**[Timer: 7 minuta]**

📚 **FACILITATOR NOTES:**

**Kako voditi:**
- Cirkuliraj po razredu, ohrabruj studentice da nastave pisati
- Ako netko zapne, predloži: "Razmisli - što bi korisnik želio raditi u DIY app-u? Što bi mu bilo korisno?"
- Na kraju: trebalo bi biti 50-100+ Post-it notes na whiteboardu (barem 5-8 per osoba x 8-30 studentica)

**Troubleshooting:**
- **Problem**: Studentice pišu preširoke kategorije ("Content", "Funkcionalnosti").
  **Rješenje**: "Budi specifičnija - umjesto 'Alati', napiši konkretne alate: Bušilica, Čekić..."
- **Problem**: Previše se fokusiraju na jednu kategoriju.
  **Rješenje**: "Razmislite i o drugim aspektima: ne samo proizvodi, nego i radionice, tutorials, user account features..."

---

### **KORAK 2: Group Similar Ideas (10 min)**

**Upute za studentice:**

"Sada ćemo **grupirati** slične Post-it notes.

**Kako:**
1. Kao grupa, počnite prepoznavati **patterns** - koji Post-it notes idu zajedno?
2. Premještajte Post-it notes blizu jedni drugima ako su slični
3. Ne forsirajte kategorije još - samo logično grupirajte

**Primjer:**
Ako imate Post-it notes "Bušilica", "Čekić", "Ljestve", "Brusilica" → stavite ih zajedno (to su svi Alati).

**[Timer: 10 minuta]**

Počnite!"

📚 **FACILITATOR NOTES:**

**Kako voditi:**
- Hodaj oko grupa, promatraj kako razmišljaju
- Ako vidiš da neka grupa skuplja nelogične stvari zajedno, pitaj: "Zašto ste stavili X i Y zajedno? Jesu li povezani?"
- Ohrabruj diskusiju - nema točnog/krivog, nego razmjena mišljenja
- Nakon 7 min, daj warning: "Još 3 minute!"

**Što promatrati:**
- Jesu li grupe previše velike? (npr. sve stavili u jednu gomilu) → predloži da razbiju u manje grupe
- Jesu li grupe premale? (svaki Post-it svoja grupa) → predloži da pronađu povezanosti

**Troubleshooting:**
- **Problem**: Grupa se ne slaže gdje ide jedan Post-it note.
  **Rješenje**: "U redu je! Možeš staviti Post-it note između dvije grupe ili duplicirati (napisati drugi Post-it s istim tekstom) ako ide u obje kategorije."

---

### **KORAK 3: Define Main Categories (8 min)**

**Upute za studentice:**

"Sada definirajte **4-6 glavnih kategorija** iz vaših grupa.

**Kako:**
1. Pogledajte grupe koje ste stvorili
2. Za svaku grupu, smislite **ime kategorije** koje najbolje opisuje grupu
3. Napišite ime kategorije na **novi Post-it note (možda drugačija boja)** i stavite ga **iznad/na vrh** te grupe

**Primjeri mogućih kategorija za CraftEase:**
- Radionice (Workshops)
- Alati (Tools)
- Materijali (Materials)
- Tutoriali (Tutorials)
- Korisnički Profil (User Account)
- O Trgovini (About Store)

**Cilj:** 4-6 broad categories (ne više od 6!)

**[Timer: 8 minuta]**

Počnite!"

📚 **FACILITATOR NOTES:**

**Kako voditi:**
- Podsjetnik: 4-6 kategorija je optimalno. Ako imaju 10+, predloži da spoje neke.
- Ohrabruj da imena kategorija budu **user-friendly** (ne tehnički žargon)

**Primjer DOBRIH kategorija:**
- "Radionice" (jasno)
- "Alati" (jasno)
- "Tutoriali" (jasno)

**Primjer LOŠIH kategorija:**
- "Content" (previše vague)
- "Stuff" (nespecifično)
- "Backend Features" (tehnički, ne user-facing)

**Troubleshooting:**
- **Problem**: Grupa ima 12 kategorija.
  **Rješenje**: "Možete li spojiti neke? Npr. 'Video tutoriali' i 'PDF vodiči' mogu biti pod jednu kategoriju 'Tutoriali'."

---

### **KORAK 4: Refine Subcategories (8 min)**

**Upute za studentice:**

"Sada refinirajte - stavite **specifične Post-it notes pod relevantnu glavnu kategoriju**.

**Kako:**
1. Uzmite Post-it notes iz svake grupe
2. Poredajte ih **ispod** glavne kategorije (kao tree struktura)
3. Ako nešto ne paše, **premjestite** ili **preimenujte**

**Primjer strukture:**
```
RADIONICE
├── Polaganje pločica
├── Bojanje zidova
├── Montaža regala

ALATI
├── Bušilica
├── Čekić
├── Ljestve
```

**[Timer: 8 minuta]**

Ajmo!"

📚 **FACILITATOR NOTES:**

**Kako voditi:**
- Provjeravaj da struktura ima smisla
- Ako vidiš "Bušilica" pod "Radionice" → pitaj: "Jestesite sigurni da to ide ovdje?"
- Neki Post-it notes mogu ići u 2 kategorije - to je OK! Mogu duplicirati.

**Troubleshooting:**
- **Problem**: Jedna kategorija ima 30 Post-it notes, ostale po 2-3.
  **Rješenje**: "Možete li razbiti tu veliku kategoriju u subkategorije?"

---

### **KORAK 5: Validate & Adjust (2 min)**

**Upute za studentice:**

"Zadnji korak: Zamislite da ste korisnik.

**Postavite si pitanja:**
- 'Gdje bih našao radionicu za bojanje zidova?' (Kategoriaj 'Radionice'? → Trebalo bi biti tu!)
- 'Kako provjeriti ima li trgovina bušilice na skladištu?' (Alati → Bušilica → Check dostupnost?)
- 'Gdje mogu vidjeti svoje prijave na radionice?' (Korisnički Profil?)

Ako nešto nije jasno ili je na krivom mjestu → **ajustirajte**!"

**[2 minute za quick review]**

📚 **FACILITATOR NOTES:**

**Što raditi nakon vježbe:**
- **Fotografiraj svaki grupni whiteboard** (dokazni materijal za projekt!)
- Ako imate vremena, neka jedna ili dvije grupe prezentiraju svoju taxonomy (2 min prezentacija)

**Cilj vježbe:**
Ne mora biti "savršeno" - cilj je da studentice razumiju proces grupiranja i kategorizacije. Real-world scenario: radile bi card sorting s pravim korisnicima.

---

## ⏰ **11:00-11:15 (15 min) - PAUZA ☕**

"Odličan posao na taxonomy vježbi! Pauza 15 min. Vidimo se u 11:15 za nastavak!"

---

## ⏰ **11:15-11:25 (10 min) - TEORIJA: NAVIGATION & BREADCRUMB**

### **Slajd 16: Breadcrumb - Introduction**

**Breadcrumb navigation** (puteljak) = sekundarni navigation aid koji pokazuje korisniku **gdje se nalazi** na website-u.

**Zašto se zove "breadcrumb"?**
Iz bajke **Hansel i Gretel** - djeca bacaju mrvice kruha (breadcrumbs) kroz šumu da pronađu put kući. Isto tako, breadcrumb na websiteu pokazuje put natrag na homepage.

**Kako izgleda:**
```
Home > Proizvodi > Laptopi > Gaming Laptopi > Asus ROG
```

Svaki dio je **klikabilan link** → možeš se vratiti na bilo koju razinu.

**Pravila za breadcrumbs:**
1. **Ne zamjenjuju glavni menu** - oni su DODATAK
2. **Ne koristi ih za jednostavne site-ove** (ako imaš samo 3 stranice, ne treba ti breadcrumb)
3. **Koristi ih za complex site-ove** s više razina hijerarhije (e-commerce, dokumentacija, news site)

**Primjer - Guardian News:**
(Pokazati slajd 17 ako imaš screenshot)

Breadcrumb: `Home > Culture > TV & Radio > Show Details`

→ Korisnik odmah zna gdje je i može kliknuti "Culture" da vidi sve Culture člantke.

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Breadcrumbs su posebno korisni kada korisnici dolaze kroz Google search direktno na "duboku" stranicu. Bez breadcrumba, bili bi zbunjeni gdje su. S breadcrumbom, instantly znaju context.

**Česta pitanja:**

Q: "Treba li svaki website breadcrumb?"
A: NE. Samo ako imaš **3+ razine** dubine. Website s 5 stranica ne treba breadcrumb.

Q: "Gdje staviti breadcrumb - gore ili dolje?"
A: **Gore, ispod glavnog menua** - to je standard. Korisnici očekuju ga tamo.

**Troubleshooting:**
- **Problem**: Studentice ne razumiju kada koristiti breadcrumb.
  **Rješenje**: Pravilo: Ako imaš više od 3 razine dubine (Home → Category → Subcategory → Product), koristi breadcrumb.

📖 **Linkovi za dublje razumijevanje:**
- [Breadcrumb Navigation Best Practices - Smashing Magazine](https://www.smashingmagazine.com/2022/04/breadcrumbs-ux-design/)

---

## ⏰ **11:25-11:35 (10 min) - TEORIJA: INFORMATION MAPPING (SITEMAP)**

### **Slajd 24-25: Information Mapping - Sitemap**

**Sitemap** = vizualna reprezentacija strukture website-a ili app-a. Pokazuje kako su stranice povezane (parent-child odnosi).

**Zašto je važan?**
- Daje **bird's-eye view** cijele strukture
- Pomaže timu (dizajnerima, developerima, klijentima) da vide kompletan plan
- Identificira missing pages ili probleme u strukturi

**Struktura sitemap-a:**
```
Homepage (Level 1)
├── O nama (Level 2)
├── Proizvodi (Level 2)
│   ├── Laptopi (Level 3)
│   ├── Mobiteli (Level 3)
│   └── Tableti (Level 3)
├── Blog (Level 2)
└── Kontakt (Level 2)
```

**Tool-ovi za kreiranje sitemap-a:**
- **Figma** (možeš crtat manually)
- **Diagrams.net** (besplatno, jednostavno) → https://app.diagrams.net/
- **SmartDraw** → https://www.smartdraw.com/software/tree-diagram-maker.htm
- **Miro** (collaborative whiteboard)

**[Pokažite primjer sitemap-a na slajdu ili screenshare diagrams.net]**

**Zadatak za sljedeći korak:**
Nakon što napravimo wireframe, studentice mogu kreirati sitemap za CraftEase (ali to je za kasnije, možda kao homework).

📚 **FACILITATOR NOTES:**

**Za tvoje razumijevanje:**
Sitemap je kao blueprint za kuću - prije nego počneš graditi, moraš imati plan.

Real-world workflow:
1. IA research (user goals, content inventory)
2. Card sorting / Taxonomy (što smo radili danas)
3. **Sitemap creation** (struktura stranica)
4. Wireframing (layout individual pages)
5. Hi-fi design

**Česta pitanja:**

Q: "Koliko razina dubine je previše?"
A: Pravilo: **3-4 razine max**. Ako ideš dublje (Level 5, 6...), korisnici će se gubiti. Radije reorganizuj strukturu.

Q: "Trebam li staviti SVE stranice u sitemap?"
A: Za početni sitemap: stavi main pages. Za detailed sitemap: možeš dodati i subpages, ali može postati overwhelming.

**Troubleshooting:**
- **Problem**: Studentice ne znaju koji tool koristiti.
  **Rješenje**: Za početnike, preporuči **diagrams.net** - besplatno, intuitivno, nema registraciju.

📖 **Linkovi za dublje razumijevanje:**
- [Diagrams.net Tutorial](https://www.diagrams.net/)
- [Udemy Sekcija 4: Sitemaps](https://uxmentor.me/sitemaps-the-beginners-guide/)

---

## ⏰ **11:35-12:00 (25 min) - HANDS-ON VJEŽBA: LOW-FIDELITY WIREFRAME**

### **Slajd 26-27: Low-Fidelity Wireframes - Introduction**

**Low-fidelity wireframe** (skraćeno: **lo-fi wireframe**) = osnovna skica interface-a. Fokus na **funkcionalnost**, ne na vizualni dizajn.

**Karakteristike:**
- **Jednostavni oblici** (pravokutnici, krugovi, linije)
- **Bez boja** (sivo, crno-bijelo)
- **Bez pravog teksta** (placeholderi: "Logo", "Button", "Text")
- **Bez slika** (samo box s X unutra kao placeholder)

**Razlika low-fi vs high-fi:**
- **Low-fi**: Brza skica, fokus na layout i strukturu
- **High-fi**: Detaljni dizajn s bojama, fontovima, slikama

**(Pokazati slajd 27 - usporedba low-fi vs high-fi)**

**Zašto koristiti low-fi?**
- **Brzo** - možeš nacrtati u 10-15 minuta
- **Fleksibilno** - lako mijenjati
- **Fokus na strukturu** - ne gubiš vrijeme na boje/fontove
- **Idealno za testiranje** early concepts s korisnicima ili timom

**Alati:**
- **Papir i olovka** (najbrže!)
- **Figma** (digitalno)
- **Balsamiq** (specijaliziran za wireframing)

---

### **VJEŽBA: Design CraftEase Homepage (Low-Fi Wireframe)**

**Trajanje:** 20 min

**Cilj:**
Svaka studentica će kreirati **low-fidelity wireframe za homepage CraftEase aplikacije**.

**Što homepage treba omogućiti:**
1. **Registracija za DIY radionice** - korisnik vidi listu radionica i može se prijaviti
2. **Browse project tutorials** - korisnik vidi tutoriale (video ili članci)
3. **Check real-time tool/material availability** - korisnik može provjeriti je li alat/materijal dostupan u trgovini

---

**Upute za studentice (3 min):**

"U sljedećih 20 minuta, svaka će kreirati **low-fidelity wireframe za CraftEase homepage**.

**Možete koristiti:**
- **Papir i olovka** (najbrže!)
- **Figma** ili **Balsamiq** (ako vam je draže digitalno) → Link: https://balsamiq.com

**Što nacrtati:**

**1. Header (vrh stranice):**
- Logo (napiši "LOGO" u box)
- Navigation menu (napiši stavke: Home, Radionice, Tutoriali, Alati, O nama, Kontakt)
- Search bar (pravokutnik s ikonom povećalo)
- Login/Register buttons (dva buttona)

**2. Hero sekcija (ispod headera):**
- Velika slika/ilustracija (napravi box s X unutra - placeholder)
- Heading text (napiši "Heading")
- Subheading text
- Call-to-action button ("Pregledaj radionice")

**3. Sekcija: Nadolazeće radionice:**
- Naslov: "Nadolazeće radionice"
- 3-4 kartice radionica (svaka kartica ima: slika placeholder, naslov, datum, "Prijavi se" button)

**4. Sekcija: Featured Tutoriali:**
- Naslov: "Featured Tutoriali"
- 3 kartice tutoriala (slika placeholder, naslov, kratak opis)

**5. Sekcija: Provjeri dostupnost alata:**
- Search bar ("Pretraži alat...")
- Button ("Provjeri")
- Text: "Trenutno dostupno: 23 alata"

**6. Footer (dno stranice):**
- Links: O nama, Kontakt, Uvjeti korištenja, Privacy
- Social media ikone (Facebook, Instagram)

**Koristite:**
- **Pravokutnike** za boxes, buttons, text areas
- **Krugove** za ikone
- **Linije** za separaciju sekcija
- **Labelirajte** sve (napiši "Button", "Image", "Text", "Logo"...)

**Pravila:**
- Bez boja (samo crno/sivo/bijelo)
- Bez pravog teksta (placeholderi: "Heading", "Lorem ipsum...")
- Fokus na **layout** - gdje ide što

**[Timer: 20 minuta]**

Počnite!"

📚 **FACILITATOR NOTES:**

**Kako voditi:**
- Cirkuliraj po razredu, provjeravaj progress
- Podsjeć da ne trebaju biti "umjetnička djela" - to je rough sketch!
- Ako netko zapne, pomozi s pitanjima:
  - "Što je prva stvar koju korisnik vidi? (Hero sekcija?)"
  - "Gdje bi bio najbolji položaj za 'Prijavi se na radionicu' button?"
- Nakon 15 min, daj warning: "Još 5 minuta!"

**Što promatrati:**
- Je li struktura logična? (Header → Hero → Sections → Footer)
- Ima li premalo/previše sadržaja na homepage?
- Je li navigation jasan?

**Troubleshooting:**
- **Problem**: Studentica pokušava crtati detaljne ilustracije.
  **Rješenje**: "Ne trebaju detalji! Samo napravi box s X unutra - to je placeholder. Fokusiraj se na layout, ne na ljepotu."
- **Problem**: Wireframe je prekompliciran (10+ sekcija).
  **Rješenje**: "Homepage ne treba sve! Odaberi 3-4 najvažnije sekcije. Ostalo može biti na drugim stranicama."
- **Problem**: Ne zna odakle početi.
  **Rješenje**: "Počni odozgo: Logo i menu na vrh. Onda pitaj se: Što korisnik treba vidjeti prvo? To je tvoja Hero sekcija."

---

## ⏰ **12:00-12:15 (15 min) - PEER REVIEW & ADJUSTMENTS**

### **Slajd 29: Interactive Feedback - Peer Review**

"Sada ćemo napraviti **peer review** - dat ćete feedback jedni drugima.

**Kako:**
1. **Pair up** - pronađi partnera (osoba do tebe)
2. **Razmjena wireframe-a** (ili pokažite na papiru)
3. **5 minuta po osobi** - dajete feedback prema ovim kriterijima:"

**Feedback kriteriji (na slajdu 29):**

**1. Clarity & Structure (Jasnoća i Struktura):**
- Jesu li sve sekcije jasne i razumljive?
- Je li layout logičan? (Header → Content → Footer)

**2. Navigation & Usability (Navigacija i Upotrebljivost):**
- Je li navigacija intuitivna?
- Jesu li važni elementi (search bar, buttons) lako vidljivi?

**3. Consistency & Balance (Konzistentnost i Balans):**
- Jesu li elementi konzistentne veličine?
- Ima li dovoljno spacing-a između sekcija?

**4. Creativity & Additional Features (Kreativnost i Dodatne Značajke):**
- Je li dizajn engaging?
- Imaš li sugestiju za poboljšanje?

**Format feedback-a:**
- **1 stvar koja je DOBRA** ("Sviđa mi se kako si organizirala radionice sekciju!")
- **1 stvar za POBOLJŠANJE** ("Možda bi search bio bolji ako je veći i prominentniji?")

**[Timer: 10 minuta - 5 min po osobi]**

Počnite!"

📚 **FACILITATOR NOTES:**

**Kako voditi:**
- Cirkuliraj i slušaj feedback razgovore
- Ohrabruj constructive feedback (ne samo "lijepo je" - nego konkretni komentari)
- Ako čuješ dobar feedback, highlight ga: "Odličan point - to je upravo ono što smo učili o navigation!"

**Troubleshooting:**
- **Problem**: Parovi šute, ne znaju što reći.
  **Rješenje**: Daj prompt: "Pitaj partnera: Gdje bi kliknula PRVO kad bi otvorila ovu stranicu? Je li to mjesto gdje želiš da klikne?"
- **Problem**: Feedback je prekritizan ("Ovo je loše dizajnirano").
  **Rješenje**: Intervenira: "Fokusirajmo se na constructive feedback - kako može poboljšati, a ne samo što je loše."

---

### **Slajd 30: A Little Adjustment**

"Na temelju feedback-a koji ste dobili, napravite **barem 2 izmjene** na svom wireframe-u da ga poboljšate.

**[Timer: 3 minute za quick adjustments]**"

📚 **FACILITATOR NOTES:**
- Ovo je quick iteration - ne mora biti perfektno, nego pokazati proces iterate-review-adjust.

---

## ⏰ **12:15-12:25 (10 min) - ZAKLJUČAK & RECAP**

### **Slajd 31: Conclusion**

"Odličan posao danas! Prošli smo jako puno materijala.

**Što smo naučili:**

1. **Information Architecture (IA)** = organizacija i struktura sadržaja
2. **8 Dan Brown-ovih principa** (Objects, Choices, Disclosure, Exemplars, Front Doors, Multiple Classifications, Focused Navigation, Growth)
3. **Kako kreirati IA** - 8-step proces
4. **Taxonomy & Classification** - grupiranje sadržaja (Post-it vježba)
5. **Navigation types** - top, side, dropdown, breadcrumb...
6. **Sitemap** - vizualna struktura website-a
7. **Low-fidelity wireframes** - brze skice layout-a

**Zašto je IA važna:**
- Pomaže korisnicima da brzo pronađu što traže
- Smanjuje frustraciju
- Povećava conversion rates
- Čini proizvod scalable (može rasti)

IA je **temelj** dobrog UX dizajna. Bez dobre IA, čak i najljepši dizajn neće funkcionirati jer korisnici neće moći navigirati.

**CraftEase projekt:**
Nastavit ćete razvijati vaš CraftEase projekt kroz sljedeća predavanja - ovo je samo početak!"

---

## ⏰ **12:25-12:30 (5 min) - PITANJA I ZAKLJUČAK**

### **Slajd 32: Questions**

**Što reći studentima:**

"Ima li pitanja o današnjem gradivu? Bilo što - IA principi, taxonomy, wireframing, CraftEase projekt...?"

**[Odgovori na pitanja - 3 min]**

---

**Wrap-up (2 min):**

"Hvala svima! Odličan rad danas.

**Za sljedeći put:**
- Možete nastaviti raditi na CraftEase wireframe-u (opcionalno)
- Ako želite, kreirajte sitemap za CraftEase u Figma ili diagrams.net (opcionalno homework)

**Resursi su na slajdu 33** - provjerite linkove za dublje učenje.

Vidimo se sljedeći put! 🎉"

---

## 🔄 **BACKUP AKTIVNOSTI**

### **BACKUP AKTIVNOST 1: Card Sorting - Alternative CraftEase Taxonomy (15 min)**

**Cilj:** Vježbati taxonomy na drugačiji način, digitalno

**Kada koristiti:**
- Post-it vježba je završena prerano
- Studentice žele vidjeti alternative approach

**Materijali:**
- Laptopi / tableti
- Online tool: **Optimal Workshop** (besplatna verzija) ili **Miro**

**Upute:**
1. Otvorite Miro ili Optimal Workshop
2. Napišite **15-20 content items** za CraftEase (npr. "Bušilica", "Radionica bojanja", "Video tutorial...")
3. **Individual sorting**: Svaka studentica grupira items kako njoj ima smisla (5 min)
4. **Compare**: Usporedite s kolegicom - jeste li grupirali isto? (5 min)
5. **Discussion**: Zašto postoje razlike? Što to znači za IA? (5 min)

📚 **FACILITATOR NOTES:**

**Kako voditi:**
- Objasni: "U real-world scenariju, radili biste card sorting s pravim korisnicima da vidite kako ONI misle o kategorizaciji."
- Highlight razlike u grupiranju - to je normalno! IA često zahtijeva kompromis između različitih mental modela.

**Troubleshooting:**
- **Problem**: Nemaju pristup Miro/Optimal Workshop.
  **Rješenje**: Možete napraviti manual card sorting s fizičkim karticama ili Post-it notes (isti proces).

📖 **Reference:**
- [Card Sorting Guide - NN/g](https://www.nngroup.com/articles/card-sorting-definition/)

---

### **BACKUP AKTIVNOST 2: IA Critique - Analiza Postojećeg Website-a (15 min)**

**Cilj:** Primijeniti naučene principe na real-world primjer

**Kada koristiti:**
- Ima vremena nakon wireframe vježbe
- Studentice žele vidjeti praktičnu primjenu

**Upute:**
1. **Odaberite website** (npr. Ikea.hr, Njuskalo.hr, ili bilo koji poznati)
2. **Analizirajte IA** (10 min):
   - Je li navigacija jasna?
   - Koliko razina dubine ima?
   - Koriste li breadcrumbs?
   - Je li taxonomy logična?
   - Koje principe Dan Brown-a primjenjuju? (Objects, Choices, Disclosure...)
3. **Diskusija** (5 min): Što bi poboljšali?

📚 **FACILITATOR NOTES:**

**Kako voditi:**
- Odaberi website koji studentice poznaju (lakše će kritizirati)
- Guided questions: "Gdje je search bar? Je li lako vidljiv? Kako biste kategorizirali proizvode?"

**Primjeri website-a za analizu:**
- **Dobri primjeri IA**: Amazon, Netflix, Airbnb
- **Problematični primjeri**: Government websites (često loša IA), neki mali webshop-ovi

**Troubleshooting:**
- **Problem**: Studentice kažu "Sve je ok" - ne vide probleme.
  **Rješenje**: Daj im konkretni task: "Pokušaj pronaći [specifičan proizvod/info]. Koliko klikova ti je trebalo? Je li bilo intuitivno?"

---

### **BACKUP AKTIVNOST 3: Sitemap Speed Challenge (10 min)**

**Cilj:** Brzo kreirati sitemap za jednostavan projekt

**Kada koristiti:**
- Prije ili poslije wireframe vježbe
- Kao warm-up za IA thinking

**Upute:**
1. **Scenarij**: Klijent želi website za lokalnu pekaru
   - **Stranice**: Homepage, O nama, Proizvodi (Kruh, Pecivo, Torte), Kontakt, Online narudžbe
2. **Challenge** (7 min): Nacrtaj sitemap na papiru ili u Figma
   - Definiraj hijerarhiju (parent-child odnosi)
   - Koliko razina dubine?
3. **Share** (3 min): Pokaži kolegama - jesu li svi napravili slično?

📚 **FACILITATOR NOTES:**

**Kako voditi:**
- Ovo je brza vježba - ne treba biti perfektna
- Cilj: vježbati razmišljanje o strukturi
- Nakon vježbe, pokažite jedan "idealan" primjer sitemap-a

**Primjer strukture:**
```
Homepage
├── O nama
├── Proizvodi
│   ├── Kruh
│   ├── Pecivo
│   └── Torte
├── Online narudžbe
└── Kontakt
```

---

### **BACKUP AKTIVNOST 4: Navigation Design Variants (10 min)**

**Cilj:** Eksperimentirati s različitim navigation tipovima

**Kada koristiti:**
- Nakon teorije o navigation types
- Studentice žele hands-on s navigation-om

**Upute:**
1. **Zadatak**: Za CraftEase, skicirajte **3 različita navigation pristupa**:
   - **Varijanta A**: Top horizontal menu
   - **Varijanta B**: Side navigation (hamburger menu za mobile)
   - **Varijanta C**: Bottom bar navigation (mobile-first)
2. **Vrijeme**: 7 min - nacrtaj quick sketches
3. **Odluka**: Koja varijanta je NAJBOLJA za CraftEase? Zašto? (3 min diskusija)

📚 **FACILITATOR NOTES:**

**Kako voditi:**
- Podsjetnik: CraftEase je web app (ne samo mobile), pa treba navigation koji radi i na desktop i mobile
- Guide diskusiju: "Zašto je top menu bolji od side menu za ovaj use case?"

**Očekivani zaključak:**
- **Desktop**: Top horizontal menu (standard za web apps)
- **Mobile**: Hamburger ili bottom bar (ovisno o broju menu items)

---

### **BACKUP AKTIVNOST 5: "Find It Fast" Game - IA Scavenger Hunt (15 min)**

**Cilj:** Zabavna vježba testiranja IA na real website-u

**Kada koristiti:**
- Studentice su umorne od teorije - trebaju energizer
- Nakon pauze

**Upute:**
1. **Odaberi website** (npr. Ikea.hr)
2. **Challenge** - Svaka studentica mora pronaći:
   - Proizvod koji košta ispod 50kn
   - Stranicu s customer service kontaktom
   - Blog članak (ako ima)
   - Delivery informacije
3. **Timer**: 5 min
4. **Whoever finds all 4 first wins!** 🏆
5. **Debrief** (5 min): Kako ste našli? Što vam je pomoglo? (IA elementi: search, navigation, breadcrumbs...)

📚 **FACILITATOR NOTES:**

**Kako voditi:**
- Make it fun - competitive element motivira
- Nakon game, analyze: "Zašto je bilo lako/teško pronaći? Što bi trebao website poboljšati?"

**Troubleshooting:**
- **Problem**: Neki website je prejednostavan (sve na homepage).
  **Rješenje**: Odaberi complex website s više razina (Amazon, Ikea, news site...)

---

### **BACKUP AKTIVNOST 6: Wireframe Iteration - Mobile Version (15 min)**

**Cilj:** Adaptirati desktop wireframe za mobile

**Kada koristiti:**
- Nakon desktop wireframe vježbe
- Ima vremena i energije za još jednu vježbu

**Upute:**
1. **Zadatak**: Uzmite svoj CraftEase desktop wireframe i **adaptirajte ga za mobile** (smartphone screen)
2. **Što promijeniti:**
   - Top menu → Hamburger menu
   - 3 kolumne sadržaja → 1 kolumna (stack vertikalno)
   - Manji buttoni, veći touch targets
3. **Vrijeme**: 12 min
4. **Compare**: Pokažite kolegicom - koje odluke ste donijeli? (3 min)

📚 **FACILITATOR NOTES:**

**Kako voditi:**
- Naglasi: Mobile-first thinking je važno - većina korisnika danas pristupa na mobitel
- Podsjetnik: Finger-friendly - buttoni moraju biti dovoljno veliki za touch (min 44x44px)

**Troubleshooting:**
- **Problem**: Studentica ne zna kako smanjiti sadržaj za mobile.
  **Rješenje**: "Prioritize! Što je NAJVAŽNIJE za mobile korisnika? Stavi to gore. Manje važne stvari možeš sakriti u hamburger menu ili staviti niže."

---

### **BACKUP AKTIVNOST 7: IA Horror Stories - Discuss Bad Examples (10 min)**

**Cilj:** Učenje kroz loše primjere - što NE raditi

**Kada koristiti:**
- Kao diskusija između teorije
- Break od hands-on vježbi

**Upute:**
1. **Facilitator priča "horror story"** (3 min):
   - Primjer website-a s lošom IA (npr. government site gdje je nemoguće pronaći formular)
   - Što je bilo loše? (previše kategorija, nejasne labele, nema search...)
2. **Studentice share** (5 min):
   - "Jeste li ikada koristili website/app gdje niste mogli pronaći što tražite? Što je bilo problem?"
3. **Extract lessons** (2 min):
   - Koje IA principe su prekršili?
   - Kako bi vi to popravili?

📚 **FACILITATOR NOTES:**

**Kako voditi:**
- Encourage honest discussion - svi smo imali frustrirajuća iskustva s lošom IA
- Connect to principles: "To je kršenje principa Choices - previše opcija!"

**Primjeri loših IA:**
- Government websites (često kaotični)
- Stari corporate sites (menu struktura po odjelima umjesto po user needs)
- E-commerce s lošim filterima (ne možeš pronaći što tražiš)

---

## 🌐 **EKSTERNI RESURSI**

**Udemy tečaj preporuke za ovaj dan:**
- **Section 3: User Flows** - Kako korisnici navigiraju kroz app
- **Section 4: Sitemaps** - Kreiranje sitemap-a, best practices
- **Section 5: Wireframing** - Low-fidelity wireframing basics

**Tools iz External Resources PDF-a:**
- [Figma](https://figma.com) - Za wireframing i sitemap
- [Diagrams.net](https://app.diagrams.net/) - Besplatni tool za sitemap
- [Balsamiq](https://balsamiq.com) - Specijalizirani wireframing tool
- [Miro](https://miro.com) - Collaborative whiteboard za card sorting

**Članci iz External Resources PDF-a:**
- [What Are User Flows In UX Design?](https://careerfoundry.com/en/blog/ux-design/what-are-user-flows/) - Dobro za razumijevanje user flows
- [Sitemaps - The Beginner's Guide](https://uxmentor.me/sitemaps-the-beginners-guide/) - Sve o sitemap-ovima
- [How to Create a Wireframe](https://www.invisionapp.com/inside-design/how-to-wireframe/) - Step-by-step wireframing guide

**Design Inspiration iz External Resources PDF-a:**
- [Dribbble](https://dribbble.com/) - Inspiracija za wireframes i layouts
- [Behance](https://www.behance.net/) - UX/UI projekti
- [Pttrns](https://pttrns.com/) - Mobile design patterns (korisno za navigation ideas)

---

## 📚 **DODATNI RESURSI ZA FACILITATORA**

**Prije predavanja, pregledaj:**
1. [Information Architecture Basics - NN/g](https://www.nngroup.com/articles/information-architecture-sitemaps/)
2. [8 Principles of IA - Medium Article](https://medium.com/@izharul/dan-browns-eight-useful-principles-of-information-architecture-b31bd019917d)
3. [Udemy teÄaj: Section 4 - Sitemaps](https://uxmentor.me/sitemaps-the-beginners-guide/)

**Za tvoje dalje učenje:**
- [Information Architecture for the World Wide Web (knjiga)](http://shop.oreilly.com/product/9780596527341.do) - "Polar Bear Book" (biblija IA)
- [How to Make Sense of Any Mess (knjiga)](http://www.howtomakesenseofanymess.com/) - Besplatna online knjiga o IA

**Pripremna lista:**
- [ ] Pripremi Post-it notes (različite boje ako moguće)
- [ ] Testiraj pristup whiteboard-u ili zidnom prostoru za Post-it vježbu
- [ ] Pripremi backup: papir i olovke za wireframing (ako netko nema laptop)
- [ ] Screenshare/projektor spreman za pokazivanje website primjera
- [ ] Fotografiraj grupne rezultate Post-it vježbe za dokumentaciju

---

**KRAJ SINOPSISA - DAN 5** ✅
