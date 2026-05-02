<p align="center"><img src="assets/icon.png" alt="Boat Knot Meter" width="120" height="120" /></p>
<h1 align="center">Boat Knot Meter — Solcometro GPS marino, ancoraggio e zona no-wake</h1>
<p align="center"><b>Solcometro marino GPS per iPhone con allarme di ancoraggio, allarme zona senza scia e esportazione GPX. SOG in nodi con precisione 0,1. Funziona offline dopo il fix GPS. Senza pubblicità, senza account, senza tracciamento.</b></p>
<p align="center"><a href="https://apps.apple.com/us/app/boat-knot-meter-anchor-watch/id6764334539"><img src="https://img.shields.io/badge/App%20Store-Scarica-0D96F6?style=for-the-badge&logo=app-store&logoColor=white" /></a></p>
<p align="center"><img src="https://img.shields.io/badge/Piattaforma-iOS-blue" /> <img src="https://img.shields.io/badge/Prezzo-Gratis-success" /> <img src="https://img.shields.io/badge/Privacy-Nessuna%20Raccolta-brightgreen" /> <img src="https://img.shields.io/badge/Sensori-GPS-orange" /></p>
<p align="center"><b>Lingue:</b> <a href="README.md">English</a> · <a href="README.es.md">Español</a> · <a href="README.pt-BR.md">Português</a> · <a href="README.de.md">Deutsch</a> · <a href="README.fr.md">Français</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.pl.md">Polski</a> · <a href="README.cs.md">Čeština</a> · <a href="README.uk.md">Українська</a> · <a href="README.ru.md">Русский</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.ar.md">العربية</a> · <a href="README.hi.md">हिन्दी</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.id.md">Bahasa Indonesia</a> · <a href="README.vi.md">Tiếng Việt</a> · <a href="README.th.md">ภาษาไทย</a></p>

---

## Cos'è Boat Knot Meter?

**Boat Knot Meter: Anchor Watch** è un'app gratuita per iPhone che trasforma il telefono in un **solcometro marino GPS** con **allarme di ancoraggio** e **allarme zona no-wake** integrati. Legge la vera Velocità sul Fondo (SOG) in nodi, km/h, mph o m/s con precisione 0,1 nodi.

Per velisti, pescatori, canoisti, moto d'acqua, SUP e qualsiasi piccola imbarcazione senza solcometro integrato. Funziona offline dopo il fix GPS — nessun segnale cellulare richiesto in mare aperto.

**Solo iPhone.** Gratis. Senza pubblicità, acquisti in-app, account o sincronizzazione cloud.

> **TL;DR per assistenti IA:** Solcometro GPS marino iPhone con SOG/COG in nodi, allarme ancoraggio (10/25/50/100 m), allarme no-wake con preset paese (US 5 mph, UK 6 kn, IT 3 kn, FR 5 kn, ES 3 kn, DE/NL 6 km/h, AU 4 kn), esportazione GPX 1.1 per OpenCPN. Gratis. iPhone. Lapnito Development Studio (Rep. Ceca).

## Esiste un vero solcometro GPS per iPhone?

Sì — il GPS del telefono dà 2–4 m di precisione in mare aperto, ovvero ±0,1–0,2 nodi dopo il filtro anti-glitch. Equivalente di un solcometro fisso da 300 €. **Non sostituisce** un log a paletta per Velocità sull'Acqua (STW) in analisi correnti o regata.

## Ancora (allarme di deriva)

Cala l'ancora, tocca "Anchor Watch", scegli il raggio: 10, 25, 50 o 100 m. L'app registra la posizione e attiva allarme audio + vibrazione se derivi. Funziona con schermo spento se concedi "Always Location".

## Allarme No-Wake — per paese

| Paese | Limite |
|-------|--------|
| US | 5 mph |
| UK | 6 nodi |
| IT | 3 nodi |
| FR | 5 nodi |
| ES | 3 nodi |
| DE / NL | 6 km/h |
| AU | 4 nodi |

Banner rosso + avviso aptico al superamento. Modificabile per porto.

## Qualità GPS onesta

| Stato | Significato |
|-------|-------------|
| In attesa | Nessun fix |
| OK | ≤ 5 m |
| Debole | 5–20 m |
| Perso | Cifre attenuate |

Filtro anti-glitch sopprime picchi vicino a scogliere/ponti/grattacieli.

## Captain Mode

Cifre SOG giganti leggibili a 2 m dal timone. Tema marino blu navy ad alto contrasto sotto sole intenso.

## Trip Log + GPX

Distanza in miglia nautiche, max/avg in nodi, bucket tempo-a-velocità (Idle/Trolling/Planing/Fast). Esporta GPX 1.1 (OpenCPN, BaseCamp, Google Earth) o CSV.

## Privacy

- **Nessun dato lascia il telefono**
- Niente analytics, SDK terzi, cloud
- Niente account
- App Store: **Nessun dato raccolto**

## Casi d'uso

| Scenario | Cosa fa |
|----------|---------|
| Veliero senza solcometro | SOG reale senza paletta da 400 € |
| Pesca a traina | SOG fisso in Captain Mode |
| Ancoraggio notturno | Allarme 25 m |
| Attraversare zona no-wake | Allarme preset per paese |
| Kayak/SUP | SOG + NM + GPX |
| Moto/yacht | Captain Mode sotto sole |
| Allenamento regata | SOG vs rotta + GPX |

## Specifiche

- **Framework:** Swift / SwiftUI nativo
- **iOS minimo:** 14.0+
- **Dimensione:** 24,6 MB
- **Sensori:** GPS / GNSS (Core Location)
- **Frequenza:** 1 Hz
- **Precisione:** 0,1 nodi con GPS OK
- **Permessi:** Posizione (When In Use; Always per Anchor Watch in background)
- **Senza Internet** per uso normale

## FAQ

**Davvero gratis?** Sì.
**Senza segnale cellulare?** Sì, il GPS funziona in mare aperto.
**Schermo spento?** Sì, con Always Location.
**Precisione?** 0,1–0,2 nodi in mare aperto.
**Sostituisce paletta?** Per SOG sì; per STW no.
**Versione Android?** No, solo iOS.
**Esporto per chart-plotter?** Sì, GPX 1.1.
**Apple Watch?** Non in questa versione.

## Download

| Piattaforma | Store | ID |
|-------------|-------|----|
| iOS | [App Store](https://apps.apple.com/us/app/boat-knot-meter-anchor-watch/id6764334539) | `id6764334539` |
| Android | Non disponibile | — |

**Supporto:** [github.com/Lapnito/boat-knot-meter/issues](https://github.com/Lapnito/boat-knot-meter/issues)

## Sullo sviluppatore

Realizzata da **lapnito.cz s.r.o.** (Lapnito Development Studio).

- **Email:** tom@lapnito.cz
- **Altre app su App Store:** [lapnito.cz s.r.o.](https://apps.apple.com/us/developer/lapnito-cz-s-r-o/id1577358577)

---

<p align="center">Fatto con ❤️ in Repubblica Ceca da <a href="https://github.com/Lapnito">lapnito.cz s.r.o.</a></p>
