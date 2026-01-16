<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Yazhini | Freelance Copywriter</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0b0d10;
      --card:#151922;
      --accent:#7cff00;
      --text:#f2f4f8;
      --muted:#a1a7b3;
    }
    *{margin:0;padding:0;box-sizing:border-box;font-family:'Inter',sans-serif}
    body{background:var(--bg);color:var(--text);line-height:1.6}
    section{padding:90px 8%}
    h1,h2,h3{line-height:1.2}
    h2{font-size:2.4rem;margin-bottom:30px}
    p{color:var(--muted)}
    a{text-decoration:none;color:inherit}

    /* HERO */
    .hero{min-height:100vh;display:flex;flex-direction:column;justify-content:center}
    .badge{color:var(--accent);font-weight:600;letter-spacing:2px;font-size:.8rem;margin-bottom:18px}
    .hero h1{font-size:3.8rem;font-weight:800;max-width:900px}
    .hero h1 span{color:var(--accent)}
    .hero p{max-width:650px;margin-top:20px;font-size:1.15rem}
    .cta{margin-top:40px;display:inline-block;padding:16px 36px;border-radius:40px;background:var(--accent);color:#000;font-weight:700}

    /* GRID */
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:28px}
    .card{background:var(--card);padding:30px;border-radius:22px;transition:.35s}
    .card:hover{transform:translateY(-10px)}
    .card h3{margin-bottom:12px}

    /* ABOUT */
    .about{max-width:800px}

    /* FOOTER */
    footer{text-align:center;padding:50px;color:#6f7685;font-size:.9rem}
  </style>
</head>
<body>

<section class="hero">
  <div class="badge">BEGINNER · SERIOUS · RESULT‑FOCUSED</div>
  <h1>I help brands say <span>less</span> and sell <span>more</span>.</h1>
  <p>
    I'm Yazhini — a beginner freelance copywriter.
    I focus on clarity, structure, and persuasion.
    No fake expertise. Just honest work that converts.
  </p>
  <a href="#contact" class="cta">Hire Me</a>
</section>

<section>
  <h2>Services</h2>
  <div class="grid">
    <div class="card">
      <h3>Copywriting</h3>
      <p>Clear, persuasive writing for websites, emails, and business documents.</p>
    </div>
    <div class="card">
      <h3>Content Writing</h3>
      <p>Articles, blogs, and written content focused on clarity and structure.</p>
    </div>
    <div class="card">
      <h3>Proofreading & Editing</h3>
      <p>Grammar, clarity, and flow checks to make your content professional.</p>
    </div>
    <div class="card">
      <h3>Microsoft Word Typing</h3>
      <p>Accurate typing, formatting, and document cleanup.</p>
    </div>
    <div class="card">
      <h3>Data Entry & Excel</h3>
      <p>Organized data handling, basic Excel work, and spreadsheets.</p>
    </div>
    <div class="card">
      <h3>Email Handling</h3>
      <p>Professional email drafting, replies, and inbox support.</p>
    </div>
    <div class="card">
      <h3>Essay Writing</h3>
      <p>Structured essays with clear arguments and logical flow.</p>
    </div>
  </div>
</section>

<section>
  <h2>About Me</h2>
  <div class="about card">
    <p>
      I'm starting out — and that's my advantage.
      I research deeply, write intentionally, and care about results because every project matters.
      If you want honest effort over empty promises, I'm a good fit.
    </p>
  </div>
</section>

<section>
  <h2>Sample Work</h2>
  <div class="grid">
    <div class="card">
      <h3>Instagram Reel Script</h3>
      <p>20‑second hook‑based script for a motivation brand (concept).</p>
    </div>
    <div class="card">
      <h3>Landing Page Copy</h3>
      <p>Hero section + CTA for a startup website (practice).</p>
    </div>
  </div>
</section>

<section id="contact">
  <h2>Contact</h2>
  <div class="card">
    <p>Email: yazhiniwrites@gmail.com</p>
    <p>Freelancer: freelancer.in/u/yazhinipd2</p>
  </div>
</section>

<footer>
  © 2026 Yazhini · Built with intent
</footer>

</body>
</html>
