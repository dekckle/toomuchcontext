# toomuchcontext
gravity forgot this folder
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Too Much Context</title>
  <style>
    body {
      background: #121212;
      color: #eee;
      font-family: 'Courier New', Courier, monospace;
      margin: 0; padding: 0;
    }
    header {
      padding: 1rem;
      text-align: center;
      background: #1f1f1f;
      border-bottom: 2px solid #444;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
      letter-spacing: 0.1em;
    }
    header p {
      margin: 0.5rem 0 0;
      font-style: italic;
      color: #888;
      font-size: 0.9rem;
    }
    main {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 1rem;
      padding: 1rem;
      max-width: 900px;
      margin: 1rem auto;
    }
    .photo-card {
      background: #222;
      border: 1px solid #333;
      padding: 0.5rem;
      box-shadow: 0 0 5px #000;
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
      transition: transform 0.2s ease;
    }
    .photo-card:hover {
      transform: scale(1.05);
      box-shadow: 0 0 15px #55ff55;
    }
    .photo-card img {
      max-width: 100%;
      border: 1px solid #444;
      margin-bottom: 0.5rem;
    }
    .caption {
      font-size: 0.85rem;
      color: #bbb;
      font-style: italic;
      height: 2.4em; /* two lines */
      overflow: hidden;
    }
    footer {
      text-align: center;
      color: #555;
      font-size: 0.8rem;
      padding: 1rem;
      border-top: 1px solid #333;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>TOO MUCH CONTEXT</h1>
    <p>Context melted in the hallway.</p>
  </header>
  <main>
    <div class="photo-card">
      <img src="https://i.imgur.com/7D1rLsT.jpg" alt="Bottle on jar" />
      <div class="caption">Bottle on top of jar. Because why not?</div>
    </div>
    <div class="photo-card">
      <img src="https://i.imgur.com/yXLHzxH.jpg" alt="Fork on book" />
      <div class="caption">Fork resting on a book, questioning reality.</div>
    </div>
    <div class="photo-card">
      <img src="https://i.imgur.com/Gx7O47F.jpg" alt="Random chair" />
      <div class="caption">Chair in a kitchen sink. Nothing to see here.</div>
    </div>
  </main>
  <footer>
    Made to confuse. Copyright 2025.
  </footer>
</body>
</html>
