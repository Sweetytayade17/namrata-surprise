# namrata-surprise
https://media.tenor.com/-H2gDMEiiRUAAAAi/cute-hug-love.gif<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Namrata Surprise 💌</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #ffe6f0;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
      overflow: hidden;
    }
    .envelope {
      background: #fff0f5;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      text-align: center;
      transition: all 0.5s ease;
    }
    .heart {
      display: none;
      font-size: 40px;
      cursor: pointer;
    }
    .message-page {
      display: none;
      background: white;
      color: #444;
      padding: 20px;
      border-radius: 20px;
      max-width: 90vw;
      max-height: 80vh;
      overflow-y: auto;
      text-align: left;
      position: relative;
    }
    .arrow {
      position: absolute;
      bottom: 10px;
      right: 10px;
      font-size: 24px;
      cursor: pointer;
      color: pink;
    }
    .next-content {
      display: none;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 20px;
    }
    .next-content img {
      width: 200px;
      border-radius: 16px;
      margin-bottom: 20px;
    }
  </style>
</head>
<body>
  <div class="envelope" id="envelope">
    <p>Click the envelope 💌</p>
  </div>  <div class="heart" id="heart">❤️</div>  <div class="message-page" id="message">
    <h2>Namrata..</h2>
    <p>Tu majhya sathi fkt bestfriend nahi… tu ek emotion ahes.<br>
    Tujha ek msg majha purn mood change krtoo. Tu majhi favorite notification ahes hoti…<br>
    Ani nehmiii rahnr mala tujhy sobtt — life time rhych ahee.<br>
    Tujhy majhy madhe khup veda misunderstanding zali... pn we end up at fixing everything.<br>
    I know long distance ahe... mushkil ahe... pn tujyakdun long distance hot ny... mjhy kdun pn ny hot...<br>
    <strong>We love each other very muchh🧿</strong><br><br>
    Aapan ekach college la jaun hasnar… ekach bench var basnar… ekach exam sathi stress ghener… aani ekach divshi degree gheun ekatra photo ghetnar.<br>
    Aapli friendship distance ne kami nahi zali… pan ti time ni azun strong zali.<br>
    Tu 1ashi person ahes jin te srv mjhy sathi kel je ek mulga ky konti mulgi pn ny kela.<br>
    Tu mjhy support system ahes, tu majhi strength ahes.<br>
    Tu mjhyy life chi ek best beautiful ani most fav part ahes. Tu mjhii priority banlii ahe.<br>
    Mi tula khup khi bolii i knoww... I'm sorry for that all.<br>
    Pn mi tula khrch kdhichh ny sodun janr… kdhich tula ya natta lay akhru svas prynt japnar mii shappath ni.🤞🏻<br><br>
    <em>I Love you so much bala🫀😭🧿💋</em><br>♾️
    </p>
    <div class="arrow" onclick="goToNext()">➡️</div>
  </div>  <div class="next-content" id="next">
    <img src="https://media.tenor.com/-H2gDMEiiRUAAAAi/cute-hug-love.gif" alt="hug animation">
    <p><strong>Tu fkt majhi ahess ani majhich rhshil ♾️🤞🏻</strong></p>
    <div class="arrow" onclick="goToKiss()">➡️</div>
  </div>  <div class="next-content" id="kiss">
    <img src="https://media.tenor.com/I6gZsOE1rEsAAAAi/love-couple-kiss.gif" alt="kiss animation">
    <p><strong>I’ll always be here, tujha sobat. Always. 💋</strong></p>
    <div class="arrow" onclick="goToMemories()">➡️</div>
  </div>  <div class="next-content" id="memories">
    <p><strong>Our cutest memories</strong></p>
    <img src="https://via.placeholder.com/200x200.png?text=Photo+1" alt="memory 1">
    <img src="https://via.placeholder.com/200x200.png?text=Photo+2" alt="memory 2">
    <div class="arrow" onclick="goToFinal()">➡️</div>
  </div>  <div class="next-content" id="final">
    <h2>Love you 💗</h2>
    <p>Miss you already 🥹</p>
    <img src="https://media.tenor.com/XhSXqfMYRG8AAAAi/anime-sad.gif" alt="crying">
  </div>  <script>
    const envelope = document.getElementById('envelope');
    const heart = document.getElementById('heart');
    const message = document.getElementById('message');
    const next = document.getElementById('next');
    const kiss = document.getElementById('kiss');
    const memories = document.getElementById('memories');
    const final = document.getElementById('final');

    envelope.onclick = () => {
      envelope.style.display = 'none';
      heart.style.display = 'block';
    };

    heart.onclick = () => {
      heart.style.display = 'none';
      message.style.display = 'block';
    };

    function goToNext() {
      message.style.display = 'none';
      next.style.display = 'flex';
    }

    function goToKiss() {
      next.style.display = 'none';
      kiss.style.display = 'flex';
    }

    function goToMemories() {
      kiss.style.display = 'none';
      memories.style.display = 'flex';
    }

    function goToFinal() {
      memories.style.display = 'none';
      final.style.display = 'flex';
    }
  </script></body>
</html>
