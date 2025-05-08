<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Tienda de Ropa Deportiva</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #222;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .productos {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
    }
    .producto {
      background-color: white;
      border: 1px solid #ddd;
      border-radius: 5px;
      margin: 15px;
      width: 250px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
      padding: 15px;
    }
    .producto img {
      width: 100%;
      height: auto;
      border-radius: 5px;
    }
    .precio {
      font-size: 1.2em;
      color: #27ae60;
      margin-top: 10px;
    }
    footer {
      background-color: #222;
      color: white;
      text-align: center;
      padding: 20px;
    }
    .contacto input, .contacto textarea {
      width: 90%;
      padding: 10px;
      margin: 10px 0;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    .contacto {
      background: white;
      padding: 20px;
      margin: 20px auto;
      max-width: 600px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
  </style>
</head>
<body>

<header>
  <h1>Tienda SportFit</h1>
  <p>¡La mejor ropa deportiva para tu estilo de vida activo!</p>
</header>

<section class="productos">
  <div class="producto">
    <img src="https://via.placeholder.com/250x250?text=Camiseta+Deportiva" alt="Camiseta Deportiva">
    <h3>Camiseta Running</h3>
    <p class="precio">$25.00</p>
  </div>

  <div class="producto">
    <img src="https://via.placeholder.com/250x250?text=Leggings" alt="Leggings Deportivos">
    <h3>Leggings Yoga</h3>
    <p class="precio">$35.00</p>
  </div>

  <div class="producto">
    <img src="https://via.placeholder.com/250x250?text=Shorts" alt="Shorts Deportivos">
    <h3>Shorts de Entrenamiento</h3>
    <p class="precio">$20.00</p>
  </div>
</section>

<section class="contacto">
  <h2>Contáctanos</h2>
  <form>
    <input type="text" name="nombre" placeholder="Tu nombre" required><br>
    <input type="email" name="email" placeholder="Tu correo electrónico" required><br>
    <textarea name="mensaje" rows="5" placeholder="Tu mensaje"></textarea><br>
    <input type="submit" value="Enviar">
  </form>
</section>

<footer>
  <p>&copy; 2025 Tienda SportFit - Todos los derechos reservados.</p>
</footer>

</body>
</html>
