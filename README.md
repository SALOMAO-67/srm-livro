
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="SRM - Inteligência Artificial para Microempreendedores Individuais. Livro digital com tutoriais e ferramentas para MEIs.">
  <title>SRM - Inteligência Artificial para MEIs</title>
  
  <!-- Pré-carregamento de recursos importantes -->
  <link rel="preconnect" href="https://cdnjs.cloudflare.com">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  
  <!-- Fontes modernas -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">
  
  <!-- Ícones -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  
  <!-- Favicon -->
  <link rel="icon" href="https://drive.google.com/thumbnail?id=1x8NM3nLMO7Z0OxosNt9BEtTk7uhX6xi6&sz=w64" type="image/png">
  
  <style>
    :root {
      --primary: #0066cc;
      --primary-dark: #003366;
      --primary-light: #0055aa;
      --accent: #28a745;
      --text: #2d3748;
      --text-light: #4a5568;
      --bg: #f8fafc;
      --white: #ffffff;
      --transition: all 0.3s ease;
    }
    
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    
    body {
      font-family: 'Poppins', sans-serif;
      line-height: 1.6;
      color: var(--text);
      background-color: var(--bg);
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }
    
    header, footer {
      background: linear-gradient(135deg, var(--primary-dark), var(--primary));
      color: var(--white);
      padding: 1.5rem 2rem;
      text-align: center;
    }
    
    header {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 1rem;
    }
    
    header img {
      max-height: 80px;
      height: auto;
      width: auto;
      transition: var(--transition);
    }
    
    header img:hover {
      transform: scale(1.05);
    }
    
    h1, h2, h3 {
      line-height: 1.2;
    }
    
    h1 {
      font-size: clamp(1.5rem, 4vw, 2.2rem);
      font-weight: 700;
    }
    
    h2 {
      font-size: clamp(1.3rem, 3vw, 1.8rem);
      color: var(--primary-dark);
      margin-bottom: 1.5rem;
      position: relative;
      display: inline-block;
    }
    
    h2::after {
      content: '';
      position: absolute;
      bottom: -8px;
      left: 0;
      width: 60px;
      height: 3px;
      background: var(--accent);
    }
    
    nav {
      background-color: var(--primary-light);
      padding: 1rem;
      position: sticky;
      top: 0;
      z-index: 100;
    }
    
    .nav-container {
      display: flex;
      justify-content: center;
      gap: 1.5rem;
    }
    
    nav a {
      color: var(--white);
      text-decoration: none;
      font-weight: 500;
      padding: 0.5rem 1rem;
      border-radius: 4px;
      transition: var(--transition);
      display: flex;
      align-items: center;
      gap: 0.5rem;
    }
    
    nav a:hover, nav a:focus {
      background-color: rgba(255, 255, 255, 0.2);
      transform: translateY(-2px);
    }
    
    .menu-icon {
      font-size: 1.1rem;
    }
    
    main {
      flex: 1;
      padding: 2rem;
      max-width: 1200px;
      margin: 0 auto;
      width: 100%;
    }
    
    section {
      margin-bottom: 3rem;
      padding: 1.5rem;
      background-color: var(--white);
      border-radius: 8px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
      transition: var(--transition);
    }
    
    section:hover {
      box-shadow: 0 10px 15px rgba(0, 0, 0, 0.1);
    }
    
    ul {
      list-style: none;
    }
    
    #capitulos li {
      padding: 0.8rem 0;
      border-bottom: 1px solid #e2e8f0;
      display: flex;
      align-items: center;
      gap: 0.8rem;
    }
    
    #capitulos li::before {
      content: '\f054';
      font-family: 'Font Awesome 6 Free';
      font-weight: 900;
      color: var(--accent);
      font-size: 0.8rem;
    }
    
    #capitulos li:last-child {
      border-bottom: none;
    }
    
    p {
      color: var(--text-light);
      margin-bottom: 1.5rem;
    }
    
    .cta {
      display: inline-block;
      background: var(--accent);
      color: var(--white);
      text-align: center;
      padding: 1rem 2rem;
      border-radius: 6px;
      margin: 1.5rem 0;
      text-decoration: none;
      font-weight: 600;
      transition: var(--transition);
      border: 2px solid transparent;
    }
    
    .cta:hover, .cta:focus {
      background: transparent;
      color: var(--accent);
      border-color: var(--accent);
      transform: translateY(-3px);
      box-shadow: 0 10px 20px rgba(40, 167, 69, 0.2);
    }
    
    footer {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 1.5rem;
      padding: 2rem;
    }
    
    footer img {
      max-height: 60px;
    }
    
    .social-icons {
      display: flex;
      gap: 1.5rem;
    }
    
    .social-icons a {
      color: var(--white);
      text-decoration: none;
      font-size: 1.5rem;
      transition: var(--transition);
      width: 40px;
      height: 40px;
      display: flex;
      align-items: center;
      justify-content: center;
      border-radius: 50%;
    }
    
    .social-icons a:hover, .social-icons a:focus {
      background-color: rgba(255, 255, 255, 0.2);
      transform: translateY(-3px);
    }
    
    /* Mobile styles */
    @media (max-width: 768px) {
      .nav-container {
        flex-direction: column;
        gap: 0.5rem;
        align-items: center;
      }
      
      nav a {
        width: 100%;
        justify-content: center;
      }
      
      main {
        padding: 1rem;
      }
      
      section {
        padding: 1.2rem;
      }
      
      header img {
        max-height: 60px;
      }
      
      footer img {
        max-height: 50px;
      }
    }
    
    /* Acessibilidade - foco visível */
    a:focus, button:focus {
      outline: 3px solid var(--accent);
      outline-offset: 3px;
    }
    
    /* Animação suave para scroll */
    html {
      scroll-behavior: smooth;
    }
    
    /* Efeito de carregamento suave */
    @media (prefers-reduced-motion: reduce) {
      * {
        transition: none !important;
        animation: none !important;
      }
      
      html {
        scroll-behavior: auto;
      }
    }
  </style>
