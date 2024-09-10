<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Formulário</title>
 
    <style>
      body {
        font-family: Arial, sans-serif;
        background-color: #167D7F;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        margin: 0;
      }

      form {
        background: #fffdfdd2;
        padding: 20px;
        border-radius: 8px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        max-width: 400px;
        width: 100%;
      }

      p {
        margin: 0 0 15px;
      }

      label {
        display: block;
        margin-bottom: 5px;
        font-weight: bold;
        color: #333;
      }

    


      input[type="date"] {
        width: 125px;
        padding: 10px;
        border: 1px solid #ddd;
        border-radius: 4px;
        box-sizing: border-box;
        margin-bottom: 10px;
      }

      input[type="radio"] {
        margin-right: 5px;
      }

      .gender-label {
        display: inline-block;
        margin-right: 10px;
      }

      button {
        background-color: #007bff;
        color: #fff;
        border: none;
        padding: 10px 20px;
        border-radius: 4px;
        cursor: pointer;
        font-size: 16px;
        transition: background-color 0.3s;
      }

      button[type="reset"] {
        background-color: BLACK;
      }

      button:hover {
        background-color: #0056b3;
      }

      button[type="reset"]:hover {
        background-color: #5a6268;
      }
      .date {
        width: 5%;
      }
      .mail-input{
        width: 65%;
      }
      .name-input{
        width: 65%;
      }
      .pass-input{
        width: 25%;
    
      }
      .cofirm-password{
        width: 30%;
      }
    </style>
  </head>
  <body>
    <form action="#" method="get" target="_blank" autocomplete="off">
      <h2>Formulário</h2>

      <p>
        <label for="nome">Nome:</label>
        <input
          type="text"
          id="nome"
          name="nome"
          placeholder="Nome Completo"
          class="name-input"
        />
      </p>
      <label for="date">Data:</label>
      <input
        type="date"
        id="date"
        name="date"
        value="2024-07-22"
        class="date"
      />
    </p>
      <p>
        <label>Gênero:</label>
        <label class="gender-label" for="feminino">
          <input type="radio" id="feminino" name="genero" value="feminino" />
          Feminino
        </label>
        <label class="gender-label" for="masculino">
          <input type="radio" id="masculino" name="genero" value="masculino" />
          Masculino
          <label class="gender-label" for="masculino">
            <input type="radio" id="masculino" name="genero" value="masculino" />
            Outro
            
          <p>

          <p>

            <label for="email">Seu Email:</label>
            <input type="email" id="email" name="email" placeholder="ex.: email@email.com" class="mail-input">
        </p>
        <p>
            <label for="password">Senha:</label>
            <input type="password"name="password" id="password" placeholder="Digite sua senha" class="pass-input" maxlength="5">
        </p>
        <p>
            <label for="confirm-password">Confirme a Senha:</label>
            <input type="password" name="confirm-password" id="confirm-password" placeholder="Confirme sua senha" maxlength="5" class="cofirm-password">
        </p>
        <p>
            <button type="reset">Reset</button>
            <button type="submit">Enviar</button>

        </p>
        </label>
      </p>
    </form>
    
  </body>
</html>
