# Adatkezelési tájékoztató — Magyar PM-benchmark mini-felmérés

> **Verzió:** 1.0  
> **Érvényesség kezdete:** 2026-05-20  
> **Készült:** EU 2016/679 (GDPR) rendelet és a magyar 2011. évi CXII. törvény (Infotv.) alapján.

---

## 1. Adatkezelő adatai

**Adatkezelő neve:** Bell Gábor egyéni vállalkozó  
**Székhely:** [KITÖLTENDŐ — bejegyzett székhely címe]  
**Nyilvántartási szám:** [KITÖLTENDŐ — EV nyilvántartási szám]  
**Adószám:** [KITÖLTENDŐ — magyar adószám, formátum: XXXXXXXX-X-XX]  
**Email:** bellgab@gmail.com  
**Telefon:** [opcionális — KITÖLTENDŐ vagy üresen hagyni]

**Adatvédelmi kapcsolattartó:** Az adatkezelővel azonos személy (egyéni vállalkozói méret miatt külön adatvédelmi tisztviselő kinevezése nem kötelező a GDPR 37. cikke szerint).

> **TODO Gábornak:** ezeket a mezőket pótolni a publikálás előtt. Ha a székhely lakcímmel egyezik, akkor azt kell beírni — a magánlakcím EV esetében hivatalos székhely-cím.

---

## 2. Az adatkezelés célja és jogalapja

### 2.1 Az adatkezelés céljai

**A "Magyar PM-benchmark" online kérdőív kitöltése során kezelt adatok célja:**

1. **Aggregált eredmény-email kiküldése:** ha a kitöltő megadja az email-címét, az adatkezelő egyetlen alkalommal kiküldi neki a felmérés aggregált (személyhez nem köthető) eredményét.
2. **Opcionális pilot-megkeresés:** az adatkezelő SynCore néven egy magyar ingatlankezelő szoftvert fejleszt. Ha a kitöltő érdeklődést mutat (pl. a survey-ben opcionálisan jelzi), az adatkezelő egyszer felveheti vele a kapcsolatot a pilot-program kapcsán.
3. **Belső kutatási elemzés:** a felmérés válaszai (személyhez nem köthető, aggregált formában) felhasználásra kerülnek a SynCore termékfejlesztési döntéseihez.

### 2.2 Az adatkezelés jogalapja

**A GDPR 6. cikk (1) bekezdés a) pontja szerinti hozzájárulás** — az érintett a kérdőív kitöltésével és az email-mező opcionális kitöltésével **kifejezetten hozzájárul** az 1-2. pontok szerinti email-elérhetőség-kezeléshez. A hozzájárulás bármikor visszavonható (lásd 7. pont).

A kérdőív többi (anonim) kérdéseinek kezelése a GDPR 6. cikk (1) bekezdés f) pontja szerinti **jogos érdeken** alapul: az adatkezelő mint szoftverfejlesztő jogos érdeke, hogy piackutatási adatokat gyűjtsön a termékfejlesztéshez. Mivel ezek az adatok személyhez nem köthetők (csak ipar-specifikus operatív kérdések), az érintett magánéletére gyakorolt hatás minimális.

---

## 3. A kezelt személyes adatok köre

**Kötelezően kezelt adatok (anonim, NEM személyes):**
- A Q1-Q5 kérdésekre adott válaszok (multiple-choice, nincs szabadszöveg).
- A kitöltés időbélyege (Tally automatikus rögzítés).

**Opcionálisan kezelt személyes adat:**
- **Email-cím** — kizárólag akkor, ha az érintett a Q6 mezőt önkéntesen kitölti.

**Más személyes adatot az adatkezelő NEM gyűjt:** nem kéri a nevet, telefonszámot, lakcímet, IP-címet vagy bármi más személyazonosító adatot.

### 3.1 Mit jelent ez gyakorlatban?

- Aki **NEM** adja meg az email-címét → teljes anonimitás. A válasza nem köthető senkihez.
- Aki **megadja** az email-címét → a Q1-Q5 válaszai az email-mellé kerülnek a Tally-adatbázisban. Ezt csak az adatkezelő látja.

---

## 4. Az adatok tárolásának helye

### 4.1 Tally.so (elsődleges tárolás)

