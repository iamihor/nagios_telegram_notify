# Повідомлення від Nagios XI через Telegram

Скрпити notify_host_by telegram та notify_service_by_telegram використовують curl для з'єднання з серевром Telegram.

За допомогою BotFather потрібно створити бота. Після створення буде повідомлено "token to access the HTTP API", цей код у вигляді NNNNNNN:AAAAA-AAAAAAA  і є $BOT-TOKEN$, який потрібно замінити у командах для повідомлень про хост і про сервіс.
Також потрібно отримати ваш Telegram ID за допомогою @my_id_bot. Цей ID потрібно вказати в поле "Pager Number" під час створення Contact для повідомленнь через телеграм.
В налаштуваннях Contacts на закладці "Alert Setting" потрібно в "Manage host notification commands" та "Manage Service notification commands" вибрати notify_host_by telegram та notify_service_by_telegram відповідно.
