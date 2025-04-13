<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Livro Interativo SRM</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }
    header {
      background-color: #007acc;
      color: white;
      padding: 20px;
      text-align: center;
    }
    header img {
      height: 60px;
      max-width: 100%;
    }
    nav {
      background-color: #005a99;
      padding: 10px;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }
    nav a {
      color: white;
      margin: 5px;
      padding: 8px 12px;
      text-decoration: none;
      background-color: #007acc;
      border-radius: 5px;
      font-size: 14px;
      display: flex;
      align-items: center;
      gap: 5px;
    }
    nav a:hover {
      background-color: #004d80;
    }
    section {
      background: white;
      padding: 20px;
      margin: 10px;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }
    .checklist ul {
      list-style: none;
      padding: 0;
    }
    .checklist li::before {
      content: "[ ] ";
    }
    .cta {
      background-color: #e8f5ff;
      padding: 20px;
      border: 2px dashed #007acc;
      border-radius: 8px;
      margin-top: 30px;
      text-align: center;
    }
    .cta a {
      display: inline-block;
      background-color: #00b894;
      color: white;
      padding: 10px 20px;
      margin-top: 10px;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
    }
    .social {
      text-align: center;
      margin-top: 30px;
    }
    .social a {
      margin: 0 10px;
      color: #007acc;
      font-size: 22px;
      text-decoration: none;
    }
    footer {
      text-align: center;
      margin: 20px 0;
      color: #777;
      font-size: 14px;
    }
    @media screen and (max-width: 600px) {
      nav {
        flex-direction: column;
        align-items: center;
      }
      nav a {
        width: 90%;
        justify-content: center;
      }
      .cta a {
        width: 90%;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="logo-srm.png" alt="Logo SRM">
    <h1>Inteligência Artificial para MEIs</h1>
    <p>Transformando seu Negócio com a SRM no Mundo Virtual</p>
  </header>

  <nav>
    <a href="#intro"><i class="fas fa-book"></i> Introdução</a>
    <a href="#cap1"><i class="fas fa-globe"></i> Mundo Digital</a>
    <a href="#cap2"><i class="fas fa-robot"></i> IA na Prática</a>
    <a href="#cap3"><i class="fas fa-tools"></i> Passo a Passo</a>
    <a href="#cap4"><i class="fas fa-exclamation-triangle"></i> Desafios</a>
    <a href="#cap5"><i class="fas fa-lightbulb"></i> Futuro</a>
    <a href="#cap6"><i class="fas fa-check"></i> Conclusão</a>
  </nav>

  <section id="intro">
    <h2>Introdução</h2>
    <p>Conheça a missão da SRM e como a Inteligência Artificial pode ser uma aliada poderosa para os microempreendedores.</p>
  </section>

  <section id="cap1">
    <h2>Capítulo 1 - O Mundo Digital e o MEI</h2>
    <p>Entenda os desafios e as oportunidades do empreendedorismo virtual, com apoio tecnológico da SRM.</p>
  </section>

  <section id="cap2">
    <h2>Capítulo 2 - IA na Prática</h2>
    <p>Aprenda a aplicar ferramentas como ChatGPT, Midjourney e automações para o dia a dia do seu negócio.</p>
    <div class="checklist">
      <strong>Checklist:</strong>
      <ul>
        <li>Entendi o que é IA</li>
        <li>Conheci ao menos 2 ferramentas</li>
        <li>Experimentei uma aplicação prática</li>
      </ul>
    </div>
  </section>

  <section id="cap3">
    <h2>Capítulo 3 - Passo a Passo com a SRM</h2>
    <p>Veja como a SRM ajuda você a implementar IA com tutoriais e integração de sistemas.</p>
  </section>

  <section id="cap4">
    <h2>Capítulo 4 - Superando Desafios</h2>
    <p>Descubra como superar obstáculos comuns como falta de recursos ou medo de tecnologia.</p>
  </section>

  <section id="cap5">
    <h2>Capítulo 5 - O Futuro do MEI</h2>
    <p>Conheça as tendências e como manter-se competitivo usando tecnologia.</p>
  </section>

  <section id="cap6">
    <h2>Capítulo 6 - Conclusão</h2>
    <p>Resumo do aprendizado, próximos passos e acesso aos recursos da SRM.</p>
    <p><a href="Livro_IA_para_MEIs_SRM_Interativo.pdf" download>Baixar PDF do Livro</a></p>
    <div class="cta">
      <h3>Adquira o Livro Completo!</h3>
      <p>Quer ir além? Acesse a versão completa do livro com dicas exclusivas, vídeos tutoriais e acesso à comunidade SRM.</p>
      <a href="https://sualoja.kiwify.com.br/livrosrm" target="_blank">Comprar na Kiwify</a>
    </div>
  </section>

  <div class="social">
    <h3>Nos siga e fale conosco:</h3>
    <a href="https://wa.me/5599999999999" target="_blank" title="WhatsApp"><i class="fab fa-whatsapp"></i></a>
    <a href="https://instagram.com/srm_oficial" target="_blank" title="Instagram"><i class="fab fa-instagram"></i></a>
    <a href="https://facebook.com/srmoficial" target="_blank" title="Facebook"><i class="fab fa-facebook"></i></a>
  </div>

  <footer>
    <p>&copy; 2025 SRM - Soluções para Microempreendedores com IA</p>
  </footer>
</body>
</html>
