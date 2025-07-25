# 🏠 realtor
realtor 2.0

📋 **Описание проекта**
AI-система для анализа переписок менеджеров по недвижимости – инновационное решение для автоматической оценки качества работы менеджеров и готовности клиентов к покупке недвижимости.

✨ **Ключевые возможности:**

🎯 **Анализ менеджеров по 5 критериям:** выявление потребностей, презентация объектов, работа с возражениями, установление доверия, закрытие сделки

📊 **Оценка готовности клиентов:** 10-балльная шкала готовности к покупке с подробным обоснованием

📚 **Обучение на профессиональной литературе:** система базируется на знаниях из книг по продажам (СПИН-продажи, техники Хопкинса и др.)

💾 **Универсальная загрузка данных:** автоматическое определение формата и структуры любых диалогов (CSV, JSON, Excel)

🧠 **Интеллектуальные рекомендации:** персонализированные советы по улучшению техник продаж

📈 **Визуализация результатов:** интерактивные графики и детальные отчеты

🏗️ **Архитектура проекта**

```
realtor/
├── 📊 01_data_analysis.ipynb          # Анализ и обработка реального датасета
├── 📚 02_books_processing.ipynb       # Извлечение знаний из книг по продажам
├── 🤖 03_model_training.ipynb         # Обучение и калибровка AI-модели
├── 💬 04_conversation_analyzer.ipynb  # Главный анализатор переписок
├── 🧪 05_evaluation_demo.ipynb        # Демонстрация и тестирование системы
├── 📖 books/                          # Профессиональная литература 
├── 💾 data/                           # Датасеты и обработанные данные
├── 🧠 models/                         # Обученные модели и база знаний
├── 📋 results/                        # Результаты анализа и отчеты
└── 📄 requirements.txt                # Python зависимости
```

🔧 **Возможности системы**

👔 **Для руководителей:**
- Объективная оценка работы команды менеджеров
- Выявление точек роста и обучающих потребностей  
- Сравнительная аналитика по сотрудникам
- Отчеты по эффективности отдела продаж

👥 **Для менеджеров:**
- Персональные рекомендации по улучшению техник
- Анализ сильных и слабых сторон
- Обучающие материалы на основе лучших практик
- Трекинг личного прогресса

📊 **Для аналитиков:**
- Детальная статистика по продажам
- Корреляция между качеством диалогов и конверсией
- A/B тестирование различных подходов к продажам
- Предиктивная аналитика готовности клиентов

---

🚀 **Планируемые улучшения:**
- Интеграция с CRM-системами (Bitrix24, amoCRM)
- Мобильное приложение для менеджеров
- Real-time анализ диалога
- API для внешних систем