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
      <h3>Obsesión</h3>
      <audio controls preload="none" src="musica/cancion1.mp3"></audio>
      <div class="acciones"><a class="boton" href="musica/cancion1.mp3" download>Descargar MP3</a><a class="enlace" href="#letra1">Ver letra</a></div>
    </div>
    <div class="tarjeta" id="cancion2">
      <h3>Eres Mía</h3>
      <audio controls preload="none" src="musica/cancion2.mp3"></audio>
      <div class="acciones"><a class="boton" href="musica/cancion2.mp3" download>Descargar MP3</a><a class="enlace" href="#letra2">Ver letra</a></div>
    </div>
    <div class="tarjeta" id="cancion3">
      <h3>La Bella y la Bestia</h3>
      <audio controls preload="none" src="musica/cancion3.mp3"></audio>
      <div class="acciones"><a class="boton" href="musica/cancion3.mp3" download>Descargar MP3</a><a class="enlace" href="#letra3">Ver letra</a></div>
    </div>
    <div class="tarjeta" id="cancion4">
      <h3>Yo Quisiera Amarla</h3>
      <audio controls preload="none" src="musica/cancion4.mp3"></audio>
      <div class="acciones"><a class="boton" href="musica/cancion4.mp3" download>Descargar MP3</a><a class="enlace" href="#letra4">Ver letra</a></div>
    </div>
    <div class="tarjeta" id="cancion5">
      <h3>Yo También</h3>
      <audio controls preload="none" src="musica/cancion5.mp3"></audio>
      <div class="acciones"><a class="boton" href="musica/cancion5.mp3" download>Descargar MP3</a><a class="enlace" href="#letra5">Ver letra</a></div>
    </div>
  </div>
</div>

<!-- F. LETRAS -->
<div id="letras" class="seccion">
  <h2>Letras</h2>
  <div class="letras">
    <div class="letra" id="letra1">
      <h3>Obsesión</h3>
      <audio controls preload="none" src="musica/cancion1.mp3"></audio>
      <p>Pensarte se volvió mi costumbre,<br>tu nombre es la canción que repito.<br>Entre luces y sombras te busco<br>y en cada bachata te escribo.</p>
      <a class="volver" href="#catalogo">Volver al catálogo</a>
    </div>
    <div class="letra" id="letra2">
      <h3>Eres Mía</h3>
      <audio controls preload="none" src="musica/cancion2.mp3"></audio>
      <p>Cada verso que escribo te nombra,<br>cada acorde me lleva a tu voz.<br>Si el tiempo nos separa un momento,<br>mi canción te encuentra mejor.</p>
      <a class="volver" href="#catalogo">Volver al catálogo</a>
    </div>
    <div class="letra" id="letra3">
      <h3>La Bella y la Bestia</h3>
      <audio controls preload="none" src="musica/cancion3.mp3"></audio>
      <p>Ella es la luz que enciende mi cuarto,<br>yo soy el invierno que aprendió a sonreír.<br>Entre cuento y canción nos hallamos<br>y la historia empieza otra vez.</p>
      <a class="volver" href="#catalogo">Volver al catálogo</a>
    </div>
    <div class="letra" id="letra4">
      <h3>Yo Quisiera Amarla</h3>
      <audio controls preload="none" src="musica/cancion4.mp3"></audio>
      <p>Quisiera decirte lo que callo<br>sin romper la calma de tu mirada.<br>Hay verdades que pesan en el pecho<br>y se cantan despacio al final.</p>
      <a class="volver" href="#catalogo">Volver al catálogo</a>
    </div>
    <div class="letra" id="letra5">
      <h3>Yo También</h3>
      <audio controls preload="none" src="musica/cancion5.mp3"></audio>
      <p>Si tú sueñas con la misma estrella,<br>yo también la miro al anochecer.<br>Dos caminos que se cruzan lento<br>y una canción para volver.</p>
      <a class="volver" href="#catalogo">Volver al catálogo</a>
    </div>
  </div>
</div>

<!-- ÁLBUMES -->
<div id="albumes" class="seccion">
  <h2>Álbumes musicales</h2>
  <div class="albumes">
    <div class="album" style="background-image:url('imagenes/album1.jpg')"><span class="anio">2011</span><h3>Fórmula, Vol. 1</h3><p>Su primer álbum como solista.</p></div>
    <div class="album" style="background-image:url('imagenes/album2.jpg')"><span class="anio">2014</span><h3>Fórmula, Vol. 2</h3><p>Segunda entrega de la serie Fórmula.</p></div>
    <div class="album" style="background-image:url('imagenes/album3.jpg')"><span class="anio">2017</span><h3>Golden</h3><p>Álbum con colaboraciones de varios géneros.</p></div>
    <div class="album" style="background-image:url('imagenes/album4.jpg')"><span class="anio">2022</span><h3>Fórmula, Vol. 3</h3><p>Tercera entrega de la serie Fórmula.</p></div>
  </div>
</div>

<!-- CONCIERTOS -->
<div id="conciertos" class="seccion">
  <h2>Conciertos y presentaciones</h2>
  <div class="conciertos">
    <div class="concierto c-coral"><h3>Abril de 2026</h3><p>Inicio de la gira «Mejor Tarde Que Nunca» con Prince Royce, en Estados Unidos.</p></div>
    <div class="concierto c-verde"><h3>Julio de 2026</h3><p>Conciertos en estadios de Barcelona y Madrid, España.</p></div>
    <div class="concierto c-amarillo"><h3>11 y 12 de septiembre de 2026</h3><p>Lima, Perú, Estadio Nacional.</p></div>
    <div class="concierto c-azul"><h3>23 de noviembre de 2026</h3><p>Buenos Aires, Argentina.</p></div>
    <div class="concierto c-coral"><h3>Próximas fechas</h3><p>Se anunciarán en sus redes oficiales.</p></div>
  </div>
</div>

<!-- G. PIE DE PÁGINA -->
<div class="pie">
  <p><b>Estudiante:</b> Niurka Sarela León Briones</p>
  <p>Carrera: Sistemas de Información</p>
  <p>Asignatura: [escribe tu asignatura] · 2026</p>
  <p>Proyecto: Sitio web musical de Romeo Santos</p>
  <div class="redes">
    <a href="https://www.instagram.com/romeosantos/" target="_blank" rel="noopener">Instagram</a>
    <a href="https://www.youtube.com/@RomeoSantos" target="_blank" rel="noopener">YouTube</a>
    <a href="https://www.facebook.com/RomeoSantos/" target="_blank" rel="noopener">Facebook</a>
  </div>
</div>

<a id="subir" href="#inicio" aria-label="Volver al inicio">&#8593;</a>

</body>
</html>
