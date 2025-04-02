<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tactori - Transformamos la forma en que las empresas operan</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Inter', sans-serif;
      background-color: #f9f9f9;
      color: #333;
      text-align: center;
    }

    header {
      background-color: #fff;
      padding: 20px;
    }

    header img {
      max-width: 150px;
    }

    nav {
      margin-top: 10px;
    }

    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #333;
      font-weight: 600;
    }

    section {
      padding: 50px 20px;
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    h2 {
      font-size: 1.5rem;
      font-weight: 300;
      margin-bottom: 20px;
    }

    .services {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }

    .service {
      max-width: 300px;
      margin: 20px;
    }

    .service img {
      max-width: 100px;
      margin-bottom: 15px;
    }

    .contact-form {
      max-width: 600px;
      margin: 0 auto;
      text-align: left;
    }

    .contact-form label {
      display: block;
      margin-bottom: 5px;
      font-weight: 600;
    }

    .contact-form input,
    .contact-form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    .contact-form button {
      background-color: #333;
      color: #fff;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    footer {
      background-color: #333;
      color: #fff;
      padding: 20px;
      margin-top: 50px;
    }
  </style>
</head>
<body>

  <header>
    <img src="Tactori_Logo.png" alt="Logo de Tactori" />
    <nav>
      <a href="#quienes-somos">Quiénes Somos</a>
      <a href="#servicios">Servicios</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <section id="inicio">
    <h1>Transformamos la forma en que las empresas operan</h1>
    <h2>En Tactori, estamos comprometidos en impulsar la planificación de la demanda, forecasting, modelos de capacidad y consultoría para fábricas.</h2>
  </section>

  <section id="servicios">
    <h2>Nuestros Servicios</h2>
    <div class="services">
      <div class="service">
        <img src="icono_planificacion.png" alt="Planificación de la Demanda" />
        <h3>Planificación de la Demanda</h3>
        <p>Optimizamos la gestión de la demanda para mejorar la eficiencia y reducir costos.</p>
      </div>
      <div class="service">
        <img src="icono_forecasting.png" alt="Forecasting" />
        <h3>Forecasting</h3>
        <p>Proveemos pronósticos precisos para una mejor toma de decisiones estratégicas.</p>
      </div>
      <div class="service">
        <img src="icono_capacidad.png" alt="Modelos de Capacidad" />
        <h3>Modelos de Capacidad</h3>
        <p>Desarrollamos modelos que permiten una planificación efectiva de recursos y producción.</p>
      </div>
      <div class="service">
        <img src="icono_consultoria.png" alt="Consultoría para Fábricas" />
        <h3>Consultoría para Fábricas</h3>
        <p>Brindamos asesoramiento especializado para optimizar procesos industriales.</p>
      </div>
    </div>
  </section>

  <section id="contacto">
    <h2>Ponte en contacto</h2>
    <div class="contact-form">
      <form action="enviar_formulario.php" method="post">
        <label for="nombre">Nombre*</label>
        <input type="text" id="nombre" name="nombre" required />

        <label for="email">Correo Electrónico*</label>
        <input type="email" id="email" name="email" required />

        <label for="mensaje">Mensaje</label>
        <textarea id="mensaje" name="mensaje" rows="5"></textarea>

        <label>
          <input type="checkbox" name="acepto" required />
          Por la presente acepto que estos datos se almacenen y procesen con el fin de establecer contacto. Soy consciente de que puedo revocar mi consentimiento en cualquier momento*
        </label>

        <button type="submit">Enviar</button>
      </form>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Tactori. Todos los derechos reservados.</p>
  </footer>

</body>
</html>
