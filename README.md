<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Babe Check 💬</title>
  <style>
    body {
      font-family: sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      background: #fef6f9;
      margin: 0;
      text-align: center;
    }
    h1 { font-size: 2em; margin-bottom: 20px; }
    button {
      margin: 10px;
      padding: 15px 30px;
      font-size: 1.2em;
      border: none;
      border-radius: 12px;
      cursor: pointer;
      transition: transform 0.2s;
    }
    .yes { background: #ff5e7e; color: white; }
    .no { background: #ccc; }
    button:hover { transform: scale(1.05); }
  </style>
</head>
<body>
  <h1>Can I call you <em>babe</em>?</h1>
  <button class="yes" onclick="answer(true)">Yes</button>
  <button class="no" onclick="answer(false)">No</button>
  <script>
    function answer(isYes) {
      alert(isYes ? "You're my girlfriend ❤️" : "Maybe someday 🙂");
    }
  </script>
</body>
</html>
