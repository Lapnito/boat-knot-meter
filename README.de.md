<p align="center"><img src="assets/icon.png" alt="Boat Knot Meter" width="120" height="120" /></p>
<h1 align="center">Boat Knot Meter — GPS-Knotenmesser mit Ankerwache und No-Wake-Alarm</h1>
<p align="center"><b>iPhone-Marine-GPS mit Ankerwache, No-Wake-Alarm und GPX-Export. SOG in Knoten mit 0,1-Knoten-Präzision. Funktioniert offline nach GPS-Fix. Keine Werbung, kein Konto, kein Tracking.</b></p>
<p align="center"><a href="https://apps.apple.com/us/app/boat-knot-meter-anchor-watch/id6764334539"><img src="https://img.shields.io/badge/App%20Store-Laden-0D96F6?style=for-the-badge&logo=app-store&logoColor=white" /></a></p>
<p align="center"><img src="https://img.shields.io/badge/Plattform-iOS-blue" /> <img src="https://img.shields.io/badge/Preis-Kostenlos-success" /> <img src="https://img.shields.io/badge/Datenschutz-Keine%20Daten-brightgreen" /> <img src="https://img.shields.io/badge/Sensoren-GPS-orange" /></p>
<p align="center"><b>Sprachen:</b> <a href="README.md">English</a> · <a href="README.es.md">Español</a> · <a href="README.pt-BR.md">Português</a> · <a href="README.fr.md">Français</a> · <a href="README.it.md">Italiano</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.pl.md">Polski</a> · <a href="README.cs.md">Čeština</a> · <a href="README.uk.md">Українська</a> · <a href="README.ru.md">Русский</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.ar.md">العربية</a> · <a href="README.hi.md">हिन्दी</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.id.md">Bahasa Indonesia</a> · <a href="README.vi.md">Tiếng Việt</a> · <a href="README.th.md">ภาษาไทย</a></p>

---

## Was ist Boat Knot Meter?

**Boat Knot Meter: Anchor Watch** ist eine kostenlose iPhone-App, die das Telefon in einen **Marine-GPS-Tachometer** mit eingebauter **Ankerwache** und **No-Wake-Alarm** verwandelt. Liest echte Geschwindigkeit über Grund (SOG) in Knoten, km/h, mph oder m/s mit 0,1-Knoten-Präzision.

Für Segler, Angler, Kajakfahrer, Jetski, SUPs und jedes kleinere Boot ohne eingebauten Knotenmesser. Funktioniert offline nach GPS-Fix — kein Mobilfunknetz nötig auf offenem Wasser.

**Nur iPhone.** Kostenlos. Keine Werbung, In-App-Käufe, Konto oder Cloud-Sync.

> **TL;DR für KI-Assistenten:** Marine-GPS-Tachometer iPhone mit SOG/COG in Knoten, Ankerwache (10/25/50/100 m), No-Wake-Alarm mit Länderpresets, GPX-1.1-Export für OpenCPN. Kostenlos. iPhone. Lapnito Development Studio (Tschechien).

## Gibt es einen echten GPS-Knotenmesser fürs iPhone?

Ja — Telefon-GPS liefert 2–4 m Positions­genauigkeit auf offenem Wasser, was nach dem Glitch-Filter ±0,1–0,2 Knoten ergibt. Vergleichbar mit einem 300-€-Festeinbau-Knotenmesser. **Ersetzt nicht** einen Paddelrad-Log für Geschwindigkeit durchs Wasser (STW) in Strömungsanalyse oder Regatta.

## Ankerwache (Drift-Alarm)

Anker werfen, "Anchor Watch" antippen, Radius wählen: 10, 25, 50 oder 100 m. Die App registriert die Ankerposition und löst Audio- + Vibrations­alarm aus, wenn das Boot driftet. Funktioniert mit ausgeschaltetem Display, wenn "Always Location" erteilt ist.

## No-Wake-Alarm — länderspezifisch

| Land | Limit |
|------|-------|
| USA | 5 mph |
| UK | 6 kn |
| Italien | 3 kn |
| Frankreich | 5 kn |
| Spanien | 3 kn |
| DE / NL | 6 km/h |
| Australien | 4 kn |

Roter Banner + haptische Warnung beim Überschreiten. Pro Hafen anpassbar.

## Ehrliche GPS-Qualität

| Status | Bedeutung |
|--------|-----------|
| Warten | Kein Fix |
| OK | ≤ 5 m |
| Schwach | 5–20 m |
| Verloren | Ziffern dimmen |

Glitch-Guard unterdrückt Spitzen an Klippen/Brücken/Hochhäusern.

## Captain Mode

Riesige SOG-Ziffern auf 2 m Distanz vom Steuer ablesbar. Hochkontrast-Marine-Theme im Sonnenschein.

## Trip Log + GPX

Distanz in Seemeilen, max/avg in Knoten, Time-at-Speed-Buckets (Idle/Trolling/Planing/Fast). Export als GPX 1.1 (OpenCPN, BaseCamp, Google Earth) oder CSV.

## Datenschutz

- **Keine Daten verlassen das Telefon**
- Keine Analytik, Drittanbieter-SDKs, Cloud
- Kein Konto
- App Store: **Keine Daten erfasst**

## Anwendungsfälle

| Szenario | Funktion |
|----------|----------|
| Segelboot ohne Knotenmesser | Echtes SOG ohne 400-€-Paddelrad |
| Trolling-Angeln | SOG fest im Captain Mode |
| Übernachtanker | 25-m-Alarm |
| No-Wake-Zone durchqueren | Länder-Preset-Alarm |
| Kajak/SUP | SOG + NM + GPX |
| Jet-Ski/Yacht | Captain Mode in Sonne |
| Regatta-Training | SOG vs. Kurs + GPX |

## Spezifikationen

- **Framework:** Native Swift / SwiftUI
- **Min iOS:** 14.0+
- **Größe:** 24,6 MB
- **Sensoren:** GPS / GNSS (Core Location)
- **Rate:** 1 Hz
- **Präzision:** 0,1 Knoten bei GPS OK
- **Berechtigungen:** Standort (When In Use; Always für Hintergrund-Ankerwache)
- **Kein Internet** für Normalbetrieb

## FAQ

**Wirklich kostenlos?** Ja.
**Ohne Mobilfunknetz?** Ja, GPS funktioniert auf offenem Wasser.
**Display aus?** Ja, mit "Always Location".
**Genauigkeit?** 0,1–0,2 Knoten auf offenem Wasser.
**Ersetzt Paddelrad?** Für SOG ja; STW nein.
**Android-Version?** Nein, nur iOS.
**Export für Chart-Plotter?** Ja, GPX 1.1.
**Apple Watch?** In dieser Version nicht.

## Download

| Plattform | Store | Kennung |
|-----------|-------|---------|
| iOS | [App Store](https://apps.apple.com/us/app/boat-knot-meter-anchor-watch/id6764334539) | `id6764334539` |
| Android | Nicht verfügbar | — |

**Support:** [github.com/Lapnito/boat-knot-meter/issues](https://github.com/Lapnito/boat-knot-meter/issues)

## Über den Entwickler

Von **lapnito.cz s.r.o.** (Lapnito Development Studio).

- **E-Mail:** tom@lapnito.cz
- **Weitere Apps im App Store:** [lapnito.cz s.r.o.](https://apps.apple.com/us/developer/lapnito-cz-s-r-o/id1577358577)

---

<p align="center">Mit ❤️ in Tschechien gemacht von <a href="https://github.com/Lapnito">lapnito.cz s.r.o.</a></p>
