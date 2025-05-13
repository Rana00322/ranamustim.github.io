# ranamustim.github.io 
<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <title>Asker Sözlüm için</title>
  <style>
    body {
      background: #fff;
      text-align: center;
      font-family: 'Arial', sans-serif;
    }
    .envelope {
      width: 200px;
      margin: 100px auto 20px;
      cursor: pointer;
    }
    .message-box {
      display: none;
      width: 80%;
      margin: 0 auto;
      background: #ffe6f0;
      border: 2px dashed #ff4d6d;
      padding: 20px;
      border-radius: 15px;
      font-size: 16px;
      color: #333;
      white-space: pre-line;
    }
  </style>
</head>
<body>

  <h2>Sana özel bir mektubum var</h2>
  <img src="https://em-content.zobj.net/source/apple/354/love-letter_1f48c.png" class="envelope" onclick="showMessage()">

  <div id="message" class="message-box">
    Çok şey istemiyorum, tek yapmak istediğim elini tutmak, sana sarılabilmek.
    Gerçekten sevmek isteyen mesafelere rağmen sever birtanem. İyi ki hayatımdasın.
    Senin gibi birini bulduğum için çok şanslıyım. Seninle gelecek istiyorum...
    (Mektubun tam metnini buraya yazabilirsin.)
  </div>

  <script>
    function showMessage() {
      document.getElementById('message').style.display = 'block';
    }
  </script>

</body>
</html>