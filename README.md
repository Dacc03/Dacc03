<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Deybbi Crisanto — Software Engineer</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;500;600;700;800&family=DM+Sans:ital,wght@0,300;0,400;0,500;1,300&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<!-- NAV -->
<nav>
  <a href="#hero" class="nav-logo">DC<span>.</span></a>
  <ul>
    <li><a href="#proyectos">Proyectos</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#sobre-mi">Sobre mí</a></li>
    <li><a href="#educacion">Educación</a></li>
    <li><a href="#contacto" class="nav-cta">Contacto</a></li>
  </ul>
</nav>

<!-- HERO -->
<section id="hero">
  <div class="hero-glow"></div>
  <div class="hero-glow2"></div>
  <div class="hero-inner">
    <div class="hero-tag">Disponible para prácticas pre-profesionales</div>
    <h1 class="hero-name">Deybbi<br><span>Crisanto.</span></h1>
    <p class="hero-title">Software Engineer — Full Stack</p>
    <p class="hero-desc">
      Estudiante de Ingeniería de Software en UPC, 9no ciclo. Desarrollo aplicaciones web full stack con Vue.js, ASP.NET Core y Spring Boot. Actualmente construyendo una plataforma de accesibilidad para personas con discapacidad visual usando IA y visión computacional.
    </p>
    <div class="hero-ctas">
      <a href="mailto:dacc7056@gmail.com" class="btn-primary">✉ Escribirme</a>
      <a href="https://github.com/Dacc03" target="_blank" rel="noopener" class="btn-outline">⌥ GitHub</a>
      <a href="https://www.linkedin.com/in/deybbicrisanto2003/" target="_blank" rel="noopener" class="btn-outline">↗ LinkedIn</a>
    </div>
    <div class="hero-stats">
      <div>
        <div class="stat-num">9no</div>
        <div class="stat-label">Ciclo — UPC</div>
      </div>
      <div>
        <div class="stat-num">4+</div>
        <div class="stat-label">Proyectos</div>
      </div>
      <div>
        <div class="stat-num">Full</div>
        <div class="stat-label">Stack</div>
      </div>
    </div>
  </div>
</section>

<!-- PROYECTOS -->
<section id="proyectos">
  <div class="container">
    <div class="section-header">
      <span class="section-tag">Proyectos</span>
      <h2 class="section-title">Lo que he construido</h2>
    </div>
    <div class="projects-grid">

      <!-- TESIS — FEATURED -->
      <div class="project-card featured">
        <div>
          <div class="project-badge badge-thesis">★ Proyecto principal</div>
          <h3 class="project-title" style="margin-top:0.75rem; font-size:1.5rem;">Plataforma de accesibilidad con IA</h3>
          <p class="project-desc">
            Plataforma web que asiste a personas con discapacidad visual en Lima Metropolitana mediante visión computacional (Google Vision API, OpenCV) e inteligencia artificial generativa (GPT-4o). Permite interpretar entornos visuales en tiempo real con retroalimentación en audio. Proyecto de tesis desarrollado con metodología ágil SCRUM.
          </p>
          <div class="project-stack">
            <span class="stack-tag">Google Vision API</span>
            <span class="stack-tag">OpenCV</span>
            <span class="stack-tag">GPT-4o</span>
            <span class="stack-tag">Vue.js</span>
            <span class="stack-tag">Python</span>
            <span class="stack-tag">WCAG 2.1</span>
          </div>
          <div class="project-links" style="margin-top:1rem;">
            <a href="https://github.com/Dacc03" target="_blank" rel="noopener" class="project-link">↗ Ver en GitHub</a>
          </div>
        </div>
        <div class="featured-visual">👁</div>
      </div>

      <!-- EventGO -->
      <div class="project-card">
        <div class="project-badge badge-frontend">Frontend</div>
        <h3 class="project-title">EventGO</h3>
        <p class="project-desc">
          Plataforma de gestión de eventos que conecta anfitriones con organizadores. Desarrollada con Vue.js y Clean Architecture, con soporte multilenguaje (ES/EN), autenticación y despliegue en Firebase Hosting.
        </p>
        <div class="project-stack">
          <span class="stack-tag">Vue.js</span>
          <span class="stack-tag">DDD</span>
          <span class="stack-tag">i18n</span>
          <span class="stack-tag">Firebase</span>
          <span class="stack-tag">GitFlow</span>
        </div>
        <div class="project-links">
          <a href="https://github.com/Dacc03" target="_blank" rel="noopener" class="project-link">↗ GitHub</a>
        </div>
      </div>

      <!-- Microservicios Spring Boot -->
      <div class="project-card">
        <div class="project-badge badge-backend">Backend</div>
        <h3 class="project-title">Microservicios Spring Boot</h3>
        <p class="project-desc">
          Arquitectura de microservicios con DDD y CQRS implementada en Spring Boot. Incluye gestión de tareas y eventos con patrones de diseño empresarial, API REST documentada y despliegue en Render.
        </p>
        <div class="project-stack">
          <span class="stack-tag">Spring Boot</span>
          <span class="stack-tag">DDD</span>
          <span class="stack-tag">CQRS</span>
          <span class="stack-tag">REST API</span>
          <span class="stack-tag">Render</span>
        </div>
        <div class="project-links">
          <a href="https://github.com/Dacc03" target="_blank" rel="noopener" class="project-link">↗ GitHub</a>
        </div>
      </div>

      <!-- LetPot Platform -->
      <div class="project-card">
        <div class="project-badge badge-fullstack">Full Stack</div>
        <h3 class="project-title">LetPot Platform</h3>
        <p class="project-desc">
          Plataforma full stack con ASP.NET Core 9 en backend y Vue.js en frontend. Arquitectura limpia con separación de capas, endpoints REST y persistencia con SQL Server.
        </p>
        <div class="project-stack">
          <span class="stack-tag">ASP.NET 9</span>
          <span class="stack-tag">C#</span>
          <span class="stack-tag">Vue.js</span>
          <span class="stack-tag">SQL Server</span>
          <span class="stack-tag">Clean Arch</span>
        </div>
        <div class="project-links">
          <a href="https://github.com/Dacc03" target="_blank" rel="noopener" class="project-link">↗ GitHub</a>
        </div>
      </div>

    </div>
  </div>