A kérdőív platformja **Tally Forms BV** (székhely: Belgium, EU). Tally.so a GDPR-rel összhangban tárolja az adatokat **az EU-ban** (AWS Frankfurt és Dublin régiók). Tally adatfeldolgozási szerződése (DPA) elérhető: [tally.so/help/data-processing-agreement](https://tally.so/help/data-processing-agreement).

### 4.2 Email-küldő rendszer (másodlagos érintkezés)

Az aggregált eredmény-email és az opcionális pilot-megkereszés **Google Workspace (Gmail)** rendszeréből kerül kiküldésre (bellgab@gmail.com). A kiküldött emailek a Gmail "Sent" mappájában tárolódnak. Google adatfeldolgozási irányelvei: [policies.google.com/privacy](https://policies.google.com/privacy).

### 4.3 NEM tároljuk

- Saját szerveren (a SynCore még fejlesztés alatt, a survey-adat NEM kerül a v1 rendszerbe).
- Külső, EU-n kívüli adatfeldolgozónál.
- Marketing-automation eszközben (pl. Mailchimp) — ilyet NEM használunk.

---

## 5. Az adatok tárolásának időtartama

**Email-cím (Tally + Gmail tárolásban):** **12 hónap** a kitöltés napjától számítva.

**Részletes ütemezés:**
- T+0 (kitöltés napja) → tárolás kezdete.
- T+0 — T+12 hónap → az adatkezelő használhatja az emailt aggregált eredmény-küldésre (egyszer) és opcionálisan pilot-megkeresésre (egyszer).
- **T+12 hónap → manuális törlés** a Tally-rendszerből (a Tally automata-retention csak Business csomagon érhető el; ingyenes csomagon az adatkezelő manuális kötelessége). A Gmail-archívumból is törlés (a kiküldött aggregált eredmény-email + lead-megkeresés).

**Indok:** A 12 hónap fedi a SynCore v1 fejlesztési időszak első felét, ezalatt egy vagy két email-kommunikáció lehetséges (eredmény + pilot). A 12 hónap utáni tárolás már aránytalan az érintett szempontjából.

**Operatív intézkedés:** Az adatkezelő naptári emlékeztetőt állít be minden kitöltés-batch T+12 hónapjára, hogy a manuális törlés ne maradjon ki.

**Anonim válaszok (Q1-Q5):** ha a kitöltő NEM adta meg az email-címét, a válasz aggregált formában korlátlanul megőrizhető (személyhez nem köthető). Ha email-t is megadott, a válasz az email-lel együtt törlésre kerül 12 hónap után.

---

## 6. Adatfeldolgozók

Az adatkezelő harmadik felet csak az adattárolás technikai megvalósítására vesz igénybe:

| Adatfeldolgozó | Tevékenység | Székhely / Tárolás | DPA |
|---|---|---|---|
| **Tally Forms BV** | Online kérdőív hosting + válaszok tárolása | Belgium / EU (AWS Frankfurt, Dublin) | [Tally DPA](https://tally.so/help/data-processing-agreement) |
| **Google Ireland Ltd.** | Email küldés (Gmail) | Írország / EU | [Google DPA](https://workspace.google.com/terms/dpa_terms.html) |

**Más adatfeldolgozót az adatkezelő NEM vesz igénybe.** Az adatok harmadik fél részére (beleértve hatóságot is) átadásra **CSAK törvényi kötelezettség alapján** kerülhetnek (pl. bírósági végzés).

---

## 7. Az érintett jogai

Az érintett **bármikor, ingyenesen, formai kötöttség nélkül** gyakorolhatja a következő jogokat:

### 7.1 Hozzáférés joga (GDPR 15. cikk)
- Kérheted, hogy az adatkezelő tájékoztasson arról, milyen személyes adatokat kezel rólad.
- Másolat kérhető a tárolt adatokról.

### 7.2 Helyesbítés joga (GDPR 16. cikk)
- Ha a tárolt email-címed elavult vagy hibás, kérheted a helyesbítést.

### 7.3 Törlés joga ("right to be forgotten", GDPR 17. cikk)
- Bármikor kérheted a teljes email-címed és hozzá kapcsolódó válaszaid törlését.
- **Egy email a bellgab@gmail.com-ra → 7 napon belül törlés.**

### 7.4 Hozzájárulás visszavonása (GDPR 7. cikk (3) bek.)
- Az email-elérhetőség kezeléséhez adott hozzájárulás bármikor visszavonható, ugyanazon az úton, ahogyan megadtad (egy email a bellgab@gmail.com-ra elég).

### 7.5 Adathordozhatóság (GDPR 20. cikk)
- Kérheted, hogy az adatkezelő strukturált, géppel olvasható formában (CSV, JSON) adja át neked a rád vonatkozó adatokat.

### 7.6 Tiltakozás (GDPR 21. cikk)
- Ha az adatkezelés jogos érdeken alapul, tiltakozhatsz ellene.

---

## 8. Adatbiztonsági intézkedések

Az adatkezelő az alábbi technikai és szervezeti intézkedéseket alkalmazza:

- **Hozzáférés-kontroll**: a Tally-fiókhoz és a Gmail-hez csak az adatkezelő fér hozzá, kétfaktoros hitelesítéssel.
- **Titkosítás átvitel közben**: a Tally és a Gmail HTTPS/TLS protokollt használ.
- **Tárolási titkosítás**: a Tally AWS-tárolása "encryption at rest" szabványnak megfelelő.
- **Nincs nyilvános exportált CSV**: az adatkezelő NEM tárol exportált CSV-t megosztott rendszerben (Dropbox, Google Drive nyilvános mappa stb.). Ha analízis céljából exportál, a fájl a saját, jelszóval védett számítógépén marad.
- **Megosztás kizárt**: a válaszokat harmadik féllel az adatkezelő NEM osztja meg, kivéve aggregált, anonimizált formában (lásd 2.1).

**Adatvédelmi incidens (adatszivárgás) esetén:**
- 72 órán belül bejelentés a NAIH-nak (GDPR 33. cikk).
- Ha az érintettre jelentős kockázattal jár, az érintett kiértesítése is megtörténik (GDPR 34. cikk).

---

## 9. Panasztétel és jogorvoslat

### 9.1 Az adatkezelőhöz fordulás

Ha bármilyen kérdésed, panaszod vagy kérésed van az adatkezeléssel kapcsolatban, írj **bellgab@gmail.com**-ra. Az adatkezelő 30 napon belül érdemi választ ad.

### 9.2 NAIH (felügyeleti hatóság)

Ha a válasz nem kielégítő, panaszt tehetsz a Nemzeti Adatvédelmi és Információszabadság Hatóságnál:

**Nemzeti Adatvédelmi és Információszabadság Hatóság (NAIH)**  
Cím: 1055 Budapest, Falk Miksa utca 9-11.  
Postacím: 1363 Budapest, Pf.: 9.  
Telefon: +36 (1) 391-1400  
Email: ugyfelszolgalat@naih.hu  
Web: [naih.hu](https://naih.hu)

### 9.3 Bírósági jogorvoslat

Lakóhelyed szerinti törvényszékhez fordulhatsz, ha úgy ítéled, hogy az adatkezelésed jogai sérültek (GDPR 79. cikk + Infotv. 23. §).

---

## 10. A tájékoztató módosítása

Az adatkezelő fenntartja a jogot, hogy a tájékoztatót egyoldalúan módosítsa. A módosított tájékoztató a publikálás napjától hatályos. A módosításról a már nyilvántartott email-címen tájékoztatást küldünk (ha érdemi változás történik).

---

## Mellékletek

### A) Q6 rövid változat (a Tally-formban inline megjelenik)

```
Email gyűjtésére csak akkor kerül sor, ha önként megadod.
Felhasználás: aggregált eredmény + opcionálisan 1 pilot-megkeresés.
Tárolás: Tally.so (EU) és Gmail, 12 hónapig.
Törölhető bármikor (1 email a bellgab@gmail.com-ra).
Részletes tájékoztató: [link]
```

### B) Tally setup-tudnivalók

A Tally-formban három helyen kell adatkezelési információt megjeleníteni:

1. **Form-header alatt rövid utalás**: pl. *"Az opcionális email-cím kezeléséhez lásd az [adatkezelési tájékoztatót](link)."* (1 mondatos)
2. **Q6 alatti sub-text**: az A) mellékletbeli rövid változat.
3. **Záró-képernyő (Thank you)**: 1 mondat utalás + link a teljes tájékoztatóra.

A Tally beállítások közt **a GDPR consent checkbox** is bekapcsolható ("Show GDPR consent" toggle, Form Settings → Privacy). Ezt **bekapcsoljuk**, és az alábbi szöveg jelenik meg a Submit gomb fölött:

```
[ ] Hozzájárulok az adataim 12 hónapos kezeléséhez az
    Adatkezelési tájékoztatóban foglaltak szerint.
```

A checkbox **kötelező** csak akkor, ha a Q6 ki van töltve. Ha nincs email, a checkbox nem szükséges (az anonim Q1-Q5-höz jogos érdek = elég).

> **Megjegyzés a Tally korlátairól:** A "conditionally required" checkbox a Tally-ban Pro-funkció ($25/hó). Az ingyenes csomagon az egyszerűbb megoldás: a Q6 alatt egy információs blokk, ami magyarázza, hogy az email kitöltése automatikus hozzájárulást jelent — ez GDPR-szempontból elégséges, ha a tájékoztató előtte felugrott. Az "explicit checkbox" jobb pratika, de jogilag NEM kötelező.

### C) Hosztolási opciók a teljes tájékoztatóra

Mivel SynCore-nek még nincs saját domain-je, a hosszú tájékoztatónak link-elhető helyen kell lennie:

1. **GitHub repo public file** (legegyszerűbb): pl. `https://github.com/bellgab/syncore-public/blob/main/adatkezelesi-tajekoztato.md` (publikus repó, csak ezt a fájlt tartalmazza).
2. **GitHub Pages** (~10 perc setup): `https://bellgab.github.io/syncore-privacy/` — szebb URL, HTML-rendereléssel.
3. **Tally inline static page** (Tally Pro): a Tally-fiókban közvetlenül.
4. **Saját domain** (későbbi): pl. `syncore.hu/adatkezeles` — ha lesz domain és landing.

**Javaslat:** GitHub public file vagy GitHub Pages (1-2 órás setup), ezzel egy stabil URL-t kapunk a tájékoztatóra anélkül, hogy a SynCore domain-re várnánk.

---

## Status

- [ ] Adatkezelő-mezők kitöltve (székhely, nyilvántartási szám, adószám)
- [ ] Tájékoztató publikálva nyilvános URL-en (GitHub repo / Pages)
- [ ] Tally-form GDPR consent toggle bekapcsolva
- [ ] Q6 sub-text + form-header utalás beillesztve
- [ ] Záró-képernyőn link a tájékoztatóra
- [ ] T+12 hónapos törlés naptári emlékeztető beállítva
