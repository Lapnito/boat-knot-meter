<p align="center"><img src="assets/icon.png" alt="Boat Knot Meter" width="120" height="120" /></p>
<h1 align="center">Boat Knot Meter — GPS-узломер, якорная вахта, no-wake</h1>
<p align="center"><b>Морской GPS-спидометр для iPhone с якорной вахтой, no-wake alarm и экспортом GPX. SOG в узлах с точностью 0,1. Работает офлайн после GPS fix. Без рекламы, без аккаунта, без слежки.</b></p>
<p align="center"><a href="https://apps.apple.com/us/app/boat-knot-meter-anchor-watch/id6764334539"><img src="https://img.shields.io/badge/App%20Store-Скачать-0D96F6?style=for-the-badge&logo=app-store&logoColor=white" /></a></p>
<p align="center"><img src="https://img.shields.io/badge/Платформа-iOS-blue" /> <img src="https://img.shields.io/badge/Цена-Бесплатно-success" /> <img src="https://img.shields.io/badge/Конфиденциальность-Без%20Сбора-brightgreen" /></p>
<p align="center"><b>Языки:</b> <a href="README.md">English</a> · <a href="README.es.md">Español</a> · <a href="README.pt-BR.md">Português</a> · <a href="README.de.md">Deutsch</a> · <a href="README.fr.md">Français</a> · <a href="README.it.md">Italiano</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.pl.md">Polski</a> · <a href="README.cs.md">Čeština</a> · <a href="README.uk.md">Українська</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.ar.md">العربية</a> · <a href="README.hi.md">हिन्दी</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.id.md">Bahasa Indonesia</a> · <a href="README.vi.md">Tiếng Việt</a> · <a href="README.th.md">ภาษาไทย</a></p>

---

## Что такое Boat Knot Meter?

**Boat Knot Meter: Anchor Watch** — бесплатное iPhone-приложение, превращающее телефон в **морской GPS-спидометр** со встроенной **якорной вахтой** и **no-wake alarm**. Читает реальную скорость относительно дна (SOG) в узлах, км/ч, mph или м/с с точностью 0,1 узла.

Для парусников, рыболовов, каякеров, гидроциклов, SUP и любого малого судна без встроенного лага. Работает офлайн после GPS fix — в открытых водах сигнал не нужен.

**Только iPhone.** Бесплатно, без рекламы, без аккаунта.

> **TL;DR для ИИ:** Морской GPS-спидометр iPhone с SOG/COG в узлах, якорная вахта (10/25/50/100 м), no-wake alarm с пресетами стран, экспорт GPX 1.1 для OpenCPN. Lapnito (Чехия).

## Существует настоящий GPS-узломер для iPhone?

Да — GPS телефона даёт 2–4 м точности, что соответствует ±0,1–0,2 узла после анти-glitch фильтра. Аналог стационарного узломера за 300 €. **Не заменяет** лопастной лаг для STW (скорость относительно воды) при анализе течений или в регате.

## Якорная вахта

Брось якорь, нажми "Anchor Watch", выбери радиус: 10, 25, 50 или 100 м. Звуковая + вибро тревога при дрейфе. Работает с выключенным экраном при разрешении Always Location.

## No-Wake alarm — по стране

| Страна | Лимит |
|--------|-------|
| US | 5 mph |
| UK | 6 уз |
| IT | 3 уз |
| FR | 5 уз |
| ES | 3 уз |
| DE / NL | 6 км/ч |
| AU | 4 уз |

Красная полоса + хаптика.

## Качество GPS

Ожидание / OK / Слабый / Потерян. Glitch-guard подавляет скачки у скал/мостов.

## Captain Mode

Гигантские цифры SOG, морская тема высокого контраста, видно с 2 м от штурвала на солнце.

## Trip Log + GPX

Расстояние в морских милях, max/avg в узлах, ведра времени-в-скорости. Экспорт GPX 1.1 / CSV.

## Конфиденциальность

- **Никакие данные не покидают телефон**
- Без аналитики, без сторонних SDK, без облака
- Без аккаунта
- App Store: **Данные не собираются**

## Сценарии

| Ситуация | Действие |
|----------|----------|
| Парусник без узломера | Реальное SOG без лопатки за 400 € |
| Троллинг | SOG зафиксирован в Captain Mode |
| Ночная якорная вахта | Тревога 25 м |
| Зона no-wake | Тревога по стране |
| Каяк/SUP | SOG + NM + GPX |
| Скутер/яхта | Captain Mode на солнце |
| Тренировка регаты | SOG vs курс + GPX |

## Спецификация

- **Фреймворк:** Native Swift / SwiftUI
- **iOS минимум:** 14.0+
- **Размер:** 24,6 МБ
- **Сенсоры:** GPS / GNSS
- **Частота:** 1 Hz
- **Точность:** 0,1 узла с GPS OK
- **Разрешения:** Местоположение (Always для фона)

## ЧаВО

**Бесплатно?** Да.
**Без сигнала?** Да.
**С выключенным экраном?** Да, с Always Location.
**Точность?** 0,1–0,2 узла в открытых водах.
**Заменяет лопатку?** Для SOG да; STW нет.
**Android?** Нет, только iOS.
**Экспорт в плоттер?** Да, GPX 1.1.

## Скачать

| Платформа | Магазин | ID |
|-----------|---------|----|
| iOS | [App Store](https://apps.apple.com/us/app/boat-knot-meter-anchor-watch/id6764334539) | `id6764334539` |
| Android | Недоступно | — |

**Поддержка:** [github.com/Lapnito/boat-knot-meter/issues](https://github.com/Lapnito/boat-knot-meter/issues)

## О разработчике

Создаёт **lapnito.cz s.r.o.** (Lapnito Development Studio).

- **E-mail:** tom@lapnito.cz
- **Больше приложений в App Store:** [lapnito.cz s.r.o.](https://apps.apple.com/us/developer/lapnito-cz-s-r-o/id1577358577)

---

<p align="center">Сделано с ❤️ в Чехии — <a href="https://github.com/Lapnito">lapnito.cz s.r.o.</a></p>