</section>

<!-- SKILLS -->
<section id="skills">
  <div class="container">
    <div class="skills-layout">
      <div>
        <div class="section-header" style="margin-bottom:1.5rem;">
          <span class="section-tag">Skills</span>
          <h2 class="section-title">Stack técnico</h2>
        </div>
        <p class="skills-intro">
          Desarrollo interfaces modernas con Vue.js y backends robustos con Spring Boot y ASP.NET Core. Aplico principios de arquitectura limpia, DDD y SCRUM en todos mis proyectos.
        </p>
      </div>
      <div class="skills-groups">
        <div class="skill-group">
          <div class="skill-group-title">Frontend</div>
          <div class="skill-list">
            <span class="skill-pill">Vue.js</span>
            <span class="skill-pill">JavaScript</span>
            <span class="skill-pill">HTML/CSS</span>
            <span class="skill-pill">PrimeVue</span>
            <span class="skill-pill">UI/UX</span>
          </div>
        </div>
        <div class="skill-group">
          <div class="skill-group-title">Backend</div>
          <div class="skill-list">
            <span class="skill-pill">ASP.NET 9</span>
            <span class="skill-pill">C#</span>
            <span class="skill-pill">Spring Boot</span>
            <span class="skill-pill">Java</span>
            <span class="skill-pill">REST API</span>
          </div>
        </div>
        <div class="skill-group">
          <div class="skill-group-title">Base de datos</div>
          <div class="skill-list">
            <span class="skill-pill">SQL Server</span>
            <span class="skill-pill">MySQL</span>
            <span class="skill-pill">Supabase</span>
            <span class="skill-pill">Firebase</span>
          </div>
        </div>
        <div class="skill-group">
          <div class="skill-group-title">Arquitectura & Proceso</div>
          <div class="skill-list">
            <span class="skill-pill">DDD</span>
            <span class="skill-pill">CQRS</span>
            <span class="skill-pill">Clean Arch</span>
            <span class="skill-pill">SCRUM</span>
            <span class="skill-pill">GitFlow</span>
            <span class="skill-pill">C++</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- SOBRE MÍ -->
