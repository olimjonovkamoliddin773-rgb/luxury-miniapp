# SHOHFARM Telegram Bot

Telegram-бот для заявок на перемещение товаров между филиалами SHOHFARM.

## Основные функции
- выбор филиала-источника;
- несколько товаров в одной заявке;
- SQLite;
- принятие заявки;
- обязательный комментарий при отклонении;
- уведомление инициатора;
- `/myid`;
- администратор: Telegram ID `6315295677`.

## Запуск

Установить зависимости:

```bash
pip install -r requirements.txt
```

Задать переменные окружения:

- `TELEGRAM_BOT_TOKEN`
- `TRANSFER_CHANNEL_ID`
- `ADMIN_ID`

Запуск:

```bash
python bot.py
```

Не помещайте токен Telegram в GitHub.
