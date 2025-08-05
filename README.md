<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <meta name="description" content="Egle Sky – Futuristic Hindi Sci-Fi Action Game"/>
  <title>Egle Sky – Official Game Website</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background-color: #0b0c10;
  color: #ffffff;
}

header {
  background: #1f2833;
  padding: 10px 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  height: 60px;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
  padding: 0;
  margin: 0;
}

nav a {
  color: #66fcf1;
  text-decoration: none;
  font-weight: bold;
}

#hero {
  background: url('hero.jpg') no-repeat center center/cover;
  padding: 100px 20px;
  text-align: center;
}

.hero-btn {
  background: #45a29e;
  color: #0b0c10;
  padding: 12px 24px;
  text-decoration: none;
  font-size: 18px;
  font-weight: bold;
  border-radius: 5px;
}

section {
  padding: 40px 20px;
  text-align: center;
}

video {
  width: 90%;
  max-width: 720px;
  border: 4px solid #66fcf1;
  border-radius: 10px;
}

.gallery img {
  width: 30%;
  margin: 10px;
  border-radius: 10px;
  border: 2px solid #45a29e;
}

.download-btn {
  display: inline-block;
  background: #66fcf1;
  color: #0b0c10;
  padding: 14px 30px;
  font-size: 18px;
  font-weight: bold;
  border-radius: 5px;
  text-decoration: none;
}

form input, form textarea {
  width: 90%;
  max-width: 400px;
  padding: 12px;
  margin: 10px auto;
  display: block;
  border: none;
  border-radius: 5px;
}

form input[type="submit"] {
  background: #1f2833;
  color: #66fcf1;
  font-weight: bold;
  cursor: pointer;
}

footer {
  background: #1f2833;
  color: #c5c6c7;
  padding: 20px;
  text-align: center;
}
  <header>
    <img src="logo.png" alt="Egle Sky Logo" class="logo"/>
    <nav>
      <ul>
        <li><a href="#trailer">Trailer</a></li>
        <li><a href="#screenshots">Screenshots</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#download">Download</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="hero">
    <h1>Welcome to Egle Sky</h1>
    <p>The ultimate sci-fi eagle action game in Hindi!</p>
    <a href="#download" class="hero-btn">Download Now</a>
  </section>

  <section id="trailer">
    <h2>🎬 Game Trailer</h2>
    <video controls>
      <source src="trailer.mp4" type="video/mp4" />
      Your browser does not support video playback.
    </video>
  </section>

  <section id="screenshots">
    <h2>🖼️ Game Screenshots</h2>
    <div class="gallery">
      <img src="screenshot1.jpg" alt="Screenshot 1" />
      <img src="screenshot2.jpg" alt="Screenshot 2" />
      <img src="screenshot3.jpg" alt="Screenshot 3" />
    </div>
  </section>

  <section id="about">
    <h2>📄 About the Game</h2>
    <p>
      Egle Sky is a high-octane Hindi sci-fi game where you fly as an eagle warrior 
      and battle alien invaders. Featuring thrilling action, immersive storyline, and stunning visuals.
    </p>
  </section>

  <section id="download">
    <h2>📥 Download Egle Sky</h2>
    <a href="https://your-download-link.com" class="download-btn">Download APK</a>
  </section>

  <section id="contact">
    <h2>📧 Contact Us</h2>
    <form action="mailto:mkdhandhal4@gmail.com" method="post" enctype="text/plain">
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your mkdhandhal4@gmail.com " required />
      <textarea name="message" rows="4" placeholder="Your Message" required></textarea>
      <input type="submit" value="Send Message" />
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Egle Sky Game. All rights reserved.</p>
  </footer>

</body>
</html>

  
    

  
