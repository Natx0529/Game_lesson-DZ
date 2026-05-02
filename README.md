# Мини-игры в браузере

Небольшие игры на **чистом HTML/CSS/JavaScript** (Canvas), без фреймворков и шага сборки. Достаточно открыть страницу в современном браузере.

## Состав

| Файл | Описание |
|------|----------|
| [`index.html`](index.html) | Главная страница со списком игр |
| [`mountain-race.html`](mountain-race.html) | Горная гонка: полосы, нитро, ИИ-соперники |
| [`billiard.html`](billiard.html) | Упрощённый пул (8-ball): два игрока, счёт забитых шаров |

## Запуск

### Вариант 1 — файлом

Откройте в браузере `index.html` (двойной щелчок или перетаскивание в окно браузера).

> Некоторые браузеры ограничивают функции при открытии `file://`. Если что-то ведёт себя странно, используйте локальный сервер.

### Вариант 2 — локальный сервер

Из корня репозитория:

```bash
npm start
```

Откройте в браузере адрес, который покажет [serve](https://www.npmjs.com/package/serve) (обычно `http://localhost:3000`).

Требуется [Node.js](https://nodejs.org/) (для `npm` и `npx`).

## Структура репозитория

```
Game/
├── index.html           # точка входа (меню игр)
├── mountain-race.html   # гонка
├── billiard.html        # бильярд
├── package.json         # npm start (опционально)
├── .gitignore
├── .gitattributes
├── LICENSE              # MIT
└── README.md
```

## Требования

- Современный браузер с поддержкой Canvas и ES6 (Chrome, Firefox, Edge, Safari).

## Git

В корне есть `.gitignore` и `.gitattributes`. Чтобы версионировать проект:

```bash
git init
git add .
git commit -m "Initial commit"
```

## Лицензия

MIT — см. файл [LICENSE](LICENSE).
