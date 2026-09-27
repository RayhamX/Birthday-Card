<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Happy Birthday, Jyoti 🎉</title>
  <style>
    body {
      font-family: 'Comic Sans MS', cursive, sans-serif;
      background: #fef6e4;
      color: #333;
      text-align: center;
      margin: 0;
      padding: 20px;
    }
    h1 {
      color: #ff6f61;
    }
    .section {
      margin: 30px auto;
      padding: 20px;
      max-width: 600px;
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    .button {
      display: inline-block;
      margin-top: 15px;
      padding: 10px 20px;
      background: #ff6f61;
      color: #fff;
      border-radius: 5px;
      text-decoration: none;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <h1>🎂 Happy Birthday, Jyoti 🎂</h1>

  <div class="section">
    <h2>The Note</h2>
    <p>Dear Jyoti, you’re officially 17! 🎉  
    Thanks for being the best friend ever—annoying, hilarious, and irreplaceable.  
    May your day be full of cake, laughter, and zero homework!</p>
  </div>

  <div class="section">
    <h2>Technical Data</h2>
    <ul style="list-style:none; padding:0;">
      <li><strong>Model:</strong> Jyoti 2009 Edition</li>
      <li><strong>Age:</strong> <span id="age"></span> years</li>
      <li><strong>Annoyance Output:</strong> Unregulated ⚡</li>
      <li><strong>Warranty:</strong> Unlimited, bestie-backed 💖</li>
    </ul>
  </div>

  <div class="section">
    <h2>The Card</h2>
    <p>This webpage doubles as your birthday card!  
    Click below to save it as a PDF and stick it on your cake box 🎁</p>
    <button class="button" onclick="window.print()">Download Card</button>
  </div>

  <script>
    // Simple age calculator
    const birthYear = 2009;
    const currentYear = new Date().getFullYear();
    document.getElementById('age').textContent = currentYear - birthYear;
  </script>
</body>
</html>
