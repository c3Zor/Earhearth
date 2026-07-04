# EARHEART — Multi-Agent Swarm Ataskaita

> 2026-07-04. Du swarm'ai: rinkos/strategijos (18 agentų) + patentų gilioji analizė (11 agentų), ~1,9 mln tokenų, visi kritiniai teiginiai adversariškai patikrinti skeptikų agentų.
> **Tai strateginė analizė, ne teisinė išvada — galutiniam FTO reikalingas patentų advokatas.**

## VERDIKTAS: CONDITIONAL GO

90 dienų, dviejų „kill gate" seka (patentai + paklausa), kainuojanti <5 % seed raundo. Techninis signalas validuotas ✅, patentų kelias atrodo praeinamas su konkrečiais design-around ✅, bet fem-first pozicionavimas dabartine forma fiziologiškai nepagrįstas ⚠️ ir paklausa $199+ kainoje neįrodyta ⚠️.

---

## 1. RINKA (Swarm #1)

**Kas patvirtinta:**

- **Oura dominuoja žiedus:** 5,5 mln+ parduota, ~80 % rinkos, ~$1 mlrd pajamų 2025, $11 mlrd vertinimas, IPO paduotas. Vartotojai moka prenumeratą ($5,99/mėn) už HRV/miego/ciklo įžvalgas. [businesswire.com](https://www.businesswire.com/news/home/20250922351288/en/)
- **Smart glasses masiškėja BE biometrikos:** Meta/EssilorLuxottica pardavė ~7 mln akinių vien 2025 m. — bet nė vieni vartotojiški akiniai nematuoja jokios biometrikos (Meta Aria Gen 2 su PPG nosies atramoje — tik research). Niša „biometrinis akinių aksesuaras" **neužimta**. [cnbc.com](https://www.cnbc.com/2026/02/11/ray-ban-maker-essilorluxottica-triples-sales-of-meta-ai-glasses.html)
- **Užausinė PPG moksliškai validuota:** peer-reviewed tyrimai (PMC11902391), STAT Health klinikinis in-ear jutiklis (Johns Hopkins/JACC). Tavo prototipo rezultatas dera su literatūra.
- **~92 % JAV suaugusiųjų naudoja optiką, ~68 % receptinę** (The Vision Council 2024) — bazė didžiulė, BET adresuojama rinka sąžiningai yra ~$0,4–0,7 mlrd (smart-ring-adjacent), ne femtech TAM ($9–75 mlrd spread'as — nekvotuotinas).

**Kritinės problemos (juodoji kepurė laimėjo):**

1. **Fem-first ciklo sekimas dabartine forma neveikia fiziologiškai:** visi veikiantys ciklo sekikliai (Oura, Apple Watch, Natural Cycles) remiasi **naktine** temperatūra — akiniai naktį nusiimami. Sąžiningas produktas šiandien = **all-day stress/HRV companion** (šito claim'o niekas neturi!). Alternatyva: „dviejų kojinių" sistema (diena ant akinių + naktis ant miego juostos).
2. **Kainos precedentas:** vienintelis shipping clip-on akinių aksesuaras — JLab JBuds Frames už **$49** (audio). $199–249 kainos hipotezę BŪTINA testuoti presale/fake-door metodu prieš tooling'ą.
3. **Rinka teisminė:** Oura per ITC išmetė Ultrahuman ir RingConn iš JAV (2025-10). **Ultrahuman elektronika prototipe = paveldėta rizika — produktas turi būti clean-room** (pvz., ADPD4101 + nRF52).

## 2. CEO PANELĖ — visi trys: **CONDITIONAL**

| CEO | Verdiktas | Pagrindinė sąlyga |
|---|---|---|
| Hardware (Oura/Whoop tipo) | Conditional | FTO claim-chart ant Shennib '584; clean-room rebuild; 30+ moterų wear study; presale testas $199+ |
| Fem-health (Clue/Elvie tipo) | Conditional | Ciklo claim'ą validuoti ARBA sąžiningai užmušti; 30 moterų / 30 dienų studija (plaukai, hijab, makiažas, rėmeliai) |
| IP/Deep-tech | Conditional | „IP-timing play, apsirengęs consumer-hardware kostiumu" — finansuotų tik IP žaidimą: file provisionals DABAR, bandyti nupirkti/licencijuoti Shennib '584 iš individualaus išradėjo |

## 3. PATENTAI (Swarm #2 — patikrinta skeptikų)

### 3.1 US7677723B2 („Eyeglasses with a heart rate monitor", IngenioSpec) — IŠNARSTYTA

**Statusas (patvirtinta):** galioja, visi palaikymo mokesčiai sumokėti (paskutinis 2021 — daugiau mokėti nereikia, nebenustos galioti anksčiau laiko). **Baigiasi 2027-10-21.** Prioritetas 2003-10-09, granted 2010-03-16. Savininkas: IngenioSpec LLC (IpVenture įpėdinis).

**Geografija (patvirtinta per Espacenet):** šeima **TIK JAV** (family 038040411) — jokių EP/CN/JP/WO. **ES/Lietuvoje kurti, gaminti ir pardavinėti — visiškai laisva jau dabar.**

**Claim'ų analizė (patikrinta paraidžiui):**

- **Claims 1, 2–5, 26 — EARHEART architektūra jau apeina:**
  - Claim 1 reikalauja elektronikos **įmontuotos rėmelyje** + audio išvesties — „kojinė" ant pasyvių akinių neatitinka.
  - Claims 2–5 (clip prie ausies) reikalauja laidu prijungto clip'o prie **rėmelyje įmontuotos** elektronikos + **transmisinės** (kiaurai kūno) šviesos — EARHEART yra savarankiškas modulis su **reflektine** PPG.
  - Claim 26 reikalauja jutiklio **nosies atramoje** + garsiakalbio.
- **⚠️ CLAIM 23 — VIENINTELĖ TIKRA GRĖSMĖ:** dengia BET KOKĮ prie galvos dėvimą aparatą su (a) optiniu HR monitoriumi, (b) įrenginiu, renkančiu **exercise/aktyvumo duomenis**, ir (c) belaidžiu **abiejų** duomenų srautų siuntimu. Kojinė su PPG + akselerometru + BLE atitiktų visus elementus.

**Design-around claim 23 (inžinieriaus + IP stratego konsensusas):** shipping'inti **BE exercise-data funkcijos** — arba be akselerometro, arba IMU griežtai užrakintas tik judesio artefaktų filtravimui (niekada nelogina, nerodo, nesiunčia aktyvumo duomenų; „configured to" reiškia, kad galimybė turi būti **realiai nesama**, ne tik išjungta app'e). Tai užmuša (b) ir automatiškai (c). Po 2027-10-21 — akselerometrą galima grąžinti.

**Ar naudojamas / ar pavojingas savininkas:** IngenioSpec = grynas **NPE** („patentų trolis", Unified Patents apibrėžimu), ~56 eyewear patentai, 3 ITC bangos nuo 2023 (atsakovai nuo Apple/Meta/Samsung iki seed-stage startuolių), 8+ licenciatai, 4 rinkos pasitraukimai. **BET: pats '723 niekada nebuvo panaudotas byloje** — darbiniai jų patentai yra kiti šeimos nariai, ir **visi kiti 2003-prioriteto monitoring šeimos nariai jau PASIBAIGĘ** (2024–2025). '723 yra paskutinis gyvas — ir jam liko ~15 mėn.

**Kiti gyvi IngenioSpec šeimos patentai:** US7581833B2 (after-market komponentai, iki 2027-01) — reikalauja elektronikos ABIEJOSE dviejų dalių kojelės pusėse → kojinė ant pasyvių akinių neatitinka; US12535698B2 (reflektinė PPG nuo galvos, bet baigiasi jau 2026-10-11 ir reikalauja garsiakalbio).

### 3.2 Kiti patentai — FTO prioritetai advokatui

| Patentas | Statusas | Rizika EARHEART |
|---|---|---|
| **US12498584B2 (Shennib)** „Eyeglass hearing device with biosensors" — smilkinio arterija (STA) | Granted 2025-12, iki **~2044** | **Sumažinta po vietos patikslinimo (žr. 3.3):** EARHEART matuoja **mastoidinėje srityje už ausies** (posterior auricular arterija), ne prie smilkinio arterijos, kurią nurodo Shennib claims — skirtingos anatominės vietos, keliai nesikerta. Lieka FTO prioritetas #1 patvirtinti: (a) ar visi nepriklausomi claims turi STA/vietos apribojimą, (b) ar reikalauja klausos funkcijos + spyruoklinės kojelės. Individualus išradėjas → licencijos/pirkimo opcija lieka kaip offensive ėjimas |
| **US9217882B2 (Olympus)** detachable temple tip su elektronika | Aktyvus iki ~2033 | #2 prioritetas — claim 17 apie temple tip; patikrinti, ar reikalauja display funkcijos |
| US10598960B2 (e-Vision) docking modulis | **NEBEGALIOJA** — PTAB IPR nukirto visus claims (FWD 2025-12-30) | Nėra ✅ |
| US20200271960A1 (Innocean) modulinė kojelė su HR | **Apleista paraiška** | Nėra — bet puikus **drafting lane** mūsų pačių paraiškai |
| US6431705B1 (Infoeye) eyewear HR monitor | **Pasibaigęs** (prioritetas 1999!) | Nėra — **prior art ginklas** prieš '723 ir kitus (invalidity rezerve) |

### 3.3 Vietos patikslinimas: MASTOIDAS, ne smilkinio arterija (2026-07-04)

Founderis patikslino: EARHEART jutiklis dirba **mastoidinėje srityje** — už ausies kaušelio, virš mastoidinio kaulo (kraujotaka: *posterior auricular* arterija), o **ne** prie smilkinio arterijos (STA), kuri eina *prieš* ausį smilkinio srityje. Pasekmės:

- **Shennib '584 rizika mažėja:** jo claims nurodo biosensorius kojelėje *adjacent to the superficial temporal artery*. Jei STA vieta yra claim limitation — EARHEART šio elemento neturi. Skirtingi anatominiai keliai, produktai nesikerta.
- **Ką vis tiek patikrinti su advokatu:** (1) ar *visi* Shennib nepriklausomi claims turi STA apribojimą (jei bent vienas kalba apie „biosensor in temple portion" be vietos — mastoid argumentas jo neapeina); (2) žodžio *adjacent* aiškinimo ribas.
- **Mūsų dokumentacijos taisyklė:** visur nuosekliai vartoti *mastoid / posterior auricular region, posterior to the auricle* — tai ir diferenciacija nuo Shennib, ir tikslus mūsų provisional paraiškos core claim'o žodynas. Mastoido kaulinis pagrindas (stabilus kontaktas) — inžinerinis argumentas, kuris kartu yra ir teisinė riba.

## 4. AR DAUGIAU DAVIKLIŲ PADEDA? (tiesus atsakymas)

1. **Apėjimui — NE.** Patentas pažeidžiamas, kai produktas turi VISUS claim'o elementus; papildomi jutikliai teisiškai inertiški. Išsigelbėja tik **trūkstamas** elementas.
2. **Akselerometras — vienintelis jutiklis, kuris riziką DIDINA** (įtraukia į claim 23 per exercise-data elementą). Iki 2027-10 JAV rinkai — be aktyvumo funkcijos.
3. **Savo patentui — TAIP.** Platus multi-sensor aprašymas (PPG + SpO2 + temp + IMU + EEG ateičiai) stiprina MŪSŲ paraišką: siauras core claim (retrofit kojinė ant kojelės galo + reflektinė PPG už ausies) + sluoksniuoti dependent claims visiems jutikliams.
4. **Produktui — TAIP, bet po gate'ų.** Diferenciacija, ne teisinė apsauga.

## 5. STRATEGIJŲ REITINGAS

1. **FILE PROVISIONAL DABAR** (easy) — prieš bet kokį viešą demo/pitch deck (ES/PCT teisės miršta nuo atskleidimo!). Dengti: kojinę, day/night dviejų kojinių sistemą, ne-spyruoklinius kontakto sprendimus, on-device privacy architektūrą.
2. **Design-around claim 23** (easy) — be exercise-data; firmware/BOM sprendimas, ne redesign.
3. **EU-first launch** (easy) — '723 tik JAV; Lietuvoje/ES viskas laisva dabar. JAV vartotojų rinka — po 2027-10-21 (arba anksčiau su design-around, bet NPE + ITC rizika pre-revenue startuoliui nepateisinama).
4. **Clean-room rebuild** (būtina) — nulis Ultrahuman turinio produkte.
5. **FTO opinion** ($40–60K) — Shennib '584 + Olympus '882 claim chart'ai; kill gate #1.
6. **Shennib licencija/pirkimas** (offensive) — paversti didžiausią riziką ~2044 m. grioviu.
7. **Invalidity rezerve** — US6431705B1 (1999) prior art prieš visą 2003 šeimą; IPR analizė stalčiuje kaip derybų svertas.

## 6. KOMANDA IR STRUKTŪRA

**Spin-off (atskira NewCo) — TAIP:** (1) IP izoliacija — provisionals ir galima Shennib licencija švarioje cap table; (2) atsakomybės užtvara — teisminė rinka (ITC bylos); (3) clean-room įrodomumas — atskiri repo, žmonės, dokumentacija; (4) seed investuotojai nori pure-play. Pagrindinė įmonė — equity dalis + licencija atgal.

**Founder komanda (3 kėdės):**
1. **CEO/komercija** — kanalas (optikos, lęšių gamintojai: Zeiss/Hoya be wearable istorijos), fundraising; + patentų advokatas ant retainer'io.
2. **CTO hardware/firmware** — clean-room rebuild (ADPD4101 + nRF52), kojinės mechanika be spyruoklių; žmogus, nelietęs Ultrahuman prototipo.
3. **Signalo/klinikinės validacijos lyderis** — HRV algoritmai, wear study (n≥30 moterų); gali būti akademinis partneris.

**Advisory:** patentų advokatas, fem-health GTM, regulatory (wellness vs medical riba).

## 7. 90 DIENŲ PLANAS SU KILL GATES

| Sav. | Darbas | Kill kriterijus |
|---|---|---|
| 0–2 | File provisionals; advokatas engaged; Ultrahuman IP karantinas | — |
| 0–8 | **GATE 1:** FTO claim chart (Shennib '584, Olympus '882, IngenioSpec šeima, Valencell) | Shennib skaito ant adapterio be apėjimo/licencijos → **STOP** |
| 0–12 | Clean-room rebuild + 30 moterų wear study (signalo prieinamumas, komfortas, ciklo signalas dienos duomenyse) | Signalas <70–80 % dienos → repozicionuoti arba stop |
| 4–12 | **GATE 2:** presale/fake-door testas $199–249 (tikslas ~1 000 depozitų); 10 pokalbių su optikomis; pokalbis su Natural Cycles/Clue dėl duomenų integracijos | WTP arčiau $49 nei $199 → perkainoti/stop |
| 12+ | Abu gate'ai žali → seed raundas, optikos pilotas, EU launch seka | |

---

*Šaltiniai: visi teiginiai turi URL originaliuose swarm rezultatuose (session task outputs). Kritiniai patentų teiginiai patikrinti nepriklausomų skeptikų agentų prieš Google Patents / Espacenet / USITC pirminius šaltinius. 2 iš 11 pirminių patentų teiginių buvo PANEIGTI patikros metu ir čia pateikti jau ištaisyti (pvz., pirminis klaidingas teiginys, kad '723 nepriklausomi claim'ai dengia attachable clip).*
