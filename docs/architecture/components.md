Компонент	Призначення



Frontend (мобільний або веб)	- Інтерфейс, через який студент бачить оцінки, дедлайни, нагадування
Backend (сервер) -	Обробляє дані, авторизацію, зберігає інформацію про оцінки та дедлайни
Database (база даних)	- Зберігає користувачів, предмети, оцінки, дедлайни
Notification Service -	Відповідає за сповіщення — надсилає нагадування
API (REST) -	Канал обміну даними між frontend і backend
External Services (опціонально) -	Наприклад, інтеграція з Telegram або email для нагадувань


Концептуальна архітектура онлайн-щоденника студента:

![Architecture Overview](architecture_overview.png)

Посилання на дошку GitHub Projects:
https://github.com/users/Olivinskijt/projects/1/views/1