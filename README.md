<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AK — Home</title>
  <style>
    /* Global Styles */
    * { box-sizing: border-box; margin: 0; padding: 0; }
    html, body {
      height: 100%;
      font-family: Arial, sans-serif;
      background-color: #111;
      color: white;
    }
    a { color: white; text-decoration: none; }

    /* Header */
    header {
      background: rgba(255, 255, 255, 0.1);
      padding: 20px;
      text-align: center;
    }
    nav a {
      margin: 0 15px;
      font-weight: bold;
    }

    /* Sections */
    section {
      padding: 40px 20px;
      text-align: center;
    }

    /* Car Cards */
    .slide {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }
    .car-box {
      background: rgba(255, 255, 255, 0.1);
      padding: 20px;
      border-radius: 10px;
      width: 300px;
    }
    .car-box img {
      width: 100%;
      border-radius: 10px;
    }
    .price {
      margin-top: 10px;
      font-size: 20px;
      font-weight: bold;
      color: #ffcc00;
    }

    /* Video & Image Boxes */
    .box {
      background: #222;
      padding: 15px;
      border-radius: 12px;
      box-shadow: 0 0 20px rgba(255,255,255,0.2);
      text-align: center;
      max-width: 800px;
      width: 100%;
      margin: 0 auto;
    }
    video, img {
      max-width: 100%;
      border-radius: 8px;
    }

    /* Footer */
    footer {
      background: rgba(255, 255, 255, 0.1);
      padding: 10px;
      text-align: center;
    }
  </style>
</head>
<body>

  <!-- HEADER -->
  <header>
    <h1>AK</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#cars">Cars</a>
      <a href="#media">Media</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- HOME -->
  <section id="home">
    <h2>Welcome to AK Designer Website</h2>
    <p>Modern design, clean white menus, and vibrant background effects.</p>
  </section>

  <!-- FEATURED CARS -->
  <section id="cars">
    <h2>Featured Cars</h2>
    <div class="slide">
      <div class="car-box">
        <img src="NEW-LAND-ROVER-DEFENDER-130.jpg" alt="Land Rover Defender 130">
        <div class="price">$5,000,000 USD</div>
      </div>
      <div class="car-box">
        <img src="Porsche-car.jpg" alt="Porsche Car">
        <div class="price">$5,000,000 USD</div>
      </div>
    </div>
  </section>

  <!-- MEDIA SECTION -->
  <section id="media">
    <h2>Luxury Media Showcase</h2>

    <!-- Video -->
    <div class="box">
      <video controls autoplay muted loop>
        <source src="porsche.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div class="price">$5,000,000 USD</div>
    </div>

    <!-- Image -->
    <div class="box">
      <img src="car.jpg" alt="Luxury Car">
      <div class="price">$500,000 USD</div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:mehrakabir188@gmail.com">mehrakabir188@gmail.com</a></p>
  </section>

  <!-- FOOTER -->
  <footer>
    © AK — All Rights Reserved
  </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AK — Home</title>
  <style>
    /* Global Styles */
    * { box-sizing: border-box; margin: 0; padding: 0; }
    html, body {
      height: 100%;
      font-family: Arial, sans-serif;
      background-color: #111;
      color: white;
    }
    a { color: white; text-decoration: none; }

    /* Header */
    header {
      background: rgba(255, 255, 255, 0.1);
      padding: 20px;
      text-align: center;
    }
    nav a {
      margin: 0 15px;
      font-weight: bold;
      display: inline-block;
    }

    /* Sections */
    section {
      padding: 40px 20px;
      text-align: center;
    }

    /* Car Cards */
    .slide {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }
    .car-box {
      background: rgba(255, 255, 255, 0.1);
      padding: 20px;
      border-radius: 10px;
      width: 300px;
      flex: 1 1 280px;
    }
    .car-box img {
      width: 100%;
      border-radius: 10px;
    }
    .price {
      margin-top: 10px;
      font-size: 20px;
      font-weight: bold;
      color: #ffcc00;
    }

    /* Video & Image Boxes */
    .box {
      background: #222;
      padding: 15px;
      border-radius: 12px;
      box-shadow: 0 0 20px rgba(255,255,255,0.2);
      text-align: center;
      max-width: 800px;
      width: 100%;
      margin: 20px auto;
      flex: 1 1 300px;
    }
    video, img {
      max-width: 100%;
      border-radius: 8px;
    }

    /* Footer */
    footer {
      background: rgba(255, 255, 255, 0.1);
      padding: 10px;
      text-align: center;
      font-size: 14px;
    }

    /* Responsive Adjustments */
    @media (max-width: 768px) {
      nav a { margin: 5px; font-size: 14px; }
      section { padding: 20px 10px; }
      .price { font-size: 18px; }
      header { padding: 15px; }
    }
    @media (max-width: 480px) {
      h1, h2 { font-size: 20px; }
      .car-box, .box { padding: 10px; }
      .price { font-si
