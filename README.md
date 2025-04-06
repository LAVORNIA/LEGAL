<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lavornia - Asesoramiento Legal</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f0fdfb;
      color: #1a3e3e;
    }
    header {
      background-color: #a8dadc;
      padding: 2rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    header p {
      font-size: 1.2rem;
      margin-top: 0.5rem;
    }
    section {
      max-width: 800px;
      margin: 2rem auto;
      padding: 1rem;
    }
    .services, .about, .contact {
      margin-bottom: 2rem;
    }
    h2 {
      border-bottom: 2px solid #457b9d;
      padding-bottom: 0.5rem;
      margin-bottom: 1rem;
    }
    form {
      display: flex;
      flex-direction: column;
    }
    input, textarea, select {
      padding: 0.75rem;
      margin-bottom: 1rem;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 1rem;
    }
    button {
      background-color: #457b9d;
      color: white;
      padding: 0.75rem;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-size: 1rem;
    }
    button:hover {
      background-color: #1d3557;
    }
    footer {
      background-color: #a8dadc;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Lavornia</h1>
    <p>Asesoramiento legal personalizado</p>
  </header>

  <section class="services">
    <h2>Servicios</h2>
    <p>Seleccioná la materia legal que deseás tratar:</p>
    <select>
      <option value="civil">Derecho Civil</option>
      <option value="penal">Derecho Penal</option>
      <option value="internacional">Derecho Internacional</option>
      <option value="ambiental">Derecho Ambiental</option>
      <option value="laboral">Derecho Laboral</option>
      <option value="comercial">Derecho Comercial</option>
    </select>
    <ul>
      <li>Consultas legales generales</li>
      <li>Redacción y revisión de contratos</li>
      <li>Asesoramiento personalizado según la materia</li>
      <li>Defensa jurídica y representación</li>
    </ul>
  </section>

  <section class="about">
    <h2>Sobre mí</h2>
    <p>Soy Nicolás Lavornia, abogado con experiencia en brindar soluciones legales claras, personalizadas y efectivas. Mi enfoque está en construir relaciones de confianza con cada cliente.</p>
  </section>

  <section class="contact">
    <h2>Contacto</h2>
    <form action="mailto:nicolavornia@gmail.com" method="post" enctype="text/plain">
      <input type="text" name="nombre" placeholder="Tu nombre" required>
      <input type="email" name="email" placeholder="Tu email" required>
      <textarea name="mensaje" rows="5" placeholder="Tu mensaje" required></textarea>
      <button type="submit">Enviar mensaje</button>
    </form>
  </section>

  <footer>
    &copy; 2025 Lavornia. Todos los derechos reservados.
  </footer>
</body>
</html>
