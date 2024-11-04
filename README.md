Вот обновлённый пример `README.md`, который отражает суть вашего проекта:

---

# Telegram Notification Bot for CRM Pulse

## Описание проекта

Данный проект представляет собой Telegram-бота, который автоматически отправляет уведомления о наступивших задачах в CRM Pulse. Основное предназначение проекта — информировать пользователей о задачах, которые нужно выполнить, и поддерживать их в курсе важных событий в CRM.

## Установка и настройка

### Предварительные требования

Перед запуском проекта убедитесь, что у вас установлены следующие компоненты:

- Python 3.7 или выше
- Виртуальное окружение (рекомендуется)

### Установка зависимостей

Склонируйте репозиторий и установите зависимости с помощью:

```bash
pip install -r requirements.txt
```

### Настройка переменных окружения

Создайте файл `.env` в корневом каталоге проекта и добавьте следующие переменные:

```
TG_TOKEN="tg-token"
DB_NAME="db_name"
DB_USER="user"
DB_PASS="password"
```

- **`TG_TOKEN`**: токен вашего Telegram-бота.
- **`DB_NAME`**: имя базы данных CRM.
- **`DB_USER`**: имя пользователя базы данных.
- **`DB_PASS`**: пароль для базы данных.

### Дополнительные инструкции

Для дальнейших настроек и подробной документации посетите сайт CRM Pulse в разделе "Настройки".

## Запуск проекта

Активируйте виртуальное окружение и выполните запуск основного файла:

```bash
python src/main.py
```

После запуска бот будет проверять базу данных каждую минуту и отправлять уведомления в Telegram о наступивших задачах.

## Контакты и поддержка

Если у вас возникли вопросы или требуется помощь, свяжитесь с разработчиком или посетите сайт проекта @mikkey_dee.
