- 👋 Hi, I’m @tgr3000
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
tgr3000/tgr3000 i a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>

<html lang="en">

<head>

  <meta charset="UTF-8">

  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Portofolio</title>

  <style>

    body {

      font-family: Arial, sans-serif;

      line-height: 1.6;

      background-color: #f9f9f9;

      color: #333;

      margin: 0;

      padding: 0;

    }

    header {

      background-color: #333;

      color: #fff;

      padding: 20px;

      text-align: center;

    }

    main {

      padding: 20px;

    }

    section {

      margin-bottom: 30px;

    }

    h2 {

      font-size: 24px;

      margin-bottom: 10px;

    }

    p {

      margin-bottom: 10px;

    }

    .project {

      margin-bottom: 20px;

    }

    img {

      max-width: 100%;

      height: auto;

    }

    footer {

      background-color: #333;

      color: #fff;

      padding: 20px;

      text-align: center;

    }

    h1#portfolio-header {

      font-family: Arial, sans-serif;

    }

  </style>

</head>

<body>

  <header>

    <h1 id="portfolio-header">Portofolio Saya</h1>

  </header>

  <main>

    <section id="about">

      <h2>Tentang Saya</h2>

      <p>Saya adalah seorang desainer grafis yang memiliki minat dalam pembuatan desain visual yang menarik dan kreatif. Saya berpengalaman dalam menghasilkan desain logo, brosur, dan ilustrasi.</p>

    </section>

    <section id="projects">

      <h2>Proyek Terbaru</h2>

      <div class="project">

        <img src="project1.jpg" alt="Proyek 1">

        <h3>Proyek 1</h3>

        <p>Deskripsi proyek 1.</p>

      </div>

      <div class="project">

        <img src="project2.jpg" alt="Proyek 2">

        <h3>Proyek 2</h3>

        <p>Deskripsi proyek 2.</p>

      </div>

    </section>

  </main>

  <footer>

    <p>Hak Cipta &copy; 2023 Nama Saya. Semua Hak Dilindungi.</p>

  </footer>

      <script>

    // Kode JavaScript di sini

    // Contoh kode JavaScript untuk mengubah font tulisan "Portofolio Saya" pada header setiap 1 detik

    const headerText = document.getElementById('portfolio-header');

    const fonts = ['Arial', 'Helvetica', 'Verdana', 'Times New Roman', 'Courier New', 'poppins'];

    let currentIndex = 0;

    setInterval(function() {

      headerText.style.fontFamily = fonts[currentIndex];

      currentIndex++;

      if (currentIndex >= fonts.length) {

        currentIndex = 0;

      }

    }, 300);

  </script>

</body>

</html>


