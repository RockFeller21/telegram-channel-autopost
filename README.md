# Telegram Channel Mailing Bot

A bot for automating scheduled mailings to Telegram channels with a convenient admin panel, flexible settings, and support for multiple mailings.

Бот для автоматизации рассылок сообщений в Telegram-каналы с удобной админ-панелью, гибкими настройками и поддержкой нескольких рассылок.

---

🇬🇧 English

## Features

- Create and manage unlimited mailings
- Mailing interval in seconds (can be changed at any time)
- Intuitive admin panel with inline buttons
- Bot permission check in the channel
- "Back" button at every step
- All data stored in SQLite

---

## Installation

1. **Clone the repository or download the code archive.**

2. **Install dependencies:**
   ```
   pip install -r req.txt
   ```

3. **Get your Telegram bot token from [@BotFather](https://t.me/BotFather).**

4. **Add your token and admin ID to `config.py`:**
   ```python
   API_TOKEN = 'YOUR_TELEGRAM_BOT_TOKEN'
   ADMIN_ID = YOUR_TELEGRAM_ID  # Example: 123456789
   ```

5. **Run the bot:**
   ```
   python main.py
   ```

---

## Usage

- Use the "Create mailing" button to add a new mailing.
- Use "Manage mailings" to edit, enable/disable, or delete mailings.
- All actions are available only to the admin (ID specified in `config.py`).
- The bot must be an admin in the target channel.

---

## Important

- The interval is specified in seconds (e.g., 60 = once per minute).
- The bot must be added to the channel and have admin rights.

---

## License

MIT

---

# 🇷🇺 Русский

---

## Возможности

- Создание и управление неограниченным количеством рассылок
- Интервал рассылки в секундах (можно менять в любой момент)
- Интуитивная админ-панель с инлайн-кнопками
- Проверка прав бота в канале
- Кнопка "Вернуться" на каждом шаге
- Хранение всех данных в SQLite

---

## Установка

1. **Склонируйте репозиторий или скачайте архив с кодом.**

2. **Установите зависимости:**
   ```
   pip install -r req.txt
   ```

3. **Получите токен Telegram-бота у [@BotFather](https://t.me/BotFather).**

4. **Добавьте ваш токен и ID администратора в `config.py`:**
   ```python
   API_TOKEN = 'YOUR_TELEGRAM_BOT_TOKEN'  # <-- Укажите сюда ваш токен.
   ADMIN_ID = YOUR_TELEGRAM_ID            # Например: 123456789
   ```

5. **Запустите бота:**
   ```
   python main.py
   ```

---

## Использование

- Для создания рассылки используйте кнопку "Создать рассылку".
- Для управления рассылками — "Управление рассылками".
- Все действия доступны только администратору (ID указывается в `config.py`).
- Бот должен быть админом в целевом канале.

---

## Важно

- Интервал указывается в секундах (например, 60 — раз в минуту).
- Для работы с каналом бот должен быть добавлен в канал и иметь права администратора.

---

## Лицензия

MIT
