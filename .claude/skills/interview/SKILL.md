---
name: interview
description: Struktūruoja žalias interviu pastabas į docs/interviews/ įrašą ir prižiūri sintezę. Naudok, kai vartotojas numeta pokalbio pastabas, transkriptą ar sako „užrašyk interviu".
---

# /interview — interviu žurnalo įrašas

Tu gauni žalias pastabas iš rinkos validacijos pokalbio (tekstas, balso transkriptas, punktai). Tavo darbas — paversti jas struktūruotu įrašu per ≤2 min vartotojo laiko.

## Žingsniai

1. Perskaityk `docs/interviews/_template.md` — tai privaloma įrašo struktūra.
2. Iš pastabų užpildyk šabloną. Griežtos taisyklės:
   - **Faktai atskirai nuo interpretacijų.** Citatas palik pažodžiui, žymėk `>`. Ko pastabose nėra — neišgalvok, palik `[nepaklausta]`.
   - **„Raudonos vėliavos" sekcija negali būti tuščia be paaiškinimo.** Jei viskas „patvirtino hipotezes" — įrašyk įspėjimą, kad interviu galėjo būti vedantis (leading).
   - Kainos signalus fiksuok tik per realų elgesį (ką žmogus jau moka), ne hipotetinius atsakymus.
3. Jei trūksta kritinės info (segmentas, ar nešioja akinius, dabartinis sekimas) — užduok vartotojui 1–3 trumpus klausimus PRIEŠ rašydamas failą.
4. Išsaugok kaip `docs/interviews/YYYY-MM-DD-<vardas-arba-pseudonimas>.md` (data — pokalbio, ne įrašymo, jei nurodyta).
5. Suskaičiuok interviu failus kataloge. Jei nuo paskutinio `synthesis.md` atnaujinimo susikaupė ≥3 nauji įrašai — atnaujink sintezę:
   - Pattern'ai tik iš ≥3 nepriklausomų interviu.
   - Atnaujink hipotezių statusus ir „Poveikis sprendimo vartams" skaitiklius.
   - Perskaityk visus interviu failus iš naujo, ne iš atminties.
6. Užbaigk trumpa santrauka: ką šis interviu pakeitė (arba nepakeitė) hipotezių lentelėje.

## Ko nedaryti

- Nekurk optimistinių išvadų iš mandagumo signalų („skamba įdomiai" ≠ pirkimo signalas).
- Neatnaujink sintezės po kiekvieno įrašo — tik kas ≥3, kad pattern'ai turėtų iš ko rastis.
