<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>THE WORLD OF FASHION</title>
  <!-- Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&family=Playfair+Display:wght@400;600;700&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header">
    <div class="container header-inner">
      <a class="logo" href="#" aria-label="Atelier Noir">Atelier Noir</a>
      <nav class="nav" aria-label="Main">
        <a href="#">Collections</a>
        <a href="#">Editorial</a>
        <a href="#">Showroom</a>
        <a href="#">Contact</a>
      </nav>
      <div class="header-actions">
        <button class="btn btn-ghost" aria-pressed="false">Sign in</button>
        <button class="btn btn-primary">Shop</button>
      </div>
    </div>
  </header>

  <main>
    <section class="hero">
      <div class="container hero-inner">
        <div class="hero-copy">
          <h1 class="display">A season of quiet luxury</h1>
          <p class="lead">A curated edit of timeless silhouettes and modern tailoring. Hand‑finished, limited runs.</p>
          <div class="hero-actions">
            <a class="btn btn-primary" href="#">Shop the edit</a>
            <a class="btn btn-outline" href="#">Learn more</a>
          </div>
        </div>
        <div class="hero-visual" role="img" aria-label="Model wearing Atelier Noir collection" style="background-image:url('https://images.unsplash.com/photo-1520975910398-6fbd1a9f7a41?q=80&w=1600&auto=format&fit=crop');"></div>
      </div>
    </section>

    <section class="container section">
      <h2 class="section-title">New arrivals</h2>
      <p class="section-sub">Selected pieces from our latest capsule — crafted in small batches.</p>

      <div class="grid products">
        <article class="product-card">
          <div class="media" style="background-image:url('https://images.unsplash.com/photo-1503341455253-b2e723bb3dbb?q=80&w=1000&auto=format&fit=crop');" aria-hidden="true"></div>
          <div class="product-body">
            <h3 class="product-title">Tailored Wool Coat</h3>
            <p class="product-meta">Made in Italy · 1 of 45</p>
            <div class="product-row">
              <span class="price">$1,200</span>
              <button class="btn btn-sm btn-outline">View</button>
            </div>
          </div>
        </article>

        <article class="product-card">
          <div class="media" style="background-image:url('https://images.unsplash.com/photo-1541099649105-f69ad21f3246?q=80&w=1000&auto=format&fit=crop');" aria-hidden="true"></div>
          <div class="product-body">
            <h3 class="product-title">Silk Slip Dress</h3>
            <p class="product-meta">Hand‑dyed · Limited</p>
            <div class="product-row">
              <span class="price">$420</span>
              <button class="btn btn-sm btn-outline">View</button>
            </div>
          </div>
        </article>

        <article class="product-card">
          <div class="media" style="background-image:url('https://images.unsplash.com/photo-1500917293891-ef795e70e1f6?q=80&w=1000&auto=format&fit=crop');" aria-hidden="true"></div>
          <div class="product-body">
            <h3 class="product-title">Structured Tote</h3>
            <p class="product-meta">Vegetable‑tanned leather</p>
            <div class="product-row">
              <span class="price">$680</span>
              <button class="btn btn-sm btn-outline">View</button>
            </div>
          </div>
        </article>

        <article class="product-card">
          <div class="media" style="background-image:url('https://images.unsplash.com/photo-1514996937319-344454492b37?q=80&w=1000&auto=format&fit=crop');" aria-hidden="true"></div>
          <div class="product-body">
            <h3 class="product-title">Cropped Knit</h3>
            <p class="product-meta">Merino wool · Soft finish</p>
            <div class="product-row">
              <span class="price">$230</span>
              <button class="btn btn-sm btn-outline">View</button>
            </div>
          </div>
        </article>
      </div>
    </section>

    <section class="newsletter">
      <div class="container newsletter-inner">
        <div>
          <h3>Be first to know</h3>
          <p class="muted">Sign up for limited drops and editorial notes.</p>
        </div>
        <form class="subscribe" onsubmit="event.preventDefault(); alert('Subscribed — replace this with integration');">
          <label class="sr-only" for="email">Email</label>
          <input id="email" type="email" placeholder="you@example.com" required>
          <button class="btn btn-primary">Subscribe</button>
        </form>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container footer-inner">
      <div class="brand">
        <a class="logo" href="#">Atelier Noir</a>
        <p class="muted">Seasonless design • Small batch</p>
      </div>
      <div class="links">
        <a href="#">Shipping</a>
        <a href="#">Returns</a>
        <a href="#">Privacy</a>
      </div>
    </div>
  </footer>

  <!-- small script to toggle dark theme for demo -->
  <script>
    // Toggle with "d" key for quick demo
    document.addEventListener('keydown', e => {
      if (e.key.toLowerCase() === 'd') {
        const t = document.documentElement.getAttribute('data-theme') === 'dark' ? 'light' : 'dark';
        document.documentElement.setAttribute('data-theme', t);
      }
    });
  </script>
</body>
</html>
