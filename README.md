# Микровервис для редактирования профиля пользователя.
В данном сервисе зарегистрированный пользователь может пожет отредактировать свой профиль, а именно поменять Фамилию, Имя, Отчество, Адрес, Номер паспорта, E-mail, Номер телефона, Фото профиля.

## Действия сущностей:
### Пользователь может:
- Получить/отредактировать Профиль

## Ограничения:
+ Нельзя задать пустыми Фамилию, Имя, Адрес, Номер паспорта
+ E-mail и Номер телефона не могут быть пустыми одновременно

## Информация о сущностях:
### Пользователь
+ ID
+ Пользователь (из сервиса ААиР)

### Профиль
+ ID
+ Имя
+ Фамилия
+ Отчество
+ Адрес
+ Номер паспорта
+ E-mail
+ Номер телефона
+ Фото профиля
+ Пользователь

## Межсервисное взаимодействие:
### Сервис Аутентификации и Авторизации может:
+ При создании нового аккаунта пользователя должен создаваться его профиль
+ При удалении аккаунта пользователя должен удалиться и его профиль


## Диаграмма вариантов использования сервиса Profile

[![Диаграмма вариантов использования сервиса Profile]
(https://github.com/SakhalinNovosibirskTomsk/Profile/blob/main/Docs/Use%20cases%20%D1%81%D0%B5%D1%80%D0%B2%D0%B8%D1%81%D0%B0%20Profile.drawio.png)](https://github.com/SakhalinNovosibirskTomsk/Profile/blob/main/Docs/Use%20cases%20%D1%81%D0%B5%D1%80%D0%B2%D0%B8%D1%81%D0%B0%20Profile.drawio.png)
[Ссылка на картинку](https://github.com/SakhalinNovosibirskTomsk/Profile/blob/main/Docs/Use%20cases%20%D1%81%D0%B5%D1%80%D0%B2%D0%B8%D1%81%D0%B0%20Profile.drawio.png)

[Ссылка на исходник схемы](https://github.com/SakhalinNovosibirskTomsk/Profile/blob/main/Docs/Use%20cases%20%D1%81%D0%B5%D1%80%D0%B2%D0%B8%D1%81%D0%B0%20Profile.drawio)


## БД сервиса ReceiptWriteOff

### ER-диаграмма
[![ER-диаграмма БД сервиса ReceiptWriteOff](https://github.com/SakhalinNovosibirskTomsk/Profile/blob/main/Docs/ER-%D0%B4%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0%20%D0%91%D0%94%20%D1%81%D0%B5%D1%80%D0%B2%D0%B8%D1%81%D0%B0%20Profile.drawio.png)]
(https://github.com/SakhalinNovosibirskTomsk/Profile/blob/main/Docs/ER-%D0%B4%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0%20%D0%91%D0%94%20%D1%81%D0%B5%D1%80%D0%B2%D0%B8%D1%81%D0%B0%20Profile.drawio.png)
[Ссылка на картинку](https://github.com/SakhalinNovosibirskTomsk/Profile/blob/main/Docs/ER-%D0%B4%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0%20%D0%91%D0%94%20%D1%81%D0%B5%D1%80%D0%B2%D0%B8%D1%81%D0%B0%20Profile.drawio.png)

[Ссылка на исходник схемы](https://github.com/SakhalinNovosibirskTomsk/Profile/blob/main/Docs/ER-%D0%B4%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0%20%D0%91%D0%94%20%D1%81%D0%B5%D1%80%D0%B2%D0%B8%D1%81%D0%B0%20Profile.drawio)
