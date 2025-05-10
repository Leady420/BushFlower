<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Landing Page</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #f8f9fa, #e3eaf1);
      color: #333;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      text-align: center;
      padding: 2rem;
    }

    .container {
      max-width: 600px;
      background: white;
      padding: 2rem;
      border-radius: 1rem;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }

    p {
      font-size: 1.2rem;
      color: #666;
      margin-bottom: 2rem;
    }

    .cta-button {
      padding: 0.75rem 1.5rem;
      background-color: #007bff;
      color: white;
      text-decoration: none;
      font-size: 1rem;
      border-radius: 0.5rem;
      transition: background-color 0.3s;
    }

    .cta-button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Welcome to My Website</h1>
    <p>This is a simple landing page built with HTML and CSS.</p>
    <a href="#" class="cta-button">Get Started</a>
  </div>
</body>
</html>
