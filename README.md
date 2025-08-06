# AK-BUSSINESS
AK BUSINESS, we specialize in delivering top-notch solutions tailored to meet your needs. Whether you're an individual, small business, or large enterprise, we offer a wide range of services designed to help you succeed. From cutting-edge products to dedicated customer support, we are committed to excellence in everything we do.
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

    header {
      background: #1a1a1a;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      background: #333;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px 0;
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
      padding: 50px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      color: #333;
    }

    footer {
      text-align: center;
      background: #1a1a1a;
      color: white;
      padding: 20px;
    }

    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      border: 1px solid #ccc;
      border-radius: 6px;
    }

    .contact-form button {
      margin-top: 10px;
      padding: 10px 20px;
      background: #333;
      color: white;
      border: none;
      cursor: pointer;
      border-radius: 6px;
    }

    .contact-form button:hover {
      background: #555;
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

    header {
      background: #1a1a1a;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      background: #333;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px 0;
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
      padding: 50px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      color: #333;
    }

    footer {
      text-align: center;
      background: #1a1a1a;
      color: white;
      padding: 20px;
    }

    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      border: 1px solid #ccc;
      border-radius: 6px;
    }

    .contact-form button {
      margin-top: 10px;
      padding: 10px 20px;
      background: #333;
      color: white;
      border: none;
      cursor: pointer;
      border-radius: 6px;
    }

    .contact-form button:hover {
      background: #555;
    }

    /* 3D car wallpaper in Home section */
    #home {
      background: url('https://images.unsplash.com/photo-1609250292017-9446cb6de13c?auto=format&fit=crop&w=1350&q=80') no-repeat center center/cover;
      color: white;
      padding: 100px 20px;
      text-shadow: 1px 1px 5px rgba(0,0,0,0.7);
      border-radius: 8px;
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
    <p>Driven by innovation. Designed for success.</p>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>AK BUSINESS delivers cutting-edge business solutions with a creative touch. We help you scale, adapt, and grow with confidence in a fast-changing world.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <ul>
      <li>Business Consulting</li>
      <li>Digital Marketing</li>
      <li>Web & App Development</li>
      <li>Brand Strategy</li>
      <li>Customer Support Solutions</li>
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
Background: url(https://images.app.goo.gl/8rM5xoF8VyZ1bByW6'')
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    scroll-behavior: smooth;
    background: url('https://images.unsplash.com/photo-1609250292017-9446cb6de13c?auto=format&fit=crop&w=1400&q=80') no-repeat center center fixed;
    background-size: cover;
    color: white;
  }

  /* Add background overlay for readability */
  body::before {
    content: "";
    position: fixed;
    top: 0; left: 0; right: 0; bottom: 0;
    background-color: rgba(0,0,0,0.6); /* Dark overlay */
    z-index: -1;
  }

  header, nav, section, footer {
    background: transparent;
  }

  nav a {
    color: #fff;
  }

  section {
    padding: 50px 20px;
    max-width: 1000px;
    margin: auto;
    background-color: rgba(255,255,255,0.1); /* Slight section background */
    border-radius: 10px;
    margin-bottom: 20px;
  }

  /* Keep the rest of your styles unchanged below... */
</style>
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

  .contact-form button:hover {
    background: #005fa3;
  }
</style>
