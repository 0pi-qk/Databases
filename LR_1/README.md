### Задание
Создать и заполнить базу данных своего варианта в PostgreSQL. Таблицы (минимум по 10 записей в каждой) связать между собой полями идентификаторов. Предусмотреть наличие связей типа: «один ко многим». С помощью команд интерактивного терминала psql просмотреть структуру базы данных, структуру таблиц, просмотреть данные в них, изменить структуру таблиц, добавить столбцы, добавить данные, создать столбцы с пользовательскими типами данных. Предусмотреть наличие таблиц-справочников и таблиц, использующих справочники.

### Задание по варианту:
Создать и заполнить базу данных туристического агентства, состоящую из четырех таблиц. Первая таблица должна содержать поля: идентификатор заказа, дата заказа, номер заказа, идентификатор тура, идентификатор руководителя тура, количество участников и другие поля при необходимости. Вторая: идентификатор тура, вид тура (автобусный, железнодорожный, авиа), стоимость тура, дата начала тура, идентификатор города путешествия и другие поля при необходимости. Третья: идентификатор руководителя тура, фамилия руководителя, дата рождения и другие поля при необходимости. Четвертая: справочник городов. На основании созданных таблиц создать таблицу, содержащую, например, поля: дата заказа, фамилия руководителя тура, вид тура, наименование города путешествия, дата начала тура, стоимость тура.