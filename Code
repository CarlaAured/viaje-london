<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Viaje a London</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: sans-serif;
    }
    body {
      background: #f9f9f9;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: #111;
      color: #fff;
      padding: 1rem;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 1rem;
      background: #222;
      padding: 0.5rem;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      padding: 0.5rem 1rem;
      border-radius: 5px;
    }
    nav a:hover {
      background: #555;
    }
    section {
      padding: 2rem;
      display: none;
    }
    section.active {
      display: block;
    }
    iframe {
      width: 100%;
      height: 500px;
      border: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>Viaje a London</h1>
  </header>

  <nav>
    <a href="#" onclick="showTab('presentacion')">Presentación</a>
    <a href="#" onclick="showTab('mapa')">Mapa</a>
    <a href="#" onclick="showTab('outfits')">Outfits</a>
    <a href="#" onclick="showTab('gastos')">Gastos</a>
    <a href="#" onclick="showTab('fotos')">Fotos</a>
  </nav>

  <main>
    <section id="presentacion" class="active">
      <h2>Presentación</h2>
      <p>Bienvenidos al plan de viaje a Londres. Aquí encontrarás toda la información sobre nuestras actividades, planificación y mucho más.</p>
    </section>

    <section id="mapa">
      <h2>Mapa</h2>
      <!-- Sustituye la URL con tu enlace embebido de Google Maps -->
      <iframe src="https://www.google.com/maps/embed?..." allowfullscreen></iframe>
    </section>

    <section id="outfits">
      <h2>Outfits</h2>
      <p>Ideas de ropa para llevar según el clima y las actividades planeadas.</p>
      <!-- Puedes incluir imágenes o listas aquí -->
    </section>

    <section id="gastos">
      <h2>Gastos</h2>
      <!-- Sustituye la URL con tu enlace embebido de Google Sheets -->
      <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-.../pubhtml?widget=true&amp;headers=false"></iframe>
    </section>

    <section id="fotos">
      <h2>Fotos</h2>
      <p>Aquí se mostrará una galería o texto relacionado con las fotos del viaje.</p>
    </section>
  </main>

  <script>
    function showTab(id) {
      document.querySelectorAll('section').forEach(sec => sec.classList.remove('active'));
      document.getElementById(id).classList.add('active');
    }
  </script>
</body>
</html>
