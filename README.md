<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Romeo Santos | El Rey de la Bachata</title>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Figtree:wght@400;600;700&family=Noto+Serif:wght@700&display=swap">
  <link rel="stylesheet" href="estilos.css">
</head>
<body>

<!-- A. ENCABEZADO -->
<div id="inicio" class="encabezado">
  <div class="marca">
    <img class="logo" src="imagenes/artista.jpg" alt="Romeo Santos">
    <h1>ROMEO SANTOS</h1>
  </div>
  <div class="menu">
    <a href="#artista">Artista</a>
    <a href="#galeria">Galería</a>
    <a href="#videos">Videos</a>
    <a href="#catalogo">Canciones</a>
    <a href="#letras">Letras</a>
    <a href="#albumes">Álbumes</a>
    <a href="#conciertos">Conciertos</a>
  </div>
</div>

<!-- B. PRESENTACIÓN -->
<div id="artista" class="seccion presentacion">
  <div class="arco"><img src="imagenes/artista.jpg" alt="Fotografía de Romeo Santos"></div>
  <div class="presentacion-texto">
    <h2>Anthony «Romeo» Santos</h2>
    <p>Anthony Santos, conocido como Romeo Santos, nació el 21 de julio de 1981 en el Bronx, Nueva York, de padre dominicano y madre puertorriqueña. Fue la voz principal del grupo Aventura, que llevó la bachata a todo el mundo. En 2011 empezó su carrera como solista y desde entonces es conocido como el Rey de la Bachata.</p>
    <div class="dato coral"><b>País de origen:</b> Estados Unidos (raíces dominicanas y puertorriqueñas)</div>
    <div class="dato verde"><b>Género musical:</b> Bachata</div>
    <div class="dato amarillo"><b>Inicio de carrera:</b> 1994 con Aventura; solista desde 2011</div>
  </div>
</div>

<!-- C. GALERÍA -->
<div id="galeria" class="seccion">
  <h2>Galería</h2>
  <div class="galeria">
    <div class="polaroid"><img src="imagenes/foto1.jpg" alt="Romeo Santos en concierto"></div>
    <div class="polaroid"><img src="imagenes/foto2.jpg" alt="Romeo Santos en el escenario"></div>
    <div class="polaroid"><img src="imagenes/foto3.jpg" alt="Romeo Santos con su público"></div>
    <div class="polaroid"><img src="imagenes/foto4.jpg" alt="Retrato de Romeo Santos"></div>
  </div>
</div>

<!-- D. VIDEOS -->
<div id="videos" class="seccion">
  <h2>Videos musicales</h2>
  <div class="video-caja">
    <video controls preload="metadata" poster="imagenes/foto1.jpg">
      <source src="videos/video.mp4" type="video/mp4">
      Tu navegador no admite el elemento video.
    </video>
    <!-- Alternativa con YouTube (reemplaza ID_DEL_VIDEO):
    <iframe src="https://www.youtube.com/embed/ID_DEL_VIDEO" title="Video musical" allowfullscreen></iframe> -->
  </div>
</div>

<!-- E. CATÁLOGO -->
<div id="catalogo" class="seccion">
  <h2>Canciones</h2>
  <div class="catalogo">
    <div class="tarjeta" id="cancion1">
