<!DOCTYPE html>
<html>
<head>
  <title>Valentine 💖</title>
  <style>
    body {
      background: pink;
      height: 100vh;
      margin: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      font-family: Arial;
      overflow: hidden;
    }
    h1 { text-align: center; }
    button {
      font-size: 22px;
      padding: 12px 30px;
      border-radius: 10px;
      border: none;
    }
    #yes { background: #ff4d6d; color: white; }
    #no {
      background: #555;
      color: white;
      position: absolute;
    }
  </style>
</head>

<body>
  <h1>💖 Shuttumani, will you be my Valentine? 💖</h1>
  <button id="yes" onclick="yes()">YES 💘</button>
  <button id="no">NO 😅</button>

  <script>
    const noBtn = document.getElementById("no");
    setInterval(() => {
      noBtn.style.left = Math.random() * (window.innerWidth - 100) + "px";
      noBtn.style.top = Math.random() * (window.innerHeight - 50) + "px";
    }, 500);

    function yes() {
      document.body.innerHTML =
        "<h1>🎉 YAY SHUTTUMANI!!! 🎉</h1><p>You made me so happy ❤️</p>";
    }
  </script>
</body>
</html>
