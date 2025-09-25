# Capazu-webb
<html lang="es">
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CTP Ing. Carlos Pascua Zúñiga</title>
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
      cursor: pointer;
    }
    nav a.active {
      font-weight: bold;
      text-decoration: underline;
    }
    .container {
      width: 90%;
      max-width: 1000px;
      margin: auto;
      padding: 20px;
    }
    .tab {
      display: none;
    }
    .tab.active {
      display: block;
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
    <h1>CTP Ing. Carlos Pascua Zúñiga</h1>
    <p>Formando líderes con valores y conocimientos</p>
  </header>

  <nav>
    <a id="tablink-especialidades" class="active">Especialidades</a>
    <a id="tablink-historia">Historia</a>
    <a id="tablink-normativas">Normativas</a>
    <a id="tablink-galeria">Galería</a>
    <a id="tablink-contacto">Contacto</a>
  </nav>

  <div class="container">
    <!-- Especialidades -->
    <section id="tab-especialidades" class="tab active">
      <h2>Especialidades disponibles</h2>
      <ul>
        <li>💻 Desarrollo Web — aprendizaje de tecnologías como HTML, CSS, JavaScript, backend y frontend.</li>
        <li>🏦 Banca y Finanzas — formación en operaciones bancarias, gestión financiera y atención al cliente.</li>
        <li>📊 Contabilidad — aprendizaje de contabilidad general, costos, auditoría e informes financieros.</li>
        <li>📋 Gestión Administrativa — administración empresarial, recursos humanos, organización.</li>
        <li>🏗️ Construcción Civil — diseño, cálculos estructurales, obras civiles y mantenimiento.</li>
        <li>🖊️ Dibujo Técnico — representación gráfica, planos, herramientas CAD.</li>
      </ul>
      <p>Estas especialidades buscan preparar al estudiante para el mundo laboral, combinando conocimientos teóricos con práctica técnica.</p>
    </section>

    <!-- Historia -->
    <section id="tab-historia" class="tab">
      <h2>Historia</h2>
      <p>
        El CTP Ing. Carlos Pascua Zúñiga inició su actividad educativa en 1967 bajo la dirección administrativa del señor José Joaquín Trejos Fernández. :contentReference[oaicite:4]{index=4}  
        A lo largo de los años, ha evolucionado equipando instalaciones modernas, ampliando sus especialidades y adaptándose a las necesidades educativas y técnicas de la región. :contentReference[oaicite:5]{index=5}  
        Actualmente celebra más de 50 años de servicio educativo. :contentReference[oaicite:6]{index=6}  
      </p>
    </section>

    <!-- Normativas -->
    <section id="tab-normativas" class="tab">
      <h2>Normativas del Colegio</h2>
      <ul>
        <li>Respeto mutuo entre estudiantes, docentes y personal administrativo.</li>
        <li>Uso obligatorio del uniforme completo durante el horario lectivo.</li>
        <li>Prohibido el uso de dispositivos electrónicos en clases sin autorización.</li>
        <li>Cumplimiento de horarios de entrada y salida.</li>
        <li>Fomentar la responsabilidad y el trabajo en equipo.</li>
        <!-- Aquí puedes agregar normas específicas del colegio si las obtienes -->
      </ul>
    </section>

    <!-- Galería -->
    <section id="tab-galeria" class="tab">
      <h2>Galería</h2>
      <div class="imagenes">
        <img src="https://via.placeholder.com/400x250" alt="Foto del colegio">
        <img src="https://via.placeholder.com/400x250" alt="Aulas del colegio">
        <img src="https://via.placeholder.com/400x250" alt="Áreas verdes del colegio">
      </div>
    </section>

    <!-- Contacto -->
    <section id="tab-contacto" class="tab">
      <h2>Contacto</h2>
      <p>
        Dirección: Avenida 27, Santiago de San Rafael, Heredia, Costa Rica <br>
        Teléfono: (pendiente de confirmar) <br>
        Email: (pendiente de confirmar)
      </p>
    </section>
  </div>

  <footer>
    <p>&copy; 2025 CTP Ing. Carlos Pascua Zúñiga | Sitio prototipo</p>
  </footer>

  <script>
    // Manejo de pestañas
    const tabs = ["especialidades","historia","normativas","galeria","contacto"];
    tabs.forEach(name => {
      document.getElementById("tablink-" + name).addEventListener("click", () => {
        // desactivar todos los enlaces
        tabs.forEach(n => {
          document.getElementById("tablink-" + n).classList.remove("active");
          document.getElementById("tab-" + n).classList.remove("active");
        });
        // activar el actual
        document.getElementById("tablink-" + name).classList.add("active");
        document.getElementById("tab-" + name).classList.add("active");
      });
    });
  </script>
</body>
</html>

