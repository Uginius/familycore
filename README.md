# Семейное ядро / FamilyCore

Лендинг продукта «Семейное ядро» — системы семейных договорённостей с AI-брифингами.

---

## Структура проекта

```
familycore/
├── index.html     # Русская версия (основная)
├── en.html        # English version
├── style.css      # Общие стили
├── favicon.svg    # Иконка сайта
├── CNAME          # Домен для GitHub Pages
└── README.md
```

## Стек

- **HTML + CSS + vanilla JS** — статический сайт, без сборки
- **Google Fonts** — DM Serif Display + Onest
- **Хостинг** — GitHub Pages (или любой статический хостинг)

## Локальная разработка

```bash
python3 -m http.server 8000
# или
npx serve .
```

## Деплой на GitHub Pages

1. Создайте репозиторий на GitHub
2. Залейте файлы
3. **Settings → Pages → Source:** Deploy from a branch → `main` / `root`
4. Добавьте `CNAME` с содержимым `familycore.app`
5. DNS: CNAME-запись `familycore.app` → `<username>.github.io`

## Языки

| Версия | Файл | Бренд |
|--------|-------|-------|
| Русская | `index.html` | Семейное ядро |
| English | `en.html` | FamilyCore |

Переключатель `EN` / `RU` в навигации.

## Лицензия

Проприетарный проект. Все права защищены.
