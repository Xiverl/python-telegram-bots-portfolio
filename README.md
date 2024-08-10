# Telegram Bot Portfolio

Этот репозиторий содержит коллекцию Telegram ботов, разработанных мной для демонстрации моих навыков в создании ботов и работе с API Telegram. Каждый бот представляет собой отдельный проект с уникальными функциями и возможностями.

## Содержание

1. [Список ботов](#список-ботов)
2. [Технологии](#технологии)
3. [Установка и запуск](#установка-и-запуск)
4. [Структура проекта](#структура-проекта)
5. [Вклад в проект](#вклад-в-проект)
6. [Лицензия](#лицензия)
7. [Контакты](#контакты)

## Список ботов

1. **WeatherBot**: Предоставляет актуальную информацию о погоде по запросу пользователя.
2. **TranslatorBot**: Переводит текст с одного языка на другой.
3. **ReminderBot**: Помогает пользователям устанавливать напоминания и получать уведомления.
4. **QuizBot**: Проводит викторины на различные темы.
5. **NewsBot**: Отправляет пользователям последние новости по выбранным категориям.

## Технологии

- Python 3.8+
- python-telegram-bot
- asyncio
- aiohttp
- SQLite (для хранения данных)
- Различные API (OpenWeatherMap, Google Translate, NewsAPI и др.)

## Установка и запуск

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/your-username/telegram-bot-portfolio.git
   ```

2. Перейдите в директорию проекта:
   ```
   cd telegram-bot-portfolio
   ```

3. Установите зависимости:
   ```bash
   pip install -r requirements.txt
   ```

4. Создайте файл `.env` в корневой директории и добавьте необходимые токены и ключи API:
   ```python
   TELEGRAM_BOT_TOKEN=your_telegram_bot_token
   OPENWEATHERMAP_API_KEY=your_openweathermap_api_key
   ...
   ```

5. Запустите нужного бота:
   ```bash
   python bots/weather_bot.py
   ```

## Структура проекта

```
telegram-bot-portfolio/
│
├── bots/
│   ├── weather_bot.py
│   ├── translator_bot.py
│   ├── reminder_bot.py
│   ├── quiz_bot.py
│   └── news_bot.py
│
├── utils/
│   ├── database.py
│   └── api_helpers.py
│
├── requirements.txt
├── .env
└── README.md
```

## Вклад в проект

Если у вас есть предложения по улучшению ботов или вы нашли ошибку, пожалуйста, создайте issue или отправьте pull request.

## Лицензия

Этот проект лицензирован под MIT License - см. файл [LICENSE](LICENSE) для деталей.

## Контакты

Елынин Денис - [den.elynin0903@gmail.com](mailto:den.elynin0903@gmail.com)

Ссылка на проект: [https://github.com/your-username/telegram-bot-portfolio](https://github.com/your-username/telegram-bot-portfolio)
