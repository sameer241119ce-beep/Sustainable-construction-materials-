# Sustainable-construction-materials-
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Sustainable Construction Materials</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{--accent:#2b9348;--muted:#6b7280;--bg:#f7faf9;--card:#ffffff}
    *{box-sizing:border-box}
    body{font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,"Helvetica Neue",Arial;line-height:1.45;margin:0;background:var(--bg);color:#0f172a}
    .container{max-width:1000px;margin:32px auto;padding:24px}
    header{display:flex;align-items:center;justify-content:space-between;gap:16px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:56px;height:56px;border-radius:8px;background:linear-gradient(135deg,var(--accent),#166534);display:flex;align-items:center;justify-content:center;color:white;font-weight:700}
    nav a{margin-left:12px;text-decoration:none;color:var(--muted);font-weight:600}
    .hero{display:grid;grid-template-columns:1fr;gap:18px;background:linear-gradient(180deg,rgba(43,147,72,0.06),transparent);padding:22px;border-radius:12px}
    .hero h1{margin:0;font-size:28px}
    .hero p{margin:6px 0;color:var(--muted)}
    .cta{margin-top:8px}
    .btn{background:var(--accent);color:white;padding:10px 16px;border-radius:8px;text-decoration:none;font-weight:600}
    .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin-top:20px}
    .card{background:var(--card);padding:16px;border-radius:10px;box-shadow:0 6px 18px rgba(15,23,42,0.06)}
    .card h3{margin:0 0 8px 0}
    .products{display:grid;grid-template-columns:repeat(2,1fr);gap:14px;margin-top:18px}
    .product{display:flex;gap:12px;align-items:flex-start}
    .product .img{width:88px;height:64px;border-radius:8px;background:#e6f4ea;display:flex;align-items:center;justify-content:center;color:var(--accent);font-weight:700}
    footer{margin-top:28px;text-align:center;color:var(--muted);font-size:14px}
    .features{display:flex;gap:12px;flex-wrap:wrap}
    .feature{background:#fcfff6;border:1px solid rgba(43,147,72,0.06);padding:10px;border-radius:8px;flex:1;min-width:220px}
    form{display:grid;gap:10px}
    input,textarea,select{padding:10px;border-radius:8px;border:1px solid #e6e9ee;font-size:14px}
    .small{font-size:13px;color:var(--muted)}
    @media (max-width:900px){.grid{grid-template-columns:1fr}.products{grid-template-columns:1fr}.brand .hide-sm{display:none}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">SC</div>
        <div>
          <div style="font-weight:700">Sustainable Construction</div>
          <div class="small">Eco-friendly building materials</div>
        </div>
      </div>
      <nav>
        <a href="#about">About</a>
        <a href="#products">Products</a>
        <a href="#benefits">Benefits</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <section class="hero" id="home">
      <div>
        <h1>Sustainable materials for modern construction</h1>
        <p>We produce eco-friendly, durable and cost-effective building materials — made from fly ash, recycled plastic, and bamboo — to help reduce construction waste and carbon footprint.</p>
        <div class="cta"><a class="btn" href="#contact">Get a Quote</a></div>
      </div>
      <div class="grid" style="margin-top:8px">
        <div class="card">
          <h3>Our Mission</h3>
          <p class="small">To replace conventional materials with greener alternatives while keeping performance and affordability.</p>
        </div>
        <div class="card">
          <h3>Certifications</h3>
          <p class="small">Products designed to meet green building standards and local construction codes.</p>
        </div>
        <div class="card">
          <h3>Support</h3>
          <p class="small">Design consultation and technical support for builders and architects.</p>
        </div>
      </div>
    </section>

    <section id="about" style="margin-top:22px">
      <div class="card">
        <h2>About Us</h2>
        <p class="small">We are a startup focused on manufacturing sustainable construction materials: fly-ash bricks, recycled plastic pavers, and treated bamboo elements. Our process minimizes landfill waste and uses low-energy manufacturing methods. We also provide testing and consulting to help buildings qualify for green certifications.</p>
        <div style="margin-top:12px" class="features">
          <div class="feature"><strong>Low Carbon</strong><div class="small">Reduced embodied energy compared to traditional materials.</div></div>
          <div class="feature"><strong>Durable</strong><div class="small">Engineered for long-term performance and weather resistance.</div></div>
          <div class="feature"><strong>Affordable</strong><div class="small">Competitive pricing through recycled inputs and efficient manufacturing.</div></div>
        </div>
      </div>
    </section>

    <section id="products" style="margin-top:22px">
      <h2 style="margin-bottom:8px">Products</h2>
      <div class="products">
        <div class="card product">
          <div class="img">B</div>
          <div>
            <h3 style="margin:0">Fly-ash Bricks</h3>
            <p class="small">Lightweight, strong bricks manufactured from industrial by-products. Suitable for walls and partitions.</p>
            <div class="small"><strong>Price:</strong> ₹9 - ₹12 / brick (est.)</div>
          </div>
        </div>

        <div class="card product">
          <div class="img">P</div>
          <div>
            <h3 style="margin:0">Plastic-Recycled Pavers</h3>
            <p class="small">Pavers and tiles made from processed plastic waste — ideal for walkways and landscaping.</p>
            <div class="small"><strong>Price:</strong> ₹120 - ₹200 / sq.ft (est.)</div>
          </div>
        </div>

        <div class="card product">
          <div class="img">BB</div>
          <div>
            <h3 style="margin:0">Treated Bamboo Elements</h3>
            <p class="small">Structural and decorative elements using sustainably grown bamboo, treated for durability.</p>
            <div class="small"><strong>Price:</strong> Depends on specification</div>
          </div>
        </div>

        <div class="card product">
          <div class="img">C</div>
          <div>
            <h3 style="margin:0">Composite Panels</h3>
            <p class="small">Insulated panels using recycled cores — for fast construction and thermal efficiency.</p>
          </div>
        </div>
      </div>
    </section>

    <section id="benefits" style="margin-top:22px">
      <div class="card">
        <h2>Benefits for Builders</h2>
        <ul class="small">
          <li>Lower lifecycle carbon emissions</li>
          <li>Cost savings through efficient logistics</li>
          <li>Improved site waste management</li>
          <li>Support for obtaining green building credits</li>
        </ul>
      </div>
    </section>

    <section id="contact" style="margin-top:22px">
      <div class="card">
        <h2>Contact & Get a Quote</h2>
        <p class="small">Fill the form or email us at <a href="mailto:info@sustainablebuild.example">info@sustainablebuild.example</a></p>
        <form onsubmit="event.preventDefault();alert('Thanks! Your request has been submitted (demo).');">
          <input required placeholder="Name" />
          <input required placeholder="Email" type="email" />
          <input placeholder="Company / Project" />
          <select>
            <option>Product of interest: Fly-ash bricks</option>
            <option>Plastic pavers</option>
            <option>Treated bamboo</option>
            <option>Composite panels</option>
          </select>
          <textarea rows="4" placeholder="Project description / message"></textarea>
          <div style="display:flex;gap:10px"><button class="btn" type="submit">Request Quote</button><a class="btn" href="mailto:info@sustainablebuild.example">Email Us</a></div>
        </form>
        <p class="small" style="margin-top:12px">Result for experiment: Paste the link to your hosted website here.</p>
      </div>
    </section>

    <footer>
      © <span id="year"></span> Sustainable Construction • Made for Experiment 5
    </footer>
  </div>

  <script>document.getElementById('year').textContent=new Date().getFullYear();</script>
</body>
</html>
