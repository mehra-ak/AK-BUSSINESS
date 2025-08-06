# AK-BUSINESS
AK BUSINESS, 
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>AK BUSINESS</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      scroll-behavior: smooth;
      background: #f9f9f9;
    }
    }
  </style>
</head>
<body>

  <header>
    <h1>AK BUSINESS</h1>
    <p>Your trusted partner in business solutions</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="home">
    <h2>Welcome to AK BUSINESS</h2>
    <p>We offer innovative and customized business solutions to help you grow. From strategy to execution, our experienced team is ready to support your success.</p>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>AK BUSINESS is committed to delivering high-quality services that meet the demands of the modern business world. With years of experience and a passion for innovation, we strive to help our clients thrive in competitive markets.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <ul>
      <li>Business Consulting</li>
      <li>Digital Marketing</li>
      <li>Web Development</li>
      <li>Project Management</li>
      <li>Startup Support</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form class="contact-form" onsubmit="submitForm(event)">
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
    <p id="form-response" style="color: green; font-weight: bold;"></p>
  </section>

  <footer>
    <p>&copy; 2025 AK BUSINESS. All rights reserved.</p>
  </footer>

  <script>
    function submitForm(e) {
      e.preventDefault();
      document.getElementById("form-response").innerText = "Thank you! We'll get back to you soon.";
      e.target.reset();
    }
  </script>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>AK BUSINESS</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      scroll-behavior: smooth;
      background: #f9f9f9;
    }

    
  </style>
</head>
<body></body>
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    scroll-behavior: smooth;
    background: linear-gradient(to right, #e0f0ff, #ffffff); /* light blue to white */
    color: #000;
  }

  header {
    background-color: #005fbb; /* deep blue */
    color: white;
    padding: 20px;
    text-align: center;
  }

  nav {
    background-color: #0074d9; /* brighter blue */
    display: flex;
    justify-content: center;
    gap: 20px;
    padding: 12px 0;
  }

  nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
  }

  nav a:hover {
    text-decoration: underline;
  }

  section {
    background-color: white;
    padding: 50px 20px;
    max-width: 1000px;
    margin: 20px auto;
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  }

  h2 {
    color: #003d80; /* dark blue */
  }

  footer {
    text-align: center;
    background: #003366;
    color: white;
    padding: 20px;
  }

  .contact-form input,
  .contact-form textarea {
    width: 100%;
    padding: 10px;
    margin-top: 10px;
    border: 1px solid #ccc;
    border-radius: 6px;
  }

  .contact-form button {
    margin-top: 10px;
    padding: 10px 20px;
    background: #0074d9;
    color: white;
    border: none;
    cursor: pointer;
    border-radius: 6px;
  }
<script>
  const numbers = [1, 2, 2, 3, 4, 4, 5];
  const unique = [...new Set(numbers)];

  console.log("Original:", numbers);
  console.log("Without duplicates:", unique);
</script>
<script>
  const numbers = [1, 2, 2, 3, 4, 4, 5];
  const unique = [...new Set(numbers)];

  console.log("Original:", numbers);
  console.log("Without duplicates:", unique);
</script>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Colorful Font Website</title>

  <!-- Import a Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@600&display=swap" rel="stylesheet">

  <style>
    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
      overflow: hidden;
      font-family: 'Poppins', sans-serif;
    }

    /* Background video style */
    #background-video {
      position: fixed;
      right: 0;
      bottom: 0;
      min-width: 100%;
      min-height: 100%;
      z-index: -1;
      object-fit: cover;
    }

    /* Content over the video */
    .content {
      position: relative;
      z-index: 1;
      text-align: center;
      padding-top: 20%;
    }

    h1 {
      font-size: 60px;
      background: linear-gradient(90deg, #00f, #0ff, #0f0, #ff0, #f00, #f0f);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      animation: rainbow 5s linear infinite;
      text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.7);
    }

    p {
      font-size: 24px;
      color: #ffffff;
      text-shadow: 1px 1px 4px black;
    }

    /* Optional: animate the gradient */
    @keyframes rainbow {
      0% { background-position: 0% 50%; }
      100% { background-position: 100% 50%; }
    }
  </style>
</head>
<body>

  <!-- Video Background -->
  <video autoplay muted loop id="background-video">
    <source src="mylivewallpapers-com-Dark-Spiderman-4K.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>

  <!-- Colorful Font Content -->
  <div class="content">
    <h1>Welcome to AK Business</h1>
    <p>Your Success, Our Mission</p>
  </div>

</body>
</html> .contact-form button:hover {
    background: #005fa3;
  }
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>AK BUSINESS Logo</title>
  <style>
    body {
      background-color: #f0f8ff;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    
  </style>
</head>
<body>
  <div style="text-align:center">
    <div class="logo">AK BUSINESS</div>
    <div class="tagline">Empowering Your Future</div>
  </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Contact AK BUSINESS</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f6fa;
    }

    .contact-section {
      max-width: 700px;
      margin: 80px auto;
      background: white;
      padding: 40px;
      border-radius: 16px;
      box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
    }

    .contact-section h2 {
      font-size: 32px;
      text-align: center;
      color: #0a0a23;
      margin-bottom: 30px;
    }

    .contact-section form {
      display: flex;
      flex-direction: column;
    }

    .contact-section input,
    .contact-section textarea {
      padding: 14px;
      margin-bottom: 20px;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-size: 16px;
      resize: none;
    }

    .contact-section button {
      padding: 14px;
      background-color: #007bff;
      color: white;
      border: none;
      border-radius: 8px;
      font-size: 16px;
      cursor: pointer;
      transition: 0.3s;
    }

    .contact-section button:hover {
      background-color: #0056b3;
    }

    @media (max-width: 768px) {
      .contact-section {
        margin: 40px 20px;
        padding: 30px;
      }
    }
  </style>
</head>
<body>

  <section class="contact-section">
    <h2>Connect With AK BUSINESS</h2>
    <form action="mailto:your@email.com" method="post" enctype="text/plain">
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

</body>
</html>
