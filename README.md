# Best Portfolio Templates — подборка с GitHub

Сайт-витрина лучших open-source портфолио-шаблонов с GitHub + все шаблоны прямо в этом репозитории.

**Живая витрина:** https://kanatormonov2003-eng.github.io/web-portfolio-showcase/

## Шаблоны в подборке

| Шаблон | Стек | Звёзды | Подходит для |
|---|---|---|---|
| **[vCard](templates/vcard)** | HTML · CSS · JS | 8.1k★ | Сайт-визитка, быстрый старт |
| **[Simplefolio](templates/simplefolio)** | SCSS · Webpack | 14.2k★ | Классическое портфолио разработчика |
| **[DevPortfolio](templates/devportfolio)** | Astro · Tailwind v4 | 5.0k★ | Резюме-сайт с проектами и опытом |
| **[AstroPaper](templates/astro-paper)** | Astro · Tailwind · MDX | 5.1k★ | Блог + портфолио |

Все шаблоны собраны и готовы к просмотру:
- `templates/vcard/` — чистый HTML, открывается как есть
- `templates/simplefolio/dist/` — собранная Webpack-версия
- `templates/devportfolio/dist/` — собранная Astro-версия
- `templates/astro-paper/dist/` — собранная Astro-версия (блог)

## Структура

```
├── index.html               # сайт-витрина (RU/EN)
├── assets/shots/            # скриншоты шаблонов
└── templates/
    ├── vcard/               # шаблон + исходники
    ├── simplefolio/         # шаблон + dist/
    ├── devportfolio/        # шаблон + dist/
    └── astro-paper/         # шаблон + dist/
```

## Как использовать

1. Открой демо любого шаблона на витрине
2. Скачай оригинал с GitHub (ссылка на каждой карточке) или используй версию из `templates/`
3. Замени контент: для vCard — прямо в HTML, для Astro-шаблонов — в `src/config.ts`

## Развертывание витрины

Сайт-витрина — статический HTML. Репозиторий настроен на GitHub Pages:

```bash
# локально
python -m http.server 8000
# открой http://localhost:8000
```

## Лицензии

Все шаблоны распространяются по лицензии MIT (см. LICENSE в папках шаблонов).
Витрина сделана самостоятельно и тоже на MIT.
