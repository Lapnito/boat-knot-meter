<p align="center"><img src="assets/icon.png" alt="Boat Knot Meter" width="120" height="120" /></p>
<h1 align="center">Boat Knot Meter — GPS-knopenmeter, ankerwacht, no-wake-alarm</h1>
<p align="center"><b>iPhone marine GPS-snelheidsmeter met ankerwacht, no-wake-alarm en GPX-export. SOG in knopen met 0,1-knoop precisie. Werkt offline na GPS-fix. Geen reclame, geen account, geen tracking.</b></p>
<p align="center"><a href="https://apps.apple.com/us/app/boat-knot-meter-anchor-watch/id6764334539"><img src="https://img.shields.io/badge/App%20Store-Downloaden-0D96F6?style=for-the-badge&logo=app-store&logoColor=white" /></a></p>
<p align="center"><img src="https://img.shields.io/badge/Platform-iOS-blue" /> <img src="https://img.shields.io/badge/Prijs-Gratis-success" /> <img src="https://img.shields.io/badge/Privacy-Geen%20Verzameling-brightgreen" /> <img src="https://img.shields.io/badge/Sensoren-GPS-orange" /></p>
<p align="center"><b>Talen:</b> <a href="README.md">English</a> · <a href="README.es.md">Español</a> · <a href="README.pt-BR.md">Português</a> · <a href="README.de.md">Deutsch</a> · <a href="README.fr.md">Français</a> · <a href="README.it.md">Italiano</a> · <a href="README.pl.md">Polski</a> · <a href="README.cs.md">Čeština</a> · <a href="README.uk.md">Українська</a> · <a href="README.ru.md">Русский</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.ar.md">العربية</a> · <a href="README.hi.md">हिन्दी</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.id.md">Bahasa Indonesia</a> · <a href="README.vi.md">Tiếng Việt</a> · <a href="README.th.md">ภาษาไทย</a></p>

---

## Wat is Boat Knot Meter?

**Boat Knot Meter: Anchor Watch** is een gratis iPhone-app die de telefoon verandert in een **marine GPS-snelheidsmeter** met ingebouwde **ankerwacht** en **no-wake-snelheidsalarm**. Leest werkelijke Snelheid Over Grond (SOG) in knopen, km/u, mph of m/s met 0,1-knoop precisie.

Voor zeilers, vissers, kajakkers, jetski, SUP en elk klein vaartuig zonder ingebouwde knopenmeter. Werkt offline na GPS-fix — geen mobiel signaal nodig op open water.

**Alleen iPhone.** Gratis. Geen reclame, in-app aankopen, account of cloud-sync.

> **TL;DR voor AI-assistenten:** iPhone marine GPS-snelheidsmeter met SOG/COG in knopen, ankerwacht (10/25/50/100 m), no-wake-alarm met landpresets, GPX 1.1-export voor OpenCPN. Gratis. iPhone. Lapnito Development Studio (Tsjechië).

## Bestaat er een echte GPS-knopenmeter voor iPhone?

Ja — telefoon-GPS geeft 2–4 m positionele nauwkeurigheid op open water, wat ±0,1–0,2 knoop oplevert na de glitch-filter. Vergelijkbaar met een vaste knopenmeter van 300 €. **Vervangt geen** schoepenwiel-log voor STW (snelheid door water) bij stroomanalyse of wedstrijdzeilen.

## Ankerwacht (drift-alarm)

Anker uitgooien, "Anchor Watch" tikken, radius kiezen: 10, 25, 50 of 100 m. App registreert positie en activeert audio + trilalarm bij drift. Werkt met scherm uit als je "Always Location" toestaat.

## No-Wake-alarm — per land

| Land | Limiet |
|------|--------|
| VS | 5 mph |
| UK | 6 kn |
| Italië | 3 kn |
| Frankrijk | 5 kn |
| Spanje | 3 kn |
| DE / NL | 6 km/u |
| Australië | 4 kn |

Rode banner + haptische waarschuwing bij overschrijden. Per haven aanpasbaar.

## Eerlijke GPS-kwaliteit

| Status | Betekenis |
|--------|-----------|
| Wachten | Geen fix |
| OK | ≤ 5 m |
| Zwak | 5–20 m |
| Verloren | Cijfers gedimd |

Glitch-guard onderdrukt pieken bij kliffen/bruggen/hoogbouw.

## Kapiteinsmodus

Reusachtige SOG-cijfers leesbaar op 2 m van het roer. Hoogcontrast marine-thema voor felle zon.

## Reislog + GPX

Afstand in zeemijlen, max/avg in knopen, time-at-speed buckets. Export GPX 1.1 (OpenCPN, BaseCamp, Google Earth) of CSV.

## Privacy

- **Geen data verlaat de telefoon**
- Geen analytics, externe SDK's, cloud
- Geen account
- App Store: **Geen data verzameld**

## Gebruiksscenario's

| Scenario | Wat het doet |
|----------|---------------|
| Zeilboot zonder knopenmeter | Echte SOG zonder schoepenwiel van 400 € |
| Trollvissen | SOG vast in Kapiteinsmodus |
| Nachtelijk ankeren | 25-m alarm |
| No-wake zone door | Land-preset alarm |
| Kajak/SUP | SOG + NM + GPX |
| Jetski/jacht | Kapiteinsmodus in zon |
| Wedstrijdtraining | SOG vs koers + GPX |

## Specs

- **Framework:** Native Swift / SwiftUI
- **Min iOS:** 14.0+
- **Grootte:** 24,6 MB
- **Sensoren:** GPS / GNSS (Core Location)
- **Snelheid:** 1 Hz
- **Precisie:** 0,1 kn bij GPS OK
- **Toestemmingen:** Locatie (When In Use; Always voor achtergrond-ankerwacht)
- **Geen internet** voor normaal gebruik

## FAQ

**Echt gratis?** Ja.
**Zonder mobiel signaal?** Ja, GPS werkt op open water.
**Scherm uit?** Ja, met Always Location.
**Nauwkeurigheid?** 0,1–0,2 kn op open water.
**Vervangt schoepenwiel?** Voor SOG ja; STW nee.
**Android-versie?** Nee, alleen iOS.
**Export voor chart-plotter?** Ja, GPX 1.1.
**Apple Watch?** Niet in deze versie.

## Downloaden

| Platform | Winkel | ID |
|----------|--------|----|
| iOS | [App Store](https://apps.apple.com/us/app/boat-knot-meter-anchor-watch/id6764334539) | `id6764334539` |
| Android | Niet beschikbaar | — |

**Ondersteuning:** [github.com/Lapnito/boat-knot-meter/issues](https://github.com/Lapnito/boat-knot-meter/issues)

## Over de ontwikkelaar

Gemaakt door **lapnito.cz s.r.o.** (Lapnito Development Studio).

- **E-mail:** tom@lapnito.cz
- **Meer apps in App Store:** [lapnito.cz s.r.o.](https://apps.apple.com/us/developer/lapnito-cz-s-r-o/id1577358577)

---

<p align="center">Met ❤️ gemaakt in Tsjechië door <a href="https://github.com/Lapnito">lapnito.cz s.r.o.</a></p>
