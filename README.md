# jhoandersontattoo
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jhoanderson Tattoo</title>
  <style>
    body {
      margin: 0;
      background-color: #0d0d0d;
      color: #f8f8f8;
      font-family: 'Arial', sans-serif;
    }
    header {
      background-color: #111;
      padding: 2rem;
      text-align: center;
      border-bottom: 2px solid #ffd700;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
      color: #ffd700;
    }
    .tattoo-quote-section {
      display: flex;
      align-items: center;
      gap: 2rem;
      padding: 2rem;
    }
    .tattoo-quote-section .image {
      flex: 1;
    }
    .tattoo-quote-section .image img {
      width: 100%;
      border-radius: 1rem;
      box-shadow: 0 0 20px rgba(255, 215, 0, 0.3);
    }
    .tattoo-quote-section .text {
      flex: 1;
    }
    .tattoo-quote-section .text h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
      color: #ffd700;
    }
    .tattoo-quote-section .text p,
    .tattoo-quote-section .text ul {
      font-size: 1.1rem;
      line-height: 1.5;
    }
    .tattoo-quote-section .text ul {
      list-style: none;
      padding: 0;
      margin-bottom: 1rem;
    }
    .tattoo-quote-section .text a {
      display: inline-block;
      padding: 0.75rem 1.5rem;
      background-color: #ffd700;
      color: #111;
      border-radius: 0.5rem;
      text-decoration: none;
      font-weight: bold;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background-color: #111;
      border-top: 1px solid #333;
      color: #888;
    }
    .social-links {
      margin-top: 1rem;
    }
    .social-links a {
      margin: 0 0.5rem;
      color: #ffd700;
      text-decoration: none;
      font-weight: bold;
    }
    .floating-buttons {
      position: fixed;
      bottom: 20px;
      right: 20px;
      display: flex;
      flex-direction: column;
      gap: 10px;
      z-index: 1000;
    }
    .floating-buttons a {
      background-color: #ffd700;
      color: #111;
      padding: 0.75rem;
      border-radius: 50%;
      text-align: center;
      font-size: 1.2rem;
      width: 50px;
      height: 50px;
      line-height: 1.5;
      text-decoration: none;
      box-shadow: 0 0 10px rgba(255, 215, 0, 0.6);
      transition: transform 0.3s ease;
    }
    .floating-buttons a:hover {
      transform: scale(1.1);
    }
    .tattoo-machine {
      position: fixed;
      bottom: 20px;
      left: 20px;
      width: 80px;
      height: 80px;
      background-image: url('https://cdn-icons-png.flaticon.com/512/4042/4042731.png');
      background-size: contain;
      background-repeat: no-repeat;
      animation: rotateTattooMachine 2s linear infinite;
    }
    @keyframes rotateTattooMachine {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }
  </style>
</head>
<body>
  <header>
    <h1>Jhoanderson Tattoo</h1>
    <p>Arte que deja huella</p>
  </header>

  <section class="tattoo-quote-section">
    <div class="image">
      <img src="/mnt/data/A_digital_painting_in_a_dark_fantasy_tattoo_art_st.png" alt="Jhoanderson Tattoo Logo">
    </div>
    <div class="text">
      <h2>Cotiza Tu Tatuaje</h2>
      <p>
        ¡Haz realidad tu idea con <strong>Jhoanderson Tattoo</strong>! Rellena el formulario con tu diseño deseado, tamaño aproximado,
        zona del cuerpo y estilo preferido. Te responderemos con una cotización personalizada lo antes posible.
      </p>
      <ul>
        <li>📍 <strong>Ubicación:</strong> Venezuela</li>
        <li>🖌️ <strong>Especialidad:</strong> Tatuajes personalizados de alto nivel artístico</li>
      </ul>
      <a href="#cotizar">Solicitar Cotización</a>
      <div class="social-links">
        <a href="https://wa.me/1234567890" target="_blank">📱 WhatsApp</a>
        <a href="https://instagram.com/jhoandersontattoo" target="_blank">📸 Instagram</a>
      </div>
    </div>
  </section>

  <div class="floating-buttons">
    <a href="https://wa.me/1234567890" target="_blank" title="WhatsApp">💬</a>
    <a href="https://instagram.com/jhoandersontattoo" target="_blank" title="Instagram">📷</a>
  </div>

  <div class="tattoo-machine" title="Máquina de tatuar animada"></div>

  <footer>
    &copy; 2025 Jhoanderson Tattoo. Todos los derechos reservados.
  </footer>
</body>
</html>
