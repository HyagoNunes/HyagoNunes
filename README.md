<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Hyago Nunes - Perfil GitHub</title>
  <!-- Importação de fonte do Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    /* Reset básico e fonte */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Roboto', sans-serif;
      background: linear-gradient(135deg, #0d2538, #203a43);
      color: #333;
      line-height: 1.6;
      padding: 20px;
    }
    a {
      color: #3498db;
      text-decoration: none;
      transition: color 0.3s;
    }
    a:hover {
      color: #1d6fa5;
    }
    /* Container centralizado */
    .container {
      max-width: 900px;
      background: #fff;
      margin: 30px auto;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
      animation: fadeIn 1s ease-out;
    }
    /* Animação simples de fadeIn */
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    header {
      text-align: center;
      margin-bottom: 30px;
    }
    header h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
      color: #0d2538;
    }
    header p {
      font-size: 1.1rem;
      color: #555;
    }
    hr {
      border: none;
      border-top: 1px solid #ddd;
      margin: 30px 0;
    }
    h2 {
      color: #0d2538;
      margin-bottom: 15px;
    }
    ul {
      margin-left: 20px;
      margin-bottom: 20px;
    }
    li {
      margin-bottom: 10px;
    }
    .center {
      text-align: center;
    }
    .badges img {
      margin: 5px;
      transition: transform 0.3s;
    }
    .badges img:hover {
      transform: scale(1.05);
    }
    .projects li {
      margin-bottom: 15px;
    }
    .projects a {
      font-weight: 700;
    }
    .social a {
      display: inline-block;
      margin-right: 15px;
      margin-bottom: 10px;
      font-weight: bold;
    }
    /* Efeito de entrada dos elementos */
    .fade-in {
      opacity: 0;
      animation: fadeIn 1s forwards;
    }
    .fade-in.delay-1 {
      animation-delay: 0.5s;
    }
    .fade-in.delay-2 {
      animation-delay: 1s;
    }
  </style>
</head>
<body>
  <div class="container">
    <header class="fade-in">
      <h1>Olá, eu sou o Hyago Nunes</h1>
      <p>Seja bem-vindo ao meu espaço no GitHub. Aqui, compartilho meus projetos e reflexões sobre tecnologia, com foco em desenvolvimento e automação.</p>
    </header>

    <hr>

    <section class="fade-in delay-1">
      <h2>Sobre Mim</h2>
      <p>Atualmente, dedico meu tempo a explorar soluções inovadoras, principalmente na criação de <strong>automação de processos</strong>. Meu interesse por <strong>I.A</strong> me impulsiona a buscar sempre novas formas de transformar ideias em realidade.</p>
      <p><strong>Minhas Especialidades:</strong></p>
      <ul>
        <li>Desenvolvimento de aplicações em <strong>Python</strong> e <strong>JavaScript</strong>.</li>
        <li>Criação e manutenção de bots inteligentes para diferentes plataformas.</li>
        <li>Implementação de processos automatizados que otimizam fluxos de trabalho.</li>
      </ul>
      <p>Sinta-se à vontade para trocar ideias ou tirar dúvidas sobre qualquer um desses assuntos.</p>
    </section>

    <hr>

    <section class="fade-in delay-2">
      <h2>Estatísticas do GitHub</h2>
      <div class="center">
        <img src="https://github-readme-stats.vercel.app/api?username=HyagoNunes&show_icons=true&theme=radical" alt="Estatísticas do GitHub">
        <br>
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=HyagoNunes&layout=compact&theme=radical" alt="Principais Linguagens">
      </div>
    </section>

    <hr>

    <section class="fade-in">
      <h2>Tecnologias e Ferramentas</h2>
      <div class="badges center">
        <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
        <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
        <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
        <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
        <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
        <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
      </div>
    </section>

    <hr>

    <section class="fade-in delay-1">
      <h2>Projetos Recentes</h2>
      <ul class="projects">
        <li>
          <strong><a href="https://github.com/HyagoNunes/Discord-Bot-Voidzinho" target="_blank">Discord-Bot-Voidzinho</a></strong>  
          Bot inteligente para o Discord, com funcionalidades que exploram o potencial da inteligência artificial.
        </li>
        <li>
          <strong><a href="https://github.com/HyagoNunes/Script-FreeBTC" target="_blank">Script-FreeBTC</a></strong>  
          Solução automatizada para reivindicações no FreeBitcoin, otimizando a interação com a plataforma.
        </li>
        <li>
          <strong><a href="https://github.com/HyagoNunes/WebCripto" target="_blank">WebCripto</a></strong>  
          Projeto web dedicado a oferecer informações detalhadas sobre o universo das criptomoedas.
        </li>
        <li>
          <strong><a href="https://github.com/HyagoNunes/Flag-API" target="_blank">Flag-API</a></strong>  
          API que disponibiliza dados e imagens sobre bandeiras do mundo, útil para diversas aplicações.
        </li>
      </ul>
    </section>

    <hr>

    <section class="fade-in delay-2">
      <h2>Conecte-se Comigo</h2>
      <div class="social">
        <p>
          <strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/seu-perfil/" target="_blank">Hyago Nunes</a>
        </p>
        <p>
          <strong>GitHub:</strong> <a href="https://github.com/HyagoNunes" target="_blank">HyagoNunes</a>
        </p>
        <p>
          <strong>Contato:</strong><br>
          <strong>E-mail:</strong> <a href="mailto:hyagonunesb96@gmail.com">hyagonunesb96@gmail.com</a><br>
          <strong>Discord:</strong> mg7sr.fox | #5539
        </p>
      </div>
    </section>

    <footer class="center" style="margin-top: 30px; color: #777;">
      <p>Obrigado pela visita! Fique à vontade para acompanhar meu trabalho e trocar ideias.</p>
    </footer>
  </div>
</body>
</html>
