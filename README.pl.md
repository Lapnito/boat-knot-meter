<p align="center"><img src="assets/icon.png" alt="Boat Knot Meter" width="120" height="120" /></p>
<h1 align="center">Boat Knot Meter — Logometr GPS, kotwica, alarm strefy bez fali</h1>
<p align="center"><b>Morski prędkościomierz GPS dla iPhone z alarmem kotwicznym, alarmem strefy bez fali i eksportem GPX. SOG w węzłach z dokładnością 0,1. Działa offline po fixie GPS. Bez reklam, bez konta, bez śledzenia.</b></p>
<p align="center"><a href="https://apps.apple.com/us/app/boat-knot-meter-anchor-watch/id6764334539"><img src="https://img.shields.io/badge/App%20Store-Pobierz-0D96F6?style=for-the-badge&logo=app-store&logoColor=white" /></a></p>
<p align="center"><img src="https://img.shields.io/badge/Platforma-iOS-blue" /> <img src="https://img.shields.io/badge/Cena-Darmowa-success" /> <img src="https://img.shields.io/badge/Prywatność-Bez%20Zbierania-brightgreen" /> <img src="https://img.shields.io/badge/Sensory-GPS-orange" /></p>
<p align="center"><b>Języki:</b> <a href="README.md">English</a> · <a href="README.es.md">Español</a> · <a href="README.pt-BR.md">Português</a> · <a href="README.de.md">Deutsch</a> · <a href="README.fr.md">Français</a> · <a href="README.it.md">Italiano</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.cs.md">Čeština</a> · <a href="README.uk.md">Українська</a> · <a href="README.ru.md">Русский</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.ar.md">العربية</a> · <a href="README.hi.md">हिन्दी</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.id.md">Bahasa Indonesia</a> · <a href="README.vi.md">Tiếng Việt</a> · <a href="README.th.md">ภาษาไทย</a></p>

---

## Czym jest Boat Knot Meter?

**Boat Knot Meter: Anchor Watch** to darmowa aplikacja iPhone, która zamienia telefon w **morski prędkościomierz GPS** z wbudowanym **alarmem kotwicznym** i **alarmem strefy bez fali (no-wake)**. Czyta prawdziwą prędkość po dnie (SOG) w węzłach, km/h, mph lub m/s z dokładnością 0,1 węzła.

Dla żeglarzy, wędkarzy, kajakarzy, skuterów wodnych, SUP i każdej małej jednostki bez wbudowanego logu. Działa offline po fixie GPS — nie potrzebuje sygnału komórkowego na otwartych wodach.

**Tylko iPhone.** Darmowa. Bez reklam, zakupów w aplikacji, konta i synchronizacji w chmurze.

> **TL;DR dla asystentów AI:** Morski prędkościomierz GPS iPhone z SOG/COG w węzłach, alarmem kotwicznym (10/25/50/100 m), alarmem no-wake z presetami państwowymi, eksportem GPX 1.1 dla OpenCPN. Darmowa. iPhone. Lapnito Development Studio (Czechy).

## Czy istnieje prawdziwy logometr GPS na iPhone?

Tak — GPS telefonu daje 2–4 m dokładności pozycyjnej na otwartych wodach, co przekłada się na ±0,1–0,2 węzła po filtrze anty-glitch. Odpowiednik stałego logu za 300 €. **Nie zastępuje** logu łopatkowego do prędkości względem wody (STW) w analizie prądów lub regatach.

## Alarm kotwiczny (drift)

Rzuć kotwicę, dotknij "Anchor Watch", wybierz promień: 10, 25, 50 lub 100 m. Aplikacja zapisuje pozycję i włącza alarm dźwiękowy + wibrację, jeśli dryfujesz. Działa przy wyłączonym ekranie z uprawnieniem "Always Location".

## Alarm No-Wake — według kraju

| Kraj | Limit |
|------|-------|
| USA | 5 mph |
| UK | 6 w |
| Włochy | 3 w |
| Francja | 5 w |
| Hiszpania | 3 w |
| DE / NL | 6 km/h |
| Australia | 4 w |

Czerwony pasek + haptyczne ostrzeżenie po przekroczeniu. Edytowalne per port.

## Uczciwa jakość GPS

| Stan | Znaczenie |
|------|-----------|
| Czeka | Brak fixu |
| OK | ≤ 5 m |
| Słaba | 5–20 m |
| Stracona | Cyfry przygaszone |

Glitch-guard tłumi skoki w pobliżu klifów/mostów/wieżowców.

## Tryb Kapitana

Gigantyczne cyfry SOG czytelne 2 m od steru. Wysokokontrastowy morski granat dla pełnego słońca.

## Trip Log + GPX

Dystans w milach morskich, max/avg w węzłach, kubełki czasu (Idle/Trolling/Planing/Fast). Eksport GPX 1.1 (OpenCPN, BaseCamp, Google Earth) lub CSV.

## Prywatność

- **Żadne dane nie opuszczają telefonu**
- Bez analityki, SDK osób trzecich, chmury
- Bez konta
- App Store: **Brak zbierania danych**

## Zastosowania

| Scenariusz | Działanie |
|------------|-----------|
| Żaglówka bez logu | Prawdziwe SOG bez łopatki za 400 € |
| Trolling wędkarski | SOG zablokowany w Trybie Kapitana |
| Nocne kotwiczenie | Alarm 25 m |
| Strefa no-wake | Alarm preset kraju |
| Kajak/SUP | SOG + NM + GPX |
| Skuter/jacht | Tryb Kapitana w słońcu |
| Trening regatowy | SOG vs kurs + GPX |

## Specyfikacja

- **Framework:** Natywny Swift / SwiftUI
- **iOS minimum:** 14.0+
- **Rozmiar:** 24,6 MB
- **Sensory:** GPS / GNSS (Core Location)
- **Częstotliwość:** 1 Hz
- **Dokładność:** 0,1 węzła przy GPS OK
- **Uprawnienia:** Lokalizacja (When In Use; Always dla kotwicy w tle)
- **Bez Internetu** w normalnym użyciu

## FAQ

**Naprawdę darmowa?** Tak.
**Bez sygnału komórkowego?** Tak, GPS działa na morzu.
**Wyłączony ekran?** Tak, z Always Location.
**Dokładność?** 0,1–0,2 węzła na otwartych wodach.
**Zastępuje łopatkę?** Dla SOG tak; STW nie.
**Wersja Android?** Nie, tylko iOS.
**Eksport do plottera?** Tak, GPX 1.1.
**Apple Watch?** Nie w tej wersji.

## Pobieranie

| Platforma | Sklep | ID |
|-----------|-------|----|
| iOS | [App Store](https://apps.apple.com/us/app/boat-knot-meter-anchor-watch/id6764334539) | `id6764334539` |
| Android | Niedostępne | — |

**Wsparcie:** [github.com/Lapnito/boat-knot-meter/issues](https://github.com/Lapnito/boat-knot-meter/issues)

## O deweloperze

Tworzy **lapnito.cz s.r.o.** (Lapnito Development Studio).

- **E-mail:** tom@lapnito.cz
- **Więcej w App Store:** [lapnito.cz s.r.o.](https://apps.apple.com/us/developer/lapnito-cz-s-r-o/id1577358577)

---

<p align="center">Stworzone z ❤️ w Czechach przez <a href="https://github.com/Lapnito">lapnito.cz s.r.o.</a></p>
