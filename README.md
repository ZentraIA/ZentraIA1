<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>ZentraIA – Automatización con IA</title>
  <style>
    /* Reset básico */
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: Arial, sans-serif; line-height: 1.6; color: #333; }

    /* Header */
    .header {
      background: #0a1f44;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    .header h1 { font-size: 2rem; }
    .header h1 span { color: #0055ff; }
    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      gap: 1.5rem;
      margin-top: 10px;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }

    /* Hero */
    .hero {
      padding: 60px 20px;
      text-align: center;
    }
    .hero h2 { color: #0a1f44; font-size: 1.8rem; margin-bottom: 10px; }
    .hero p { margin-bottom: 20px; }
    .cta {
      display: inline-block;
      background: #0055ff;
      color: #fff;
      padding: 10px 20px;
      border-radius: 4px;
      text-decoration: none;
      font-weight: bold;
    }

    /* Servicios */
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 40px 20px;
    }
    .service {
      border: 1px solid #ccc;
      border-radius: 8px;
      overflow: hidden;
      text-align: center;
      background: #fafafa;
    }
    .service img {
      width: 100%;
      height: auto;
      display: block;
    }
    .service h3 {
      margin: 15px 0 10px;
      color: #0a1f44;
    }
    .service p { padding: 0 15px 20px; }

    /* Sobre Nosotros */
    .about {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      align-items: center;
      padding: 40px 20px;
    }
    .about img {
      max-width: 400px;
      width: 100%;
      border-radius: 8px;
    }
    .about div { flex: 1; }
    .about h2 { margin-bottom: 15px; color: #0a1f44; }

    /* Contacto */
    .contact {
      background: #f4f4f4;
      padding: 40px 20px;
      text-align: center;
    }
    .contact a {
      color: #0055ff;
      text-decoration: none;
      font-weight: bold;
    }

    /* Footer */
    .footer {
      background: #0a1f44;
      color: #fff;
      text-align: center;
      padding: 15px 0;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header class="header">
    <h1>Zentra<span>IA</span></h1>
    <nav>
      <ul>
        <li><a href="#services">Servicios</a></li>
        <li><a href="#about">Sobre Nosotros</a></li>
        <li><a href="#contact">Contacto</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero -->
  <section class="hero">
    <h2>Automatiza tu negocio con Inteligencia Artificial</h2>
    <p>Transforma procesos, incrementa eficiencia y mejora la experiencia de tus clientes.</p>
    <a href="#contact" class="cta">Contáctanos</a>
  </section>

  <!-- Servicios -->
  <section id="services" class="services">
    <div class="service">
      <img src="https://source.unsplash.com/featured/?automation" alt="Automatización">
      <h3>Automatización de Negocios</h3>
      <p>Implementamos soluciones que optimizan tareas repetitivas y aumentan la productividad.</p>
    </div>
    <div class="service">
      <img src="https://source.unsplash.com/featured/?chatbot" alt="Chatbots de IA">
      <h3>Creación de Chatbots de IA</h3>
      <p>Desarrollamos asistentes conversacionales que mejoran la atención al cliente 24/7.</p>
    </div>
    <div class="service">
      <img src="https://source.unsplash.com/featured/?voice-assistant" alt="Asistentes de Voz">
      <h3>Asistentes de Voz con IA</h3>
      <p>Diseñamos asistentes de voz personalizados para interactuar de forma natural con tus usuarios.</p>
    </div>
  </section>

  <!-- Sobre Nosotros -->
  <section id="about" class="about">
    <img src="https://source.unsplash.com/featured/?artificial-intelligence" alt="Inteligencia Artificial">
    <div>
      <h2>Sobre Nosotros</h2>
      <p>En ZentraIA, somos apasionados por la innovación tecnológica. Nos especializamos en implementar inteligencia artificial para automatizar procesos de negocio, crear chatbots inteligentes y asistentes de voz que permiten a las empresas ofrecer experiencias únicas a sus clientes. Nuestro enfoque se basa en comprender las necesidades de cada cliente y diseñar soluciones a medida que mejoren la eficiencia y reduzcan costos.</p>
    </div>
  </section>

  <!-- Contacto -->
  <section id="contact" class="contact">
    <h2>Contacto</h2>
    <p>Escríbenos a <a href="mailto:zentraia24@gmail.com">zentraia24@gmail.com</a> y arrancamos tu proyecto de automatización.</p>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <p>&copy; 2025 ZentraIA. Todos los derechos reservados.</p>
  </footer>

</body>
</html>
