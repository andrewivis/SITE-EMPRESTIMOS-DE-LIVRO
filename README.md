# SITE-EMPRESTIMOS-DE-LIVRO
TELA LOGIN - FRONT

<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Login - Empréstimo de Livros</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      background-color: #6a0dad; /* Roxo */
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .login-container {
      background-color: #fff;
      padding: 2rem;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
      width: 300px;
      text-align: center;
    }

    .login-container h2 {
      margin-bottom: 1.5rem;
      color: #6a0dad;
    }

    input[type="text"],
    input[type="password"] {
      width: 100%;
      padding: 0.5rem;
      margin: 0.5rem 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    button {
      background-color: #6a0dad;
      color: white;
      padding: 0.5rem 1rem;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      margin-top: 1rem;
      width: 100%;
    }

    button:hover {
      background-color: #580c9c;
    }
  </style>
</head>
<body>
  <div class="login-container">
    <h2>Login - Biblioteca</h2>
    <form>
      <input type="text" placeholder="Usuário" required><br>
      <input type="password" placeholder="Senha" required><br>
      <button type="submit">Entrar</button>
    </form>
  </div>
</body>
</html>
