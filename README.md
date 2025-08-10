<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>AK — Home</title>
  <style>
    :root{
      --bg-yellow: #ffd95a;
      --bg-blue: #4da6ff;
    }
    *{box-sizing:border-box;margin:0;padding:0}
    html,body{height:100%;font-family:Inter, system-ui, -apple-system, "Segoe UI", Roboto, 'Helvetica Neue', Arial;}
    .bg{
      position:fixed;inset:0;z-index:-2;overflow:hidden;
    }
    .bg::before, .bg::after{
      content:"";position:absolute;border-radius:50%;filter:blur(120px);
      width:70vmax;height:70vmax;opacity:0.95;
    }
    .bg::before{left:-10%;top:-20%;background: radial-gradient(circle at 30% 30%, var(--bg-yellow), transparent 100%);}
    .bg::after{right:-10%;bottom:-10%;background: radial-gradient(circle at 70% 70%, var(--bg-blue), transparent 100%);}
    .overlay{position:fixed;inset:0;background:linear-gradient(180deg, rgba(0,0,0,0.15), rgba(0,0,0,0.22));z-index:-1;}
    .container{max-width:1100px;margin:0 auto;padding:40px 24px;}
    header{display:flex;align-items:center;justify-content:space-between;padding:10px 0}
    .logo{color:#fff;font-weight:700;letter-spacing:0.6px;font-size:20px}
    nav{display:flex;gap:18px;align-items:center}
    nav a{color:#fff;text-decoration:none;font-weight:600;padding:8px 12px;border-radius:8px;transition:background .18s}
    nav a:hover{background:rgba(255,255,255,0.06)}
    .cta{background:rgba(255,255,255,0.08);padding:9px 14px;border-radius:10px}
    .hero{display:grid;grid-template-columns:1fr 420px;gap:32px;align-items:center;padding:40px 0}
    .hero h1{color:#fff;font-size:44px;line-height:1.02;margin-bottom:12px}
    .hero p{color:rgba(255,255,255,0.92);font-size:16px;margin-bottom:20px}
    .hero .actions{display:flex;gap:12px}
    .btn{background:transparent;color:#fff;border:1px solid rgba(255,255,255,0.18);padding:10px 14px;border-radius:10px;font-weight:700;text-decoration:none}
    .btn:hover{background:rgba(255,255,255,0.06)}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border-radius:16px;padding:22px;backdrop-filter:blur(6px);box-shadow:0 6px 30px rgba(0,0,0,0.18)}
    .card h3{color:#fff;margin-bottom:10px}
    .contact-item{display:flex;flex-direction:column;gap:8px;margin-bottom:12px}
    .contact-item a{color:#fff;text-decoration:none;font-weight:700}
    footer{padding:28px 0;color:rgba(255,255,255,0.9)}
    @media (max-width:880px){.hero{grid-template-columns:1fr;}nav{display:none}}
    .menu-toggle{display:none;background:transparent;border:1px solid rgba(255,255,255,0.08);padding:8px 10px;border-radius:8px;color:#fff}
    @media (max-width:880px){.menu-toggle{display:inline-block}}
    form input, form textarea{width:100%;padding:12px;border-radius:10px;border:1px solid rgba(255,255,255,0.08);background:transparent;color:#fff}
    form label{color:rgba(255,255,255,0.85);font-weight:600;font-size:13px}
    form button{margin-top:8px;padding:10px 14px;border-radius:10px;background:transparent;border:1px solid rgba(255,255,255,0.18);color:#fff;font-weight:700}
  </style>
</head>
<body>
  <div class="bg"></div>
  <div class="overlay"></div>
  <div class="container">
    <header>
      <div class="logo">AK</div>
      <nav>
        <a href="#home">Home</a>
        <a href="#work">Work</a>
        <a href="#about">About</a>
        <a href="#contact" class="cta">Contact</a>
      </nav>
      <button class="menu-toggle">Menu</button>
    </header>
    <main class="hero" id="home">
      <div>
        <h1>Clean design, beautiful results.</h1>
        <p>Modern, minimal interfaces and brand-first websites — white UI on a soft yellow & blue blurred backdrop.</p>
        <div class="actions">
          <a class="btn" href="#contact">Get in touch</a>
          <a class="btn" href="#work">See work</a>
        </div>
      </div>
      <aside class="card">
        <h3>Contact</h3>
        <div class="contact-item">
          <label>Email</label>
          <a href="mailto:mehrakabir188@gmail.com">mehrakabir188@gmail.com</a>
        </div>
      </aside>
    </main>
    <footer>
      <div style="display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:12px">
        <div style="color:rgba(255,255,255,0.85)">© <strong>AK</strong> — All white UI · yellow-blue blur</div>
        <div><a href="mailto:mehrakabir188@gmail.com" style="color:#fff;text-decoration:none;font-weight:700">mehrakabir188@gmail.com</a></div>
      </div>
    </footer>
  </div>
</body>
</html>
