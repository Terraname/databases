# databases
Database models and control systems labs for 5th semester
1.	Данные студента:
  -	Петров А. П.
  -	Группа 153502
  -	Интернет-магазин спортивных товаров
2.	Функциональные требования:
  - Предметная область
  -	Авторизация пользователя
  -	Управление пользователей (CRUD)
  -	Система ролей
    + Администратор
    +	Продавец
    +	Покупатель
    +	Пользователь без регистрации
  -	зможность пользователей без регистрации
     + Просмотр списка товаров
     + Выбор товаров в корзину и просмотр общей стоимости
     + Авторизация
     + Регистрация
  -	Возможности пользователей-покупателей
     + Просмотр списка товаров
     + Выбор товаров в корзину и просмотр общей стоимости
     + Оформление заказа
     + Отслеживание статуса заказа
  -	Возможности пользователей-продавцов
     + Добавление новых товаров
     + Изменение информации о существующих товарах
     + Изменение информации о количестве товаров в наличии
4.	Описание сущностей:
  -	User(Ползователь)
    + Имя
    + Фамилия
    + Логин
    + Пароль
  -	Product
    + название
    + описание
    + цена
    + количество в наличии
    + изображение
    + грузоперевозчик
  -	Cart
    + пользователь
    + продукты
  -	Products
    + товар
    + количество
  -	Review
    + текст
    + оценка
    + пользователь
    + товар
  -	Order
    + дата
    + статус
    + общая стоимость
    + адрес
  -	Address
    + страна
    + город
    + улица
    + дом
    + кваптира
  -	Cathegory
    + имя
    + описание
  -	Image
    + ссылка
    + описание
    + формат
    + качество
  -	Storage_location
    + имя
    + адрес
    + товары
    + поставщики
  -	Shipping_provider
    + имя
    + сайт
    + ментод доставки
    + стоимость
    + обслуживаемые регионы
5.	Ограничения:
