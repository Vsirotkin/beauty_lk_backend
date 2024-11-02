### README.md

Личный Кабинет на https://www.nokturn-beauty.ru/

Цель проекта
Создать личный кабинет для пользователей сайта Nokturn Beauty, чтобы предоставить им инструмент для управления информацией о личных данных, балансе клиентской карты (КК) и историей покупок. Личный кабинет будет доступен как на десктопной, так и на мобильной версиях сайта, аналогично функционалу, представленному на сайте https://lk.mozaika-shop.ru/lk.


Текущее состояние
На данный момент у покупателей есть возможность получить и активировать клиентскую карту в магазинах "Ноктюрн". Также разработаны процедуры для начисления и списания бонусных баллов с карты. Однако пользователи могут узнать баланс своей карты только в магазине, обратившись к продавцу.

Задачи
Создать личный кабинет на сайте, где пользователи смогут:
Просматривать информацию о своих персональных данных.
Проверять баланс своей клиентской карты.
Ознакомиться с историей покупок.
Функциональные требования


Регистрация и авторизация
Пользователи должны иметь возможность зарегистрироваться или сменить номер телефона по входящему номеру телефона или по смс-коду.
Возможность восстановления пароля через электронную почту.


Профиль пользователя
Просмотр и редактирование личной информации (ФИО, адрес электронной почты, номер телефона).
Информация о клиентской карте (КК) и текущем балансе.

История покупок
Просмотр истории покупок, включая дату, сумму и статус (успешно/отменено).

Блок информации о КК
Информация о начисленных и списанных баллах с КК.
Возможность получения уведомлений о важных событиях, связанных с КК.

Технические требования
Стек технологий
Frontend: Vue.js для создания пользовательского интерфейса.
Backend: Open source проект Saleor, выполненный на Django и GraphQL для обработки запросов и управления данными.
Аутентификация и безопасность
Использование JWT (JSON Web Token) для управления сессиями пользователей.