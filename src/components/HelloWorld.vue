<template>
<header>
  <div class="hello">
    <h1><a href="https://zh.wikipedia.org/wiki/%E7%B6%B2%E8%B7%AF%E8%BF%B7%E5%9B%A0">{{ msg }}</a></h1>
  </div>
</header>
<main>
  <div>
    <div class="row even">
      <img src="https://memeprod.sgp1.digitaloceanspaces.com/user-wtf/1627019326645.jpg"  class="smallpic"/>
      <div class="container">
        <h2>網路迷因（英語：Internet meme）</h2>
        <p>
          是指一夕間在網際網路上被大量宣傳及轉播，一舉成為備受注目的事物，亦可稱為網路爆紅事物（Internet phenomena）[1]。
          由於網際網路缺乏實體界線的特性，各種資訊與概念傳播的速度也因而更快速及廣闊，例如幽默、令人好奇或者與性有關係的事物等等。不過，網路名氣衰退的速度通常與其成長的速度一樣快速。羅馬尼亞流行曲《Dragostea Din Tei》就是一個例子。
          在華人網路界的語境下對「迷因」一詞的詮釋，已與迷因本身內涵有些變化，使得「網路迷因」已經有類似「網路哏」的意思。
        </p>
      </div>
    </div>
    <div class="row odd">
      <img src="https://memeprod.sgp1.digitaloceanspaces.com/user-wtf/1627258257013.jpg"  class="smallpic"/>
      <div class="container">
        <h2>網路迷因（英語：Internet meme）</h2>
        <p>
          是指一夕間在網際網路上被大量宣傳及轉播，一舉成為備受注目的事物，亦可稱為網路爆紅事物（Internet phenomena）[1]。
          由於網際網路缺乏實體界線的特性，各種資訊與概念傳播的速度也因而更快速及廣闊，例如幽默、令人好奇或者與性有關係的事物等等。不過，網路名氣衰退的速度通常與其成長的速度一樣快速。羅馬尼亞流行曲《Dragostea Din Tei》就是一個例子。
          在華人網路界的語境下對「迷因」一詞的詮釋，已與迷因本身內涵有些變化，使得「網路迷因」已經有類似「網路哏」的意思。
        </p>
      </div>
    </div>
     <div class="row even">
      <img src="https://memeprod.sgp1.digitaloceanspaces.com/user-wtf/1627309986339.jpg"  class="smallpic"/>
      <div class="container">
        <h2>描述</h2>
        <p>
          一個網路迷因存在的形式可以是超連結、影片、圖片、音樂和網站等。它可能只是一個單詞或短語，包括故意將單詞或拼寫錯誤，如將「more」寫成「moar」、「me」寫成「meh」、「the」寫成「teh」和「what」寫成「wat」、「that」和「dat」、「for」和「4」、「too」和「圖」、「young」和「樣」、「simple」和「森破」等。這些小動作往往都會透過社群網路、部落格、直郵或新聞來源傳播。它們之中不少與現有的各種網路文化或次文化有關[6]。網路迷因可能會保持不變，亦可能會隨著時間推移變化。網路迷因會因評論、戲仿、或新聞報導而變化。網路迷因可以以很快的速度發展和傳播，有時更加可以在幾天之內散播到世界各地。網路迷因的快速增長和影響力有時會引起了研究人員和業界的關注[7]。在學術方面，研究人員會研究網路迷因如何演變，並預測迷因能否成功在網路上傳播。在商業方面，公司則會利用其普及的特性，使之成為一種廉價的大規模的廣告形式[3]。
        </p>
      </div>
    </div>
    <div class="row odd">
      <img src="https://memes.tw/user-wtf/1627477613464.jpg"  class="smallpic"/>
      <div class="container">
        <h2>種類和用途</h2>
        <p>
          公共關係、廣告和營銷專業人士均將網路迷因定義為一種病毒行銷和游擊營銷方式。而使用迷因來推廣產品或服務的行動則被稱為「迷因營銷」[8]。網路迷因因為通常都符合時尚潮流，所以被視為有成本效益的。
          在市場營銷方面，營銷人員會使用網路迷因製作影片，使大眾對產品或服務產生興趣。2006年電影《飛機上有蛇》便是一例子[9]。營銷人員亦會使用網路爆紅的短語或單詞作宣傳，目的是引起他人注意[10]。
        </p>
      </div>
    </div>
  </div>
    <div>
       <input type="button" onclick = "location.href='#home'" value="回到最上層">
    </div>
</main>
  <footer>
    <h3><a href="https://memes.tw/" target="_blank">Meme 觀看</a></h3>
      Copyright ©2077 Unknow All Rights Reserved.<br>所有圖片和資料皆從<a href="https://memes.tw/">迷因梗圖倉庫</a>以及<a href="https://zh.wikipedia.org/wiki/%E7%B6%B2%E8%B7%AF%E8%BF%B7%E5%9B%A0">維基百科</a>而來.
  </footer>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
p {
  font-family: sans-serif;
  color: white;
}
footer {
  color: grey;
  font-size: .5rem;
  }

div {
  margin: auto;
}
.odd {
  flex-direction: row-reverse;
}
.row {
  display: flex;
}
.input {
  background-color: black;
  border: 1px solid white;
  text-align: center;
  border-radius: 9px;
  color: white;
}

@media only screen and (max-device-width: 768px), only screen and (max-width: 768px) {
  .row {
    display: inherit;
    margin: 0 1rem;
  }
}
</style>
