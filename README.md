<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Cadastro de Novo usuario</title>
</head>
<body>

  <h1>Formulario de Cadastrosuario</h1>

  <form action="#" method="post">
    <label for="nome ">Nome completo:</label><br>
    <input type="text" id="Nome" name="Nome"><br><br>
    
   <label for="gmail">E-Mail</label><br>
   <input type="email"id="gmail" name="gmail" ><br><br>

   <label for="nome">Nome de Novo</label><br>
   <input type="text" id="nome"name="nome"><br><br>

   <label for="senha">Senhas</label><br>
   <input type="password" id="senha" name="senha"><br><br>

   <label for="Csenha">Confirmar senha</label><br>
   <input type="password" id="Csenha" name="Csenha" ><br><br>

   <label for="data">Data de nascimento</label><br>
   <input type="date" id="data" name="data"><br><br>

   <label for="telefone">Telefone</label><br>
   <input type="tel" id="telefone" name="telefone"><br>
   
   <label for="Gênero">Gênero</label><br>
  
   <label for="genero">Masculino</label><br>
   <input type="radio" id="Masculino" name="resposta" value="Masculino"><br>

   <label for="genero">Feminino</label><br>
   <input type="radio" id="feminino" name="resposta" value="Feminino"><br>

   <label for="genero">Outro</label><br>
   <input type="radio" name="resposta" id="Gênero" value="Outros"><br><br>
   
   <label for="interesses">Interesses:</label><br><br>

   <label for="tecnologia">Tecnologia</label>
   <input type="checkbox" id="tecnologia" name="resposta" value="Tecnologia"  >

    <label for="musica">Musica</label>
   <input type="checkbox" id="musica" name="resposta" value="Musica" >

    <label for="esporte">Esporte</label>
   <input type="checkbox" id="esporte" name="resposta" value="Esporte">

    <label for="filme">Filme</label> 
    <input type="checkbox" id="filme" name="resposta" value="Filme"> <br><br>

   <label for="estado">Escolha o seu estado</label><br>
    <select id="estado" name="estado">

     <option value="estado">Estados</option>
     <option value="sp">São Paulo</option>
     <option value="mg">Minas Gerais</option>
     <option value="rj">Rio de Janeiro</option>
     <option value="am">Amazonia</option>

   </select><br><br>

   <label for="cidade">Cidade</label><br>
   <input type="text" id="cidade" name="cidade"><br><br>

   <label for="imagem">Coloquei sua imagem</label>
   <input type="file" id="imagem" name="imagem" accept="imagem/*" ><br><br>

   <label for="mensagem">Mensagem:</label><br>
   <textarea id="mensagem" name="mensagem" rows="4" cols="40" ></textarea><br><br>



   <input type="reset" value="reseta">
   <input type="submit" value="envia">
  </form>

</body>
</html>
