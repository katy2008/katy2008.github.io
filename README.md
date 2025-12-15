<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Kateryna Kruhlyk — Graphic Designer & Illustrator</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Helvetica, Arial, sans-serif;
      background: #ffffff;
      color: #111;
      padding: 32px 20px; /* ← МІНІМАЛЬНІ ПОЛЯ */
    }

    .container {
      width: 100%;
      max-width: none; /* ← НЕ ОБМЕЖУЄМО ШИРИНУ */
    }

    h1 {
      font-size: 48px;
      font-weight: 500;
      margin-bottom: 8px;
    }

    .subtitle {
      font-size: 18px;
      color: #555;
      margin-bottom: 48px;
    }

    section {
      margin-bottom: 72px;
    }

    h2 {
      font-size: 22px;
      font-weight: 500;
      margin-bottom: 20px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
      gap: 16px;
    }

    .work {
      border: 1px solid #eaeaea;
      min-height: 220px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 14px;
      color: #999;
    }

    .contact a {
      display: block;
      font-size: 18px;
      color: #111;
      text-decoration: none;
      margin-bottom: 10px;
    }

    .contact a:hover {
      text-decoration: underline;
    }

    footer {
      margin-top: 100px;
      font-size: 14px;
      color: #888;
    }
  </style>
</head>

<body>
  <div class="container">

    <header>
      <h1>Kateryna Kruhlyk</h1>
      <p class="subtitle">Graphic Designer / Illustrator</p>
    </header>

    <section>
      <h2>Selected works</h2>

      <div class="grid">
        <div class="work">Project 1</div>
        <div class="work">Project 2</div>
        <div class="work">Project 3</div>
        <div class="work">Project 4</div>
        <div class="work">Project 5</div>
        <div class="work">Project 6</div>
      </div>
    </section>

    <section class="contact">
      <h2>Contact</h2>
      <a href="https://www.instagram.com/fckkkyropinion/" target="_blank">Instagram</a>
      <a href="mailto:fckyropinion@gmail.com">fckyropinion@gmail.com</a>
    </section>

    <footer>
      © 2025 Kateryna Kruhlyk
    </footer>

  </div>
</body>
</html>
