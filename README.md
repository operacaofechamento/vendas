!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Operação Fechamento - Encontre seu imóvel ideal</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Poppins', sans-serif; }
    body { background: #f8f9fa; color: #222; }
    header { display: flex; justify-content: space-between; align-items: center; padding: 1.5rem 10%; background: #fff; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
    header h1 { font-size: 1.4rem; color: #007bff; }
    nav a { margin-left: 1.5rem; text-decoration: none; color: #333; font-weight: 500; }
    .hero { text-align: center; padding: 5rem 10%; background: url('https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=1600&q=80') center/cover no-repeat; color: #fff; position: relative; }
    .hero::before { content: ''; position: absolute; top: 0; left: 0; right: 0; bottom: 0; background: rgba(0,0,0,0.6); }
    .hero-content { position: relative; z-index: 1; max-width: 700px; margin: 0 auto; }
    .hero h2 { font-size: 2.4rem; margin-bottom: 1rem; }
    .hero p { font-size: 1.1rem; margin-bottom: 2rem; }
    .whatsapp-btn { background: #25D366; color: white; padding: 14px 30px; border-radius: 8px; text-decoration: none; font-weight: bold; transition: 0.3s; }
    .whatsapp-btn:hover { background: #1eb45f; }
    section { padding: 4rem 10%; text-align: center; }
    section h3 { font-size: 1.8rem; margin-bottom: 2rem; color: #007bff; }
    form { display: flex; flex-direction: column; max-width: 400px; margin: 0 auto; gap: 1rem; }
    input, button { padding: 12px; border-radius: 6px; border: 1px solid #ccc; font-size: 1rem; }
    button { background: #007bff; color: #fff; border: none; cursor: pointer; font-weight: 600; }
    button:hover { background: #0056b3; }
    footer { text-align: center; padding: 2rem; background: #fff; margin-top: 3rem; box-shadow: 0 -2px 5px rgba(0,0,0,0.05); }
    .socials a { margin: 0 10px; text-decoration: none; color: #007bff; font-weight: 500; }

    /* Botão flutuante WhatsApp */
    .whatsapp-float {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #25D366;
      color: white;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 28px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
      transition: 0.3s;
      z-index: 1000;
    }
    .whatsapp-float:hover { background-color: #1eb45f; transform: scale(1.1); }

    @media (max-width: 768px) {
      .hero h2 { font-size: 1.8rem; }
      header { flex-direction: column; }
    }
  </style>
</head>
<body>
  <header>
    <h1>Operação Fechamento</h1>
    <nav>
      <a href="#sobre">Sobre</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h2>Encontre o imóvel dos seus sonhos</h2>
      <p>Condições especiais direto com a construtora. Financiamento fácil e localização privilegiada.</p>
      <a href="https://wa.me/5521999999999" target="_blank" class="whatsapp-btn">💬 Fale com um corretor agora</a>
    </div>
  </section>

  <section id="sobre">
    <h3>Por que escolher a Operação Fechamento?</h3>
    <p>Equipe especializada em imóveis na planta, prontos e oportunidades exclusivas da Cury Construtora.</p>
  </section>

  <section id="contato">
    <h3>Cadastre-se e receba nossas melhores ofertas</h3>
    <form action="https://formspree.io/f/mkgwnyzy" method="POST">
      <input type="text" name="nome" placeholder="Seu nome" required>
      <input type="tel" name="telefone" placeholder="Seu WhatsApp" required>
      <input type="email" name="email" placeholder="Seu e-mail" required>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <p>© 2025 Operação Fechamento. Todos os direitos reservados.</p>
    <div class="socials">
      <a href="https://instagram.com/seuinsta" target="_blank">Instagram</a>
      <a href="https://facebook.com/seufb" target="_blank">Facebook</a>
      <a href="https://wa.me/5521999999999" target="_blank">WhatsApp</a>
    </div>
  </footer>

  <!-- Botão flutuante WhatsApp -->
  <a href="https://wa.me/5521999999999" class="whatsapp-float" target="_blank" title="Fale conosco no WhatsApp">💬</a>
</body>
</html>
