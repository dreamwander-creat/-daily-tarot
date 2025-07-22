<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8">
  <title>夢行漫遊｜三張塔羅牌占卜</title>
  <style>
    body {
      background: linear-gradient(to bottom, #f6f1ec, #fdfaf6);
      font-family: "Noto Serif TC", serif;
      text-align: center;
      padding: 50px;
    }
    h1 {
      color: #333;
      font-size: 2.2em;
      margin-bottom: 10px;
    }
    .card-container {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 30px;
    }
    .tarot-card {
      width: 180px;
      height: 280px;
      perspective: 1000px;
    }
    .card-inner {
      position: relative;
      width: 100%;
      height: 100%;
      transform-style: preserve-3d;
      transition: transform 0.8s;
      cursor: pointer;
    }
    .tarot-card.flipped .card-inner {
      transform: rotateY(180deg);
    }
    .card-front, .card-back {
      position: absolute;
      width: 100%;
      height: 100%;
      backface-visibility: hidden;
    }
    .card-front {
      transform: rotateY(180deg);
    }
    .card-back {
      background: url('https://upload.wikimedia.org/wikipedia/commons/thumb/3/3d/RWS_Tarot_Back.jpg/240px-RWS_Tarot_Back.jpg') no-repeat center center;
      background-size: cover;
    }
    .meaning {
      margin-top: 12px;
      font-size: 1em;
      color: #444;
      max-width: 180px;
      margin-left: auto;
      margin-right: auto;
      min-height: 40px;
    }
    button {
      background: #5e4b3c;
      color: white;
      border: none;
      padding: 12px 24px;
      font-size: 16px;
      cursor: pointer;
      border-radius: 6px;
      box-shadow: 2px 2px 8px rgba(0,0,0,0.15);
      transition: background 0.3s, transform 0.2s;
    }
    button:hover {
      background: #7b614d;
      transform: translateY(-2px);
    }
  </style>
</head>
<body>
  <h1>夢行漫遊｜三張塔羅牌占卜</h1>
  <p>點擊按鈕，讓宇宙告訴你過去、現在與未來的訊息。</p>
  <button onclick="drawThreeCards()">抽三張牌</button>

  <div class="card-container" id="card-container"></div>

  <script>
    const cards = [...]; // 請插入你的完整 78 張牌卡資料陣列

    function drawThreeCards() {
      const shuffled = [...cards].sort(() => 0.5 - Math.random());
      const selected = shuffled.slice(0, 3);

      const container = document.getElementById("card-container");
      container.innerHTML = "";

      selected.forEach((card) => {
        const cardWrapper = document.createElement("div");
        cardWrapper.className = "tarot-card";

        const cardInner = document.createElement("div");
        cardInner.className = "card-inner";

        const front = document.createElement("div");
        front.className = "card-front";
        const frontImg = document.createElement("img");
        frontImg.src = card.image;
        frontImg.alt = card.name;
        front.appendChild(frontImg);

        const back = document.createElement("div");
        back.className = "card-back";

        const meaning = document.createElement("div");
        meaning.className = "meaning";
        meaning.innerText = "";

        cardInner.appendChild(front);
        cardInner.appendChild(back);
        cardWrapper.appendChild(cardInner);
        cardWrapper.appendChild(meaning);

        cardWrapper.addEventListener("click", () => {
          cardWrapper.classList.toggle("flipped");
          meaning.innerText = `${card.name}｜${card.meaning}`;
        });

        container.appendChild(cardWrapper);
      });
    }
  </script>
</body>
</html>
