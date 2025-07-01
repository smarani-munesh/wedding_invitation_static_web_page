# wedding_invitation_static_web_page
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Wedding Invitation</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', cursive;
      background: linear-gradient(to bottom, #ffe4e1, #fff0f5);
      color: #444;
      overflow-x: hidden;
    }

    .header {
      background: url('https://i.imgur.com/JhY8W4U.png') no-repeat center top;
      background-size: contain;
      padding: 100px 20px 50px;
      text-align: center;
    }

    .header h1 {
      font-size: 3em;
      color: #c2185b;
      animation: fadeInDown 2s ease;
    }

    .header p {
      font-size: 1.3em;
      color: #6a1b9a;
      animation: fadeIn 3s ease;
    }

    .flowers {
      width: 300px;
      animation: float 4s ease-in-out infinite;
      margin: 2px auto;
    }

    .section {
      padding: 2px 2px;
      text-align: center;
      animation: fadeIn 2s ease;
    }

    .section h2 {
      color: #d81b60;
      margin-bottom: 20px;
      font-size: 2em;
    }

    .section p {
      font-size: 1.1em;
      line-height: 1.7em;
      color: #333;
    }

    .rings {
      width: 300px;
      margin-top: 30px;
      animation: zoomIn 3s ease;
    }

    .footer {
      background: #f8bbd0;
      color: #6a1b9a;
      padding: 20px;
      text-align: center;
      font-size: 1em;
    }
    .wedding-names {
  font-family: 'Great Vibes', cursive;
  font-size: 2.8em;
  text-align: center;
  margin-top: 20px;
  animation: fadeZoom 3s ease-in-out;
}

.name1 {
  color: #e5641e; /* Rose pink */
  text-shadow: 2px 2px 5px #ffc1e3;
  animation: floatIn 2s ease-in-out;
}

.weds {
  margin: 0 15px;
  color: #6a1b9a; /* Purple */
  font-size: 0.7em;
  font-style: italic;
  letter-spacing: 2px;
  animation: glow 2s infinite alternate;
}

.name2 {
  color: #e5641e; /* Sky blue */
  text-shadow: 2px 2px 5px #a3d4ff;
  animation: floatIn 2s ease-in-out;
}

/* Animations */
@keyframes fadeZoom {
  from {
    opacity: 0;
    transform: scale(0.7);
  }
  to {
    opacity: 1;
    transform: scale(1);
  }
}

@keyframes glow {
  0% {
    text-shadow: 0 0 5px #ff80ab, 0 0 10px #e91e63;
  }
  100% {
    text-shadow: 0 0 15px #ff4081, 0 0 25px #e91e63;
  }
}

@keyframes floatIn {
  0% {
    transform: translateY(-20px);
    opacity: 0;
  }
  100% {
    transform: translateY(0);
    opacity: 1;
  }
}


    /* Animations */
    @keyframes fadeInDown {
      from { opacity: 0; transform: translateY(-30px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes zoomIn {
      0% { transform: scale(0.8); opacity: 0; }
      100% { transform: scale(1); opacity: 1; }
    }

    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }

    /* Responsive */
    @media (max-width: 600px) {
      .header h1 {
        font-size: 2em;
      }
    }
  </style>
</head>
<body>

  <div class="header">
    <img src="flowers.jpg" class="flowers" alt="flowers">
    <h1>You’re Invited!</h1>
<h2 class="wedding-names">
  <span class="name1">Nandhini</span>
  <span class="weds">weds</span>
  <span class="name2">Srinivas</span>
</h2>

  </div>

  <div class="section">
    <h2>💒 Join Us</h2>
    <p>
      With love in our hearts, we invite you to celebrate the<br>
      union of our souls on<br><br>
      <strong>Sunday, 10th August 2025</strong><br>
      at <strong>Golden Blossom Resort, Hyderabad</strong><br><br>
      Ceremony starts at <strong>6:00 PM</strong>
    </p>
    <img src="rings.jpg" class="rings" alt="wedding rings">
  </div>

  <div class="section" style="background: #fce4ec;">
    <h2>📝 RSVP</h2>
    <p>
      Please let us know by July 25th.<br>
      Contact: <strong>+91 98765 743210</strong> or <strong>aarav.ananya@gmail.com</strong>
    </p>
  </div>

  <div class="footer">
    With love, <br> Ananya & Aarav ❤️
  </div>

</body>
</html>
