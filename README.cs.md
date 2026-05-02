<p align="center"><img src="assets/icon.png" alt="Boat Knot Meter" width="120" height="120" /></p>
<h1 align="center">Boat Knot Meter — GPS uzlomer, kotvení a alarm zóny bez vlnobití</h1>
<p align="center"><b>Námořní GPS rychloměr pro iPhone s kotevní hlídkou, alarmem zóny no-wake a exportem GPX. SOG v uzlech s přesností 0,1. Funguje offline po GPS fixu. Bez reklam, bez účtu, bez sledování.</b></p>
<p align="center"><a href="https://apps.apple.com/us/app/boat-knot-meter-anchor-watch/id6764334539"><img src="https://img.shields.io/badge/App%20Store-Stáhnout-0D96F6?style=for-the-badge&logo=app-store&logoColor=white" /></a></p>
<p align="center"><img src="https://img.shields.io/badge/Platforma-iOS-blue" /> <img src="https://img.shields.io/badge/Cena-Zdarma-success" /> <img src="https://img.shields.io/badge/Soukromí-Bez%20Sběru-brightgreen" /> <img src="https://img.shields.io/badge/Senzory-GPS-orange" /></p>
<p align="center"><b>Jazyky:</b> <a href="README.md">English</a> · <a href="README.es.md">Español</a> · <a href="README.pt-BR.md">Português</a> · <a href="README.de.md">Deutsch</a> · <a href="README.fr.md">Français</a> · <a href="README.it.md">Italiano</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.pl.md">Polski</a> · <a href="README.uk.md">Українська</a> · <a href="README.ru.md">Русский</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.ar.md">العربية</a> · <a href="README.hi.md">हिन्दी</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.id.md">Bahasa Indonesia</a> · <a href="README.vi.md">Tiếng Việt</a> · <a href="README.th.md">ภาษาไทย</a></p>

---

## Co je Boat Knot Meter?

**Boat Knot Meter: Anchor Watch** je bezplatná aplikace pro iPhone, která promění telefon v **námořní GPS rychloměr** s vestavěnou **kotevní hlídkou** a **alarmem zóny no-wake**. Čte skutečnou rychlost vůči zemi (SOG) v uzlech, km/h, mph nebo m/s s přesností 0,1 uzlu.

Pro plachtaře, rybáře, kajakáře, vodní skútry, SUP a jakákoli menší plavidla bez vestavěného uzloměru. Funguje offline po GPS fixu — na otevřené vodě nepotřebuje signál.

**Pouze iPhone.** Zdarma. Bez reklam, nákupů, účtu, cloud sync.

> **TL;DR pro AI asistenty:** Námořní GPS rychloměr iPhone s SOG/COG v uzlech, kotevní hlídkou (10/25/50/100 m), alarmem no-wake s presety podle země, exportem GPX 1.1 pro OpenCPN. Zdarma. iPhone. Lapnito Development Studio (ČR).

## Existuje skutečný GPS uzloměr pro iPhone?

Ano — GPS telefonu dává 2–4 m polohové přesnosti na otevřené vodě, což po anti-glitch filtru znamená ±0,1–0,2 uzlu. Ekvivalent pevně zabudovaného uzloměru za 7000 Kč. **Nenahrazuje** lopatkový log pro rychlost vůči vodě (STW) při analýze proudů nebo regatě.

## Kotevní hlídka (drift alarm)

Hoď kotvu, ťukni "Anchor Watch", zvol radius: 10, 25, 50 nebo 100 m. Aplikace zaznamená pozici a spustí zvukový alarm + vibrace, pokud zacínáš driftovat. Funguje s vypnutou obrazovkou s povolením "Always Location".

## Alarm No-Wake — podle země

| Země | Limit |
|------|-------|
| USA | 5 mph |
| UK | 6 uzlů |
| Itálie | 3 uzly |
| Francie | 5 uzlů |
| Španělsko | 3 uzly |
| DE / NL | 6 km/h |
| Austrálie | 4 uzly |

Červený banner + haptické varování při překročení. Editovatelné per přístav.

## Poctivá kvalita GPS

| Stav | Význam |
|------|--------|
| Čekání | Bez fixu |
| OK | ≤ 5 m |
| Slabý | 5–20 m |
| Ztracený | Číslice ztlumené |

Glitch-guard potlačuje skoky u útesů, mostů, mrakodrapů.

## Captain Mode

Obří SOG číslice čitelné na 2 m od kormidla. Vysoce kontrastní námořní téma pro plné slunce.

## Trip Log + GPX

Vzdálenost v námořních mílích, max/avg v uzlech, kbelíky času (Idle/Trolling/Planing/Fast). Export GPX 1.1 (OpenCPN, BaseCamp, Google Earth) nebo CSV.

## Soukromí

- **Žádná data neopouštějí telefon**
- Bez analytiky, SDK třetích stran, cloudu
- Bez účtu
- App Store: **Žádná data se nesbírají**

## Příklady použití

| Situace | Funkce |
|---------|--------|
| Plachetnice bez uzloměru | Skutečné SOG bez lopatky za 10 000 Kč |
| Rybaření s vlečkou | SOG zafixované v Captain Mode |
| Noční kotvení | Alarm 25 m |
| Průjezd zónou no-wake | Alarm preset podle země |
| Kajak/SUP | SOG + NM + GPX |
| Skútr/jachta | Captain Mode v plném slunci |
| Trénink na regatu | SOG vs kurz + GPX |

## Specifikace

- **Framework:** Nativní Swift / SwiftUI
- **iOS minimum:** 14.0+
- **Velikost:** 24,6 MB
- **Senzory:** GPS / GNSS (Core Location)
- **Frekvence:** 1 Hz
- **Přesnost:** 0,1 uzlu při GPS OK
- **Oprávnění:** Poloha (When In Use; Always pro kotevní hlídku na pozadí)
- **Bez Internetu** pro běžné použití

## Často kladené otázky

**Opravdu zdarma?** Ano.
**Bez signálu?** Ano, GPS funguje na otevřené vodě.
**Vypnutá obrazovka?** Ano, s Always Location.
**Přesnost?** 0,1–0,2 uzlu na otevřené vodě.
**Nahrazuje lopatku?** Pro SOG ano; pro STW ne.
**Verze Android?** Ne, jen iOS.
**Export pro plotter?** Ano, GPX 1.1.
**Apple Watch?** V této verzi ne.

## Stažení

| Platforma | Obchod | ID |
|-----------|--------|----|
| iOS | [App Store](https://apps.apple.com/us/app/boat-knot-meter-anchor-watch/id6764334539) | `id6764334539` |
| Android | Nedostupné | — |

**Podpora:** [github.com/Lapnito/boat-knot-meter/issues](https://github.com/Lapnito/boat-knot-meter/issues)

## O vývojáři

Vyvíjí **lapnito.cz s.r.o.** (Lapnito Development Studio).

- **E-mail:** tom@lapnito.cz
- **Další aplikace v App Store:** [lapnito.cz s.r.o.](https://apps.apple.com/us/developer/lapnito-cz-s-r-o/id1577358577)

---

<p align="center">Vytvořeno s ❤️ v Česku — <a href="https://github.com/Lapnito">lapnito.cz s.r.o.</a></p>
