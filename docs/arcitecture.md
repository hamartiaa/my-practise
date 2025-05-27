### Архитектура проекта



project/
├── src/                    # Исходный код
│   ├── models/             # Модели машинного обучения
│   │   ├── flower_classifier.py
│   │   └── labels.json
│   └── main.py             # Основной файл FastAPI приложения
├── site/                   # Веб-интерфейс
│   ├── css/                # Стили
│   ├── images/             # Изображения
│   └── flowers.html        # Страница классификатора
└── requirements.txt        # Зависимости проекта