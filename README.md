# echo_bot

Бот для первичного запуска. Возвращает отправленное сообщение.

### Как запустить
1. Создать файл `.env` с данными:
   - Обязательные
   ```dotenv
   TELEGRAM_ADMIN_CHAT_ID=123456789 # Ваш id Telegram, сюда будут отправлятся сообщения об ошибках.
   TELEGRAM_BOT_TOKEN=581247650:AAH...H7A # Токен основного бота Telegram.
   ```

   - Необязательные переменные для логирования.
   ```dotenv
   TELEGRAM_ADMIN_BOT_TOKEN=5934478120:AAF...4X8 # Токен бота Telegram для отправки сообщений об ошибках.
   ```

2. Запуск бота:
    
    ```shell
    python3 echobot.py
    ```