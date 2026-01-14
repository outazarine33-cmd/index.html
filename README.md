<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>Brand Officiel</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Inter:wght@300;400&display=swap" rel="stylesheet">

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Inter', sans-serif;
  background: linear-gradient(
    180deg,
    rgba(28,23,20,0.95),
    rgba(245,240,230,0.95)
  );
  color: #1c1714;
}

/* HERO */
.hero {
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
}

.hero-content {
  max-width: 700px;
  animation: fadeDown 1.5s ease forwards;
}

.hero h1 {
  font-family: 'Playfair Display', serif;
  font-size: 64px;
  font-weight: 600;
  margin-bottom: 20px;
  color: #f5f0e6;
}

.hero p {
  font-size: 18px;
  opacity: 0.85;
  margin-bottom: 40px;
  color: #e0d8c8;
}

.hero a {
  text-decoration: none;
  padding: 14px 40px;
  border: 1px solid #e0d8c8;
  color: #e0d8c8;
  font-size: 14px;
  letter-spacing: 2px;
  transition: all 0.4s ease;
}

.hero a:hover {
  background: #e0d8c8;
  color: #1c1714;
}

/* SECTION */
.section {
  padding: 120px 8%;
  text-align: center;
}

.section h2 {
  font-family: 'Playfair Display', serif;
  font-size: 42px;
  margin-bottom: 60px;
}

/* PRODUCTS */
.product-row {
  display: flex;
  gap: 40px;
  justify-content: center;
  flex-wrap: wrap;
}

.product-card {
  width: 280px;
  padding: 30px;
  background: rgba(255,255,255,0.85);
  border-radius: 18px;
  box-shadow: 0 20px 50px rgba(0,0,0,0.15);
  animation: fadeUp 1.2s ease forwards;
}

.product-card:nth-child(1) { animation-delay: 0.3s; }
.product-card:nth-child(2) { animation-delay: 0.6s; }
.product-card:nth-child(3) { animation-delay: 0.9s; }

.product-card h3 {
  font-family: 'Playfair Display', serif;
  font-size: 22px;
  margin-bottom: 10px;
}

.product-card p {
  font-size: 14px;
  opacity: 0.75;
}

/* FOOTER */
footer {
  padding: 60px 0;
  text-align: center;
  font-size: 12px;
  opacity: 0.6;
}

/* ANIMATIONS */
@keyframes fadeUp {
  from {
    opacity: 0;
    transform: translateY(40px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes fadeDown {
  from {
    opacity: 0;
    transform: translateY(-40px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
</style>
</head>

<body>

<section class="hero">
  <div class="hero-content">
    <h1>YOUR BRAND</h1>
    <p>Une vision. Une identité. Une élégance intemporelle.</p>
    <a href="#">DÉCOUVRIR</a>
  </div>
</section>

<section class="section">
  <h2>Collection</h2>
  <div class="product-row">
    <div class="product-card">
      <h3>Produit I</h3>
      <p>Design épuré et présence raffinée.</p>
    </div>
    <div class="product-card">
      <h3>Produit II</h3>
      <p>Équilibre entre force et élégance.</p>
    </div>
    <div class="product-card">
      <h3>Produit III</h3>
      <p>Une signature unique et assumée.</p>
    </div>
  </div>
</section>

<footer>
  © 2026 — Brand Officiel
</footer>

</body>
</html>
