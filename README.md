# cantinhokidses<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cantinho Kids ES | Cuidado, Recreação e Amor em Limeira - SP</title>
  <meta name="description" content="Cantinho Kids ES: espaço de cuidado e recreação infantil em Limeira - SP. Mensalidades a partir de R$ 400, pacotes semanais, diárias e hotelzinho com carinho, segurança e muita brincadeira. Fale no WhatsApp!">
  <meta property="og:title" content="Cantinho Kids ES | Cuidado, Recreação e Amor em Limeira - SP">
  <meta property="og:description" content="Um cantinho seguro, acolhedor e cheio de brincadeiras para o seu pequeno em Limeira - SP.">
  <meta property="og:type" content="website">

  <!-- Fontes do Google -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@400;500;600;700&family=Nunito:wght@400;600;700;800&display=swap" rel="stylesheet">

  <!-- Ícones Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

  <style>
    :root {
      --purple: #6c5ce7;
      --purple-dark: #4834d4;
      --purple-light: #f3e8ff;
      --orange: #ff7675;
      --orange-warm: #f0932b;
      --blue: #0984e3;
      --green: #00b894;
      --yellow: #f1c40f;
      --text: #2d3436;
      --text-muted: #636e72;
      --bg: #faf9f6;
      --card-bg: #ffffff;
      --radius: 20px;
      --radius-sm: 12px;
      --shadow-sm: 0 4px 12px rgba(0,0,0,0.05);
      --shadow-md: 0 10px 30px rgba(108, 92, 231, 0.08);
      --shadow-lg: 0 20px 40px rgba(0,0,0,0.1);
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Nunito', sans-serif;
      background-color: var(--bg);
      color: var(--text);
      line-height: 1.6;
      overflow-x: hidden;
    }

    h1, h2, h3, h4, .brand-name {
      font-family: 'Fredoka', cursive, sans-serif;
      font-weight: 600;
    }

    .container {
      width: 100%;
      max-width: 1140px;
      margin: 0 auto;
      padding: 0 24px;
    }

    /* HEADER & NAVEGAÇÃO */
    header {
      background: #ffffff;
      padding: 16px 0;
      box-shadow: 0 2px 10px rgba(0,0,0,0.03);
      position: sticky;
      top: 0;
      z-index: 100;
    }

    .header-content {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo-wrap {
      display: flex;
      align-items: center;
      gap: 12px;
      text-decoration: none;
      color: #2c1844;
    }

    .logo-circle {
      width: 48px;
      height: 48px;
      background: linear-gradient(135deg, var(--purple), var(--orange));
      color: #fff;
      border-radius: 50%;
      display: grid;
      place-items: center;
      font-size: 1.4rem;
    }

    .logo-text {
      font-family: 'Fredoka', cursive;
      font-size: 1.35rem;
      font-weight: 700;
      color: #2c1844;
    }

    .logo-text span {
      color: var(--orange-warm);
    }

    nav {
      display: flex;
      gap: 20px;
      align-items: center;
    }

    nav a {
      text-decoration: none;
      color: var(--text);
      font-weight: 700;
      font-size: 0.95rem;
      transition: color 0.2s;
    }

    nav a:hover {
      color: var(--purple);
    }

    .btn-header {
      background: #25d366;
      color: #fff !important;
      padding: 8px 18px;
      border-radius: 50px;
      display: inline-flex;
      align-items: center;
      gap: 8px;
      transition: transform 0.2s, background-color 0.2s;
    }

    .btn-header:hover {
      background: #1eb956;
      transform: translateY(-2px);
    }

    /* HERO */
    .hero {
      padding: 70px 0 60px;
      background: linear-gradient(180deg, #ffffff 0%, var(--bg) 100%);
      position: relative;
    }

    .hero-grid {
      display: grid;
      grid-template-columns: 1.2fr 0.8fr;
      align-items: center;
      gap: 40px;
    }

    .hero-badge {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      background: var(--purple-light);
      color: var(--purple-dark);
      padding: 6px 14px;
      border-radius: 50px;
      font-weight: 800;
      font-size: 0.85rem;
      margin-bottom: 20px;
    }

    .hero h1 {
      font-size: 2.8rem;
      line-height: 1.2;
      color: #2c1844;
      margin-bottom: 20px;
    }

    .hero h1 span {
      color: var(--orange-warm);
    }

    .hero p {
      font-size: 1.15rem;
      color: #555;
      margin-bottom: 30px;
      max-width: 520px;
    }

    .hero-btns {
      display: flex;
      flex-wrap: wrap;
      gap: 16px;
      margin-bottom: 35px;
    }

    .btn-primary {
      background: #25d366;
      color: #fff;
      font-weight: 800;
      text-decoration: none;
      padding: 14px 28px;
      border-radius: 50px;
      display: inline-flex;
      align-items: center;
      gap: 10px;
      box-shadow: 0 6px 16px rgba(37, 211, 102, 0.35);
      transition: 0.2s;
    }

    .btn-primary:hover {
      transform: translateY(-3px);
      box-shadow: 0 10px 22px rgba(37, 211, 102, 0.45);
    }

    .btn-outline {
      border: 2px solid var(--purple);
      color: var(--purple);
      font-weight: 800;
      text-decoration: none;
      padding: 12px 24px;
      border-radius: 50px;
      display: inline-flex;
      align-items: center;
      gap: 8px;
      transition: 0.2s;
    }

    .btn-outline:hover {
      background: var(--purple);
      color: #fff;
    }

    .hero-trust {
      display: flex;
      flex-wrap: wrap;
      gap: 16px;
    }

    .hero-trust span {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      font-size: 0.88rem;
      font-weight: 700;
      color: #444;
    }

    .hero-trust span i {
      color: var(--green);
    }

    .hero-card {
      background: #fff;
      border-radius: 28px;
      padding: 30px;
      box-shadow: var(--shadow-md);
      border: 1px solid rgba(0,0,0,0.05);
      text-align: center;
    }

    .hero-card i.big-icon {
      font-size: 3.5rem;
      color: var(--orange-warm);
      margin-bottom: 15px;
    }

    /* TITULOS DE SEÇÃO */
    .section-title-wrap {
      text-align: center;
      max-width: 680px;
      margin: 0 auto 50px;
    }

    .section-tag {
      font-weight: 800;
      color: var(--purple);
      text-transform: uppercase;
      font-size: 0.85rem;
      letter-spacing: 1px;
      display: block;
      margin-bottom: 8px;
    }

    .section-title {
      font-size: 2.2rem;
      color: #2c1844;
      line-height: 1.25;
      margin-bottom: 12px;
    }

    .section-title span {
      color: var(--orange-warm);
    }

    .section-desc {
      color: var(--text-muted);
      font-size: 1.05rem;
    }

    /* SOBRE NÓS */
    .section-about {
      padding: 60px 0;
    }

    .about-box {
      background: #fff;
      border-radius: 28px;
      padding: 44px;
      box-shadow: var(--shadow-sm);
    }

    .about-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 16px;
      list-style: none;
      margin-top: 25px;
    }

    .about-list li {
      display: flex;
      align-items: center;
      gap: 10px;
      font-weight: 700;
      color: #333;
    }

    .about-list li i {
      color: var(--green);
    }

    /* HISTÓRIA E PILARES */
    .section-story {
      padding: 40px 0 80px;
    }

    .story-box {
      background: #fff;
      border-radius: 28px;
      padding: 44px 48px;
      box-shadow: var(--shadow-md);
      border-left: 8px solid var(--orange-warm);
      margin-bottom: 60px;
    }

    .story-box h3 {
      font-size: 1.8rem;
      color: #2c1844;
      margin-bottom: 14px;
    }

    .story-box h3 i {
      color: var(--orange-warm);
      margin-right: 8px;
    }

    .story-box p {
      color: #555;
      font-size: 1.05rem;
      margin-bottom: 14px;
    }

    .story-box p:last-child {
      margin-bottom: 0;
    }

    .pillars-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 24px;
      margin-bottom: 60px;
    }

    .pillar {
      background: #fff;
      border-radius: var(--radius);
      padding: 30px 26px;
      box-shadow: var(--shadow-sm);
      border-top: 5px solid var(--act-color);
      transition: transform 0.2s ease;
    }

    .pillar:hover {
      transform: translateY(-4px);
    }

    .pillar .a-icon {
      width: 56px;
      height: 56px;
      border-radius: 16px;
      display: grid;
      place-items: center;
      font-size: 1.5rem;
      color: #fff;
      background: var(--act-color);
      margin-bottom: 16px;
    }

    .pillar h3 {
      font-size: 1.2rem;
      color: #2c1844;
      margin-bottom: 8px;
    }

    .pillar p {
      color: var(--text-muted);
      font-size: 0.95rem;
    }

    .commitment {
      background: linear-gradient(135deg, #f3e8ff 0%, #fff4e5 100%);
      border-radius: 28px;
      padding: 44px 48px;
      text-align: center;
    }

    .commitment h3 {
      font-size: 1.8rem;
      color: #2c1844;
      margin-bottom: 12px;
    }

    .commitment h3 span {
      color: var(--orange-warm);
    }

    .commitment p {
      color: #555;
      font-size: 1.08rem;
      max-width: 820px;
      margin: 0 auto;
    }

    /* PLANOS E PREÇOS */
    .section-pricing {
      padding: 70px 0 90px;
    }

    .pricing-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(310px, 1fr));
      gap: 30px;
      align-items: stretch;
    }

    .plan-card {
      background: #fff;
      border-radius: 24px;
      padding: 36px 30px;
      box-shadow: var(--shadow-sm);
      display: flex;
      flex-direction: column;
      position: relative;
      border: 2px solid transparent;
      transition: transform 0.2s, box-shadow 0.2s;
    }

    .plan-card:hover {
      transform: translateY(-6px);
      box-shadow: var(--shadow-lg);
    }

    .plan-card.featured {
      border-color: var(--purple);
      box-shadow: var(--shadow-md);
    }

    .plan-ribbon {
      position: absolute;
      top: -14px;
      left: 50%;
      transform: translateX(-50%);
      background: var(--purple);
      color: #fff;
      padding: 4px 16px;
      border-radius: 50px;
      font-size: 0.8rem;
      font-weight: 800;
      white-space: nowrap;
    }

    .plan-icon {
      width: 52px;
      height: 52px;
      border-radius: 14px;
      display: grid;
      place-items: center;
      background: var(--purple-light);
      color: var(--plan-color);
      font-size: 1.4rem;
      margin-bottom: 16px;
    }

    .plan-card h3 {
      font-size: 1.55rem;
      color: #2c1844;
      margin-bottom: 4px;
    }

    .plan-time {
      font-size: 0.95rem;
      color: var(--text-muted);
      margin-bottom: 20px;
    }

    .price-list {
      list-style: none;
      display: grid;
      gap: 12px;
      margin-bottom: 24px;
    }

    .price-row {
      background: #f8fafc;
      border-radius: 14px;
      padding: 12px 14px;
      border-left: 4px solid var(--plan-color, var(--purple));
    }

    .price-row-top {
      display: flex;
      justify-content: space-between;
      align-items: baseline;
      gap: 10px;
    }

    .price-label {
      font-weight: 700;
      font-size: 0.95rem;
      color: #333;
    }

    .price-value {
      font-family: 'Fredoka', sans-serif;
      font-size: 1.35rem;
      font-weight: 600;
      color: var(--plan-color, var(--purple));
      white-space: nowrap;
    }

    .price-value small {
      font-size: 0.8rem;
      font-weight: 500;
      color: var(--text-muted);
    }

    .price-perk {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      margin-top: 6px;
      background: #fff4e5;
      color: #b45309;
      font-size: 0.8rem;
      font-weight: 800;
      padding: 4px 10px;
      border-radius: 50px;
    }

    .plan-features {
      list-style: none;
      display: grid;
      gap: 10px;
      margin-bottom: 28px;
      margin-top: auto;
    }

    .plan-features li {
      font-size: 0.92rem;
      color: #555;
      display: flex;
      align-items: center;
      gap: 8px;
    }

    .plan-features li i {
      color: var(--green);
    }

    .btn-plan {
      background: var(--purple);
      color: #fff;
      font-weight: 800;
      text-align: center;
      text-decoration: none;
      padding: 12px 20px;
      border-radius: 50px;
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 8px;
      transition: opacity 0.2s;
    }

    .btn-plan:hover {
      opacity: 0.9;
    }

    /* FAQ */
    .section-faq {
      padding: 60px 0;
      background: #fff;
    }

    .faq-wrap {
      max-width: 760px;
      margin: 0 auto;
      display: grid;
      gap: 14px;
    }

    .faq-item {
      background: var(--bg);
      border-radius: var(--radius-sm);
      padding: 18px 22px;
      cursor: pointer;
    }

    .faq-item summary {
      font-weight: 700;
      font-size: 1.05rem;
      color: #2c1844;
      list-style: none;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .faq-item summary::-webkit-details-marker {
      display: none;
    }

    .faq-item summary::after {
      content: '\f078';
      font-family: 'Font Awesome 6 Free';
      font-weight: 900;
      font-size: 0.85rem;
      color: var(--purple);
      transition: transform 0.2s;
    }

    .faq-item[open] summary::after {
      transform: rotate(180deg);
    }

    .faq-item p {
      margin-top: 12px;
      color: #555;
      font-size: 0.95rem;
    }

    /* CTA FINAL */
    .section-cta {
      padding: 80px 0;
    }

    .cta-box {
      background: linear-gradient(135deg, #2c1844, var(--purple-dark));
      border-radius: 32px;
      padding: 60px 40px;
      color: #fff;
      text-align: center;
    }

    .cta-box h2 {
      font-size: 2.2rem;
      margin-bottom: 12px;
    }

    .cta-box p {
      font-size: 1.1rem;
      opacity: 0.9;
      max-width: 600px;
      margin: 0 auto 30px;
    }

    .cta-actions {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      align-items: center;
      gap: 20px;
    }

    .btn-zap-lg {
      background: #25d366;
      color: #fff;
      font-weight: 800;
      text-decoration: none;
      padding: 16px 36px;
      border-radius: 50px;
      font-size: 1.1rem;
      display: inline-flex;
      align-items: center;
      gap: 10px;
      transition: transform 0.2s;
    }

    .btn-zap-lg:hover {
      transform: scale(1.04);
    }

    .cta-phone {
      color: #fff;
      text-decoration: none;
      font-weight: 700;
      font-size: 1.05rem;
      display: inline-flex;
      align-items: center;
      gap: 8px;
    }

    /* FOOTER */
    footer {
      background: #1e1330;
      color: #a4b0be;
      padding: 50px 0 30px;
      font-size: 0.95rem;
    }

    .footer-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 40px;
      margin-bottom: 40px;
    }

    .footer-grid h4 {
      color: #fff;
      margin-bottom: 16px;
      font-size: 1.15rem;
    }

    .footer-grid ul {
      list-style: none;
      display: grid;
      gap: 10px;
    }

    .footer-grid a {
      color: #a4b0be;
      text-decoration: none;
      transition: color 0.2s;
    }

    .footer-grid a:hover {
      color: #fff;
    }

    .footer-bottom {
      border-top: 1px solid rgba(255,255,255,0.08);
      padding-top: 25px;
      text-align: center;
      font-size: 0.85rem;
    }

    /* BOTAO FLUTUANTE DO WHATSAPP */
    .zap-float {
      position: fixed;
      bottom: 24px;
      right: 24px;
      width: 60px;
      height: 60px;
      background: #25d366;
      border-radius: 50%;
      color: #fff;
      display: grid;
      place-items: center;
      font-size: 2rem;
      text-decoration: none;
      box-shadow: 0 6px 20px rgba(37, 211, 102, 0.4);
      z-index: 999;
      transition: transform 0.2s;
    }

    .zap-float:hover {
      transform: scale(1.1);
    }

    /* ANIMAÇÃO REVEAL */
    .reveal {
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 0.6s ease, transform 0.6s ease;
    }

    .reveal.active {
      opacity: 1;
      transform: translateY(0);
    }

    @media (prefers-reduced-motion: reduce) {
      .reveal {
        opacity: 1;
        transform: none;
        transition: none;
      }
    }

    @media (max-width: 768px) {
      .hero-grid { grid-template-columns: 1fr; }
      .hero h1 { font-size: 2.1rem; }
      .story-box, .commitment { padding: 32px 24px; }
      .story-box h3, .commitment h3 { font-size: 1.5rem; }
      nav a:not(.btn-header) { display: none; }
    }
  </style>
</head>
<body>

  <!-- HEADER -->
  <header>
    <div class="container header-content">
      <a href="#" class="logo-wrap">
        <div class="logo-circle"><i class="fa-solid fa-shapes"></i></div>
        <div class="logo-text">Cantinho Kids <span>ES</span></div>
      </a>
      <nav>
        <a href="#sobre">Quem somos</a>
        <a href="#historia">História</a>
        <a href="#planos">Planos</a>
        <a href="#faq">Dúvidas</a>
        <a href="#" class="btn-header" data-zap="Olá! Vim pelo site e gostaria de falar com vocês."><i class="fa-brands fa-whatsapp"></i> Fale Conosco</a>
      </nav>
    </div>
  </header>

  <!-- HERO -->
  <section class="hero">
    <div class="container hero-grid">
      <div class="hero-left">
        <span class="hero-badge"><i class="fa-solid fa-heart"></i> O melhor lugar para o seu pequeno</span>
        <h1>Cuidado, Recreação e <span>Amor</span> em Limeira - SP</h1>
        <p>Um cantinho acolhedor, seguro e cheio de carinho para seu filho brincar, se desenvolver e fazer novos amigos enquanto você trabalha com total tranquilidade.</p>
        
        <div class="hero-btns">
          <a href="#" class="btn-primary" data-zap="Olá! Vim pelo site do Cantinho Kids ES e gostaria de agendar uma visita."><i class="fa-brands fa-whatsapp"></i> Agendar uma Visita</a>
          <a href="#planos" class="btn-outline">Conhecer Planos</a>
        </div>

        <div class="hero-trust">
          <span><i class="fa-solid fa-circle-check"></i> Ambiente seguro</span>
          <span><i class="fa-solid fa-circle-check"></i> Turmas acolhedoras</span>
          <span><i class="fa-solid fa-circle-check"></i> Empresa formalizada</span>
          <span><i class="fa-solid fa-circle-check"></i> Atendimento próximo</span>
        </div>
      </div>

      <div class="hero-right">
        <div class="hero-card">
          <i class="fa-solid fa-children big-icon"></i>
          <h3>Um espaço feito com o coração</h3>
          <p style="color: #666; font-size: 0.95rem; margin-top: 8px;">Desenvolvimento pedagógico, estímulos lúdicos e alimentação carinhosa todos os dias.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- QUEM SOMOS -->
  <section class="section-about" id="sobre">
    <div class="container">
      <div class="about-box reveal">
        <div class="section-title-wrap">
          <span class="section-tag">Quem somos</span>
          <h2 class="section-title">Sobre Nós – <span>Cantinho Kids ES</span></h2>
        </div>
        <p>No Cantinho Kids ES, acreditamos que a infância é a fase mais preciosa da vida e que cada criança merece crescer em um ambiente onde o carinho, a segurança e o desenvolvimento caminhem lado a lado.</p>
        <p style="margin-top: 12px;">Localizado em Limeira, São Paulo, nosso espaço nasceu do sonho e do compromisso de oferecer um refúgio acolhedor para as famílias que buscam excelência em cuidados infantis, recreação e estímulo pedagógico.</p>

        <ul class="about-list">
          <li><i class="fa-solid fa-check"></i> Cuidados infantis</li>
          <li><i class="fa-solid fa-check"></i> Recreação diária</li>
          <li><i class="fa-solid fa-check"></i> Estímulo pedagógico</li>
          <li><i class="fa-solid fa-check"></i> Parceria com a família</li>
          <li><i class="fa-solid fa-check"></i> Cuidado individualizado</li>
          <li><i class="fa-solid fa-check"></i> Ambiente limpo e acolhedor</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- HISTÓRIA E PILARES -->
  <section class="section-story" id="historia" aria-label="Nossa história e pilares">
    <div class="container">
      <div class="story-box reveal">
        <h3><i class="fa-solid fa-heart"></i>Nossa História e Propósito</h3>
        <p>O Cantinho Kids ES foi idealizado e fundado pelo casal <strong>Giovanny S. (Giovanni Sampaio dos Santos)</strong> e <strong>Ester Rodrigues dos Santos</strong>, unidos pela paixão pela educação e pelo cuidado com o próximo. Como pais, compreendemos profundamente a importância de confiar os nossos bens mais preciosos — os nossos filhos — a um local que preze por valores éticos, responsabilidade absoluta e muito afeto.</p>
        <p>Desde a nossa fundação e estruturação, nossa trajetória tem sido pautada pela transparência e pelo rigor com a qualidade dos nossos serviços. Formalizado juridicamente e estruturado para atender às demandas das famílias limeirenses, o Cantinho Kids ES consolidou-se como um centro recreativo e de apoio infantil focado no bem-estar integral dos pequenos.</p>
      </div>

      <div class="section-title-wrap reveal">
        <span class="section-tag">Nossos pilares</span>
        <h2 class="section-title">Pilares da <span>nossa empresa</span></h2>
      </div>

      <div class="pillars-grid">
        <div class="pillar reveal" style="--act-color: var(--blue);">
          <div class="a-icon"><i class="fa-solid fa-scale-balanced"></i></div>
          <h3>Responsabilidade e Seriedade</h3>
          <p>Gestão administrativa transparente e profissional, garantindo total tranquilidade e segurança jurídica e física para pais e responsáveis.</p>
        </div>

        <div class="pillar reveal" style="--act-color: var(--green);">
          <div class="a-icon"><i class="fa-solid fa-shield-heart"></i></div>
          <h3>Segurança e Acolhimento</h3>
          <p>Estrutura física e rotina planejadas com rigor para proporcionar um ambiente seguro, lúdico e onde a criança se sinta em casa.</p>
        </div>

        <div class="pillar reveal" style="--act-color: var(--orange-warm);">
          <div class="a-icon"><i class="fa-solid fa-seedling"></i></div>
          <h3>Desenvolvimento com Afeto</h3>
          <p>Aliamos diversão a práticas lúdicas que estimulam criatividade, socialização, coordenação motora e aprendizado saudável.</p>
        </div>

        <div class="pillar reveal" style="--act-color: var(--purple);">
          <div class="a-icon"><i class="fa-solid fa-people-roof"></i></div>
          <h3>Parceria com a Família</h3>
          <p>Nossa missão é ser extensão do lar: canal de diálogo aberto, honesto e próximo com cada responsável.</p>
        </div>
      </div>

      <div class="commitment reveal">
        <h3>Compromisso com o <span>Futuro</span></h3>
        <p>O Cantinho Kids ES continua evoluindo dia após dia, investindo em capacitação, melhorias estruturais e na excelência do atendimento. O nosso compromisso é ser o parceiro de confiança dos pais em Limeira, proporcionando um ambiente onde as crianças constroem memórias felizes enquanto se desenvolvem com segurança e amor.</p>
      </div>
    </div>
  </section>

  <!-- PLANOS -->
  <section class="section-pricing" id="planos">
    <div class="container">
      <div class="section-title-wrap reveal">
        <span class="section-tag">Planos</span>
        <h2 class="section-title">Planos com <span>benefícios</span> para cada rotina</h2>
        <p class="section-desc">Mensalidade, pacotes semanais ou diárias avulsas: escolha a opção que combina com sua família e garanta a vaga pelo WhatsApp.</p>
      </div>

      <div class="pricing-grid">
        <!-- PLANO MENSALISTA -->
        <article class="plan-card featured reveal" style="--plan-color: var(--purple);">
          <span class="plan-ribbon"><i class="fa-solid fa-star"></i> Mais procurado</span>
          <div class="plan-icon"><i class="fa-solid fa-house-chimney-user"></i></div>
          <h3>Mensalistas</h3>
          <p class="plan-time">Para quem precisa de continuidade</p>

          <ul class="price-list">
            <li class="price-row">
              <div class="price-row-top">
                <span class="price-label">Individual (Meio Período)</span>
                <span class="price-value">R$ 400,00<small>/mês</small></span>
              </div>
            </li>
            <li class="price-row">
              <div class="price-row-top">
                <span class="price-label">Individual (Integral)</span>
                <span class="price-value">R$ 460,00<small>/mês</small></span>
              </div>
            </li>
            <li class="price-row">
              <div class="price-row-top">
                <span class="price-label">Combo Irmãos/Dupla (Integral)</span>
                <span class="price-value">R$ 600,00<small>/mês</small></span>
              </div>
              <span class="price-perk"><i class="fa-solid fa-piggy-bank"></i> Economia garantida para quem tem mais de um pequeno!</span>
            </li>
          </ul>

          <ul class="plan-features">
            <li><i class="fa-solid fa-check"></i> Rotina estável e vínculo com a criança</li>
            <li><i class="fa-solid fa-check"></i> Recreação e estímulo pedagógico diário</li>
            <li><i class="fa-solid fa-check"></i> Acompanhamento próximo com a família</li>
          </ul>

          <a href="#" class="btn-plan" data-zap="Olá! Tenho interesse no plano Mensalista do Cantinho Kids ES. Gostaria de garantir uma vaga."><i class="fa-brands fa-whatsapp"></i> Quero ser mensalista</a>
        </article>

        <!-- PLANO SEMANAL -->
        <article class="plan-card reveal" style="--plan-color: var(--blue);">
          <div class="plan-icon"><i class="fa-solid fa-umbrella-beach"></i></div>
          <h3>Semanal</h3>
          <p class="plan-time">Para períodos curtos e férias</p>

          <ul class="price-list">
            <li class="price-row">
              <div class="price-row-top">
                <span class="price-label">1 Semana inteira</span>
                <span class="price-value">R$ 180,00</span>
              </div>
            </li>
            <li class="price-row">
              <div class="price-row-top">
                <span class="price-label">2 Semanas de cuidado</span>
                <span class="price-value">R$ 280,00</span>
              </div>
              <span class="price-perk"><i class="fa-solid fa-tags"></i> Super desconto na segunda semana!</span>
            </li>
          </ul>

          <ul class="plan-features">
            <li><i class="fa-solid fa-check"></i> Ideal para férias escolares</li>
            <li><i class="fa-solid fa-check"></i> Semana cheia de brincadeiras e atividades</li>
            <li><i class="fa-solid fa-check"></i> Sem compromisso de mensalidade</li>
          </ul>

          <a href="#" class="btn-plan" style="background: var(--blue);" data-zap="Olá! Tenho interesse no pacote Semanal do Cantinho Kids ES. Gostaria de verificar a disponibilidade."><i class="fa-brands fa-whatsapp"></i> Reservar semana</a>
        </article>

        <!-- AVULSO & HOTELZINHO -->
        <article class="plan-card reveal" style="--plan-color: var(--orange-warm);">
          <div class="plan-icon"><i class="fa-solid fa-calendar-day"></i></div>
          <h3>Avulso &amp; Hotelzinho</h3>
          <p class="plan-time">Flexibilidade total</p>

          <ul class="price-list">
            <li class="price-row">
              <div class="price-row-top">
                <span class="price-label">Meio dia</span>
                <span class="price-value">R$ 45,00</span>
              </div>
            </li>
            <li class="price-row">
              <div class="price-row-top">
                <span class="price-label">Dia completo</span>
                <span class="price-value">R$ 70,00</span>
              </div>
            </li>
            <li class="price-row">
              <div class="price-row-top">
                <span class="price-label">Hotelzinho</span>
                <span class="price-value">R$ 100,00</span>
              </div>
              <span class="price-perk"><i class="fa-solid fa-moon"></i> Para quando você precisar de mais tempo</span>
            </li>
          </ul>

          <ul class="plan-features">
            <li><i class="fa-solid fa-check"></i> Perfeito para imprevistos e compromissos</li>
            <li><i class="fa-solid fa-check"></i> Mesmo carinho e cuidado dos mensalistas</li>
            <li><i class="fa-solid fa-check"></i> Agendamento rápido pelo WhatsApp</li>
          </ul>

          <a href="#" class="btn-plan" style="background: var(--orange-warm);" data-zap="Olá! Gostaria de agendar uma diária avulsa ou o Hotelzinho no Cantinho Kids ES."><i class="fa-brands fa-whatsapp"></i> Agendar diária</a>
        </article>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section class="section-faq" id="faq">
    <div class="container">
      <div class="section-title-wrap reveal">
        <span class="section-tag">Dúvidas comuns</span>
        <h2 class="section-title">Perguntas <span>Frequentes</span></h2>
      </div>

      <div class="faq-wrap">
        <details class="faq-item reveal">
          <summary>Quais são os valores dos planos?</summary>
          <p>Mensalistas: R$ 400,00 (meio período), R$ 460,00 (integral) e R$ 600,00 no combo irmãos/dupla integral. Pacotes semanais: R$ 180,00 (1 semana) e R$ 280,00 (2 semanas). Avulso: R$ 45,00 (meio dia), R$ 70,00 (dia completo) e Hotelzinho R$ 100,00.</p>
        </details>

        <details class="faq-item reveal">
          <summary>Vocês aceitam diárias avulsas?</summary>
          <p>Sim! A diária avulsa (meio dia ou dia completo) e o Hotelzinho são ótimos para imprevistos, compromissos ou para quem precisa de apoio em dias específicos. Consulte a disponibilidade com antecedência pelo WhatsApp.</p>
        </details>

        <details class="faq-item reveal">
          <summary>Como funciona a comunicação com os pais?</summary>
          <p>Mantemos contato próximo direto pelo WhatsApp com fotos, atualizações e informações sobre a rotina de alimentação e brincadeiras do seu pequeno durante o dia.</p>
        </details>

        <details class="faq-item reveal">
          <summary>Como agendar uma visita para conhecer o local?</summary>
          <p>Basta clicar em qualquer botão do WhatsApp nesta página e nos enviar uma mensagem. Ficaremos felizes em receber sua família!</p>
        </details>
      </div>
    </div>
  </section>

  <!-- CTA -->
  <section class="section-cta">
    <div class="container">
      <div class="cta-box reveal">
        <h2>Venha conhecer o Cantinho Kids ES</h2>
        <p>Agende uma visita e venha conversar com a gente sem compromisso. Teremos o maior prazer em acolher a sua família!</p>
        <div class="cta-actions">
          <a href="#" class="btn-zap-lg" data-zap="Olá! Vim pelo site e gostaria de mais informações sobre o Cantinho Kids ES."><i class="fa-brands fa-whatsapp"></i> Falar no WhatsApp</a>
          <span class="cta-phone"><i class="fa-solid fa-phone"></i> (19) 99022-7873</span>
          <a class="cta-phone" href="mailto:cantinhokidses@gmail.com"><i class="fa-solid fa-envelope"></i> cantinhokidses@gmail.com</a>
        </div>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <div class="container">
      <div class="footer-grid">
        <div>
          <h4>Cantinho Kids ES</h4>
          <p>Cuidado, recreação e acolhimento para o desenvolvimento saudável das crianças em Limeira - SP.</p>
        </div>
        <div>
          <h4>Navegação</h4>
          <ul>
            <li><a href="#sobre">Quem somos</a></li>
            <li><a href="#historia">Nossa História</a></li>
            <li><a href="#planos">Planos & Preços</a></li>
            <li><a href="#faq">Dúvidas Frequentes</a></li>
          </ul>
        </div>
        <div>
          <h4>Contato</h4>
          <ul>
            <li><a href="#" data-zap="Olá! Vim pelo site do Cantinho Kids ES."><i class="fa-brands fa-whatsapp"></i> (19) 99022-7873</a></li>
            <li><a href="mailto:cantinhokidses@gmail.com"><i class="fa-solid fa-envelope"></i> cantinhokidses@gmail.com</a></li>
            <li><i class="fa-solid fa-location-dot"></i> Limeira - SP</li>
          </ul>
        </div>
      </div>
      <div class="footer-bottom">
        <p>&copy; Cantinho Kids ES. Todos os direitos reservados. Limeira - SP.</p>
      </div>
    </div>
  </footer>

  <!-- BOTÃO FLUTUANTE DO WHATSAPP -->
  <a href="#" class="zap-float" data-zap="Olá! Vim pelo site e gostaria de tirar algumas dúvidas." aria-label="Falar no WhatsApp">
    <i class="fa-brands fa-whatsapp"></i>
  </a>

  <!-- SCRIPT -->
  <script>
    // Configuração oficial do número de WhatsApp
    const WHATSAPP_NUMBER = '5519990227873';

    // Aplica o link dinâmico em todos os botões com data-zap
    document.querySelectorAll('[data-zap]').forEach((el) => {
      const text = encodeURIComponent(el.dataset.zap);
      el.href = `https://wa.me/${WHATSAPP_NUMBER}?text=${text}`;
      el.target = '_blank';
      el.rel = 'noopener noreferrer';
    });

    // Animação de entrada suave (IntersectionObserver)
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('active');
        }
      });
    }, { threshold: 0.1 });

    document.querySelectorAll('.reveal').forEach((el) => {
      observer.observe(el);
    });
  </script>
</body>
</html>
