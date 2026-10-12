# IT Landing Page

Современный лендинг для IT‑компании: адаптивная вёрстка, авто‑тёмная тема, анимации и чистый код.

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)

## Скриншоты

| Светлая тема | Тёмная тема |
| --- | --- |
| ![Светлая тема](img/screenshot-light.png) | ![Тёмная тема](img/screenshot-dark.png) |

## О проекте

Это учебный лендинг для IT‑студии/аутсорса. Проект создан в рамках обучения фронтенду (HTML/CSS, адаптивность, семантика, работа с Git).

**Основные возможности:**
- Адаптивная вёрстка (Mobile First): корректно отображается на мобильных, планшетах и десктопах.
- Авто‑переключение на тёмную тему через `prefers-color-scheme`.
- Плавная прокрутка по якорям (`html { scroll-behavior: smooth }`).
- CSS‑анимации появления блоков (`fadeInUp`, `fadeInScale`).
- Векторная иконка (SVG) без потери качества.
- Чистый, читаемый код с использованием CSS‑переменных для лёгкой смены палитры.

## Технологии и стек

- **HTML5**: семантическая разметка, доступность.
- **CSS3**: Flexbox, Grid, переменные, медиа‑запросы, анимации.
- **SVG**: векторные иконки.
- **Git**: контроль версий, коммиты, история изменений.

## Особенности реализации

- Цветовая схема вынесена в `:root` и переопределяется в `@media (prefers-color-scheme: dark)`.
- Анимации реализованы через `@keyframes` и `animation`.
- Таблицы адаптируются под мобильные устройства (превращаются в карточки).
- Формы имеют базовые состояния `:focus`, `:valid`, `:invalid`.

## Демо

- Сайт доступен на GitHub Pages: https://gekafirst.github.io/my-website/
