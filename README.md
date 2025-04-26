<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="refresh" content="5; URL='https://allgo.xyz/link/2402/58989294'" />
  <title>Randkowe Przekierowanie...</title>
  <style>
    body {
      background: linear-gradient(to bottom right, #fbc2eb, #a6c1ee);
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      color: #6a1b9a;
      text-align: center;
      padding: 30px 20px;
      margin: 0;
    }
    h1 {
      font-size: 2.5em;
      margin-bottom: 0.5em;
    }
    p {
      font-size: 1.1em;
      margin: 10px 0;
    }
    a {
      color: #d500f9;
      text-decoration: none;
      font-weight: bold;
    }
    .heart {
      font-size: 4em;
      animation: pulse 1.2s infinite;
      margin-bottom: 20px;
    }
    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.2); }
      100% { transform: scale(1); }
    }
    .gif-container {
      margin: 30px 0;
    }
    .gif-container img {
      max-width: 90%;
      height: auto;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }
    .countdown {
      font-size: 1.3em;
      margin-top: 20px;
      color: #8e24aa;
    }
  </style>
</head>
<body>
  <div class="heart">💖</div>
  <h1>Randkowe Przekierowanie...</h1>
  <p>Twoje serce już wie, dokąd zmierzasz... 💌</p>
  
  <div class="gif-container">
    <img src="https://cdn.discordapp.com/attachments/1340057518134792263/1363642302400299288/full.gif?ex=6806c65c&is=680574dc&hm=1b3b5d46915c6b3f92dafb2ce305513074ab09bedbea76c7e7a2d12f3a33d1a2" alt="Randkowy GIF">
  </div>

  <p>Jeśli nie zostaniesz przekierowany automatycznie, <a href="https://allgo.xyz/link/2402/58989294">kliknij tutaj, aby się bliżej poznać</a>.</p>

  <div class="countdown">
    Przekierowanie za <span id="countdown">5</span> sekund...
  </div>

  <script>
    let seconds = 5;
    const countdownElement = document.getElementById('countdown');
    const timer = setInterval(() => {
      seconds--;
      if (seconds > 0) {
        countdownElement.textContent = seconds;
      } else {
        clearInterval(timer);
      }
    }, 1000);
  </script>
</body>
</html>
