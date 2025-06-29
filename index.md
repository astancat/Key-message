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
      font-family: 'Retro Computer', monospace;
      background: white;
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
    }

    .container {
      max-width: 640px;
      padding: 0 1rem;
      user-select: none;
      width: 100%;
    }

    h1 {
      font-size: 3rem;
      font-weight: 900;
      color: black;
      text-transform: uppercase;
      animation: glitch 1.5s infinite;
      letter-spacing: 0.15em;
      margin-bottom: 1.5rem;
    }

    p {
      font-size: 1.5rem; /* Increased size */
      font-weight: 900;   /* Extra bold */
      letter-spacing: 0.03em;
      line-height: 1.6;
      color: black;
      font-family: Arial, sans-serif;
      margin: 0 auto;
      text-align: center;
      width: 100%;
      max-width: 640px;
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
      h1 { font-size: 2rem; }
      p { font-size: 1.2rem; } /* Still bigger on mobile */
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Thank You For Your Payment!</h1>
    <p>
      You will receive your premium key shortly at the Gmail address linked to your PayPal account.
    </p>
  </div>
</body>
</html>
