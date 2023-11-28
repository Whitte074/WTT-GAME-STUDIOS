<h1>Сайт В Разработке</h1>

        <p>&copy; 2023 Игровой Разработчик</p>

        <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Привязка аккаунтов</title>
</head>
<body>

    <h2>Вход через Google</h2>

    <form action="/your-server-endpoint" method="post">
        <!-- Здесь могут быть дополнительные поля или параметры -->
        <input type="text" name="username" placeholder="Имя пользователя" required>
        <input type="password" name="password" placeholder="Пароль" required>

        <!-- Кнопка для отправки формы -->
        <button type="submit">Войти</button>
    </form>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Регистрация</title>
</head>
<body>

    <h2>Регистрация через Email</h2>

    <form action="/your-server-registration-endpoint" method="post">
        <!-- Здесь могут быть дополнительные поля или параметры -->
        <input type="email" name="email" placeholder="Email" required>
        <input type="password" name="password" placeholder="Пароль" required>

        <!-- Кнопка для отправки формы -->
        <button type="submit">Зарегистрироваться</button>
    </form>

</body>
</html>
