<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Payment Confirmation</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    @import url('https://fonts.cdnfonts.com/css/retro-computer-personal-use');

    body {
      font-family: 'Retro Computer', monospace, monospace;
      background: white;
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      overflow: hidden;
      text-align: center;
    }

    .container {
      max-width: 640px;
      user-select: none;
      padding: 0 1rem; /* Moved here */
    }

    h1 {
      font-size: 3rem;
      font-weight: 900;
      position: relative;
      color: black;
      letter-spacing: 0.15em;
      line-height: 1.1;
      margin-bottom: 1.5rem;
      text-transform: uppercase;
      animation: glitch 1.5s infinite;
    }

    p {
      font-size: 1.25rem;
      font-weight: 700;
      letter-spacing: 0.03em;
      line-height: 1.4;
      color: black;
      max-width: 90%;
      margin: 0 auto;
      font-family: Arial, sans-serif;
    }

    @keyframes glitch {
      0%   { text-shadow: 2px 0 red, -2px 0 blue; }
      20%  { text-shadow: -2px -2px red, 2px 2px blue; }
      40%  { text-shadow: 2px 2px red, -2px -2px blue; }
      60%  { text-shadow: -2px 2px red, 2px -2px blue; }
      80%  { text-shadow: 2px -2px red, -2px 2px blue; }
      100% { text-shadow: 2px 0 red, -2px 0 blue; }
    }

    @media (max-width: 480px) {
      h1 {
        font-size: 2rem;
      }
      p {
        font-size: 1rem;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Thank You For Your Payment!</h1>
    <p>You will receive your premium key shortly at the Gmail address linked to your PayPal account.</p>
  </div>
</body>
</html>
