<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Spotify Clone - Usable</title>
  <link rel="stylesheet" href="style.css" />
  <link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet" />
</head>
<body>
  <!-- Sidebar -->
  <div class="sidebar">
    <h1 class="logo">Spotify</h1>
    <ul>
      <li>Home</li>
      <li>Search</li>
      <li>Your Library</li>
    </ul>
  </div>

  <!-- Main Content -->
  <div class="main">
    <div class="top-bar">
      <input type="text" placeholder="Search for songs, artists..." />
    </div>

    <h2>Recently Played</h2>
    <div class="cards">
      <div class="card" onclick="playSong(0)">
        <img src="https://i.scdn.co/image/ab67616d0000b2738e9d1c5ec3c34fc365d3e92a" alt="Album">
        <p>Blinding Lights</p>
      </div>
      <div class="card" onclick="playSong(1)">
        <img src="https://i.scdn.co/image/ab67616d0000b273f2fc218d94f6777ba2db89e1" alt="Album">
        <p>Shape of You</p>
      </div>
      <div class="card" onclick="playSong(2)">
        <img src="https://i.scdn.co/image/ab67616d0000b273b6fd3dc99734f54e5394b4e6" alt="Album">
        <p>On My Way</p>
      </div>
    </div>
  </div>

  <!-- Play Bar -->
  <div class="play-bar">
    <div class="track-info">
      <p class="song" id="song-title">Select a Song</p>
      <p class="artist" id="song-artist">Artist Name</p>
    </div>
    <div class="controls">
      <button onclick="prevSong()">⏮️</button>
      <button onclick="togglePlay()" id="play-pause">▶️</button>
      <button onclick="nextSong()">⏭️</button>
    </div>
  </div>

  <!-- Audio Player -->
  <audio id="audio-player"></audio>

  <script src="script.js"></script>
</body>
</html>