</head>
<body>
  <header>
  <img src="https://drive.google.com/thumbnail?id=1x8NM3nLMO7Z0OxosNt9BEtTk7uhX6xi6&sz=w500" alt="Logo SRM" style="max-height: 120px 80px;">
  <h1>SRM - IA para Microempreendedores</h1>
</header>
  <nav>
    <div class="nav-container">
      <a href="#capitulos" aria-label="Capítulos do livro">
        <i class="fas fa-book menu-icon" aria-hidden="true"></i>
        <span>Capítulos</span>
      </a>
      <a href="#comprar" aria-label="Comprar o livro">
        <i class="fas fa-shopping-cart menu-icon" aria-hidden="true"></i>
        <span>Comprar Livro</span>
      </a>
      <a href="https://wa.me/5564992934568" target="_blank" rel="noopener noreferrer" aria-label="Contato via WhatsApp">
        <i class="fab fa-whatsapp menu-icon" aria-hidden="true"></i>
        <span>Contato</span>
      </a>
    </div>
  </nav>

  <main>
    <section id="capitulos">
      <h2>Principais Tópicos</h2>
      <ul>
        <li>1. Introdução à IA e à SRM</li>
        <li>2. O MEI no Mundo Digital</li>
        <li>3. Ferramentas de IA para Negócios</li>
        <li>4. Tutoriais com a SRM</li>
        <li>5. Superando Desafios</li>
        <li>6. O Futuro do Empreendedor Digital</li>
      </ul>
    </section>

    <section id="comprar">
      <h2>Adquira o Livro Completo</h2>
      <p>Versão digital interativa com tutoriais e materiais extras para impulsionar seu negócio com Inteligência Artificial.</p>
      <a class="cta" href="https://kiwifi.com.br/loja/srm-livro" target="_blank" rel="noopener noreferrer">
        Comprar agora no Kiwifi
      </a>
    </section>
  </main>

  <footer>
    <img src="https://drive.google.com/thumbnail?id=1x8NM3nLMO7Z0OxosNt9BEtTk7uhX6xi6&sz=w300" alt="Logo SRM" style="max-height: 50px;">
    <p>&copy; <aria-label="current-year">2025</aria-label> SRM - Transformando Negócios com Inteligência Artificial</p>
    <div class="social-icons">
      <a href="https://instagram.com/souza_melo3" target="_blank" rel="noopener noreferrer" aria-label="Instagram da SRM">
        <i class="fab fa-instagram" aria-hidden="true"></i>
      </a>
      <a href="https://facebook.com/srm_empresa" target="_blank" rel="noopener noreferrer" aria-label="Facebook da SRM">
        <i class="fab fa-facebook" aria-hidden="true"></i>
      </a>
      <a href="https://wa.me/5564992934568" target="_blank" rel="noopener noreferrer" aria-label="WhatsApp da SRM">
        <i class="fab fa-whatsapp" aria-hidden="true"></i>
      </a>
    </div>
  </footer>

  <script>
    // Atualiza o ano do copyright automaticamente
    document.getElementById('current-year').textContent = new Date().getFullYear();
    
    // Adiciona classe quando o usuário começa a interagir com o teclado
    document.addEventListener('keydown', function() {
      document.body.classList.add('keyboard-user');
    });
    
    // Carregamento otimizado de recursos
    if ('loading' in HTMLImageElement.prototype) {
      const images = document.querySelectorAll('img[loading="lazy"]');
      images.forEach(img => {
        img.src = img.dataset.src;
      });
    }
  </script>
</body>
</html>
