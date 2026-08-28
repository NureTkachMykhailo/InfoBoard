# InfoBoard

Практична робота №2: JSON, fetch і React без збірки.

## Рівень 1 — HTML, fetch, JSON.parse
`demos/` — незалежні сторінки (профіль, список покупок, погода через Open-Meteo API, випадкова цитата, зображення з URL у JSON). Дані — `data/*.json`.

## Рівень 2 — JSON-лабораторія
`json-lab/` — валідація і форматування довільного JSON (try/catch навколо `JSON.parse`, `JSON.stringify`).

## Рівні 3-4 — React Taskboard
`taskboard/` — фільтр за статусом, пошук за назвою, сортування. React підключений локально (`taskboard/vendor/`) без Vite/збірки, компоненти написані через `React.createElement`.

## Запуск
```bash
python3 -m http.server 5500
```
Відкрити http://localhost:5500
