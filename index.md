<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Payment Success</title>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      background-color: #000;
      height: 100%;
      font-family: Arial, sans-serif;
      color: white;
      overflow: hidden;
    }

    .message {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      font-size: 1.6rem;
      text-align: center;
      font-weight: bold;
      z-index: 1;
      max-width: 90%;
    }

    #particles-js {
      position: absolute;
      width: 100%;
      height: 100%;
      z-index: 0;
    }
  </style>
</head>
<body>
  <div class="message">
    Thank you for your payment!<br>
    You will receive your premium key shortly at the Gmail address linked to your PayPal account.
  </div>

  <div id="particles-js"></div>

  <!-- Particle.js Script -->
  <script src="https://cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js"></script>
  <script>
    particlesJS("particles-js", {
      "particles": {
        "number": {
          "value": 60,
          "density": { "enable": true, "value_area": 800 }
        },
        "color": { "value": "#ffffff" },
        "shape": { "type": "circle" },
        "opacity": {
          "value": 0.5,
          "random": true
        },
        "size": {
          "value": 3,
          "random": true
        },
        "move": {
          "enable": true,
          "speed": 1,
          "direction": "none",
          "random": false,
          "out_mode": "out"
        }
      },
      "interactivity": {
        "detect_on": "canvas",
        "events": {
          "onhover": { "enable": true, "mode": "repulse" }
        },
        "modes": {
          "repulse": { "distance": 80 }
        }
      },
      "retina_detect": true
    });
  </script>
</body>
</html>
