<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>XYLA CAYSO</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: "Times New Roman", Times, serif;
    }

    body {
      background-color: #f7dce8;
      color: #222;
      min-height: 100vh;
      overflow: hidden;
    }

    header {
      background-color: #000000;
      color: white;
      padding: 18px 20px;
      text-align: center;
      border-bottom: 4px solid #ff69b4;
    }

    .brand-title {
      font-size: 1.3rem;
      letter-spacing: 3px;
      font-weight: bold;
      margin-bottom: 15px;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 12px;
    }

    .brand-logo {
      width: 70px;
      height: 70px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #ff69b4;
    }

    nav {
      background-color: #111111;
      padding: 10px;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      gap: 35px;
    }

    nav button {
      background: none;
      border: none;
      color: white;
      cursor: pointer;
      font-size: 0.85rem;
      letter-spacing: 1.5px;
      font-weight: bold;
      transition: 0.3s;
    }

    nav button:hover,
    nav button.active {
      color: #ff69b4;
    }

    main {
      height: calc(100vh - 180px);
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 30px 20px;
    }

    .page {
      display: none;
      width: 100%;
      max-width: 850px;
      text-align: center;
    }

    .page.active {
      display: block;
    }

    .card {
      background-color: white;
      border: 3px solid black;
      border-radius: 12px;
      padding: 40px;
      width: 100%;
      box-shadow: 0 10px 30px rgba(255, 20, 147, 0.25);
    }

    .card h1 {
      font-size: 1.6rem;
      letter-spacing: 2px;
      color: black;
      margin-bottom: 10px;
    }

    .card h1::after {
      content: "";
      display: block;
      width: 80px;
      height: 3px;
      background-color: #ff69b4;
      margin: 12px auto;
    }

    .subtitle {
      font-size: 0.95rem;
      color: #d63384;
      font-style: italic;
      margin-bottom: 25px;
    }

    .avatar-group {
      display: flex;
      justify-content: center;
      gap: 22px;
      margin-bottom: 25px;
    }

    .avatar {
      width: 80px;
      height: 80px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid black;
      transition: 0.3s;
    }

    .avatar:hover {
      border-color: #ff69b4;
      transform: scale(1.08);
    }

    .description {
      font-size: 0.9rem;
      color: #333;
      line-height: 1.6;
      margin-bottom: 25px;
    }

    .btn {
      display: inline-block;
      background-color: black;
      color: white;
      padding: 11px 28px;
      border-radius: 20px;
      border: none;
      text-decoration: none;
      font-size: 0.8rem;
      letter-spacing: 1.5px;
      font-weight: bold;
      cursor: pointer;
      transition: 0.3s;
    }

    .btn:hover {
      background-color: #ff69b4;
      color: black;
    }

    .gallery {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 25px;
    }

    .gallery img {
      width: 150px;
      height: 150px;
      object-fit: cover;
      border: 3px solid black;
      border-radius: 10px;
    }

    .contact-info {
      line-height: 2;
      margin-top: 20px;
    }

    .contact-info strong {
      color: #d63384;
    }

    footer {
      position: fixed;
      bottom: 0;
      left: 0;
      width: 100%;
      background-color: black;
      color: #ffb6d5;
      text-align: center;
      padding: 12px;
      font-size: 0.75rem;
      letter-spacing: 1px;
      border-top: 3px solid #ff69b4;
    }

    @media (max-width: 600px) {

      nav ul {
        gap: 15px;
      }

      nav button {
        font-size: 0.7rem;
      }

      main {
        height: calc(100vh - 190px);
        padding: 20px 15px;
      }

      .card {
        padding: 25px 15px;
      }

      .card h1 {
        font-size: 1.2rem;
      }

      .avatar {
        width: 60px;
        height: 60px;
      }

      .gallery img {
        width: 90px;
        height: 90px;
      }
    }
  </style>
</head>

