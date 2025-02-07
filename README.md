<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Omkar's Personal Page</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: #f5f5f5;
      color: #333;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      margin: 0;
    }
    .container {
      text-align: center;
      max-width: 600px;
      padding: 20px;
      background-color: white;
      border-radius: 15px;
      box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.1);
    }
    h1 {
      color: #4a90e2;
    }
    ul {
      list-style-type: none;
      padding: 0;
    }
    li {
      margin: 10px 0;
    }
    .icon-container {
      margin: 20px;
    }
    .icon-container i {
      font-size: 40px;
      color: #4a90e2;
      margin: 10px;
      transition: transform 0.3s;
    }
    .icon-container i:hover {
      transform: scale(1.2);
    }
    .spotify-section {
      background-color: #1db954;
      color: white;
      padding: 15px;
      border-radius: 8px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>👋 Hi, I'm Omkar</h1>
    <ul>
      <li>👀 I’m interested in myself</li>
      <li>🌱 I’m currently learning everything!</li>
      <li>📬 Reach me at: <a href="mailto:your.email@example.com">your.email@example.com</a></li>
    </ul>

    <h2>Languages I Code In:</h2>
    <div class="icon-container">
      <i class="fab fa-html5"></i>
      <i class="fab fa-css3-alt"></i>
      <i class="fab fa-js"></i>
      <i class="fab fa-python"></i>
    </div>

    <div class="spotify-section">
      <h3>🎧 Spotify Playing</h3>
      <p>Currently listening to: <span id="song-title">No song playing</span></p>
    </div>
  </div>

  <script>
    // Mock Spotify Functionality
    document.getElementById('song-title').textContent = 'Despacito - Luis Fonsi';
  </script>
</body>
</html>

### Spotify Playing 🎧
[<img src="https://omkar-spotify-now-playing.vercel.app/api/spotify-playing" alt="Spotify Now Playing" width="350" />](https://omkar-spotify-now-playing.vercel.app/api/spotify-playing)


<!---
omkar-s2/omkar-s2 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
