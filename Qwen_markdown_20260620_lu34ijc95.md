# 🌤️ Telegram-бот погоды

Бот для получения актуального прогноза погоды в любом городе мира.

## ✨ Возможности
- Текущая погода по запросу
- Прогноз на 3 дня
- Ежедневная рассылка в заданное время
- Поддержка 200,000+ городов

## 🚀 Быстрый старт

1. Клонируйте репозиторий:
   git clone https://github.com/ВАШ_НИК/weather-bot.git

2. Установите зависимости:
   pip install -r requirements.txt

3. Получите API ключ на openweathermap.org

4. Заполните .env файл:
   BOT_TOKEN=ваш_токен
   WEATHER_API_KEY=ваш_ключ

5. Запустите бота:
   python bot.py

## 📱 Скриншоты

![Старт](screenshots/start.png)
![Погода](screenshots/weather.png)

## 🛠 Технологии
- Python 3.10+
- aiogram 3.x
- OpenWeatherMap API
- APScheduler