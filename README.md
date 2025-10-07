<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Landing Page - Ebook Dívidas</title>

  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">

  <style>

.nav { 
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background: white;
  z-index: 1000;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}


.lista {
    padding: 0;
    margin: 0;
    display: grid;
    background-color: white;
    width: 100%;
    text-align: right;
    grid-template-columns: 49fr 13fr 8fr 0fr;
    font-size: 20px;
    list-style-type: none;
    font-weight: bolder;
    align-items: center;  
    font-family: arial;
}

.logo {
   height: 60px;
    width: 70px;
    display: block;
}

li {
    display: inline;
    padding: 2%;
    text-align: right;
    font: 23px;
    flex: auto;
    justify-content: center;
}

li a {
    color: black;
    text-decoration: none;
    padding: 7px 20px;
    display: inline-block;
    text-align: right;
    flex: auto;
}

li a:hover {
    background-color: grey;
    text-align: right;
}

.container {
  margin-top: 120px; 
}

    :root {
      --navy: #06263a;
      --gold: #e2b07a;
      --white: #fff;
      --green: #22c55e;
      --max-width: 1100px;
    }

    * { box-sizing: border-box; margin:0; padding:0; }

    body {
      font-family: Arial;
      background: url("https://s2.glbimg.com/nIqfLY3zjr8JntK_zMS9QxXFaZk=/e.glbimg.com/og/ed/f/original/2020/09/05/alfons-morales-ylswjsy7stw-unsplash.jpg") no-repeat center/cover;
      color: var(--white);
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 2rem;
    }

    .container {
      display: grid;
      grid-template-columns: 1fr 1fr;
      background: var(--navy);
      border-radius: 12px;
      max-width: var(--max-width);
      width: 100%;
      padding: 3rem;
      gap: 2rem;
    }

    .content h1 {
      font-family: arial;
      font-size: clamp(1.8rem, 2.6vw, 2.6rem);
      margin-bottom: 1rem;
      color: var(--gold);
    }

    .content p {
      font-size: 1rem;
      line-height: 1.5;
    }

    form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }

    label {
      font-weight: 600;
      font-size: 0.9rem;
    }

    input[type="text"],
    input[type="email"],
    input[type="tel"] {
      width: 100%;
      padding: 0.8rem 1rem;
      border: none;
      border-radius: 6px;
      font-size: 1rem;
    }

    .privacy {
      font-size: 0.8rem;
      line-height: 1.4;
    }

    .privacy a {
      color: #9ddcff;
      text-decoration: underline;
    }

    button {
      background: var(--green);
      color: var(--white);
      border: none;
      padding: 1rem;
      font-size: 1rem;
      font-weight: bold;
      border-radius: 6px;
      cursor: pointer;
      transition: background 0.2s ease-in-out;
    }

    button:hover {
      background: #16a34a;
    }

    @media (max-width: 850px) {
      .container {
        grid-template-columns: 1fr;
        text-align: center;
      }
      form {
        text-align: left;
      }
    }
  </style>
</head>
<body>
<div class="nav">
  <nav>   
        <ul class="lista">
            <img class="logo" src="https://i.pinimg.com/originals/83/6e/ce/836ece7999c4401289808a8bd4bb8436.jpg" alt="">
            <li><a href="index.html">Sobre nos</a></li>
            <li><a href="#">Formulario</a></li>
        </ul>
    </nav>
</div>
  <section class="container">
    <div class="content">
      <h1>Como lidar com as dívidas da sua empresa sem perder o controle do negócio</h1>
      <p>Preencha o formulário e receba gratuitamente o eBook do escritório Del Nero Advogados, com orientações jurídicas para reorganizar dívidas, evitar medidas extremas e manter a operação da sua empresa protegida.</p>
    </div>

    <form>
      <input type="text" name="nome" placeholder="Nome completo" required>
      <input type="email" name="email" placeholder="E-mail" required>
      <input type="tel" name="telefone" placeholder="Número de telefone">
      <input type="text" name="empresa" placeholder="Nome da empresa">

      <div class="privacy">
        <input type="checkbox" id="lgpd" required>
        <label for="lgpd">Ao enviar este formulário, você concorda com o uso dos seus dados pela L Dias Advocacia para fins de envio de formulario e comunicações relacionadas.</label>
        <p>Seus dados serão tratados conforme a LGPD. <a href="#">Saiba mais em nossa Política de Privacidade.</a></p>
      </div>

      <button type="submit">Enviar</button>
    </form>
  </section>

</body>
</html>
