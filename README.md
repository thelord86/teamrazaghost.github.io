 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>WELCOME BACK RAWAN</title>
  <style>
    body {
      background-color: black;
      color: #00ff00;
      font-family: "Courier New", monospace;
      text-align: center;
      margin: 0;
      padding: 0;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      overflow: hidden;
    }
    h1 {
      font-size: 3em;
      text-shadow: 0 0 10px #00ff00, 0 0 20px #00ff00;
      animation: flicker 1.5s infinite;
    }
    @keyframes flicker {
      0%, 19%, 21%, 23%, 25%, 54%, 56%, 100% {
        opacity: 1;
      }
      20%, 24%, 55% {
        opacity: 0.2;
      }
    }
    .cursor {
      font-weight: bold;
      animation: blink 1s infinite;
    }
    @keyframes blink {
      50% { opacity: 0; }
    }
  </style>
</head>
<body>
  <h1>WELCOME BACK RAWAN<span class="cursor">_</span></h1>
</body>
</html># teamrazaghost.github.io