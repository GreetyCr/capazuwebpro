# Capazu-webb
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Colegio CTP Ing. Carlos Pascua Zúñiga</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }
    header {
      background: #004080;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background: #0066cc;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .container {
      width: 90%;
      max-width: 1000px;
      margin: auto;
      padding: 20px;
    }
    .imagenes {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
    }
    .imagenes img {
      width: 100%;
      border-radius: 10px;
      box-shadow: 0px 2px 6px rgba(0,0,0,0.2);
    }
    footer {
      background: #004080;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Colegio Técnico Profesional Ing. Carlos Pascua Zúñiga</h1>
    <p>Formando líderes con valores y conocimientos</p>
  </header>

  <nav>
    <a href="#historia">Historia</a>
    <a href="#normativas">Normativas</a>
    <a href="#galeria">Galería</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <div class="container">
    <section id="historia">
      <h2>Historia</h2>
      <p>
        El Colegio Técnico Profesional Ing. Carlos Pascua Zúñiga tiene como objetivo 
        brindar educación integral y técnica a los jóvenes, preparando a futuros 
        profesionales para los retos del mundo moderno.
      </p>
    </section>

    <section id="normativas">
      <h2>Normativas del Colegio</h2>
      <ul>
        <li>Respeto mutuo entre estudiantes, docentes y personal administrativo.</li>
        <li>Uso obligatorio del uniforme completo durante el horario lectivo.</li>
        <li>Prohibido el uso de dispositivos electrónicos en clases sin autorización.</li>
        <li>Cumplimiento de horarios de entrada y salida.</li>
        <li>Fomentar la responsabilidad y el trabajo en equipo.</li>
      </ul>
    </section>

    <section id="galeria">
      <h2>Galería</h2>
      <div class="imagenes">
        <!-- Reemplaza los enlaces de abajo por imágenes reales del colegio -->
        <img src="https://via.placeholder.com/400x250" alt="Foto del colegio">
        <img src="https://via.placeholder.com/400x250" alt="Aulas del colegio">
        <img src="https://via.placeholder.com/400x250" alt="Áreas verdes del colegio">
      </div>
    </section>

    <section id="contacto">
      <h2>Contacto</h2>
      <p>
        Dirección: [Pon la dirección aquí] <br>
        Teléfono: [Número de contacto] <br>
        Email: [Correo institucional]
      </p>
    </section>
  </div>

  <footer>
    <p>&copy; 2025 Colegio CTP Ing. Carlos Pascua Zúñiga | Sitio prototipo</p>
  </footer>
</body>
</html>
