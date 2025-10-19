# AIFF
pagina asociación IFF 
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AIFF - Asociación de Información y Formación Financiera</title>
  <style>
    body {
      font-family: 'Segoe UI', Roboto, sans-serif;
      margin: 0;
      background-color: #f4f6f9;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, #0b3d91, #1b5bd8);
      color: white;
      text-align: center;
      padding: 2.5rem 1rem;
    }

    header h1 { margin-bottom: 0.5rem; }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 1rem;
      font-weight: 500;
    }

    nav a:hover { color: #ffd700; }

    .container {
      width: 90%;
      max-width: 1000px;
      margin: auto;
    }

    section { padding: 2.5rem 0; }

    h2 {
      color: #0b3d91;
      border-left: 4px solid #0b3d91;
      padding-left: 0.5rem;
    }

    .info-card {
      background: white;
      border-radius: 10px;
      padding: 1.5rem;
      margin-top: 1rem;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    .info-card img {
      width: 100%;
      border-radius: 10px;
      margin: 1rem 0;
    }

    .boton-agregar {
      display: inline-block;
      background-color: #0b3d91;
      color: white;
      padding: 0.8rem 1.2rem;
      border-radius: 8px;
      text-decoration: none;
      font-weight: 600;
      transition: background 0.3s ease;
      margin-bottom: 1rem;
    }

    .boton-agregar:hover { background-color: #093275; }

    .form-publicacion {
      display: none;
      background: white;
      padding: 1.5rem;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      margin-top: 1rem;
    }

    .form-publicacion input,
    .form-publicacion textarea,
    .form-publicacion button {
      width: 100%;
      padding: 0.8rem;
      margin: 0.5rem 0;
      border-radius: 8px;
      border: 1px solid #ccc;
      font-size: 1rem;
    }





    footer {
      background-color: #0b3d91;
      color: white;
      text-align: center;
      padding: 1.5rem;
      margin-top: 3rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Asociación de Información y Formación Financiera (AIFF)</h1>
    <p>Impulsando la educación y cooperación financiera</p>
    <nav>
      <a href="#servicios">Áreas</a>
      <a href="#informacion">Información</a>
      <a href="#galeria">Galería</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <main class="container">
    <section id="servicios">
      <h2>Áreas de actuación</h2>
      <ul>
        <li>Formación financiera</li>
        <li>Intercambio de conocimientos</li>
        <li>Asesoramiento y orientación</li>
      </ul>
    </section>

    <section id="informacion">
      <h2>Recursos e Información</h2>

      <a href="#" class="boton-agregar" id="addPostBtn">➕ Añadir publicación</a>

      <form id="postForm" class="form-publicacion">
        <input type="text" id="titulo" placeholder="Título de la publicación" required>
        <textarea id="contenido" placeholder="Texto de la publicación" rows="4" required></textarea>
        <input type="file" id="imagen" accept="image/*">
        <button type="submit">Publicar</button>
      </form>

      <div id="publicaciones">
        <!-- Publicación inicial -->
        <div class="info-card">
          <h3>Tendencias recientes en los mercados bursátiles internacionales (2025)</h3>
          <p>Durante el año 2025, los principales índices bursátiles han mostrado una evolución mixta, marcada por la desaceleración en algunos sectores tecnológicos y el repunte de las energías renovables. El Índice Global AIFF registró un crecimiento acumulado del 4,8% en el primer semestre.</p>
         
        </div>
      </div>
    </section>


<section id="contacto">
  <h2>Contacto entre socios</h2>
  <p>Si eres miembro de la AIFF o deseas colaborar con la asociación, completa el formulario y nos pondremos en contacto contigo a la mayor brevedad.</p>

  <div class="contacto-card">
    <form id="formSocios">
      <div class="fila">
        <div class="campo">
          <label for="nombre">Nombre completo</label>
          <input type="text" id="nombre" placeholder="Tu nombre" required>
        </div>
        <div class="campo">
          <label for="correo">Correo electrónico</label>
          <input type="email" id="correo" placeholder="tu@correo.com" required>
        </div>
      </div>

      <div class="campo">
        <label for="asunto">Asunto</label>
        <input type="text" id="asunto" placeholder="Motivo del mensaje" required>
      </div>

      <div class="campo">
        <label for="mensaje">Mensaje</label>
        <textarea id="mensaje" rows="5" placeholder="Escribe aquí tu consulta o comentario" required></textarea>
      </div>

      <div class="campo">
        <label for="archivo">Adjuntar archivo (opcional)</label>
        <input type="file" id="archivo" accept=".pdf,.jpg,.png,.docx">
      </div>

      <button type="submit">📨 Enviar mensaje</button>
    </form>
  </div>
</section>

<style>
  #contacto {
    background-color: #ffffff;
    border-radius: 12px;
    padding: 2rem;
    box-shadow: 0 3px 10px rgba(0,0,0,0.1);
    margin-top: 2rem;
  }

  #contacto p {
    color: #555;
    margin-bottom: 1.5rem;
  }

  .contacto-card {
    background: #f9fafc;
    padding: 1.5rem;
    border-radius: 12px;
    border: 1px solid #e0e4ec;
  }

  form label {
    font-weight: 600;
    color: #0b3d91;
    display: block;
    margin-bottom: 0.4rem;
  }

  form input, form textarea {
    width: 100%;
    padding: 0.8rem;
    margin-bottom: 1rem;
    border-radius: 8px;
    border: 1px solid #ccc;
    font-size: 1rem;
    transition: border 0.3s ease, box-shadow 0.3s ease;
  }

  form input:focus, form textarea:focus {
    outline: none;
    border-color: #1b5bd8;
    box-shadow: 0 0 5px rgba(27,91,216,0.3);
  }

  .fila {
    display: flex;
    gap: 1rem;
  }

  .campo {
    flex: 1;
  }

  button[type="submit"] {
    background: linear-gradient(135deg, #0b3d91, #1b5bd8);
    color: white;
    border: none;
    padding: 1rem 1.5rem;
    font-size: 1rem;
    font-weight: 600;
    border-radius: 8px;
    cursor: pointer;
    transition: background 0.3s ease, transform 0.2s ease;
    width: 100%;
  }

  button[type="submit"]:hover {
    background: linear-gradient(135deg, #092b67, #164bb7);
    transform: translateY(-2px);
  }

  @media (max-width: 768px) {
    .fila {
      flex-direction: column;
    }
  }
</style>

<script>
  document.getElementById("formSocios").addEventListener("submit", (e) => {
    e.preventDefault();
    const nombre = document.getElementById("nombre").value;
    const correo = document.getElementById("correo").value;
    const asunto = document.getElementById("asunto").value;
    const mensaje = document.getElementById("mensaje").value;

    alert(`✅ Gracias, ${nombre}. Tu mensaje sobre "${asunto}" se ha enviado correctamente. Recibirás respuesta en ${correo}.`);
    e.target.reset();
  });
</script>
 <section id="contacto">
      <h2>Contáctanos</h2>
      <form>
        <input type="text" placeholder="Tu nombre" required>
        <input type="email" placeholder="Tu correo" required>
        <textarea placeholder="Tu mensaje" rows="4"></textarea>
        <button type="submit">Enviar mensaje</button>
      </form>
    </section>
  </main>

  <footer>
    © 2025 Asociación AIFF. Todos los derechos reservados.
  </footer>

  <script>
    const boton = document.getElementById('addPostBtn');
    const form = document.getElementById('postForm');
    const publicaciones = document.getElementById('publicaciones');

    // Mostrar / ocultar formulario
    boton.addEventListener('click', (e) => {
      e.preventDefault();
      form.style.display = form.style.display === 'block' ? 'none' : 'block';
    });

    // Cargar publicaciones guardadas al inicio
    window.addEventListener('DOMContentLoaded', () => {
      const guardadas = JSON.parse(localStorage.getItem('publicaciones')) || [];
      guardadas.forEach(pub => mostrarPublicacion(pub, false));
    });

    // Añadir nueva publicación
    form.addEventListener('submit', (e) => {
      e.preventDefault();
      const titulo = document.getElementById('titulo').value;
      const contenido = document.getElementById('contenido').value;
      const imagenInput = document.getElementById('imagen');

      const nueva = { titulo, contenido };

      if (imagenInput.files.length > 0) {
        const lector = new FileReader();
        lector.onload = function(evt) {
          nueva.imagen = evt.target.result;
          guardarYMostrar(nueva);
        };
        lector.readAsDataURL(imagenInput.files[0]);
      } else {
        guardarYMostrar(nueva);
      }

      form.reset();
      form.style.display = 'none';
    });

    // Guardar en localStorage y mostrar
    function guardarYMostrar(pub) {
      const publicacionesGuardadas = JSON.parse(localStorage.getItem('publicaciones')) || [];
      publicacionesGuardadas.unshift(pub);
      localStorage.setItem('publicaciones', JSON.stringify(publicacionesGuardadas));
      mostrarPublicacion(pub, true);
    }

    // Mostrar en la página
    function mostrarPublicacion(pub, animar) {
      const nueva = document.createElement('div');
      nueva.classList.add('info-card');
      nueva.innerHTML = `<h3>${pub.titulo}</h3><p>${pub.contenido}</p>`;
      if (pub.imagen) {
        const img = document.createElement('img');
        img.src = pub.imagen;
        img.alt = "Imagen de publicación";
        nueva.appendChild(img);
      }
      if (animar) nueva.style.animation = "fadeIn 0.5s ease";
      publicaciones.prepend(nueva);
    }

       document.querySelector("section#contacto form").addEventListener("submit", (e) => {
      e.preventDefault();
      alert("📩 Gracias por tu mensaje. Te responderemos pronto.");
      e.target.reset();
    });
  </script>
</body>
</html>
  
