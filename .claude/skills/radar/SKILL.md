---
name: radar
description: Savaitinis EARHEART rinkos ir patentų radaras — naujienos apie smart glasses / smart rings / hearables biometriką ir nauji patentai. Naudok, kai vartotojas prašo „radaro", rinkos atnaujinimo ar konkurentų peržiūros.
---

# /radar — rinkos ir patentų radaras

Tikslas: neleisti `docs/analysis/swarm-report.md` išvadoms pasenti. Vienas paleidimas = viena trumpa ataskaita apie tai, kas PASIKEITĖ nuo paskutinio radaro.

## Žingsniai

1. Rask paskutinę ataskaitą `docs/radar/` (failai `YYYY-MM-DD.md`). Jei katalogo nėra — tai pirmasis paleidimas, atskaitos taškas yra `docs/analysis/swarm-report.md` (2026-07-04).
2. Paieškok web'e naujienų NUO paskutinės ataskaitos datos šiomis kryptimis:
   - **Smart glasses + biometrika:** Meta/EssilorLuxottica, Google, Samsung, Apple akinių sensorika; bet koks vartotojiškas produktas, matuojantis biometriką ant akinių.
   - **Smart rings:** Oura, Ultrahuman, RingConn, Samsung Galaxy Ring — produktų, kainų, teisminių ginčų (ITC) pokyčiai.
   - **Hearables / užausiniai sensoriai:** STAT Health ir panašūs, nauji klinikiniai validavimai.
   - **Patentai:** nauji publikuoti patentai apie PPG/biometriką ant akinių kojelės ar mastoidinės srities (Google Patents paieška, paskutiniai ~3 mėn.).
3. Filtruok negailestingai: į ataskaitą patenka tik tai, kas keičia EARHEART riziką ar galimybę. Jokio naujienų sąvado dėl sąvado.
4. Kiekvienam radiniui — viena eilutė poveikio: `[⬆ galimybė / ⬇ rizika / ⚠ stebėti]` + kodėl.
5. Įrašyk `docs/radar/YYYY-MM-DD.md`:
   - **TL;DR** (≤3 sakiniai): ar kas nors keičia „CONDITIONAL GO" verdiktą?
   - **Radiniai** su šaltinių nuorodomis.
   - **Nieko nerasta** irgi yra rezultatas — įrašyk, kokios paieškos atliktos.
6. Jei radinys tiesiogiai kertasi su swarm ataskaitos išvada — pažymėk tai atskirai ir pacituok, kurią išvadą liečia.

## Ko nedaryti

- Nekartok to, kas jau buvo ankstesnėse ataskaitose.
- Necituok TAM skaičių be šaltinio — swarm ataskaita jau pažymėjo femtech TAM kaip nekvotuotiną.
