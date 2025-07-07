<!DOCTYPE html>
<html lang="az">
<head>
  <meta charset="UTF-8">
  <title>Canım Sevgilimə ❤️</title>
  <style>
    body {
      background: linear-gradient(to right, #ffe6f0, #ffe0cc);
      font-family: 'Segoe UI', sans-serif;
      text-align: center;
      padding: 50px;
      color: #333;
    }
    h1 {
      color: #d63384;
      font-size: 36px;
    }
    #mesaj {
      font-size: 22px;
      margin: 20px;
    }
    button {
      background-color: #ff66a3;
      color: white;
      border: none;
      padding: 12px 25px;
      font-size: 16px;
      border-radius: 8px;
      cursor: pointer;
      transition: background-color 0.3s;
    }
    button:hover {
      background-color: #e05591;
    }
    .footer {
      margin-top: 60px;
      font-size: 14px;
      color: #666;
      opacity: 0.8;
    }
  </style>
</head>
<body>
  <h1>Gülüm ❤️ Aişəm</h1>
  <p id="mesaj">Sən mənim hər şeyimsən.</p>
  <button onclick="mesajiDeyis()">Bir mesaj da oxu 💌</button>

  <script>
    const mesajlar = [
      "Sənin gülüşün bütün günümü işıqlandırır.",
      "Səni tanıdığım üçün şanslıyam.",
      "Hər anımda sən varsansa, hər şey gözəldir.",
      "Sənin yanımda olduğunu bilmək hər şeyə dəyər.",
      "Səni düşünmək belə gülüş gətirir üzümə.",
      "Səninlə keçən hər gün bir hədiyyədir.",
      "Ən gözəl xatirələrimiz hələ gələcəkdədir ❤️"
    ];

    function mesajiDeyis() {
      const rastgele = Math.floor(Math.random() * mesajlar.length);
      document.getElementById("mesaj").innerText = mesajlar[rastgele];
    }
  </script>

  <div class="footer">
    Hazırlandı sevgilin 💘 – Sənin Fəridin 🫶
  </div>
  <audio autoplay loop id="sevgi-mahnisi">
  <source src="cox_axtardim.mp3" type="audio/mpeg">
  Sənin brauzerin musiqi çalmağı dəstəkləmir.
</audio>

<script>
  document.getElementById("sevgi-mahnisi").volume = 0.4; // Səsi yumşaq etdim
</script>
</body>
</html>
