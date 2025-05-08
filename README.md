<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Meu Portfólio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      display: flex;
      height: 100vh;
    }

    nav {
      background-color: #f2f2f2;
      width: 250px;
      padding: 20px;
      box-shadow: 2px 0 5px rgba(0, 0, 0, 0.1);
    }

    nav h2 {
      font-size: 20px;
    }

    nav ul {
      list-style: none;
      padding: 0;
    }

    nav ul li {
      margin: 15px 0;
    }

    nav ul li a {
      text-decoration: none;
      color: #333;
    }

    main {
      padding: 40px;
      flex-grow: 1;
    }

    section {
      margin-bottom: 60px;
    }

    h1, h2 {
      color: #333;
    }
  </style>
</head>
<body>
  <nav>
    <h2>Meu Portfólio</h2>
    <ul>
      <li><a href="#inicio">Início</a></li>
      <li><a href="#perfil">Perfil</a></li>
      <li><a href="#curriculo">Currículo</a></li>
      <li><a href="#projetos">Projetos</a></li>
      <li><a href="#info">+Info</a></li>
    </ul>
  </nav>

  <main>
    <section id="inicio">
      <h1>Bem-vindo!</h1>
      <p>Esse é meu site pessoal com informações sobre mim e meus projetos.</p>
    </section>

    <section id="perfil">
      <h2>Perfil</h2>
      <p>Aqui vai uma descrição sobre você, sua história, interesses, etc.</p>
    </section>

    <section id="curriculo">
      <h2>Currículo</h2>
      <p>Detalhes sobre sua formação, experiências e habilidades.</p>
    </section>

    <section id="projetos">
      <h2>Projetos</h2>
      <p>Apresente aqui alguns projetos desenvolvidos. Pode incluir links ou imagens.</p>
    </section>

    <section id="info">
      <h2>+Informações</h2>
      <p>Entre em contato por e-mail ou redes sociais.</p>
    </section>
  </main>
</body>
</html>

