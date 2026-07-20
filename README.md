# AI Traffic — Network Intrusion Detection System (NIDS)

Проект построения и исследования моделей обнаружения сетевых вторжений на основе набора данных KDD Cup 1999 / NSL-KDD.

## Описание

Система обнаружения сетевых аномалий и вторжений (NIDS), использующая методы машинного обучения для классификации сетевого трафика как нормального или вредоносного.

## Набор данных

- **KDDTest+.arff** — тестовая выборка из NSL-KDD Dataset, содержащая 41 признак сетевого соединения и метку класса (normal / attack)

## Технологии

- Python >= 3.11
- Pandas
- Jupyter Notebook
- Poetry (управление зависимостями)

## Установка

```bash
# Клонировать репозиторий
git clone <URL_репозитория>
cd Traffic2

# Установить зависимости
poetry install

# Активировать виртуальное окружение
poetry shell
```

## Запуск

```bash
# Запустить основной скрипт
python main.py

# Или открыть Jupyter Notebook
poetry run jupyter notebook data/main.ipynb
```

## Структура проекта

```
.
├── main.py                 # Точка входа
├── pyproject.toml          # Конфигурация Poetry
├── data/
│   ├── main.ipynb          # Jupyter Notebook с анализом
│   └── KDDTest+.arff       # Тестовый набор данных
└── README.md
```

## Автор

Vlad Chernoprudov
