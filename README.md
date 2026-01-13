<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Capacity Studio</title>
  <style>
    /* ====== General Styles ====== */
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #fff3f6;
      color: #333;
    }

    header {
      background: #ff5c8a;
      color: white;
      padding: 15px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
    }

    header .logo {
      height: 50px;
    }

    nav a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    main {
      padding: 20px;
      max-width: 900px;
      margin: auto;
    }

    h1, h2 {
      color: #ff2c7d;
    }

    .section {
      background: #ffe8ef;
      padding: 15px;
      margin: 15px 0;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }

    .song-card {
      background: #fff;
      padding: 10px 15px;
      margin: 10px 0;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .song-card a {
      background: #ff5c8a;
      color: white;
      padding: 6px 12px;
      border-radius: 6px;
      text-decoration: none;
    }

    .song-card a:hover {
      background: #ff2c7d;
    }

    footer {
      text-align: center;
      padding: 15px;
      background: #ff5c8a;
      color: white;
      margin-top: 20px;
    }

    @media(max-width:600px){
      header {
        flex-direction: column;
        text-align: center;
      }
      nav a {
        display: block;
        margin: 5px 0;
      }
    }
  </style>
</head>
<body>

  <header>
    <img src="images/logo.png" alt="Logo" class="logo">
    <nav>
      <a href="#home">Home</a>
      <a href="#songs">Songs</a>
      <a href="#about">About</a>
    </nav>
  </header>

  <main>
    <!-- Home Section -->
    <section id="home" class="section">
      <h1>স্বাগতম Capacity Studio-তে</h1>
      <p>আপনার প্রিয় গান এবং ক্রিয়েটিভ ডিজাইন একসাথে এখানে।</p>
    </section>

    <!-- Songs Section -->
    <section id="songs" class="section">
      <h2>আমাদের গান</h2>

      <div class="song-card">
        <span>Song Name 1</span>
        <a href="https://link-to-song1.com" target="_blank">Play</a>
      </div>

      <div class="song-card">
        <span>Song Name 2</span>
        <a href="https://link-to-song2.com" target="_blank">Play</a>
      </div>

      <div class="song-card">
        <span>Song Name 3</span>
        <a href="https://link-to-song3.com" target="_blank">Play</a>
      </div>

      <!-- চাইলে এখানে আরো গান যোগ করতে পারেন -->
    </section>

    <!-- About Section -->
    <section id="about" class="section">
      <h2>আমাদের সম্পর্কে</h2>
      <p>Capacity Studio হলো একটি ক্রিয়েটিভ ডিজিটাল স্টুডিও যেখানে আইডিয়া, ডিজাইন এবং মিউজিক একসাথে কাজ করে।  
      আমরা আপনাকে অফিশিয়াল গান, ডিজাইন এবং ব্র্যান্ডিং সমাধান সরবরাহ করি।</p>
    </section>

  </main>

  <footer>
    <p>© 2026 Capacity Studio</p>
  </footer>

</body>
</html>
