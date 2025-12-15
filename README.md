<!DOCTYPE html>
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
      font-family: Inter, Helvetica, Arial, sans-serif;
      background: #ffffff;
      color: #111;
      padding: 80px 24px;
    }

    .container {
      max-width: 960px;
      margin: 0 auto;
    }

    h1 {
      font-size: 42px;
      font-weight: 600;
      margin-bottom: 12px;
    }

    .subtitle {
      font-size: 18px;
      color: #555;
      margin-bottom: 60px;
    }

    section {
      margin-bottom: 80px;
    }

    h2 {
      font-size: 24px;
      font-weight: 500;
      margin-bottom: 24px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 24px;
    }

    .work {
      border: 1px solid #eee;
      padding: 20px;
      min-height: 180px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #999;
      font-size: 14px;
    }

    .contact a {
      display: block;
      font-size: 18px;
      color: #111;
      text-decoration: none;
      margin-bottom: 12px;
    }

    .contact a:hover {
      text-decoration: underline;
    }

    footer {
      margin-top: 120px;
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
