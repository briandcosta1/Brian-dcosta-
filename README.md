<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Brian D’costa | Guardians of Pushpak</title>
  <meta name="description" content="Official site of Brian D’costa, author of Guardians of Pushpak — a mytho-sci-fi adventure." />
  <meta property="og:title" content="Brian D’costa — Guardians of Pushpak" />
  <meta property="og:description" content="A mytho-sci-fi odyssey where ancient flight meets modern destiny." />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://www.briandcosta.ca/" />
  <style>
    :root{
      --bg:#0b0d10; --card:#11151b; --text:#e7ecf3; --muted:#9aa7b4;
      --accent:#7dd3fc; --accent2:#c084fc; --border:#1e2630; --btn:#1f2937
    }
    *{box-sizing:border-box} html,body{margin:0;padding:0}
    body{font-family:system-ui,-apple-system,Segoe UI,Roboto,Helvetica,Arial,sans-serif;
         background:radial-gradient(900px 500px at 10% 0,rgba(125,211,252,.06),transparent),
                    radial-gradient(700px 400px at 90% 0,rgba(192,132,252,.06),transparent),
                    var(--bg); color:var(--text); line-height:1.6}
    a{color:inherit}
    .container{width:min(1100px,92%);margin:0 auto}
    header{position:sticky;top:0;z-index:10;background:rgba(11,13,16,.6);backdrop-filter:blur(8px);border-bottom:1px solid var(--border)}
    nav{display:flex;align-items:center;justify-content:space-between;padding:12px 0}
    .brand{font-weight:800;letter-spacing:.5px;background:linear-gradient(90deg,var(--accent),var(--accent2));
           -webkit-background-clip:text;background-clip:text;color:transparent}
    .links a{margin:0 10px;text-decoration:none;color:var(--text);opacity:.95}
    .links .btn{padding:10px 14px;border:1px solid var(--border);border-radius:12px;background:var(--btn)}
    .hero{display:grid;grid-template-columns:1.2fr .8fr;gap:32px;align-items:center;padding:56px 0 28px}
    h1{font-size:clamp(2.2rem,5.8vw,3.8rem);line-height:1.05;margin:.2rem 0}
    .lead{color:var(--muted);font-size:1.1rem}
    .cta-row{margin-top:14px}
    .cta-row a{display:inline-block;margin-right:10px;padding:12px 18px;border-radius:12px;text-decoration:none;border:1px solid var(--border)}
    .primary{background:linear-gradient(90deg,var(--accent),var(--accent2));color:#0b0d10;border:none;font-weight:700}
    .ghost{background:transparent}
    .card{background:var(--card);border:1px solid var(--border);border-radius:14px;padding:20px}
    .grid-3{display:grid;grid-template-columns:repeat(3,1fr);gap:20px}
    .book-cover{width:100%;border-radius:12px;border:1px solid var(--border);margin-bottom:10px}
    .muted{color:var(--muted)}
    footer{border-top:1px solid var(--border);margin-top:40px;padding:24px 0;color:var(--muted)}
    @media (max-width:900px){.hero{grid-template-columns:1fr}.grid-3{grid-template-columns:1fr 1fr}}
    @media (max-width:600px){.grid-3{grid-template-columns:1fr}.links a{display:none}.links .btn{display:inline-block}}
  </style>
</head>
<body>
  <header>
    <div class="container">
      <nav>
        <div class="brand">Brian D’costa</div>
        <div class="links">
          <a href="#books">Books</a>
          <a href="#about">About</a>
          <a href="#media">Media Kit</a>
          <a href="#contact">Contact</a>
          <a class="btn" href="https://www.paypal.me/BrianDcosta327" target="_blank" rel="noopener">Buy the Book</a>
        </div>
      </nav>
    </div>
  </header>

  <main class="container">
    <section class="hero" id="home">
      <div>
        <h1><span style="background:linear-gradient(90deg,var(--accent),var(--accent2));-webkit-background-clip:text;background-clip:text;color:transparent;">Guardians</span> of Pushpak</h1>
        <p class="lead">A mytho-sci-fi odyssey where ancient flight meets modern destiny. When the legendary <em>Pushpak Vimana</em> awakens, four unlikely guardians face gods, demons, and themselves.</p>
        <div class="cta-row">
          <a class="primary" href="https://a.co/d/9R0ogLk" target="_blank" rel="noopener">Buy on Amazon</a>
          <a class="ghost" href="https://www.paypal.me/BrianDcosta327" target="_blank" rel="noopener">Buy Direct with PayPal</a>
        </div>
        <p class="muted" style="margin-top:10px">Mythology × Sci-Fi • Fast-paced • Series Book 1</p>
      </div>
      <div class="card" style="text-align:center">
        <img class="book-cover" src="assets/cover-placeholder.jpg" alt="Guardians of Pushpak book cover">
        <div class="muted">Replace <code>/assets/cover-placeholder.jpg</code> with your real cover</div>
      </div>
    </section>

    <section id="books" style="padding:28px 0">
      <h2>Books</h2>
      <p class="muted">Book 1 is available now. Books 2 & 3 are coming soon.</p>
      <div class="grid-3">
        <article class="card">
          <img class="book-cover" src="assets/cover-placeholder.jpg" alt="Book 1 cover">
          <h3>Guardians of Pushpak</h3>
          <p class="muted">Book 1 · Available</p>
          <div class="cta-row">
            <a class="primary" href="https://a.co/d/9R0ogLk" target="_blank" rel="noopener">Buy on Amazon</a>
            <a class="" href="https://www.paypal.me/BrianDcosta327" target="_blank" rel="noopener">Buy with PayPal</a>
          </div>
        </article>
        <article class="card">
          <img class="book-cover" src="assets/book2-placeholder.jpg" alt="Book 2 placeholder">
          <h3>Wrath of Gods</h3>
          <p class="muted">Book 2 · Coming Winter 2026</p>
          <a class="" href="#contact">Notify me</a>
        </article>
        <article class="card">
          <img class="book-cover" src="assets/book3-placeholder.jpg" alt="Book 3 placeholder">
          <h3>Rise of Ravana</h3>
          <p class="muted">Book 3 · Coming Fall 2027</p>
          <a class="" href="#contact">Notify me</a>
        </article>
      </div>
    </section>

    <section id="about" style="padding:28px 0">
      <div class="card">
        <h2>About Brian</h2>
        <p>Brian D’costa is a Toronto-based writer, voice artist, and creative producer with 17+ years across animation, television, and digital media. He blends mythic imagination with modern science to craft page-turning adventures.</p>
        <p class="muted">Email: <a href="mailto:brian.dcosta1@outlook.com">brian.dcosta1@outlook.com</a></p>
      </div>
    </section>

    <section id="media" style="padding:28px 0">
      <h2>Media Kit</h2>
      <div class="grid-3">
        <a class="card" href="assets/author-photo-placeholder.jpg" download>
          <h3>Author Photo</h3>
          <p class="muted">High-res JPG</p>
        </a>
        <a class="card" href="assets/cover-placeholder.jpg" download>
          <h3>Book Cover</h3>
          <p class="muted">Front cover JPG</p>
        </a>
        <a class="card" href="assets/press-kit.zip" download>
          <h3>Press Kit</h3>
          <p class="muted">One-pager, logline, bio</p>
        </a>
      </div>
    </section>

    <section id="contact" style="padding:28px 0">
      <div class="card">
        <h2>Contact</h2>
        <p>For events, rights, or interviews, get in touch.</p>
        <ul>
          <li><strong>Email:</strong> <a href="mailto:brian.dcosta1@outlook.com">brian.dcosta1@outlook.com</a></li>
          <li><strong>Location:</strong> Toronto, Canada</li>
        </ul>
      </div>
    </section>
  </main>

  <footer>
    <div class="container">© <span id="y"></span> Brian D’costa. All rights reserved.</div>
  </footer>
  <script>document.getElementById('y').textContent=new Date().getFullYear()</script>
</body>
</html>
