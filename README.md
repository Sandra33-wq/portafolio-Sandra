<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portafolio - Sandra M. Girón Vargas</title>
  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Google Fonts para cursiva elegante -->
  <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&display=swap" rel="stylesheet" />
  <style>
    /* Paleta pastel */
    @layer utilities {
      .bg-pastel-pink { background-color: #FFE4E1; }
      .bg-pastel-purple { background-color: #E6E6FA; }
      .bg-pastel-green { background-color: #E0F8E0; }
      .bg-pastel-yellow { background-color: #FFFACD; }
    }
    /* Tipografía cursiva para el nombre */
    .font-cursive { font-family: 'Dancing Script', cursive; }
  </style>
</head>
<body class="bg-pastel-pink text-gray-800 leading-relaxed scroll-smooth">
  <!-- Hero Section -->
  <header class="bg-white/90 backdrop-blur-md shadow-md sticky top-0 z-50 animate-fadeIn">
    <div class="container mx-auto px-6 py-6 flex flex-col md:flex-row items-center justify-between">
      <div>
        <h1 class="text-4xl font-extrabold text-purple-700 font-cursive animate-pulse">Sandra M. Girón Vargas</h1>
        <p class="mt-1 text-lg text-gray-600">Escritora & Editora especializada en TDAH femenino</p>
      </div>
      <nav class="mt-4 md:mt-0">
        <ul class="flex space-x-6 font-medium text-gray-700">
          <li><a href="#proyectos" class="hover:text-purple-600 transition">Proyectos</a></li>
          <li><a href="#sobre-mi" class="hover:text-purple-600 transition">Sobre mí</a></li>
          <li><a href="#testimonios" class="hover:text-purple-600 transition">Testimonios</a></li>
          <li><a href="#blog" class="hover:text-purple-600 transition">Blog</a></li>
          <li><a href="#contacto" class="hover:text-purple-600 transition">Contacto</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main class="container mx-auto px-6 py-12 space-y-20">
    <!-- Sobre mí -->
    <section id="sobre-mi" class="flex flex-col md:flex-row items-center gap-8 animate-slideInLeft">
      <div class="md:w-1/2">
        <img src="/images/perfil.jpg" alt="Foto de Sandra" class="rounded-3xl shadow-lg w-full object-cover hover:scale-105 transition-transform" />
      </div>
      <div class="md:w-1/2">
        <h2 class="text-3xl font-semibold text-purple-700">Sobre mí</h2>
        <p class="mt-4">Soy Sandra M. Girón Vargas, mujer neurodivergente con TDAH. Combino mi experiencia personal con habilidades de escritura emocional para ayudar a mujeres a convertir sus historias en contenidos profesionales y accesibles.</p>
        <ul class="mt-4 list-disc pl-5 space-y-2">
          <li>Más de 20 proyectos completados en ebooks, diarios y reescrituras.</li>
          <li>Especialización en estilos íntimos, poéticos y reflexivos.</li>
          <li>Entregas en formatos Word, PDF y ePub/Kindle.</li>
        </ul>
      </div>
    </section>

    <!-- Ilustraciones -->
    <section id="ilustraciones" class="grid md:grid-cols-3 gap-6 animate-fadeIn">
      <div class="bg-white p-4 rounded-2xl shadow-sm hover:shadow-md transition">
        <img src="/images/illustration1.svg" alt="Ilustración suave 1" class="w-full h-40 object-contain mb-4" />
        <p class="text-center text-gray-600">Ilustraciones pastel para redes sociales.</p>
      </div>
      <div class="bg-white p-4 rounded-2xl shadow-sm hover:shadow-md transition">
        <img src="/images/illustration2.svg" alt="Ilustración suave 2" class="w-full h-40 object-contain mb-4" />
        <p class="text-center text-gray-600">Separadores emotivos entre capítulos.</p>
      </div>
      <div class="bg-white p-4 rounded-2xl shadow-sm hover:shadow-md transition">
        <img src="/images/illustration3.svg" alt="Ilustración suave 3" class="w-full h-40 object-contain mb-4" />
        <p class="text-center text-gray-600">Decoraciones accesibles para neurodivergentes.</p>
      </div>
    </section>

    <!-- Proyectos -->
    <section id="proyectos">
      <h2 class="text-3xl font-semibold text-purple-700 text-center">Proyectos Destacados</h2>
      <div class="mt-10 grid gap-8 md:grid-cols-3">
        <div class="bg-pastel-yellow rounded-2xl shadow-md overflow-hidden hover:shadow-lg transition animate-bounceIn">
          <img src="/images/mini-ebook-cover.jpg" alt="Mini-ebook" class="w-full h-48 object-cover" />
          <div class="p-6">
            <h3 class="text-2xl font-bold text-purple-800">Mini-ebook TDAH & Creatividad</h3>
            <p class="mt-2 text-gray-700">Ebook de 5 páginas con estrategias y ejercicios para canalizar la creatividad única del TDAH.</p>
            <a href="/pdfs/Proyecto1_MiniEbook_Profesional.pdf" class="mt-4 inline-block text-purple-700 font-semibold hover:underline">Ver proyecto</a>
          </div>
        </div>
        <div class="bg-pastel-green rounded-2xl shadow-md overflow-hidden hover:shadow-lg transition animate-bounceIn delay-200">
          <img src="/images/diario-preview.jpg" alt="Diario emocional" class="w-full h-48 object-cover" />
          <div class="p-6">
            <h3 class="text-2xl font-bold text-purple-800">Diario Emocional Neurodivergente</h3>
            <p class="mt-2 text-gray-700">Plantilla interactiva con secciones de estado de ánimo, gratitud, reflexión y mantra.</p>
            <a href="/pdfs/Proyecto2_DiarioTemplate_Profesional.pdf" class="mt-4 inline-block text-purple-700 font-semibold hover:underline">Ver proyecto</a>
          </div>
        </div>
        <div class="bg-pastel-purple rounded-2xl shadow-md overflow-hidden hover:shadow-lg transition animate-bounceIn delay-400">
          <img src="/images/reescritura-preview.jpg" alt="Reescritura" class="w-full h-48 object-cover" />
          <div class="p-6">
            <h3 class="text-2xl font-bold text-purple-800">Reescritura Poética</h3>
            <p class="mt-2 text-gray-700">Transformación estilística de textos, enfatizando musicalidad y profundidad emocional.</p>
            <a href="/pdfs/Proyecto3_Reescritura_Profesional.pdf" class="mt-4 inline-block text-purple-700 font-semibold hover:underline">Ver proyecto</a>
          </div>
        </div>
      </div>
    </section>

    <!-- Testimonios -->
    <section id="testimonios" class="bg-white/80 backdrop-blur-md rounded-2xl p-8 animate-fadeIn">
      <h2 class="text-3xl font-semibold text-purple-700 text-center">Testimonios</h2>
      <div class="mt-8 space-y-6">
        <div class="bg-pastel-pink rounded-xl p-6 shadow-sm hover:scale-105 transition">
          <p class="italic text-gray-800">"Trabajar con Sandra transformó por completo mi ebook. Su estilo íntimo y poético conecta verdaderamente con las lectoras."</p>
          <p class="mt-2 font-semibold text-purple-800 text-right">— Laura G.</p>
        </div>
        <div class="bg-pastel-yellow rounded-xl p-6 shadow-sm hover:scale-105 transition">
          <p class="italic text-gray-800">"La plantilla de diario es hermosa y funcional. Me ayuda a reflexionar cada día de manera profunda."</p>
          <p class="mt-2 font-semibold text-purple-800 text-right">— Marta S.</p>
        </div>
      </div>
    </section>

    <!-- Blog (placeholder) -->
    <section id="blog">
      <h2 class="text-3xl font-semibold text-purple-700 text-center">Artículos Recientes</h2>
      <!-- Aquí puedes añadir enlaces a tus posts -->
      <div class="mt-10 grid gap-8 md:grid-cols-3">
        <!-- Ejemplo de artículo -->
        <article class="bg-white rounded-2xl shadow-md overflow-hidden hover:shadow-lg transition">
          <img src="/images/blog1.jpg" alt="Blog Ventajas TDAH" class="w-full h-40 object-cover" />
          <div class="p-6">
            <h3 class="text-xl font-bold">Ventajas del TDAH en el Trabajo</h3>
            <p class="mt-2 text-gray-700">Explora cómo tu neurodivergencia puede ser tu mejor aliada profesional.</p>
            <a href="/blog/ventajas-tdah" class="mt-4 inline-block text-purple-700 font-semibold hover:underline">Leer artículo</a>
          </div>
        </article>
        <!-- Añade más según necesites -->
      </div>
    </section>

    <!-- Contacto -->
    <section id="contacto" class="bg-pastel-green rounded-2xl p-8 animate-slideInUp">
      <h2 class="text-3xl font-semibold text-purple-700 text-center">Contáctame</h2>
      <form action="/send" method="POST" class="mt-6 grid gap-4 md:grid-cols-2">
        <input type="text" name="nombre" placeholder="Tu nombre" required class="p-3 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-purple-300" />
        <input type="email" name="email" placeholder="Tu correo" required class="p-3 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-purple-300" />
        <textarea name="mensaje" rows="4" placeholder="Tu mensaje" required class="p-3 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-purple-300 col-span-full"></textarea>
        <button type="submit" class="mt-2 col-span-full bg-purple-600 text-white font-semibold px-6 py-3 rounded-full shadow hover:bg-purple-700 transition">Enviar Mensaje</button>
      </form>
    </section>
  </main>

  <footer class="bg-white/90 backdrop-blur-md py-6 mt-12 animate-fadeIn">
    <p class="text-center text-gray-600">© 2025 Sandra M. Girón Vargas. Todos los derechos reservados.</p>
  </footer>

  <!-- Animations CSS -->
  <style>
    @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }
    @keyframes slideInLeft { from { transform: translateX(-50px); opacity: 0; } to { transform: translateX(0); opacity: 1; } }
    @keyframes slideInUp { from { transform: translateY(50px); opacity: 0; } to { transform: translateY(0); opacity: 1; } }
    @keyframes bounceIn { 0% { transform: scale(0.3); opacity: 0; } 50% { transform: scale(1.05); opacity: 1; } 70% { transform: scale(0.9); } 100% { transform: scale(1); opacity: 1; } }
    .animate-fadeIn { animation: fadeIn 1s ease-out; }
    .animate-slideInLeft { animation: slideInLeft 1s ease-out; }
    .animate-slideInUp { animation: slideInUp 1s ease-out; }
    .animate-bounceIn { animation: bounceIn 1s ease-out; }
    .delay-200 { animation-delay: 0.2s; }
    .delay-400 { animation-delay: 0.4s; }
  </style>
</body>
</html>
