# EARHEART — MVP Scope

> Suderinta 2026-07-04 „office hours" sesijoje. Šaltinis: pradinis koncepcijos dokumentas (Google Docs) + scope klausimynas.

## 1. Pagrindinė prielaida ir tikroji nežinomybė

Techninė validacija **jau atlikta** — veikiantis „Frankenstein" prototipas egzistuoja (žr. C kryptį žemiau). Tai nebėra MVP rizika.

**Likusios MVP nežinomybės, kurias privalome atsakyti:**

1. **Ar yra rinka?** Kas pirktų, už kiek, ir ar fem-first pozicionavimas yra reali spraga, ar tik hipotezė.
2. **Koks patentų laukas?** Ar akinių kojelės PPG/biometrika jau užpatentuota (didieji žaidėjai turi wearable/smart-glasses portfelius) ir kur yra laisvos erdvės (freedom to operate).

## 2. MVP kryptys

### A. Rinkos validacija (PRIORITETAS — vykdoma)

- Konkurentų žemėlapis: smart rings (Oura, Ultrahuman, RingConn...), smart glasses su biometrika, užausiniai davikliai (hearables).
- Fem-first nišos patikrinimas: ar diskretiško, ne-papuošalo tipo ciklo/streso sekimo poreikis yra pagrįstas duomenimis (interviu, apklausos, bendruomenės).
- Kainos jautrumo ir segmento dydžio įvertinimas.
- **Rezultatas:** 1–2 psl. išvada „rinka yra / nėra / yra su sąlyga X".

### B. Patentų laukas (PRIORITETAS — vykdoma)

- Patentų paieška: PPG/biometrika ant akinių kojelės, užausinis optinis matavimas, smart eyewear sensorika.
- Identifikuoti blokuojančius patentus ir laisvas zonas.
- **Rezultatas:** patentų apžvalga su rizikos vertinimu (blokuoja / apeinama / laisva).

### C. „Frankenstein" prototipas — ✅ ĮVYKDYTA

- **Donoras:** Ultrahuman Ring AIR (teardown: <https://www.youtube.com/watch?v=paBIoCJARd4>).
- Elektronika sumontuota prie akinių, PPG signalas gaunamas.
- **Validacijos rezultatas:** signalo kokybė už ausies **lygiavertė matavimui ant piršto**. Kartu su unikaliai ilgu akinių dėvėjimo laiku (visa diena, be įkrovimo konflikto su naktimi) — koncepcija patvirtinta.
- Likutinis (nebūtinas) žingsnis: formalus ilgesnio dėvėjimo testas kasdienėje veikloje.

## 3. Signalai

| Signalas | MVP statusas |
|---|---|
| **PPG / HRV** | **Pagrindinis** — ✅ validuota |
| SpO2 | Oportunistinis — jutiklis žiede jau yra |
| Temperatūra | Oportunistinis |
| Akselerometras / laikysena | Oportunistinis |
| EEG | **Out of scope** (v2+) |
| Kraujospūdis | **Out of scope** (v2+) |
| Kvėpavimas | **Out of scope** (v2+) |

## 4. Aiškiai UŽ MVP ribų (out of scope)

- **Flex PCB ir savas korpusas / silikoninis adapteris** — pradedama tik po rinkos/patentų validacijos.
- **EEG elektrodai** — ateities funkcija.
- **Kraujospūdžio ir kvėpavimo algoritmai** — reikalauja atskiro R&D.
- Savas firmware / mobili aplikacija — naudojame donoro ekosistemą, kiek įmanoma.

*Pastaba: fem-first produkto funkcijos (ciklo sekimas ir pan.) MVP metu nekuriamos, bet fem-first pozicionavimas yra rinkos validacijos (A kryptis) dalis.*

## 5. Sprendimo vartai (decision gate)

| Vartai | Statusas |
|---|---|
| **Signalas:** už ausies ≥ pirštas (PPG/HRV kokybė) | ✅ Validuota (lygiavertis) |
| **Rinka:** yra / nėra / su sąlyga | ⬜ Vykdoma (A kryptis) |
| **Patentai:** laisva / apeinama / blokuota | ⬜ Vykdoma (B kryptis) |

Kai visi trys teigiami → pereinama prie Flex PCB / formos faktoriaus etapo ir finansavimo pokalbių.

## 6. Kiti žingsniai

- [ ] Patentų lauko analizė (B kryptis) — swarm research.
- [ ] Konkurentų žemėlapis ir fem-first nišos analizė (A kryptis) — swarm research.
- [ ] Multi-perspektyvų vertinimas (mąstymo kepurės + CEO panelė) → `docs/analysis/swarm-report.md`.
- [ ] Vidinis feasibility aptarimas su prototipu ir ataskaita rankose.
- [ ] (Nebūtina) Formalus ilgesnio dėvėjimo testas su prototipu.
