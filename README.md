# Tinh-yeu-athu
<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <title>Không gian tình yêu dành cho Athư</title>
  <style>
    body {
      background: linear-gradient(to right, #ffdde1, #ee9ca7);
      font-family: 'Segoe UI', sans-serif;
      text-align: center;
      color: #fff;
      overflow: hidden;
      margin: 0;
    }
    h1 {
      margin-top: 50px;
      font-size: 2.5em;
      text-shadow: 2px 2px #f06292;
    }
    .love-note {
      font-size: 1.3em;
      margin: 20px auto;
      width: 80%;
      max-width: 600px;
      background-color: rgba(255, 255, 255, 0.15);
      border-radius: 20px;
      padding: 20px;
      box-shadow: 0 0 10px rgba(255, 255, 255, 0.3);
    }
    .heart { font-family: monospace; white-space: pre; font-size: 10px; line-height: 10px; margin-top: 30px; }
    .heart-float {
      position: absolute;
      animation: float 8s infinite;
      color: #ffb6c1;
      font-size: 20px;
    }
    @keyframes float {
      0% { transform: translateY(100vh) scale(1); opacity: 1; }
      100% { transform: translateY(-10vh) scale(1.5); opacity: 0; }
    }
  </style>
</head>
<body>
  <h1>Gửi đến Athư 💖</h1>
  <div class="love-note">Em là món quà ngọt ngào nhất mà vũ trụ đã dành cho anh.</div>
  <div class="love-note">Từng ánh mắt, từng nụ cười của em đều là ánh sáng soi rọi trái tim anh.</div>
  <div class="love-note">Anh biết, dù có ngôn từ nào cũng không đủ diễn tả tình yêu anh dành cho em.</div>
  <div class="love-note">Chỉ mong mỗi ngày bên em sẽ là một phép màu dịu dàng.</div>
  <div class="heart">
    ❤❤❤❤❤❤<br>❤❤❤❤❤❤❤❤<br>❤❤❤❤❤❤❤❤❤❤<br>❤❤❤❤❤❤❤❤❤❤❤❤<br>❤❤❤❤❤❤❤❤❤❤<br>❤❤❤❤❤❤❤❤<br>❤❤❤❤❤❤<br>❤❤❤❤<br>❤❤❤<br>❤❤<br>❤
  </div>
  <script>
    function createHeart() {
      const heart = document.createElement("div");
      heart.className = "heart-float";
      heart.innerText = "❤";
      heart.style.left = Math.random() * 100 + "vw";
      heart.style.animationDuration = (Math.random() * 3 + 4) + "s";
      document.body.appendChild(heart);
      setTimeout(() => heart.remove(), 8000);
    }
    setInterval(createHeart, 300);
  </script>
</body>
</html>
