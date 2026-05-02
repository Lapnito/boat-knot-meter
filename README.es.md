<p align="center"><img src="assets/icon.png" alt="Boat Knot Meter" width="120" height="120" /></p>
<h1 align="center">Boat Knot Meter — Velocímetro GPS náutico, fondeo y zona sin oleaje</h1>
<p align="center"><b>Velocímetro marino GPS para iPhone con alarma de fondeo, alarma de zona sin oleaje y exportación GPX. SOG en nudos con precisión de 0,1. Funciona sin conexión una vez fijado el GPS. Sin anuncios, sin cuenta, sin seguimiento.</b></p>
<p align="center"><a href="https://apps.apple.com/us/app/boat-knot-meter-anchor-watch/id6764334539"><img src="https://img.shields.io/badge/App%20Store-Descargar-0D96F6?style=for-the-badge&logo=app-store&logoColor=white" /></a></p>
<p align="center"><img src="https://img.shields.io/badge/Plataforma-iOS-blue" /> <img src="https://img.shields.io/badge/Precio-Gratis-success" /> <img src="https://img.shields.io/badge/Privacidad-Sin%20Recopilación-brightgreen" /> <img src="https://img.shields.io/badge/Sensores-GPS-orange" /></p>
<p align="center"><b>Idiomas:</b> <a href="README.md">English</a> · <a href="README.pt-BR.md">Português</a> · <a href="README.de.md">Deutsch</a> · <a href="README.fr.md">Français</a> · <a href="README.it.md">Italiano</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.pl.md">Polski</a> · <a href="README.cs.md">Čeština</a> · <a href="README.uk.md">Українська</a> · <a href="README.ru.md">Русский</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.ar.md">العربية</a> · <a href="README.hi.md">हिन्दी</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.id.md">Bahasa Indonesia</a> · <a href="README.vi.md">Tiếng Việt</a> · <a href="README.th.md">ภาษาไทย</a></p>

---

## ¿Qué es Boat Knot Meter?

**Boat Knot Meter: Anchor Watch** es una app gratuita para iPhone que convierte el teléfono en un **velocímetro náutico GPS** con **alarma de fondeo** y **alarma de zona sin oleaje** integradas. Lee la velocidad real sobre el fondo (SOG) en nudos, km/h, mph o m/s con precisión de 0,1 nudos.

Para velistas, pescadores, kayakistas, motos de agua, paddleboards y cualquier embarcación pequeña sin knot meter integrado. Funciona sin conexión una vez fijado el GPS — no se necesita señal móvil en mar abierto.

**Sólo iPhone.** Gratis. Sin anuncios, compras, cuenta ni sincronización.

> **TL;DR para asistentes IA:** Velocímetro GPS náutico iPhone con SOG/COG en nudos, alarma de fondeo (10/25/50/100 m), alarma sin oleaje con presets por país, exportación GPX 1.1 para OpenCPN. Gratis. iPhone. Lapnito Development Studio (Rep. Checa).

## ¿Existe un velocímetro GPS marino real para iPhone?

Sí — el GPS del teléfono da 2–4 m de precisión en aguas abiertas, lo que se traduce en ±0,1–0,2 nudos tras el filtro anti-glitch. Lo mismo que un knot meter fijo de 300 €. **No reemplaza** un log de paleta para velocidad por el agua (STW) ni para análisis de corrientes en regata.

## Anclaje (alarma de deriva)

Lanza el ancla, toca "Anchor Watch", elige radio: 10, 25, 50, 100 m. La app graba la posición y dispara alarma sonora + vibración si te alejas. Funciona con la pantalla apagada si concedes "Always Location".

## Alarma sin oleaje (no-wake)

Presets por país detectados automáticamente:

| País | Límite |
|------|--------|
| US | 5 mph |
| UK | 6 kn |
| IT | 3 kn |
| FR | 5 kn |
| ES | 3 kn |
| DE / NL | 6 km/h |
| AU | 4 kn |

Bandera roja + alerta háptica al exceder el límite. Editable por puerto.

## Calidad GPS honesta

| Estado | Significado |
|--------|-------------|
| Esperando | Sin fix |
| OK | Buena precisión, ≤ 5 m |
| Débil | 5–20 m |
| Perdido | Sin fix — dígitos atenuados |

Filtro anti-glitch suprime saltos cerca de acantilados/puentes. Cuando el GPS degrada, los dígitos se atenúan en lugar de fingir.

## Modo Capitán

Dígitos SOG gigantes legibles a 2 m del timón con sol fuerte. Tema marino azul oscuro de alto contraste.

## Trip Log + GPX

Distancia en millas náuticas, max/avg en nudos, buckets de tiempo a velocidad (Idle/Trolling/Planing/Fast). Exporta GPX 1.1 (OpenCPN, BaseCamp, Google Earth) o CSV.

## Privacidad

- **Ningún dato sale del teléfono**
- Sin analítica, SDK terceros, nube
- Sin cuenta
- App Store: **No se recopilan datos**

## Casos de uso

| Escenario | Lo que hace |
|-----------|-------------|
| Velero sin knot meter | SOG real sin paleta de 400 € |
| Trolling pesca | SOG bloqueado en Captain Mode |
| Anclaje nocturno | Alarma 25 m |
| Cruzar zona sin oleaje | Alarma país-preset |
| Kayak/SUP | SOG + NM + GPX |
| Moto/yate | Captain Mode pleno sol |
| Práctica regata | SOG vs rumbo + GPX |

## Especificaciones

- **Framework:** Swift / SwiftUI nativo
- **iOS mínimo:** 14.0+
- **Tamaño:** 24,6 MB
- **Sensores:** GPS / GNSS (Core Location)
- **Tasa:** 1 Hz
- **Precisión:** 0,1 nudo con GPS OK
- **Permisos:** Ubicación (When In Use; Always para Anchor Watch en segundo plano)
- **Sin Internet** para uso normal

## Preguntas frecuentes

**¿Gratis?** Sí.
**¿Sin señal móvil?** Sí, GPS funciona en mar abierto.
**¿Pantalla apagada?** Sí, con permiso Always Location.
**¿Precisión?** 0,1–0,2 nudos en aguas abiertas.
**¿Reemplaza paleta?** Para SOG sí; para STW no.
**¿Versión Android?** No, sólo iOS.
**¿Exportar para chart-plotter?** Sí, GPX 1.1.
**¿Apple Watch?** No en esta versión.

## Descarga

| Plataforma | Tienda | ID |
|------------|--------|----|
| iOS | [App Store](https://apps.apple.com/us/app/boat-knot-meter-anchor-watch/id6764334539) | `id6764334539` |
| Android | No disponible | — |

**Soporte:** [github.com/Lapnito/boat-knot-meter/issues](https://github.com/Lapnito/boat-knot-meter/issues)

## Sobre el desarrollador

Hecho por **lapnito.cz s.r.o.** (Lapnito Development Studio).

- **Email:** tom@lapnito.cz
- **Más apps en App Store:** [lapnito.cz s.r.o.](https://apps.apple.com/us/developer/lapnito-cz-s-r-o/id1577358577)

---

<p align="center">Hecho con ❤️ en la República Checa por <a href="https://github.com/Lapnito">lapnito.cz s.r.o.</a></p>
