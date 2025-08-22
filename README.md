<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Happy Birthday Hoa - Sayu Theme</title>
  <style>
    body {
      margin: 0;
      font-family: 'Trebuchet MS', sans-serif;
      background: linear-gradient(135deg, #7ac9a3, #e2f3e4);
      color: #2c3e50;
      text-align: center;
      padding: 40px;
    }

    h1 {
      font-size: 3em;
      margin-top: 20px;
      color: #3e8d74;
      letter-spacing: 2px;
      text-shadow: 1px 1px 8px #fff;
    }
    .sayu-images {
      display: flex;
      justify-content: center;
      gap: 30px;
      margin-top: 40px;
      flex-wrap: wrap;
    }
    .sayu-images img {
      border-radius: 25px;
      box-shadow: 0 4px 30px rgba(62,141,116,0.15);
      width: 220px;
      height: 220px;
      object-fit: cover;
      border: 3px solid #75b897;
      background: #fff;
      transition: transform .2s;
    }
    .sayu-images img:hover {
      transform: scale(1.08) rotate(-2deg);
      border-color: #e2f3e4;
    }
    .caption {
      margin-top: 24px;
      font-size: 1.3em;
      color: #489b7b;
      font-weight: bold;
      letter-spacing: 1px;
    }
    @media (max-width: 700px) {
      .sayu-images {
        flex-direction: column;
        align-items: center;
      }
      .sayu-images img {
        width: 70vw;
        height: 70vw;
        max-width: 300px;
        max-height: 300px;
      }
    }
  </style>
</head>
<body>
  <h1>Happy Birthday Hoa!</h1>
  <div class="caption">Sayu brings you birthday wishes and lots of fun!</div>
  <div class="sayu-images">
    <!-- Image 1 -->
    <img src="img1.jpg" alt="Sayu eating noodles">
    <!-- Image 2 -->
    <img src="img2.jpg" alt="Sayu sleepy">
    <!-- Image 3 -->
    <img src="img3.jpg" alt="Sayu in box">
  </div>
  <div class="caption" style="margin-top:32px;">
    May your day be as cute and cozy as Sayu! 🎉
  </div>
</body>
</html>  
