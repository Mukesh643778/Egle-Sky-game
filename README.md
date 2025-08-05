# 🦅 Egle Sky – The Last Hope of Earth

Welcome to the official repository of **Egle Sky**, a sci-fi action game where you become the ultimate protector of Earth against alien invaders.

🌐 Live Website: [Visit Here](https://mukesh643778.github.io/Egle-Sky-game/)

---

## 📦 Features

- 🎮 **Sci-fi Storyline** – Hindi dialogues, English UI
- 🎬 **Game Trailer** – Full cinematic trailer included
- 📸 **Screenshots Gallery**
- 📱 **Android APK Download**
- 💥 **Filmi Dialogues in Hindi**
- 🛠 **Admin MCP Panel** (with password protection)
- 🎯 Mobile-friendly & Fully responsive design

---

## 📂 Folder Structure

Egle-Sky-game/ │ ├── index.html         # Main website page ├── admin.html         # Admin MCP Panel (password: eglesky123) ├── style.css          # Styling ├── logo.png           # Game Logo ├── trailer.mp4        # Game Trailer Video ├── screenshot1.png    # Game Screenshot ├── screenshot2.png    # Game Screenshot ├── screenshot3.png    # Game Screenshot ├── EgleSky.apk        # Android APK file └── README.md          # Project documentation

---

## 📥 How to Download APK

You can download the game directly from the site:

👉 [Download Egle Sky APK](https://mukesh643778.github.io/Egle-Sky-game/EgleSky.apk)

> Note: Make sure to allow "Install from unknown sources" in your Android settings.

---

## 🔐 Admin Panel

The MCP (Main Control Panel) is accessible at:

👉 `/admin.html`

**Password:** `eglesky123`

### Admin Panel Code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>MCP - Egle Sky Admin Panel</title>
  <link rel="stylesheet" href="style.css" />
  <script>
    var password = prompt("Enter MCP Password:");
    if (password !== "eglesky123") {
      alert("Access Denied");
      window.location.href = "index.html";
    }
  </script>
</head>
<body>
  <header><h1>🛠 Egle Sky MCP (Main Control Panel)</h1></header>
  <main>
    <h2>Manage Content</h2>
    <ul>
      <li><a href="index.html">View Main Website</a></li>
      <li><a href="upload.html">Upload Trailer</a></li>
      <li><a href="screenshots.html">Manage Screenshots</a></li>
      <li><a href="downloads.html">Update Downloads</a></li>
    </ul>
  </main>
  <footer><p>&copy; 2025 Egle Sky MCP Dashboard</p></footer>
</body>
</html>