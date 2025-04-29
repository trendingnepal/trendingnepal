<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>SetoPatra News</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f4f4f4;
    }

    header {
      background: #20232a;
      color: #fff;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      font-size: 1.5rem;
      font-weight: bold;
    }

    nav a {
      margin: 0 1rem;
      color: #ccc;
      text-decoration: none;
      transition: color 0.2s ease;
    }

    nav a:hover {
      color: #fff;
    }

    .hero {
      background: url('https://source.unsplash.com/1600x600/?news') no-repeat center center/cover;
      color: white;
      padding: 4rem 2rem;
      text-align: center;
    }

    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }

    .hero p {
      font-size: 1.2rem;
    }

    .news-section {
      padding: 2rem;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2rem;
    }

    .news-card {
      background: #fff;
      padding: 1rem;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      transition: transform 0.2s ease;
    }

    .news-card:hover {
      transform: translateY(-5px);
    }

    .news-card img {
      width: 100%;
      border-radius: 6px;
    }

    .news-card h3 {
      margin: 0.8rem 0 0.4rem;
    }

    .news-card p {
      font-size: 0.95rem;
      color: #333;
    }

    footer {
      background: #20232a;
      color: #aaa;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }

    .social-icons a {
      margin: 0 0.5rem;
      color: #aaa;
      text-decoration: none;
      font-size: 1.2rem;
    }

    .social-icons a:hover {
      color: #fff;
    }

    @media(max-width: 768px) {
      .hero h1 {
        font-size: 2rem;
      }
    }
  </style>
  <script>
    // Optional JS for later use
    document.addEventListener("DOMContentLoaded", () => {
      console.log("News site loaded!");
    });
  </script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">
</head>
<body>

  <header>
    <div class="logo">SetoPatra</div>
    <nav>
      <a href="#"><i class="fa fa-home"></i> Home</a>
      <a href="#"><i class="fa fa-list"></i> Categories</a>
      <a href="#"><i class="fa fa-fire"></i> Trending</a>
      <a href="#"><i class="fa fa-info-circle"></i> About</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Breaking News: Get the Latest Updates</h1>
    <p>Trusted news from around Nepal and the world. Updated every hour.</p>
  </section>

  <section class="news-section">
    <div class="news-card">
      <img src="https://source.unsplash.com/400x200/?politics" alt="news">
      <h3>Political Drama in Kathmandu</h3>
      <p>The latest debate in Parliament heats up over budget allocations and federal reforms.</p>
    </div>

    <div class="news-card">
      <img src="https://source.unsplash.com/400x200/?technology,nepal" alt="news">
      <h3>Technology Startups Rise in Nepal</h3>
      <p>Young entrepreneurs are making waves with new AI-driven services and e-commerce tools.</p>
    </div>

    <div class="news-card">
      <img src="https://source.unsplash.com/400x200/?culture,festival" alt="news">
      <h3>Indra Jatra Celebrated</h3>
      <p>Thousands gather in Kathmandu Durbar Square to celebrate the vibrant Indra Jatra festival.</p>
    </div>
  </section>

  <footer>
    <div class="social-icons">
      <a href="#"><i class="fab fa-facebook-f"></i></a>
      <a href="#"><i class="fab fa-twitter"></i></a>
      <a href="#"><i class="fab fa-youtube"></i></a>
      <a href="#"><i class="fab fa-instagram"></i></a>
    </div>
    <p>&copy; 2025 SetoPatra News. All rights reserved.</p>
  </footer>

</body>
</html>

