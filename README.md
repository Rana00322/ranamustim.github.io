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
    sözlüm seni çok seviyorum çok özledim elini tutmayı sana sarılmayı kokunu çok özledim
    bana ne zaman ihtiyacın olursa ben burdayım aramızda mesafeler olabilir ama biz bunları aşarız
    sende biliyorsun. bazen kavga da etsek kötü de davransan hep yanındayım beni hiç unutma ne yaparsan yap ben her zaman yanındayım senı bir gün bile yalnız bırakmam sende bende hiç gitme olur mu sevgilim...
  </div>

  <script>
    function showMessage() {
      document.getElementById('message').style.display = 'block';
    }
  </script>

</body>
</html>
