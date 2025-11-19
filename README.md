 #<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Catálogo de Herramientas</title>
  <style>
    body { font-family: Arial, sans-serif; background-color: #013220; color: #c0c0c0; margin: 0; padding: 0; }
    header { text-align: center; padding: 20px; background-color: #025c3a; }
    nav a { margin: 0 15px; color: #c0c0c0; text-decoration: none; }
    .catalogo { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; padding: 20px; }
    .item { background: #024d33; border: 1px solid #c0c0c0; border-radius: 10px; padding: 10px; text-align: center; }
    .item img { max-width: 100%; border-radius: 10px; }
    footer { text-align: center; padding: 20px; background-color: #025c3a; }
    .seccion { padding: 20px; }
    .whatsapp { display: inline-block; background: #25d366; color: white; padding: 10px 20px; border-radius: 5px; text-decoration: none; }
  </style>
</head>
<body>
  <header>
    <h1>Catálogo de Herramientas</h1>
    <nav>
      <a href="#catalogo">Catálogo</a>
      <a href="#detalles">Detalles</a>
      <a href="#entregas">Entregas</a>
      <a href="#nosotros">Nosotros</a>
      <a class="whatsapp" href="https://wa.me/59100000000" target="_blank">Contactar por WhatsApp</a>
    </nav>
  </header>
  
  <section id="catalogo" class="catalogo">
    <div class="item">
      <img src="herramienta1.jpg" alt="Herramienta 1">
      <h3>Taladro Profesional</h3>
      <p>Precio: 250 Bs.</p>
    </div>
    <div class="item">
      <img src="herramienta2.jpg" alt="Herramienta 2">
      <h3>Llave Inglesa</h3>
      <p>Precio: 80 Bs.</p>
    </div>
    <div class="item">
      <img src="herramienta3.jpg" alt="Herramienta 3">
      <h3>Juego de Destornilladores</h3>
      <p>Precio: 120 Bs.</p>
    </div>
  </section>
  
  <section id="detalles" class="seccion">
    <h2>Detalles</h2>
    <p>Ofrecemos herramientas de alta calidad para profesionales y aficionados.</p>
  </section>

  <section id="entregas" class="seccion">
    <h2>Entregas</h2>
    <p>Realizamos entregas a toda la ciudad con tiempos de 24 a 48 horas.</p>
  </section>

  <section id="nosotros" class="seccion">
    <h2>Sobre Nosotros</h2>
    <p>Somos una empresa dedicada a proporcionar herramientas confiables y a precios accesibles.</p>
  </section>

  <footer>
    <p>© 2025 Catálogo de Herramientas</p>
  </footer>
</body>
</html>
