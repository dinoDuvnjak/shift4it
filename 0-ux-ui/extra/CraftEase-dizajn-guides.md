# CraftEase / DIYHub — Dizajn vodič

---

## 🎨 Boje — i zašto

Za ovakav tip aplikacije (DIY, alati, radionice, majstorija) idealna paleta je **zemljana + naglasak**:

| Boja | Zašto |
|------|-------|
| **Narančasta / jantarna** | Energija, akcija, "uradi sam" vibe — misli Bauhaus, Home Depot, Hornbach |
| **Tamno siva / antracit** | Profesionalnost, alati, metal — kontrast prema narančastoj |
| **Bijela / off-white** | Čistoća, čitljivost, prostor za disanje |
| **Drvo / bež akcent** (opcionalno) | Toplina, DIY materijali, prirodnost |

> **Izbjegavaj** pastelne boje, previše plave (to je tech/fintech vibe), i previše tamne pozadine — ovo nije gaming app.

---

## ✏️ Tipografija

Dvije familije su dovoljne:

- **Naslovi** → nešto s karakterom, Bold/Black težina. Npr. **Inter, Manrope ili DM Sans** — moderno ali čitko
- **Body tekst** → ista familija, Regular/Medium težina

> **Zašto ne dekorativne fontove?** Jer ovo je funkcionalna aplikacija, ne poster. Čitljivost > stil.

### Hijerarhija (važnija od odabira fonta):

1. Veliki bold naslov
2. Manji subtitle
3. Normalan body
4. Sitni label/caption

---

## 📱 Screenovi — koji i što na njima

### KUPAC STRANA (User flow)

**1. Home / Landing DIY sekcije**
- Hero banner s CTA ("Prijavi se na radionicu")
- Istaknute radionice (kartice)
- Kratki featured tutorial
- Search/filter bar

**2. Lista radionica**
- Filter po kategoriji (drvo, elektrika, keramika...)
- Kartice radionica — slika, naziv, datum, broj mjesta, cijena
- Sortiraj po datumu / popularnosti

**3. Detalj radionice**
- Slika, opis, instruktor
- Datum, lokacija, trajanje
- Koliko mjesta ostalo
- CTA gumb → "Prijavi se"

**4. Booking / Prijava flow**
- Forma: ime, email, broj telefona
- Potvrda rezervacije (summary screen)
- Success state — "Uspješno si se prijavio!"

**5. Tutoriali**
- Grid prikaz kartica
- Kategorije / tagovi
- Thumbnail, naziv, težina projekta (lako / srednje / teško)

**6. Detalj tutoriala**
- Koraci projekta
- Lista materijala s linkovima na proizvode u trgovini
- (Opcionalno) video embed

**7. Profil korisnika**
- Moje prijave / upcoming radionice
- Završene radionice
- Spremljeni tutoriali

---

### ADMIN STRANA

**8. Admin Dashboard**
- Statistike na vrhu (broj prijava ovaj tjedan, najpopularnija radionica)
- Brze akcije

**9. Upravljanje radionicama**
- Tablica svih radionica
- Gumb "Dodaj novu radionicu"
- Edit / Delete opcije

**10. Forma za novu radionicu**
- Unos naziva, opisa, datuma, kapaciteta, cijene, slike

**11. Prikaz prijava**
- Lista tko se prijavio na koju radionicu

**12. Feedback pregled**
- Prikaz recenzija/ocjena po radionicama

---

## 🧠 Savjet za studente

Za studentski projekt **10–12 screena je zlatni standard** — dovoljno da pokažeš cijeli flow, ne previše da se izgubiš u detaljima.

Fokusiraj se na:

1. **Konzistentnost** — isti spacing, iste kartice, isti gumbi
2. **Jasna hijerarhija** — korisnik odmah zna što je klikabilno
3. **Jedan primary CTA po screenu** — ne zbunjuj korisnika s 5 gumba