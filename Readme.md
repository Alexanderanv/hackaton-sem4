# Дататон: кейс по кластеризации абонентов

## Структура проекта

```
hackaton-sem4/
├── clustering.ipynb            # Главный ноутбук с кодом кластеризации
├── requirements.txt            # Зависимости Python
├── .python-version             # Версия Python (3.13.7)
├── Analytical_report.pdf       # Аналитический отчет
├── datathon_presentation.pptx  # Презентация
├── Readme.md
└── sber_data/
    ├── activity.csv            # Активность клиентов (~1 200 000 строк): client_id, website
    ├── clients.csv             # Профиль клиентов (~50 000 строк): id, age, gender, region_id
    ├── websites.csv            # Справочник сайтов (~1 250 строк): website, category_id
    ├── categories.csv          # Категории товаров/услуг: id, name
    └── regions.csv             # Справочник регионов: id, name
```

## Установка зависимостей

### 1. Создать и активировать виртуальное окружение

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 2. Установить зависимости

```bash
pip install -r requirements.txt
```

