Цей код представляє собою простого Telegram бота, який має деякі функціональні можливості для керування повідомленнями і користувачами в чаті. Основна мета цього бота - надати адміністраторам можливість виконувати деякі дії в чаті, такі як надсилання привітального повідомлення, заборона користувача на відправку повідомлень, розблокування користувача та тимчасове блокування повідомлень користувача на певний час.

Для початку роботи з ботом, вам потрібен токен доступу, який ви можете отримати шляхом створення бота через @BotFather в Telegram. Після отримання токену вставте його в змінну TOKEN в коді.

Основні команди бота:

/info: Відповідає на повідомлення, спрямоване на користувача, до якого відноситься відповідне повідомлення.
/ban: Забороняє користувачу надсилати повідомлення в чаті.
/unban: Розблоковує користувача, щоб дозволити йому надсилати повідомлення в чаті.
/ro: Тимчасово блокує користувача на певний час (вказується у команді) з можливістю надсилання повідомлень.
/um: Розблоковує користувача після блокування.
Деякі коментарі в коді позначаються символом # і містять підказки або можливі модифікації, які можна виконати для кращого використання бота.

Перед запуском бота впевніться, що у вас встановлена бібліотека python-telegram-bot (використовуйте pip install python-telegram-bot для її встановлення).

Для запуску бота, виконайте команду python main.py в командному рядку або відкрийте файл у своєму IDE та запуст
