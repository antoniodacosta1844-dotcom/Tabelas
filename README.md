
<!DOCTYPE html>
<html lang="pt-AO">
<head>
  <meta charset="UTF-8">
  <title>Formulário de Dados Pessoais</title>
  <style>
    body { font-family: Arial, sans-serif; background:#f7f7f7; }
    .container {
      max-width: 500px; margin: 40px auto; background: #fff; padding: 30px; border-radius: 8px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.07);
    }
    h2 { text-align: center; margin-bottom: 22px; color: #196a3b; }
    label { display: block; margin: 12px 0 4px; }
    input, select {
      width: 100%; padding: 10px; border: 1px solid #ccc; border-radius: 5px; margin-bottom: 10px;
    }
    button {
      background: #196a3b; color: #fff; padding: 12px 24px; border: none; border-radius: 7px;
      cursor: pointer; font-size: 16px; width: 100%; margin-top: 12px;
    }
    button:hover { background: #138a53; }
  </style>
</head>
<body>
  <div class="container">
    <h2>Formulário de Dados Pessoais</h2>
    <form>
      <label for="nome">Nome Completo:</label>
      <input type="text" id="nome" name="nome" required>

      <label for="sobrenome">Sobrenome:</label>
      <input type="text" id="sobrenome" name="sobrenome" required>

      <label for="nascimento">Data de Nascimento:</label>
      <input type="date" id="nascimento" name="nascimento" required>

      <label for="sexo">Sexo:</label>
      <select id="sexo" name="sexo" required>
        <option value="">Selecione</option>
        <option value="masculino">Masculino</option>
        <option value="feminino">Feminino</option>
        <option value="outro">Outro</option>
      </select>

      <label for="nacionalidade">Nacionalidade:</label>
      <input type="text" id="nacionalidade" name="nacionalidade" required>

      <label for="estadoCivil">Estado Civil:</label>
      <select id="estadoCivil" name="estadoCivil" required>
        <option value="">Selecione</option>
        <option value="solteiro">Solteiro(a)</option>
        <option value="casado">Casado(a)</option>
        <option value="divorciado">Divorciado(a)</option>
        <option value="viuvo">Viúvo(a)</option>
      </select>

      <label for="endereco">Endereço:</label>
      <input type="text" id="endereco" name="endereco" required>

      <label for="telefone">Telefone:</label>
      <input type="tel" id="telefone" name="telefone" pattern="[0-9]{9,15}" required>

      <label for="email">E-mail:</label>
      <input type="email" id="email" name="email" required>
      <input type="text" id="identidade" name="identidade" required>

      <button type="submit">Enviar</button>
    </form>
  </div>
</body>
</html>
