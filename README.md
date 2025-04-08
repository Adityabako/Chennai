<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Chennai City Guide</title>
  <style>
    html {
      scroll-behavior: smooth;
    }
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(120deg, #1f1c2c, #928dab);
      color: #fff;
    }
    nav {
      position: sticky;
      top: 0;
      background-color: rgba(0, 0, 0, 0.8);
      padding: 10px 20px;
      display: flex;
      gap: 15px;
      justify-content: center;
      z-index: 1000;
    }
    nav a {
      color: #ffd700;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    header {
      text-align: center;
      padding: 60px 20px;
      background-color: rgba(0, 0, 0, 0.6);
      animation: fadeInDown 2s ease;
    }
    header h1 {
      font-size: 3em;
      margin: 0;
      color: #ffcc00;
    }
    section {
      max-width: 900px;
      margin: 40px auto;
      background-color: rgba(255, 255, 255, 0.1);
      padding: 30px;
      border-radius: 15px;
      animation: fadeInUp 1.2s ease;
    }
    section h2 {
      color: #ffd700;
    }
    section p {
      line-height: 1.6;
      font-size: 1.1em;
    }
    footer {
      text-align: center;
      padding: 20px;
      background-color: rgba(0, 0, 0, 0.6);
      color: #ccc;
    }
    @keyframes fadeInDown {
      0% { opacity: 0; transform: translateY(-50px); }
      100% { opacity: 1; transform: translateY(0); }
    }
    @keyframes fadeInUp {
      0% { opacity: 0; transform: translateY(50px); }
      100% { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <nav>
    <a href="#intro">Intro</a>
    <a href="#history">History</a>
    <a href="#culture">Culture</a>
    <a href="#food">Food</a>
    <a href="#tourism">Tourism</a>
  </nav>

  <header>
    <h1>Welcome to Chennai</h1>
  </header>

  <section id="intro">
    <h2>Introduction</h2>
    <p>Chennai is the capital of Tamil Nadu and a major cultural and economic center in India. It is known for its deep-rooted traditions and modern growth.</p>
    <p>With over 8 million residents, it’s one of the largest cities in India. It’s also famous for its coastal charm and rich art scene.</p>
  </section>

  <section id="history">
    <h2>History</h2>
    <p>Originally called Madras, Chennai was founded in 1639 by the British East India Company. It played a key role in colonial India’s development.</p>
    <p>The city later evolved into a thriving Indian metropolis, blending British architecture with South Indian legacy.</p>
  </section>

  <section id="culture">
    <h2>Culture</h2>
    <p>Chennai is home to Bharatanatyam and Carnatic music, making it a cultural epicenter. The annual December Music Festival is world-famous.</p>
    <p>Temples, sabhas, and classical performances reflect the vibrant soul of the city every single day.</p>
  </section>

  <section id="food">
    <h2>Food</h2>
    <p>From crispy dosas to spicy Chettinad curries, Chennai’s cuisine is diverse and flavorful. Street food like sundal and bhajji is popular at beaches.</p>
    <p>Traditional meals served on banana leaves continue to charm locals and tourists alike.</p>
  </section>

  <section id="tourism">
    <h2>Tourism</h2>
    <p>Major attractions include Marina Beach, Fort St. George, and Kapaleeshwarar Temple. Each location tells a story of culture and heritage.</p>
    <p>Visitors also enjoy the Chennai Rail Museum, Mahabalipuram nearby, and serene temples across the city.</p>
  </section>

  <footer>
    <p>&copy; 2025 Chennai Web | Built with ❤️</p>
  </footer>
</body>
</html>
