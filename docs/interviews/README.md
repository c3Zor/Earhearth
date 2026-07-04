# Interviu žurnalas

Rinkos validacijos (MVP A kryptis) įrodymų bazė. Kiekvienas pokalbis su potencialiu vartotoju, optikos specialistu ar ekspertu — vienas failas, viena struktūra, kaupiama automatiškai.

## Kaip naudotis

1. Po pokalbio numesk Claude sesijoje žalias pastabas (tekstu ar balsu transkribuotas) ir parašyk `/interview`.
2. Claude sukuria struktūruotą įrašą `docs/interviews/YYYY-MM-DD-vardas.md` pagal [šabloną](_template.md).
3. Kas 3–5 interviu Claude atnaujina [synthesis.md](synthesis.md) — pattern'us, signalus ir jų ryšį su MVP sprendimo vartais.

## Kodėl taip

- MVP scope reikalauja 1–2 psl. išvados „rinka yra / nėra / yra su sąlyga X". Ta išvada turi remtis įrašais, ne atmintimi.
- Struktūruoti įrašai leidžia atskirti **faktus** (ką žmogus pasakė) nuo **interpretacijų** (ką mes norim girdėti) — pagrindinė validacijos interviu klaida.
- Failai repo — versijuojami, cituojami, prieinami bet kurioje sesijoje.

## Taisyklės įrašams

- Cituok pažodžiui, kur tik įmanoma. Parafrazė žymima aiškiai.
- Fiksuok **elgesį ir praeitį** („ar dabar seki ciklą? kuo?"), ne hipotetinius pažadus („ar pirktum už 199 $?").
- Kainos jautrumas — tik per realius palyginimus (ką žmogus jau moka už Oura/aplikacijas/optiką).
