# Fronte-End-ADS[index.html](https://github.com/user-attachments/files/29617350/index.html)
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Zaqueu de Oliveira Araújo</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
      scroll-behavior: smooth;
    }

    body {
      background: linear-gradient(to right, #141e30, #243b55);
      color: #fff;
    }

    header {
      text-align: center;
      padding: 40px;
      animation: fadeDown 1s ease;
    }

    header img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 4px solid #00c3ff;
      margin-top: 15px;
      transition: 0.4s;
    }

    header img:hover {
      transform: scale(1.05);
    }

    nav {
      background: #000000a8;
      padding: 15px;
      text-align: center;
      position: sticky;
      top: 0;
    }

    nav a {
      color: #fff;
      margin: 0 20px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    nav a:hover {
      color: #00c3ff;
    }

    main {
      display: flex;
      flex-wrap: wrap;
      padding: 20px;
    }

    section {
      flex: 2;
      margin: 10px;
      background: #ffffff10;
      padding: 20px;
      border-radius: 12px;
      backdrop-filter: blur(10px);
      animation: fadeUp 1s ease;
    }

    aside {
      flex: 1;
      margin: 10px;
      background: #ffffff10;
      padding: 20px;
      border-radius: 12px;
    }

    h2 {
      margin-bottom: 10px;
      color: #00c3ff;
    }

    article {
      margin-top: 15px;
      padding: 15px;
      border-radius: 10px;
      background: #ffffff15;
      transition: 0.3s;
    }

    article:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 20px rgba(0,0,0,0.5);
    }

    a.link {
      display: inline-block;
      margin-top: 10px;
      padding: 8px 15px;
      background: #00c3ff;
      color: #000;
      border-radius: 20px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    a.link:hover {
      background: #00a2d6;
    }

    footer {
      text-align: center;
      padding: 15px;
      background: #000000a8;
      margin-top: 20px;
    }

    ul {
      padding-left: 20px;
    }

    @keyframes fadeDown {
      from { opacity: 0; transform: translateY(-30px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @media (max-width: 768px) {
      main {
        flex-direction: column;
      }
    }
  </style>
</head>

<body>

  <header>
    <h1>Zaqueu de Oliveira Araújo</h1>
    <p><strong>Usar a Tecnologia para ajudar pessoas</strong></p>
    <img src="Foto Perfil.png" alt="Foto de Zaqueu">
  </header>

  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#habilidades">Habilidades</a>
    <a href="#projetos">Projetos</a>
  </nav>

  <main>

    <section id="sobre">
      <h2>Sobre Mim</h2>
      <p>
        Pessoa comunicativa e de fácil convivência, apaixonado por tecnologia.
        Sempre buscando inovação e soluções que possam impactar positivamente
        a vida das pessoas através da tecnologia.
      </p>
    </section>

    <section id="habilidades">
      <h2>Habilidades</h2>
      <ul>
        <li>HTML5</li>
        <li>CSS3</li>
        <li>Lógica de Programação</li>
        <li>Python (básico)</li>
      </ul>
    </section>

    <section id="projetos">
      <h2>Projetos</h2>

      <article>
        <h3>Projeto Web</h3>
        <p>Criação de páginas modernas e responsivas.</p>
        <a class="link" href="https://github.com/zaqueuaraujo/projeto1" target="_blank">Ver projeto</a>
      </article>

      <article>
        <h3>Repositório de Estudos</h3>
        <p>Práticas e evolução na área de desenvolvimento.</p>
        <a class="link" href="https://github.com/zaqueuaraujo/projeto1" target="_blank">Ver projeto</a>
      </article>

    </section>

    <aside>
      <h2>Extras</h2>
      <p><strong>Hobby:</strong> Futebol ⚽</p>

      <p><strong>GitHub:</strong><br>
        <a class="link" href="https://github.com/zaqueuaraujo/projeto1" target="_blank">Acessar</a>
      </p>

      <p><strong>LinkedIn:</strong><br>
        <a class="link" href="https://www.linkedin.com/feed/" target="_blank">Acessar</a>
      </p>
    </aside>

  </main>

  <footer>
    <p>Email: Zaqueua@hotmail.com</p>
    <p>© 2026 Zaqueu</p>
  </footer>

</body>
</html>
