<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Matt Cadillac | Portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Matt Cadillac</h1>
    <nav>
      <ul>
        <li><a href="#about">About Me</a></li>
        <li><a href="#engineering">Engineering</a></li>
        <li><a href="#music">Music</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="about">
      <h2>About Me</h2>
      <img src="images/profile.jpg" alt="Photo of Matt Cadillac" class="profile-img">
      <p>Hello! I'm Matt Cadillac, a mechanical engineer and music producer passionate about innovative design and sound. This site highlights my work in both fields.</p>
    </section>

    <section id="engineering">
      <h2>Engineering</h2>
      <p>Check out some of my work in mechanical design and prototyping.</p>
      <div class="gallery">
        <model-viewer src="models/design.glb" alt="3D model" auto-rotate camera-controls></model-viewer>
        <img src="images/project1.jpg" alt="Project photo 1">
        <img src="images/project2.jpg" alt="Project photo 2">
      </div>
    </section>

    <section id="music">
      <h2>Music</h2>
      <p>Listen to my latest tracks and watch performances.</p>
      <div class="media">
        <audio controls>
          <source src="audio/track1.mp3" type="audio/mpeg">
          Your browser does not support the audio element.
        </audio>
        <video controls width="480">
          <source src="videos/performance.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
        <img src="images/music1.jpg" alt="Music event">
      </div>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Matt Cadillac</p>
  </footer>

  <!-- For 3D model viewer -->
  <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js"></script>
</body>
</html>