<section id="sobre-mi">
  <div class="container">
    <div class="about-grid">
      <div class="about-text">
        <div class="section-header" style="margin-bottom:1.5rem;">
          <span class="section-tag">Sobre mí</span>
          <h2 class="section-title">Quién soy</h2>
        </div>
        <p>Soy <strong>Deybbi Crisanto</strong>, estudiante de Ingeniería de Software en la <strong>Universidad Peruana de Ciencias Aplicadas (UPC)</strong>, actualmente en el 9no ciclo.</p>
        <p>Me apasiona construir soluciones que generen impacto real. Mi proyecto de tesis busca mejorar la autonomía de <strong>personas con discapacidad visual</strong> usando IA y visión computacional, un área donde la tecnología puede marcar una diferencia concreta.</p>
        <p>Trabajo cómodo tanto en frontend como en backend, con especial experiencia en <strong>Vue.js, ASP.NET Core y Spring Boot</strong>, aplicando siempre arquitecturas limpias y metodologías ágiles.</p>
      </div>
      <div class="about-cards">
        <div class="about-card">
          <div class="about-card-icon">🎓</div>
          <div class="about-card-title">UPC — 9no ciclo</div>
          <div class="about-card-desc">Ingeniería de Software</div>
        </div>
        <div class="about-card">
          <div class="about-card-icon">🤖</div>
          <div class="about-card-title">IA & Visión</div>
          <div class="about-card-desc">Tesis con GPT-4o y OpenCV</div>
        </div>
        <div class="about-card">
          <div class="about-card-icon">⚡</div>
          <div class="about-card-title">Full Stack</div>
          <div class="about-card-desc">Frontend + Backend + Deploy</div>
        </div>
        <div class="about-card">
          <div class="about-card-icon">♿</div>
          <div class="about-card-title">Accesibilidad</div>
          <div class="about-card-desc">WCAG 2.1 — Lima, Perú</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- EDUCACIÓN -->
<section id="educacion">
  <div class="container">
    <div class="section-header">
      <span class="section-tag">Educación</span>
      <h2 class="section-title">Formación académica</h2>
    </div>
    <div class="edu-item">
      <div class="edu-year">2021 — 2027</div>
      <div>
        <div class="edu-name">Ingeniería de Software</div>
        <div class="edu-institution">Universidad Peruana de Ciencias Aplicadas — UPC</div>
        <div class="edu-desc">9no ciclo. Especialización en arquitecturas de software, desarrollo web full stack e inteligencia artificial aplicada. Proyecto de tesis sobre accesibilidad digital para personas con discapacidad visual.</div>
      </div>
    </div>
    <div class="edu-item">
      <div class="edu-year">2024</div>
      <div>
        <div class="edu-name">Arquitectura de Software y Microservicios</div>
        <div class="edu-institution">UPC — Cursos avanzados</div>
        <div class="edu-desc">Domain-Driven Design, CQRS, patrones de microservicios con Spring Boot y ASP.NET Core, diagramas C4 con Structurizr.</div>
      </div>
    </div>
    <div class="edu-item">
      <div class="edu-year">2023</div>
      <div>
        <div class="edu-name">Desarrollo Frontend con Vue.js</div>
        <div class="edu-institution">UPC — Proyectos académicos</div>
        <div class="edu-desc">Vue 3, PrimeVue, internacionalización, Clean Architecture en frontend, despliegue en Firebase y Vercel.</div>
      </div>
    </div>
  </div>
</section>

<!-- CONTACTO -->
<section id="contacto">
  <div class="container">
    <div class="contact-inner">
      <span class="section-tag">Contacto</span>
      <h2 class="section-title" style="margin-bottom:1rem;">¿Hablamos?</h2>
      <p class="contact-desc">Estoy buscando prácticas pre-profesionales en desarrollo de software. Si tienes una oportunidad o simplemente quieres conversar sobre tecnología, escríbeme.</p>
      <div class="contact-links">
        <a href="mailto:dacc7056@gmail.com" class="btn-primary">✉ dacc7056@gmail.com</a>
        <a href="https://www.linkedin.com/in/deybbicrisanto2003/" target="_blank" rel="noopener" class="btn-outline">↗ LinkedIn</a>
        <a href="https://github.com/Dacc03" target="_blank" rel="noopener" class="btn-outline">⌥ GitHub</a>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <p>© 2025 Deybbi Crisanto Calle</p>
  <p>Lima, Perú · dacc7056@gmail.com</p>
</footer>

<script src="main.js"></script>
</body>
</html>
