Ссылка на сборку с EXE - https://disk.yandex.ru/d/EQlcH6ksuOj19w


**Это приложение позволяет пользователям выбирать и бронировать билеты на спектакли в театре. Пользователи могут выбирать даты, спектакли, зоны, а также указывать количество билетов и вводить свою электронную почту для оформления заказа. Приложение интегрируется с базой данных SQLite, где хранится информация о спектаклях, доступных зонах, и заказах.**

**Функции:**

**Выбор темы оформления:** Приложение поддерживает две темы — светлую и темную, которые можно изменить через выпадающий список.

**Выбор даты и спектакля:** Пользователи могут выбрать дату и спектакль, после чего обновляется список доступных зон и билетов.

**Информация о спектакле:** Приложение отображает описание выбранного спектакля, а также время начала и длительность.

**Бронирование билетов:** Пользователи могут выбрать количество билетов и оформить заказ. Информация о заказах сохраняется в базе данных, а количество доступных билетов обновляется.

**История заказов:** Пользователи могут просматривать историю своих заказов по электронной почте.

**Отмена последнего заказа:** Пользователи могут отменить последний сделанный заказ, что восстанавливает количество билетов в зоне.

**Генерация PDF билета:** После успешного оформления заказа, пользователю предлагается сохранить PDF файл с информацией о билете.



**Технологии:**

PyQt6: Используется для создания графического интерфейса пользователя (GUI).
SQLite: Используется для хранения данных о спектаклях, зонах, заказах и пользователях.
ReportLab: Используется для генерации PDF файлов с билетами.
Регулярные выражения: Для проверки валидности введенной электронной почты.

**Структура базы данных:**

Приложение использует следующие таблицы в базе данных SQLite:

showtimes: информация о времени спектаклей, датах и спектаклях.

zones: информация о зонах в театре, их доступности и количествах билетов.

orders: информация о заказах пользователей, включая количество билетов и связанные данные.

plays: описание спектаклей.
