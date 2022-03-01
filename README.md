## Музыкального магазина на django 3
### Функционал
* Авторизация, регистрация.
* Корзина (добавление, удаление, изменение количества товара).
* CartProduct (продукт корзины) реализован для любого типа товара. Для возможности маштабирования в дальнейшем.
* Личный кабинет с возможностью отслеживать свои заказы и просматривать детальную информацию о них.
* Возможность добавления и удаления в личном кабинете товара в "лист ожидания".
* Отправка уведомлений для пользователя о том, что товар, находящийся в списке его ожидания поступил (django signals).
* Возможность отслеживания наличия товара и бизнес-логика, не позволяющая заказывать товар, если его нет в наличии или за время формирования заказа уже кто-то забрал последнее.
* Возможность создавать галерею изображений как для исполнителя, так и для конкретного альбома (галерея изображений + ContentType).
* TabularInline и GenericTabularInline в админке для удобства добавления изображений.
* RAW SQL запросы для получения наиболее продоваемого альбома месяца.
* Можно доработать админку, сильно не настраивал, не было такой задачи.
