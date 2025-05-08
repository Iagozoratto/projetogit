<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Formulário de Cadastro</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="form-container">
    <form class="form">
      <h2>Cadastro</h2>
      <label for="nome">Nome:</label>
      <input type="text" id="nome" name="nome" placeholder="Digite seu nome" required>

      <label for="email">E-mail:</label>
      <input type="email" id="email" name="email" placeholder="Digite seu e-mail" required>

      <label for="senha">Senha:</label>
      <input type="password" id="senha" name="senha" placeholder="Digite sua senha" required>

      <label for="confirmar-senha">Confirmar Senha:</label>
      <input type="password" id="confirmar-senha" name="confirmar-senha" placeholder="Confirme sua senha" required>

      <label>Idade:</label>
      <input type="number" id="idade" name="idade" placeholder="Digite sua idade" required>

      <label>Estado:</label>
      <div class="checkbox-group">
        <label><input type="checkbox" name="estado" value="AC"> Acre</label>
        <label><input type="checkbox" name="estado" value="AL"> Alagoas</label>
        <label><input type="checkbox" name="estado" value="AP"> Amapá</label>
        <label><input type="checkbox" name="estado" value="AM"> Amazonas</label>
        <label><input type="checkbox" name="estado" value="BA"> Bahia</label>
        <label><input type="checkbox" name="estado" value="CE"> Ceará</label>
        <label><input type="checkbox" name="estado" value="DF"> Distrito Federal</label>
        <label><input type="checkbox" name="estado" value="ES"> Espírito Santo</label>
        <label><input type="checkbox" name="estado" value="GO"> Goiás</label>
        <label><input type="checkbox" name="estado" value="MA"> Maranhão</label>
        <label><input type="checkbox" name="estado" value="MT"> Mato Grosso</label>
        <label><input type="checkbox" name="estado" value="MS"> Mato Grosso do Sul</label>
        <label><input type="checkbox" name="estado" value="MG"> Minas Gerais</label>
        <label><input type="checkbox" name="estado" value="PA"> Pará</label>
        <label><input type="checkbox" name="estado" value="PB"> Paraíba</label>
        <label><input type="checkbox" name="estado" value="PR"> Paraná</label>
        <label><input type="checkbox" name="estado" value="PE"> Pernambuco</label>
        <label><input type="checkbox" name="estado" value="PI"> Piauí</label>
        <label><input type="checkbox" name="estado" value="RJ"> Rio de Janeiro</label>
        <label><input type="checkbox" name="estado" value="RN"> Rio Grande do Norte</label>
        <label><input type="checkbox" name="estado" value="RS"> Rio Grande do Sul</label>
        <label><input type="checkbox" name="estado" value="RO"> Rondônia</label>
        <label><input type="checkbox" name="estado" value="RR"> Roraima</label>
        <label><input type="checkbox" name="estado" value="SC"> Santa Catarina</label>
        <label><input type="checkbox" name="estado" value="SP"> São Paulo</label>
        <label><input type="checkbox" name="estado" value="SE"> Sergipe</label>
        <label><input type="checkbox" name="estado" value="TO"> Tocantins</label>
      </div>

      <button type="submit">Enviar</button>
    </form>
  </div>
</body>
</html>
