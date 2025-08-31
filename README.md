<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>OHASHI BEE - Resgate e Polinização</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #fffbea;
      color: #222;
    }
    header {
      background: #000;
      color: gold;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      margin: 0;
      font-size: 1.5rem;
    }
    nav a {
      color: white;
      margin-left: 1rem;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      color: gold;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1503919545880-bbad939e9335') center/cover no-repeat;
      color: white;
      text-align: center;
      padding: 6rem 1rem;
    }
    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }
    .btn-whatsapp {
      background: #25d366;
      color: white;
      padding: 1rem 2rem;
      border-radius: 50px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 3rem 2rem;
      max-width: 1000px;
      margin: auto;
    }
    section h2 {
      color: goldenrod;
      margin-bottom: 1rem;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }
    .service {
      background: #fff;
      padding: 1rem;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    footer {
      background: #000;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
    footer a {
      color: #25d366;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>OHASHI BEE</h1>
    <nav>
      <a href="#sobre">Quem Somos</a>
      <a href="#servicos">Serviços</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Protegendo as abelhas e preservando o futuro</h2>
    <a class="btn-whatsapp" href="https://wa.me/5531971449655" target="_blank">📲 Falar com Robson</a>
  </section>

  <section id="sobre">
    <h2>Quem Somos</h2>
    <p>A OHASHI BEE é especializada em <strong>resgate de enxames de abelhas Apis mellifera</strong>, garantindo a segurança da população e a preservação das abelhas. Nosso compromisso é proteger esses polinizadores essenciais e destiná-los a apiários controlados, contribuindo para a biodiversidade e para a agricultura sustentável.</p>
  </section>

  <section id="servicos">
    <h2>Serviços</h2>
    <div class="services">
      <div class="service">
        <h3>🐝 Resgate de Enxames</h3>
        <p>Remoção segura de enxames em áreas urbanas e rurais, sempre priorizando o bem-estar das abelhas.</p>
      </div>
      <div class="service">
        <h3>🍯 Instalação em Apiário</h3>
        <p>As colônias resgatadas são transferidas para colmeias adequadas, onde recebem manejo apícola profissional.</p>
      </div>
      <div class="service">
        <h3>🌱 Polinização Agrícola</h3>
        <p>Locação de colmeias para aumento da produtividade agrícola através da polinização natural.</p>
      </div>
      <div class="service">
        <h3>📚 Educação Ambiental</h3>
        <p>Palestras e ações educativas para escolas, empresas e comunidades sobre a importância das abelhas.</p>
      </div>
    </div>
  </section>

  <section id="contato">
    <h2>Contato</h2>
    <p>Entre em contato pelo WhatsApp e fale diretamente com Robson.</p>
    <p><a class="btn-whatsapp" href="https://wa.me/5531971449655" target="_blank">📲 WhatsApp: (31) 97144-9655</a></p>
    <p>Email: contato@ohashibee.com.br</p>
  </section>

  <footer>
    <p>© 2025 OHASHI BEE – Resgate e Polinização | Desenvolvido com ❤️</p>
  </footer>
</body>
</html>
