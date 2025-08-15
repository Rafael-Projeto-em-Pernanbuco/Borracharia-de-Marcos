<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Borracharia de Marcos - Exu-PE</title>
  <style>
    body {
      background-color: #000;
      color: #fff;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #013220; /* Verde escuro */
      padding: 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2em;
    }

    nav {
      text-align: center;
      margin-top: 10px;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
    }

    section {
      padding: 20px;
    }

    .services, .payment, .contact, .map {
      margin-bottom: 30px;
    }

    .chat-buttons a {
      display: inline-block;
      margin: 5px;
      padding: 10px 15px;
      background-color: #013220;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }

    form input, form button {
      padding: 10px;
      margin-top: 10px;
      width: 100%;
      max-width: 300px;
    }

    iframe {
      width: 100%;
      height: 300px;
      border: none;
    }
  </style>
</head>
<body>

  <header>
    <h1>Borracharia de Marcos</h1>
    <p>Centro - Exu, Pernambuco</p>
    <nav>
      <a href="https://dev.to/raphaelproject001" target="_blank">Dev.to</a>
      <a href="https://github.com" target="_blank">GitHub</a>
    </nav>
  </header>

  <!-- Google Tradutor -->
  <div id="google_translate_element" style="text-align:right; padding: 10px;"></div>
  <script type="text/javascript">
    function googleTranslateElementInit() {
      new google.translate.TranslateElement({ pageLanguage: 'pt' }, 'google_translate_element');
    }
  </script>
  <script src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>

  <section class="services">
    <h2>Serviços Oferecidos</h2>
    <ul>
      <li>Conserto de pneus: R$ 20,00</li>
      <li>Troca de pneus: R$ 15,00</li>
      <li>Balanceamento: R$ 30,00</li>
      <li>Alinhamento: R$ 50,00</li>
      <li>Serviços de mecânica básica: a partir de R$ 40,00</li>
    </ul>
  </section>

  <section class="payment">
    <h2>Formas de Pagamento</h2>
    <ul>
      <li>Dinheiro</li>
      <li>Cartão de Débito / Crédito</li>
      <li>PIX</li>
    </ul>
  </section>

  <section class="contact">
    <h2>Entre em Contato</h2>
    <div class="chat-buttons">
      <a href="https://wa.me/5587999999999" target="_blank">WhatsApp</a>
      <a href="https://m.me/seufacebook" target="_blank">Facebook</a>
      <a href="https://www.instagram.com/seuinstagram" target="_blank">Instagram</a>
      <a href="https://twitter.com/seutwitter" target="_blank">Twitter</a>
      <a href="mailto:contato@borrachariaexu.com">Chat Online</a> <!-- Simulado via e-mail -->
    </div>
  </section>

  <section class="map">
    <h2>Localização</h2>
    <iframe
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3949.767015907268!2d-39.71999388521974!3d-7.51422019455715!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x7a4f05b3b0b6c49%3A0x3f6c55a1b4eb4a8f!2sExu%2C%20PE!5e0!3m2!1spt-BR!2sbr!4v1621966741344!5m2!1spt-BR!2sbr"
      allowfullscreen=""
      loading="lazy">
    </iframe>
  </section>

  <section>
    <h2>Cadastro para Promoções e Novidades</h2>
    <form action="mailto:seuemail@borrachariaexu.com" method="post" enctype="text/plain">
      <input type="text" name="nome" placeholder="Seu nome" required><br>
      <input type="email" name="email" placeholder="Seu e-mail" required><br>
      <button type="submit">Cadastrar</button>
    </form>
  </section>

  <footer style="background-color:#013220; text-align:center; padding:15px;">
    <p>&copy; 2025 Borracharia de Marcos - Exu-PE. Todos os direitos reservados.</p>
  </footer>

</body>
</html>
