<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Mi Página Web</title>
    <style>
      /* Estilos para el layout */
      body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-image: url("https://img.freepik.com/vector-gratis/fondo-calor-verano-degradado_23-2149423260.jpg"); /* Cambia 'fondo.jpg' por la ruta de tu imagen de fondo */
        background-size: cover;
        background-repeat: no-repeat;
      }

      header,
      nav,
      main,
      aside,
      footer {
        display: block;
        padding: 20px;
        background-color: rgba(
          0,
          0,
          0,
          0.5
        ); /* Fondo semi-transparente para mejorar la legibilidad del texto */
        color: #fff;
      }

      header,
      footer {
        text-align: center;
      }

      nav ul {
        list-style-type: none;
        padding: 0;
        margin: 0;
      }

      nav ul li {
        display: inline;
        margin-right: 20px;
      }

      nav ul li a {
        color: #fff;
        text-decoration: none;
      }

      main {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
      }

      .content {
        flex-grow: 2;
        margin-right: 20px;
      }

      .sidebar {
        flex-basis: 200px;
      }

      img {
        max-width: 100%;
        height: auto;
        margin-bottom: 20px;
      }

      video {
        width: 100%;
        height: auto;
        margin-bottom: 20px;
      }
    </style>
  </head>
  <body>
    <header>
      <img
        src="file:///C:/Users/Alumno/Downloads/image-removebg-preview.png"
        alt="Imagen 1"
      />
    </header>
    <nav>
      <ul>
        <li><a href="#">Inicio</a></li>
        <li><a href="#plants">Plants</a></li>
        <li><a href="#zombies">Zombies</a></li>
        <li><a href="#niveles">Niveles</a></li>
      </ul>
    </nav>
    <main>
      <section class="content">
        <h2>Inicio</h2>
        <p>
          El jugador asume el papel de propietario de una casa en medio de un
          apocalipsis zombie. A medida que una horda de zombis se acerca a lo
          largo de varios carriles paralelos, el jugador debe defender su hogar
          colocando plantas, que disparan proyectiles a los zombis o los afectan
          perjudicialmente..
        </p>
        <img
          src="https://i.pinimg.com/736x/42/e5/54/42e5546a7b560dc5ac15b62cfb93cd43.jpg"
          v
          alt="Imagen 1"
        />
        <p>Cerebro - Brr.</p>
        <video controls>
          <source
            src="C:\Users\Alumno\Desktop\VIDEO\Plants vs Zombies Music Video (1).mp4"
            type="video/mp4"
          />
          Tu navegador no soporta este video.
        </video>
      </section>
      <aside class="sidebar">
        <h2>Lanzaguisantes</h2>
        <img
          src="file:///C:/Users/Alumno/Downloads/png-transparent-plants-vs-zombies-2-it-s-about-time-plants-vs-zombies-garden-warfare-plants-vs-zombies-heroes-peashooter-pea-leaf-video-game-smiley-thumbnail-removebg-preview%20(1).png"
          alt="Imagen 2"
        />
        <img
          src="file:///C:/Users/Alumno/Downloads/8ec43553b491b57df3dcb7179f138d9a-removebg-preview.png"
          alt="Imagen 3"
        />
      </aside>
    </main>
    <footer>
      <h2>Plants</h2>
      <img
        src="file:///C:/Users/Alumno/Downloads/akee.png.adapt.crop16x9-removebg-preview%20(1).png"
        alt="Imagen de Plants 1"
      />
      <img
        src="file:///C:/Users/Alumno/Downloads/images-removebg-preview-removebg-preview.png"
        alt="Imagen de Plants 2"
      />
      <img
        src="file:///C:/Users/Alumno/Downloads/a039751760d99a16b52e2acea438daa7-removebg-preview%20(1).png"
        alt="Imagen de Plants 3"
      />
      <img
        src="file:///C:/Users/Alumno/Downloads/images__1_-removebg-preview.png"
        alt="Imagen de Plants 4"
      />
      <img
        src="file:///C:/Users/Alumno/Downloads/twin-sunflower.png.adapt.crop16x9-removebg-preview.png"
        alt="Imagen de Plants 5"
      />
      <img
        src="file:///C:/Users/Alumno/Downloads/be55cf2467eb01e9950037022484111e-removebg-preview.png"
        alt="Imagen de Plants 6"
        />
      <img
        src="file:///C:/Users/Alumno/Downloads/images__2_-removebg-preview.png"
        alt="Imagen de Plants 7"
        />
      <img
        src="file:///C:/Users/Alumno/Downloads/red-stinger.png.adapt.crop16x9-removebg-preview.png"
        alt="Imagen de Plants 8"
        />
    </aside>
  </main>
  <footer>
       <h2>Zombies</h2>
       <img
        src="file:///C:/Users/Alumno/Downloads/png-transparent-plants-vs-zombies-2-it-s-about-time-plants-vs-zombies-garden-warfare-2-plants-vs-zombies-heroes-plants-vs-zombies-removebg-preview.png"
        alt="Imagen de Plants 1"
      />
      <img
        src="file:///C:/Users/Alumno/Downloads/images__3_-removebg-preview.png"
        alt="Imagen de Plants 2"
      />
      <img
        src="file:///C:/Users/Alumno/Downloads/images__5_-removebg-preview.png"
        alt="Imagen de Plants 3"
      />
      <imgil
        src="file:///C:/Users/Alumno/Downloads/4fc4f3529c974c84d873b0abd39c59de-removebg-preview.png"
        alt="Imagen de Plants 4"
      />
      <img
        src="file:///C:/Users/Alumno/Downloads/gratis-png-plants-vs-zombies-2-es-hora-de-llamar-al-deber-zombies-tirachinas-zombies-plantas-y-zombies-removebg-preview.png"
        alt="Imagen de Plants 5"
      />
      <img
        src="file:///C:/Users/Alumno/Downloads/png-transparent-plants-vs-zombies-2-it-s-about-time-plants-vs-zombies-garden-warfare-2-video-game-plants-vs-zombies-2-removebg-preview.png"
        alt="Imagen de Plants 6"
        />
      <img
        src="file:///C:/Users/Alumno/Downloads/images__4_-removebg-preview.png"
        alt="Imagen de Plants 7"
        />
      <img
        src="file:///C:/Users/Alumno/Downloads/461ddd1f0d3ab96304f7a3719f1a54e5-removebg-preview.png"
        alt="Imagen de Plants 8"
        />
    </aside>
  </main>
  <footer>
        <h2>Mapas</h2>
       <img
        src="file:///C:/Users/Alumno/Downloads/939c50169942463c31265ec3274bce54340e51e5_hq.jpg"
        alt="Imagen de Plants 1"
      />
      <img
        src="file:///C:/Users/Alumno/Downloads/images%20(6).jpg"
        alt="Imagen de Plants 2"
      />
      <img
        src="file:///C:/Users/Alumno/Downloads/images%20(7).jpg"
        alt="Imagen de Plants 3"
      />
      <img
        src="file:///C:/Users/Alumno/Downloads/maxresdefault.jpg"
        alt="Imagen de Plants 4"
      />
      <img
        src="file:///C:/Users/Alumno/Downloads/Plants-vs.-Zombies-2-1.jpeg"
        alt="Imagen de Plants 5"
      />
      <img
        src="file:///C:/Users/Alumno/Downloads/x1080.jpg"
        alt="Imagen de Plants 6"
        />
      <img
        src="file:///C:/Users/Alumno/Downloads/images%20(8).jpg"
        alt="Imagen de Plants 7"
        />
      

    
        
