<html lang="uk">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Project — Readymag style</title>

  <!-- Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">

  <style>
    /* RESET */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html, body {
      width: 100%;
      height: 100%;
      font-family: 'Inter', sans-serif;
      background: #ffffff;
      color: #000000;
    }

    body {
      overflow-x: hidden;
    }

    /* GLOBAL */
    a {
      color: inherit;
      text-decoration: none;
    }

    img {
      max-width: 100%;
      display: block;
    }

    /* LAYOUT */
    .page {
      width: 100%;
    }

    .section {
      min-height: 100vh;
      padding: 80px 6vw;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }

    /* HERO */
    .hero {
      align-items: flex-start;
    }

    .hero-title {
      font-size: clamp(32px, 6vw, 96px);
      font-weight: 500;
      line-height: 1.1;
      max-width: 12ch;
    }

    .hero-subtitle {
      margin-top: 24px;
      font-size: 18px;
      max-width: 420px;
    }

    /* IMAGE BLOCK */
    .image-block {
      margin-top: 64px;
      width: 100%;
      height: 70vh;
      background: #eaeaea;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    /* TEXT SECTION */
    .text-section {
      max-width: 720px;
      font-size: 18px;
      line-height: 1.6;
    }

    /* FOOTER */
    footer {
      padding: 40px 6vw;
      font-size: 14px;
      border-top: 1px solid #e5e5e5;
    }

    /* SIMPLE READYMAG-LIKE ANIMATION */
    .fade-in {
      opacity: 0;
      transform: translateY(40px);
      transition: all 0.8s ease;
    }

    .fade-in.visible {
      opacity: 1;
      transform: translateY(0);
    }
  </style>
</head>
<body>

  <div class="page">

    <!-- HERO -->
    <section class="section hero fade-in">
      <h1 class="hero-title">Назва проєкту або заголовок</h1>
      <p class="hero-subtitle">Короткий опис проєкту. 1–2 речення, як у Readymag.</p>
    </section>

    <!-- IMAGE -->
    <section class="section fade-in">
      <div class="image-block">
        <span>Image / Visual</span>
      </div>
    </section>

    <!-- TEXT -->
    <section class="section fade-in">
      <div class="text-section">
        <p>
          Тут основний текст. Можеш розбивати на абзаци, додавати посилання,
          робити великі відступи — Readymag це дуже любить.
        </p>
        <br />
        <p>
          Цей блок легко копіює відчуття редакційного лонгріду.
        </p>
      </div>
    </section>

    <!-- FOOTER -->
    <footer>
      © 2025 · Твоє імʼя / студія
    </footer>

  </div>

  <script>
    // Fade-in on scroll
    const elements = document.querySelectorAll('.fade-in');

    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('visible');
        }
      });
    }, { threshold: 0.2 });

    elements.forEach(el => observer.observe(el));
  </script>

</body>
</html>
