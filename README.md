# Kartossm-beltr-bell.com
<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kartoss Möbell Tröbel</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #ffecd2, #fcb69f, #ff7e5f);
      color: #333;
      transition: background 0.5s;
    }

    header {
      background: linear-gradient(90deg, #ff4e50, #f9d423);
      color: white;
      padding: 20px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }

    header h1 {
      margin: 0;
      font-size: 2.8em;
      text-shadow: 1px 1px 2px #333;
    }

    header p {
      font-size: 1.2em;
      margin-top: 5px;
      font-style: italic;
    }

    nav {
      background-color: #4caf50;
      display: flex;
      justify-content: center;
      padding: 10px 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      transition: color 0.3s, text-decoration 0.3s;
    }

    nav a:hover {
      text-decoration: underline;
      color: #ffeb3b;
    }

    .announcement {
      background: linear-gradient(90deg, #ffeb3b, #ff5722, #ff9800);
      color: #fff;
      font-weight: bold;
      padding: 20px;
      text-align: center;
      margin-bottom: 30px;
      border-radius: 8px;
      font-size: 1.5em;
      animation: pulse 1.5s infinite;
      box-shadow: 0 0 15px rgba(255,87,34,0.6);
    }

    @keyframes pulse {
      0%, 100% { transform: scale(1); opacity: 1; }
      50% { transform: scale(1.05); opacity: 0.8; }
    }

    main {
      padding: 40px 20px;
      text-align: center;
    }

    h2 {
      color: #ff6f61;
      font-size: 2em;
      margin-bottom: 30px;
    }

    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .product {
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.15);
      width: 250px;
      padding: 20px;
      cursor: pointer;
      transition: transform 0.3s, box-shadow 0.3s, background 0.3s;
    }

    .product:hover {
      transform: scale(1.05);
      box-shadow: 0 8px 16px rgba(0,0,0,0.25);
      background: linear-gradient(135deg, #ffecd2, #fcb69f, #ff7e5f);
      color: white;
    }

    .product img {
      width: 100%;
      border-radius: 8px;
    }

    .product h3 {
      margin: 15px 0 10px 0;
      color: #ff6f61;
    }

    .product p {
      font-size: 0.9em;
      color: #555;
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 20px 0;
      margin-top: 40px;
    }

    /* Responsive */
    @media (max-width: 600px) {
      .products {
        flex-direction: column;
        align-items: center;
      }

      .product {
        width: 90%;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Kartoss Möbell Tröbel</h1>
    <p>"Kartoss rein alles Pfein alles ins Haus rein"</p>
  </header>

  <div class="announcement">
    🎉 Neueröffnung am <strong>10.01.2026</strong> um 13 Uhr in der Berliner Straße – Mega Rabatte auf ALLE Möbel! 🎉
  </div>

  <main>
    <h2>Unsere Möbel</h2>
    <div class="products">
      <div class="product" onclick="window.open('https://moebline.de/schrank-mit-schubladen-stevi-buche', '_blank')">
        <img src="https://images.unsplash.com/photo-1598300059020-0de9331f6c6f?crop=entropy&cs=tinysrgb&fit=max&h=150&w=250" alt="Schrank">
        <h3>Schrank</h3>
        <p>Zum Angebot</p>
      </div>

      <div class="product" onclick="window.open('https://jona-sleep.com/products/massivholz-bett-noa', '_blank')">
        <img src="https://images.unsplash.com/photo-1582582494700-7be5a22c13f8?crop=entropy&cs=tinysrgb&fit=max&h=150&w=250" alt="Bett">
        <h3>Bett</h3>
        <p>Zum Angebot</p>
      </div>

      <div class="product" onclick="window.open('https://www.allnatura.de/tisch-konfigurator-cocina.html?srsltid=AfmBOor7iwshrOX4uoncvIHHQ18exnkW7YMHLvCB_7YKG4CVqSispfMe', '_blank')">
        <img src="https://images.unsplash.com/photo-1586105251261-72d914f7e4c1?crop=entropy&cs=tinysrgb&fit=max&h=150&w=250" alt="Tisch">
        <h3>Tisch</h3>
        <p>Zum Angebot</p>
      </div>
    </div>
  </main>

  <footer>
    &copy; 2025 Kartoss Möbell Tröbel. Alle Rechte vorbehalten.
  </footer>
</body>
</html>
