<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Let’s Travel by Vijay</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body, html {
      height: 100%;
      font-family: 'Poppins', sans-serif;
      color: white;
    }
    .video-bg {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      object-fit: cover;
      z-index: -1;
    }
    .overlay {
      background-color: rgba(0, 0, 0, 0.6);
      position: absolute;
      width: 100%;
      height: 100%;
      z-index: 0;
    }
    .content {
      position: relative;
      z-index: 1;
      text-align: center;
      padding: 80px 20px;
    }
    h1 {
      font-size: 3em;
      margin-bottom: 10px;
    }
    p {
      font-size: 1.2em;
      color: #ddd;
      margin-bottom: 30px;
    }
    .cta a {
      background: #e52d27;
      color: white;
      padding: 15px 30px;
      font-size: 1.2em;
      text-decoration: none;
      border-radius: 8px;
      transition: background 0.3s ease;
    }
    .cta a:hover {
      background: #ff5f6d;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: rgba(0,0,0,0.8);
      font-size: 0.9em;
      color: #bbb;
      position: relative;
      z-index: 1;
    }
  </style>
</head>
<body>

  <!-- Background Video -->
  <video autoplay muted loop playsinline class="video-bg">
    <source src="https://www.videvo.net/videvo_files/converted/2016_07/preview/Mountain_Snow_Scenery.mp439163.webm" type="video/webm">
    Your browser does not support the video tag.
  </video>

  <div class="overlay"></div>

  <div class="content">
    <h1>Let’s Travel by Vijay</h1>
    <p>Travel the world in 60 seconds – Experience the beauty of places like Sar Pass and beyond!</p>
    <div class="cta">
      <a href="https://www.youtube.com/@LetsTravel-by_Vijay" target="_blank">Subscribe on YouTube</a>
    </div>
  </div>

  <footer>
    © 2025 Let’s Travel by Vijay. All rights reserved.
  </footer>

</body>
</html>
