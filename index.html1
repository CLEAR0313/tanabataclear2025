<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>オンライン短冊イベント🎋</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background: linear-gradient(to bottom, #e0f7fa, #ffffff);
      margin: 0;
      padding: 2rem;
      text-align: center;
    }

    h1 {
      font-size: 2.5rem;
      color: #00695c;
      margin-bottom: 1rem;
    }

    p {
      font-size: 1.2rem;
      color: #555;
    }

    textarea {
      width: 80%;
      height: 100px;
      font-size: 1rem;
      margin-top: 1rem;
      padding: 0.5rem;
      border: 2px solid #ccc;
      border-radius: 10px;
      resize: none;
    }

    button {
      margin-top: 1rem;
      padding: 0.8rem 2rem;
      font-size: 1.1rem;
      color: #fff;
      background-color: #ff8a65;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }

    .tanzaku-area {
      margin-top: 2rem;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1rem;
    }

    .tanzaku {
      background: linear-gradient(to bottom, #fff176, #fff59d);
      border: 2px dashed #fdd835;
      border-radius: 10px;
      width: 200px;
      min-height: 150px;
      padding: 1rem;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      font-size: 1.1rem;
      color: #333;
      white-space: pre-wrap;
    }
  </style>
</head>
<body>
  <h1>🌟七夕オンライン短冊イベント🎋</h1>
  <p>あなたのお願いごとを短冊に書いて飾ろう！</p>

  <textarea id="wish" placeholder="お願いごとを書いてね..."></textarea><br>
  <button onclick="postWish()">短冊をかける ✨</button>

  <div class="tanzaku-area" id="tanzakuList"></div>

  <script>
    function postWish() {
      const wishText = document.getElementById("wish").value.trim();
      if (wishText === "") {
        alert("お願いごとを入力してください！");
        return;
      }

      const tanzaku = document.createElement("div");
      tanzaku.className = "tanzaku";
      tanzaku.textContent = wishText;

      document.getElementById("tanzakuList").appendChild(tanzaku);
      document.getElementById("wish").value = "";
    }
  </script>
</body>
</html>
