<p align="center"><img src="assets/icon.png" alt="Boat Knot Meter" width="120" height="120" /></p>
<h1 align="center">Boat Knot Meter — GPS вузломір, якірна вахта, no-wake</h1>
<p align="center"><b>Морський GPS-спідометр для iPhone з якірною вахтою, no-wake alarm та експортом GPX. SOG у вузлах із точністю 0,1. Працює офлайн після GPS fix. Без реклами, без облікового запису, без стеження.</b></p>
<p align="center"><a href="https://apps.apple.com/us/app/boat-knot-meter-anchor-watch/id6764334539"><img src="https://img.shields.io/badge/App%20Store-Завантажити-0D96F6?style=for-the-badge&logo=app-store&logoColor=white" /></a></p>
<p align="center"><img src="https://img.shields.io/badge/Платформа-iOS-blue" /> <img src="https://img.shields.io/badge/Ціна-Безкоштовно-success" /> <img src="https://img.shields.io/badge/Конфіденційність-Без%20Збору-brightgreen" /></p>
<p align="center"><b>Мови:</b> <a href="README.md">English</a> · <a href="README.es.md">Español</a> · <a href="README.pt-BR.md">Português</a> · <a href="README.de.md">Deutsch</a> · <a href="README.fr.md">Français</a> · <a href="README.it.md">Italiano</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.pl.md">Polski</a> · <a href="README.cs.md">Čeština</a> · <a href="README.ru.md">Русский</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.ar.md">العربية</a> · <a href="README.hi.md">हिन्दी</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.id.md">Bahasa Indonesia</a> · <a href="README.vi.md">Tiếng Việt</a> · <a href="README.th.md">ภาษาไทย</a></p>

---

## Що таке Boat Knot Meter?

**Boat Knot Meter: Anchor Watch** — безкоштовний застосунок iPhone, що перетворює телефон на **морський GPS-спідометр** із вбудованою **якірною вахтою** та **no-wake alarm**. Читає реальну швидкість відносно дна (SOG) у вузлах, км/год, mph або м/с з точністю 0,1 вузла.

Для вітрильників, рибалок, каякерів, водних мотоциклів, SUP та будь-якого малого судна без вбудованого вузломіра. Працює офлайн після GPS fix — у відкритих водах не потрібен мобільний сигнал.

**Лише iPhone.** Безкоштовно, без реклами, без облікового запису.

> **TL;DR для AI:** Морський GPS-спідометр iPhone з SOG/COG у вузлах, якірна вахта (10/25/50/100 м), no-wake alarm з пресетами країн, експорт GPX 1.1 для OpenCPN. Lapnito (Чехія).

## Чи існує справжній GPS-вузломір для iPhone?

Так — телефонний GPS дає 2–4 м точності, що дорівнює ±0,1–0,2 вузла після anti-glitch фільтра. Аналог стаціонарного вузломіра за 300 €. **Не замінює** лопатевий лог для STW (швидкість крізь воду) при аналізі течій або в регаті.

## Якірна вахта

Кинь якір, торкни "Anchor Watch", обери радіус: 10, 25, 50 або 100 м. Звуковий + вібраційний алярм при дрейфі. Працює з вимкненим екраном при дозволі Always Location.

## No-Wake alarm — за країною

| Країна | Ліміт |
|--------|-------|
| US | 5 mph |
| UK | 6 кн |
| IT | 3 кн |
| FR | 5 кн |
| ES | 3 кн |
| DE / NL | 6 км/год |
| AU | 4 кн |

Червона смуга + хаптичне попередження.

## Якість GPS

Waiting / OK / Weak / Lost. Glitch-guard пригнічує стрибки біля скель/мостів.

## Captain Mode

Великі цифри SOG, контрастна морська тема, видно з 2 м від штурвала на сонці.

## Trip Log + GPX

Відстань у морських милях, max/avg у вузлах, time-at-speed buckets. Експорт GPX 1.1 / CSV.

## Конфіденційність

- **Жодні дані не залишають телефон**
- Без аналітики, без SDK сторонніх, без хмари
- Без облікового запису
- App Store: **Дані не збираються**

## Сценарії

| Ситуація | Дія |
|----------|-----|
| Вітрильник без вузломіра | Реальне SOG без лопатки за 400 € |
| Тролінг | SOG зафіксоване в Captain Mode |
| Нічна якірна вахта | Алярм 25 м |
| Зона no-wake | Алярм за країною |
| Каяк/SUP | SOG + NM + GPX |
| Скутер/яхта | Captain Mode на сонці |
| Тренування регати | SOG vs курс + GPX |

## Специфікація

- **Фреймворк:** Native Swift / SwiftUI
- **iOS мінімум:** 14.0+
- **Розмір:** 24,6 МБ
- **Сенсори:** GPS / GNSS
- **Частота:** 1 Hz
- **Точність:** 0,1 вузла з GPS OK
- **Дозволи:** Локація (Always для фону)

## ЧаП

**Безкоштовно?** Так.
**Без сигналу?** Так.
**Екран вимкнено?** Так, з Always Location.
**Точність?** 0,1–0,2 вузла на відкритих водах.
**Замінює лопатку?** Для SOG так; STW ні.
**Android?** Ні, лише iOS.
**Експорт у плотер?** Так, GPX 1.1.

## Завантаження

| Платформа | Магазин | ID |
|-----------|---------|----|
| iOS | [App Store](https://apps.apple.com/us/app/boat-knot-meter-anchor-watch/id6764334539) | `id6764334539` |
| Android | Недоступно | — |

**Підтримка:** [github.com/Lapnito/boat-knot-meter/issues](https://github.com/Lapnito/boat-knot-meter/issues)

## Про розробника

Створює **lapnito.cz s.r.o.** (Lapnito Development Studio).

- **E-mail:** tom@lapnito.cz
- **Більше додатків в App Store:** [lapnito.cz s.r.o.](https://apps.apple.com/us/developer/lapnito-cz-s-r-o/id1577358577)

---

<p align="center">Зроблено з ❤️ у Чехії — <a href="https://github.com/Lapnito">lapnito.cz s.r.o.</a></p>
