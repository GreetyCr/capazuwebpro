
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
      background: #f5f7fa;
    }
    header {
      background: linear-gradient(90deg, #004080, #0066cc);
      color: white;
      padding: 20px;
      text-align: center;
    }
    header img {
      width: 120px;
      margin-bottom: 10px;
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
      font-weight: bold;
    }
    nav a.active {
      border-bottom: 3px solid yellow;
    }
    .container {
      width: 90%;
      max-width: 1100px;
      margin: auto;
      padding: 20px;
    }
    .tab {
      display: none;
      animation: fadeIn 0.6s ease-in-out;
    }
    .tab.active {
      display: block;
    }
    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }
    /* Tarjetas de especialidades */
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      border-radius: 12px;
      padding: 20px;
      text-align: center;
      box-shadow: 0px 4px 8px rgba(0,0,0,0.2);
      transition: transform 0.3s;
    }
    .card:hover {
      transform: translateY(-5px);
    }
    .card h3 {
      margin: 10px 0;
      color: #004080;
    }
    .valores ul {
      columns: 2;
      padding-left: 20px;
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
    <img src="2cc6eebb-9753-492f-80d8-c3ae6cb8e914.png" alt="Escudo del colegio">
    <h1>CTP Ing. Carlos Pascua Zúñiga</h1>
    <p>Formando líderes con valores y conocimientos</p>
  </header>

  <nav>
    <a id="tablink-presentacion" class="active">Presentación</a>
    <a id="tablink-mision">Misión y Visión</a>
    <a id="tablink-especialidades">Especialidades</a>
    <a id="tablink-normativas">Normativas</a>
    <a id="tablink-galeria">Galería</a>
    <a id="tablink-contacto">Contacto</a>
  </nav>

  <div class="container">
    <!-- Presentación -->
    <section id="tab-presentacion" class="tab active">
      <h2>PRESENTACIÓN</h2>
      <p>
        El Consejo de Profesores del Colegio Técnico Profesional Ing. Carlos Pascua Zúñiga, establece y aprueba esta Normativa Interna, en la cual se consignan las peculiaridades propias de nuestro quehacer educativo.
      </p>
      <p>
        La persona representante legal de la persona estudiante que elige este liceo para matricular a sus hijos, hijas o encargados se ven en el compromiso adquirido, ineludible, e irrenunciable, de respetar y hacer cumplir todos los artículos e incisos de esta Normativa tanto en lo que a ellos les compete, como lo que corresponda por obligación a sus tutelados.
      </p>
      <p>
        Así mismo, todo el personal docente, docente administrativo y administrativo tendrá la misma responsabilidad, es decir están obligados a respetar y cumplir todos los términos de esta normativa.
      </p>
    </section>

    <!-- Misión y Visión -->
    <section id="tab-mision" class="tab">
      <h2>Misión</h2>
      <p>
        El Colegio Técnico Profesional Ing. Carlos Pascua Zúñiga es una institución educativa académica pública que contribuye a la formación y el desarrollo moral, espiritual, intelectual, cultural, social y laboral de las personas estudiantes, en un espacio de responsabilidad ambiental e inclusión de la diversidad.
      </p>
      <h2>Visión</h2>
      <p>
        El Colegio Técnico Profesional Ing. Carlos Pascua Zúñiga, como institución educativa académica pública comprometida e inclusiva, tiene como meta cultural la formación integral y el desarrollo moral, espiritual, intelectual, cultural, social y físico de las personas estudiantes, formando ciudadanos críticos, comprometidos con el país y profesionalmente exitosos.
      </p>
      <div class="valores">
        <h3>Valores del Colegio</h3>
        <ul>
          <li><b>Formativos:</b> Disciplina, compromiso, orden, responsabilidad, puntualidad, esfuerzo y constancia.</li>
          <li><b>Morales:</b> Honor, sinceridad, honestidad, verdad y respeto.</li>
          <li><b>Espirituales:</b> Justicia, amor, perdón y fe.</li>
          <li><b>Sociales:</b> Solidaridad, cooperación, tolerancia, cortesía, equidad, igualdad, convivencia e inclusión.</li>
          <li><b>Ambientales:</b> Protección, reciclaje, equilibrio y uso racional de los recursos naturales.</li>
        </ul>
      </div>
    </section>

    <!-- Especialidades -->
    <section id="tab-especialidades" class="tab">
      <h2>Especialidades</h2>
      <div class="grid">
        <div class="card">
          <h3>💻 Desarrollo Web</h3>
          <p>Formación en HTML, CSS, JavaScript, bases de datos y programación backend y frontend.</p>
        </div>
        <div class="card">
          <h3>🏦 Banca y Finanzas</h3>
          <p>Operaciones bancarias, gestión financiera y atención al cliente.</p>
        </div>
        <div class="card">
          <h3>📊 Contabilidad</h3>
          <p>Contabilidad general, costos, auditoría y elaboración de informes financieros.</p>
        </div>
        <div class="card">
          <h3>📋 Gestión de Calidad</h3>
          <p>Administración empresarial, recursos humanos y gestión organizacional.</p>
        </div>
        <div class="card">
          <h3>🏗️ Construcción Civil</h3>
          <p>Diseño, cálculos estructurales y ejecución de proyectos de obras civiles.</p>
        </div>
        <div class="card">
          <h3>🖊️ Dibujo Técnico</h3>
          <p>Elaboración de planos, uso de software CAD y representación gráfica.</p>
        </div>
      </div>
    </section>

    <!-- Normativas -->
    <section id="tab-normativas" class="tab">
      <h2>Normativas Generales</h2>
      <ul>
        <li>Respeto mutuo entre estudiantes, docentes y personal administrativo.</li>
        <li>Uso obligatorio del uniforme completo durante el horario lectivo.</li>
        <li>Prohibido el uso de dispositivos electrónicos en clases sin autorización.</li>
        <li>Cumplimiento de horarios de entrada y salida.</li>
        <li>Fomentar la responsabilidad y el trabajo en equipo.</li>
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
        Teléfono: (2237 2710 / 2238 1982) <br>
        Email: (lic.ingcarlospascua@mep.go.cr)
        Facebook: (Comunicados: Capazu)
      </p>
    </section>
  </div>

  <footer>
    <p>&copy; 2025 CTP Ing. Carlos Pascua Zúñiga | Sitio prototipo</p>
  </footer>

  <script>
    // Manejo de pestañas
    const tabs = ["presentacion","mision","especialidades","normativas","galeria","contacto"];
    tabs.forEach(name => {
      document.getElementById("tablink-" + name).addEventListener("click", () => {
        tabs.forEach(n => {
          document.getElementById("tablink-" + n).classList.remove("active");
          document.getElementById("tab-" + n).classList.remove("active");
        });
        document.getElementById("tablink-" + name).classList.add("active");
        document.getElementById("tab-" + name).classList.add("active"); 
      });
    });
  </script>
</body>
</html>
