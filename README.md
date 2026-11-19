# 2048 Оборона / 2048 Defence

Автор: **PavlikDenis** ([github.com/PavlikDenis](https://github.com/PavlikDenis))

Игра-гибрид 2048 и tower defence: нужно собирать числа на поле и
отбиваться ими от падающих врагов. Вся игра — один self-contained
HTML-файл (`game.html`), адаптированный под требования платформы
[Яндекс Игры](https://yandex.ru/dev/games/).

---

## 🇷🇺 Лицензия

Этот проект распространяется по лицензии
**Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**.

Полный текст — в файле [`LICENSE`](./LICENSE).
Официальный текст лицензии: https://creativecommons.org/licenses/by-nc/4.0/

### Что это значит простыми словами

✅ **Можно:**
- играть в игру где угодно;
- скачивать, копировать, распространять игру;
- изменять и дорабатывать код, делать свои версии/моды.

📌 **Обязательно:**
- указывать автора оригинала — **PavlikDenis** — в любой копии или
  производной версии;
- указывать, что были внесены изменения, если вы дорабатывали код;
- указывать ссылку на эту лицензию.

❌ **Нельзя без отдельного письменного разрешения автора:**
- продавать игру или её модификации;
- зарабатывать на игре (реклама от своего имени, донаты, подписки,
  встраивание в платные сборники/публикации и т.п.) — в любой форме;
- выдавать игру или её часть за свою собственную работу без указания
  авторства.

Так как игра — это один HTML-файл, код всегда технически виден через
"Просмотр кода страницы" на любой площадке, где игра опубликована. Это
не отменяет условий лицензии — использование кода без соблюдения
условий выше является нарушением авторских прав, и автор оставляет за
собой право требовать удаления таких копий (DMCA-жалоба и т.п.) и
защищать свои права в законном порядке.

**Важно:** автор (PavlikDenis) сохраняет за собой полное право
использовать, публиковать и монетизировать игру на любых платформах
(Яндекс Игры и др.) — ограничения лицензии касаются **третьих лиц**,
а не самого автора.

---

## 🇬🇧 License

This project is licensed under the
**Creative Commons Attribution-NonCommercial 4.0 International
(CC BY-NC 4.0)** license.

Full text: see [`LICENSE`](./LICENSE) or
https://creativecommons.org/licenses/by-nc/4.0/

### In short

✅ **You may:**
- play the game anywhere;
- download, copy, and share the game;
- modify the code and create your own versions/mods.

📌 **You must:**
- credit the original author — **PavlikDenis** — in any copy or
  derivative;
- indicate if you made changes to the code;
- link back to this license.

❌ **You may not, without the author's separate written permission:**
- sell the game or any modified version of it;
- monetize the game in any way (your own ads, donations,
  subscriptions, bundling into paid collections, etc.);
- present the game or any part of it as your own original work without
  crediting the author.

Since the game ships as a single HTML file, its source is always
technically visible via "View Page Source" on any platform it's hosted
on. This does not waive the license terms — using the code without
complying with the conditions above is a copyright violation, and the
author reserves the right to request takedowns (DMCA, etc.) and pursue
legal remedies.

**Note:** the author (PavlikDenis) retains full rights to use, publish,
and monetize the game on any platform (Yandex Games, etc.) — the
license restrictions apply to **third parties**, not to the author.

---

## Структура репозитория / Repository structure

```
.
├── game.html   — вся игра (HTML + CSS + JS в одном файле)
├── LICENSE     — полный текст лицензии CC BY-NC 4.0
└── README.md   — этот файл
```

## Технические детали / Technical notes

- Игра совместима с SDK платформы Яндекс Игры (`YaGames.init()`,
  `GameplayAPI`, `LoadingAPI`) — при запуске вне платформы используется
  mock-реализация SDK для локальной разработки.
- Полная локализация RU/EN (переключается автоматически по
  `environment.i18n.lang` из SDK, либо вручную в меню).
- Для исправлений и предложений — открывайте Issue или Pull Request.
