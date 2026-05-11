# Повідомлення від Nagios XI через Telegram

Скрипти повідомлень про хост та сервіс notify_host_by telegram та notify_service_by_telegram використовують curl для з'єднання з сервером Telegram.

За допомогою BotFather потрібно створити бота. Після створення буде повідомлено "token to access the HTTP API", цей токен у вигляді NNNNNNN:AAAAA-AAAAAAA і є $BOT-TOKEN$, який потрібно замінити у скрпитах notify_host_by telegram та notify_service_by_telegram.

Також потрібно отримати ваш Telegram ID за допомогою бота @my_id_bot. Цей ID потрібно вказати в поле "Pager Number" під час створення Contacts для повідомленнь через Телеграм.
В налаштуваннях Contacts на закладці "Alert Setting" потрібно в "Manage host notification commands" та "Manage Service notification commands" вибрати notify_host_by telegram та notify_service_by_telegram відповідно.