<body>

  <header>

    <div class="brand-title">

      <img
        src="monalisa.jpg"
        alt="Mona Lisa"
        class="brand-logo"
      >

      <span>XYLA CAYSO</span>

    </div>

    <nav>
      <ul>

        <li>
          <button class="nav-btn active" onclick="showPage('home', this)">
            HOME
          </button>
        </li>

        <li>
          <button class="nav-btn" onclick="showPage('about', this)">
            ABOUT
          </button>
        </li>

        <li>
          <button class="nav-btn" onclick="showPage('gallery', this)">
            GALLERY
          </button>
        </li>

        <li>
          <button class="nav-btn" onclick="showPage('contact', this)">
            CONTACT
          </button>
        </li>

      </ul>
    </nav>

  </header>

  <main>

    <section id="home" class="page active">

      <div class="card">

        <h1>THIRD YEAR: THE ART OF ELEGANCE</h1>

        <p class="subtitle">
          Three years of creativity, growth, and unforgettable moments
        </p>

        <div class="avatar-group">

          <img
            src="IMG_20261013_090114.jpg"
            alt="Mona Lisa"
            class="avatar"
          >

        </div>

        <p class="description">
          Welcome to the Third Year of Xyla Cayso.
          This website celebrates creativity, individuality,
          growth, and memorable experiences through a
          sophisticated black and pink aesthetic inspired
          by the timeless beauty of art.
        </p>

        <button
          class="btn"
          onclick="showPage('about', document.querySelectorAll('.nav-btn')[1])">
          Learn More &gt;
        </button>

      </div>

    </section>

    <section id="about" class="page">

      <div class="card">

        <h1>ABOUT XYLA CAYSO</h1>

        <p class="subtitle">
          Creativity • Elegance • Growth
        </p>

        <p class="description">
          Welcome to my creative space. This website represents
          my journey and experiences during my third year.
          It combines classic elegance with a modern
          black and pink aesthetic.
        </p>

        <button
          class="btn"
          onclick="showPage('home', document.querySelectorAll('.nav-btn')[0])">
          BACK TO HOME
        </button>

      </div>

    </section>

    <section id="gallery" class="page">

      <div class="card">

        <h1>GALLERY</h1>

        <p class="subtitle">
          A collection of art and inspiration
        </p>

        <div class="gallery">

          <img
            src="IMG_20261013_090114.jpg"
            alt="Mona Lisa"
          >

          <img
            src="IMG_20261013_090114.jpg"
            alt="Mona Lisa"
          >

          <img
            src="IMG_20261013_090114.jpg"
            alt="Mona Lisa"
          >

        </div>

        <br>

        <button
          class="btn"
          onclick="showPage('home', document.querySelectorAll('.nav-btn')[0])">
          BACK TO HOME
        </button>

      </div>

    </section>

    <section id="contact" class="page">

      <div class="card">

        <h1>CONTACT</h1>

        <p class="subtitle">
          Get in touch with Xyla Cayso
        </p>

        <div class="contact-info">

          <p>
            <strong>Name:</strong> Xyla Cayso
          </p>

          <p>
            <strong>Email:</strong> xylacayso@example.com
          </p>

          <p>
            <strong>Theme:</strong> Black & Pink
          </p>

        </div>

        <br>

        <button
          class="btn"
          onclick="showPage('home', document.querySelectorAll('.nav-btn')[0])">
          BACK TO HOME
        </button>

      </div>

    </section>

  </main>

  <footer>
    &copy; 2027 XYLA CAYSO — THIRD YEAR
  </footer>

  <script>
    function showPage(pageId, button) {

      const pages = document.querySelectorAll(".page");

      pages.forEach(function(page) {
        page.classList.remove("active");
      });

      document.getElementById(pageId).classList.add("active");

      const buttons = document.querySelectorAll(".nav-btn");

      buttons.forEach(function(btn) {
        btn.classList.remove("active");
      });

      if (button) {
        button.classList.add("active");
      }
    }
  </script>

</body>
</html>
