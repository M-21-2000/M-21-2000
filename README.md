<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Welcome 👋</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: linear-gradient(135deg, #4facfe, #00f2fe);
      font-family: "Poppins", sans-serif;
      color: white;
      text-align: center;
    }
    .welcome-box {
      background: rgba(0, 0, 0, 0.3);
      padding: 40px;
      border-radius: 20px;
      box-shadow: 0 8px 25px rgba(0,0,0,0.3);
      animation: fadeIn 1.5s ease;
    }
    h1 {
      font-size: 3rem;
      margin-bottom: 10px;
    }
    p {
      font-size: 1.2rem;
    }
    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 25px;
      font-size: 1rem;
      color: #fff;
      background: #ff9800;
      border-radius: 30px;
      text-decoration: none;
      transition: 0.3s;
    }
    .btn:hover {
      background: #e68900;
    }
    @keyframes fadeIn {
      from {opacity: 0; transform: scale(0.9);}
      to {opacity: 1; transform: scale(1);}
    }
  </style>
</head>
<body>
  <div class="welcome-box">
    <h1>👋 Welcome!</h1>
    <p>We’re glad to have you here ✨<br>Enjoy your journey with us 🚀</p>
    <a href="#" class="btn">Get Started</a>
  </div>
</body>
</html>
