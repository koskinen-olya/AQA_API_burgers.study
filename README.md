Автотест на Java с использованием PageObject. Учебный проект в рамках курса - https://practicum.yandex.ru/qa-automation-engineer-java/.

Тестирование API сервиса ["Stellar Burgers"](https://stellarburgers.nomoreparties.site/). Тестовые сценарии:

1) Создание пользователя:
- создать уникального пользователя;
- создать пользователя, который уже зарегистрирован;
- создать пользователя и не заполнить одно из обязательных полей.
2) Логин пользователя:
- логин под существующим пользователем,
- логин с неверным логином и паролем.
3) Изменение данных пользователя:
- с авторизацией,
- без авторизации,
Для обеих ситуаций нужно проверить, что любое поле можно изменить. Для неавторизованного пользователя — ещё и то, что система вернёт ошибку.
4) Создание заказа:
- с авторизацией,
- без авторизации,
- с ингредиентами,
- без ингредиентов,
- с неверным хешем ингредиентов.
5) Получение заказов конкретного пользователя:
- авторизованный пользователь,
- неавторизованный пользователь.
