<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Explore Hokkaido</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background: #f4f4f4;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #0066cc;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    select {
      margin-top: 1rem;
      padding: 0.5rem;
    }
    .city-section {
      padding: 2rem;
      background-color: #fff;
      margin: 1rem auto;
      width: 90%;
      max-width: 1000px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .spot {
      margin-bottom: 2rem;
    }
    .spot img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
    }
    .spot iframe {
      width: 100%;
      height: 300px;
      border: none;
      border-radius: 8px;
      margin-top: 1rem;
    }
    .footer {
      background-color: #0066cc;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
    .lang-text {
      display: none;
    }
    .lang-active {
      display: block;
    }
  </style>
</head>
<body>
  <header>
    <h1 data-lang-group="title">
      <span class="lang-text lang-active" data-lang="en">Explore Hokkaido</span>
      <span class="lang-text" data-lang="ja">北海道を探検しよう</span>
      <span class="lang-text" data-lang="zh">探索北海道</span>
      <span class="lang-text" data-lang="fr">Explorez Hokkaidō</span>
      <span class="lang-text" data-lang="ru">Исследуйте Хоккайдо</span>
    </h1>
    <select id="language-selector">
      <option value="en">English</option>
      <option value="ja">日本語</option>
      <option value="zh">中文</option>
      <option value="fr">Français</option>
      <option value="ru">Русский</option>
    </select>
  </header>
  <main>
    <!-- 小樽 -->
    <section class="city-section">
      <h2 data-lang-group="city1-title">
        <span class="lang-text lang-active" data-lang="en">Otaru</span>
        <span class="lang-text" data-lang="ja">小樽</span>
        <span class="lang-text" data-lang="zh">小樽</span>
        <span class="lang-text" data-lang="fr">Otaru</span>
        <span class="lang-text" data-lang="ru">Отару</span>
      </h2>
      <div class="spot">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/39/Otaru_Canal_at_Night.jpg/800px-Otaru_Canal_at_Night.jpg" alt="Otaru Canal">
        <h3 data-lang-group="spot1-title">
          <span class="lang-text lang-active" data-lang="en">Otaru Canal</span>
          <span class="lang-text" data-lang="ja">小樽運河</span>
          <span class="lang-text" data-lang="zh">小樽运河</span>
          <span class="lang-text" data-lang="fr">Canal d'Otaru</span>
          <span class="lang-text" data-lang="ru">Канал в Отару</span>
        </h3>
        <p data-lang-group="spot1-desc">
          <span class="lang-text lang-active" data-lang="en">A scenic canal in Otaru, known for its historical stone warehouses and picturesque views.</span>
          <span class="lang-text" data-lang="ja">小樽の風光明媚な運河で、歴史的な石造倉庫と美しい景色で有名です。</span>
          <span class="lang-text" data-lang="zh">小樽的风景如画的运河，以其历史悠久的石库和美丽的景色闻名。</span>
          <span class="lang-text" data-lang="fr">Un canal pittoresque d'Otaru, connu pour ses entrepôts en pierre historiques et ses vues magnifiques.</span>
          <span class="lang-text" data-lang="ru">Живописный канал в Отару, известный своими историческими каменными складами и красивыми видами.</span>
        </p>
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3240.852879735252!2d135.26479971151667!3d43.19603527496085!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x5f0d5e731c71d54d%3A0x354a93d6cbd88ab5!2sOtaru%20Canal!5e0!3m2!1sja!2sjp!4v1713000000000!5m2!1sja!2sjp"></iframe>
      </div>
      <!-- 小樽他の観光地 -->
    </section>

    <!-- 函館 -->
    <section class="city-section">
      <h2 data-lang-group="city2-title">
        <span class="lang-text lang-active" data-lang="en">Hakodate</span>
        <span class="lang-text" data-lang="ja">函館</span>
        <span class="lang-text" data-lang="zh">函馆</span>
        <span class="lang-text" data-lang="fr">Hakodate</span>
        <span class="lang-text" data-lang="ru">Хакодате</span>
      </h2>
      <div class="spot">
        <img src="https://upload.wikimedia.org/wikipedia/commons/2/2e/Hakodate_Mountain_Sunset.jpg" alt="Hakodate Mountain Sunset">
        <h3 data-lang-group="spot1-title">
          <span class="lang-text lang-active" data-lang="en">Mount Hakodate</span>
          <span class="lang-text" data-lang="ja">函館山</span>
          <span class="lang-text" data-lang="zh">函馆山</span>
          <span class="lang-text" data-lang="fr">Mont Hakodate</span>
          <span class="lang-text" data-lang="ru">Гора Хакодате</span>
        </h3>
        <p data-lang-group="spot1-desc">
          <span class="lang-text lang-active" data-lang="en">Famous for its stunning night view, offering a panoramic look at the city of Hakodate.</span>
          <span class="lang-text" data-lang="ja">函館市を一望できる夜景で有名です。</span>
          <span class="lang-text" data-lang="zh">以壮丽的夜景而闻名，提供函馆市的全景。</span>
          <span class="lang-text" data-lang="fr">Célèbre pour sa vue nocturne époustouflante, offrant une vue panoramique sur la ville de Hakodate.</span>
          <span class="lang-text" data-lang="ru">Известен своим захватывающим ночным видом, который открывает панорамный вид на город Хакодате.</span>
        </p>
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1276.8303546193705!2d140.755128048112!3d41.75622682462648!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x5f78b7cc8709cc23%3A0x3a91a9b6b537ccba!2sMount%20Hakodate!5e0!3m2!1sja!2sjp!4v1713000000000!5m2!1sja!2sjp"></iframe>
      </div>
      <!-- 函館他の観光地 -->
    </section>

    <!-- 釧路 -->
    <section class="city-section">
      <h2 data-lang-group="city3-title">
        <span class="lang-text lang-active" data-lang="en">Kushiro</span>
        <span class="lang-text" data-lang="ja">釧路</span>
        <span class="lang-text" data-lang="zh">钏路</span>
        <span class="lang-text" data-lang="fr">Kushiro</span>
        <span class="lang-text" data-lang="ru">Куширо</span>
      </h2>
      <div class="spot">
        <img src="https://upload.wikimedia.org/wikipedia/commons/9/9c/Kushiro_Shiba_Harbor.jpg" alt="Kushiro Shiba Harbor">
        <h3 data-lang-group="spot1-title">
          <span class="lang-text lang-active" data-lang="en">Kushiro Shiba Harbor</span>
          <span class="lang-text" data-lang="ja">釧路柴港</span>
          <span class="lang-text" data-lang="zh">钏路柴港</span>
          <span class="lang-text" data-lang="fr">Port de Shiba à Kushiro</span>
          <span class="lang-text" data-lang="ru">Порт Шиба в Куширо</span>
        </h3>
        <p data-lang-group="spot1-desc">
          <span class="lang-text lang-active" data-lang="en">Known for its beautiful coastal scenery, ideal for a peaceful walk.</span>
          <span class="lang-text" data-lang="ja">美しい海岸の景色で知られ、静かな散歩に最適です。</span>
          <span class="lang-text" data-lang="zh">以美丽的海岸风光而闻名，非常适合安静的散步。</span>
          <span class="lang-text" data-lang="fr">Connu pour ses magnifiques paysages côtiers, idéal pour une promenade paisible.</span>
          <span class="lang-text" data-lang="ru">Известен своими прекрасными прибрежными пейзажами, идеально подходит для спокойных прогулок.</span>
        </p>
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3240.4130365097125!2d144.37561191968468!3d43.27801413976793!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x5f7b01e6d4efcc0f%3A0x9b7b7959b71ffb9!2sKushiro%20Shiba%20Harbor!5e0!3m2!1sja!2sjp!4v1713000000000!5m2!1sja!2sjp"></iframe>
      </div>
      <!-- 釧路他の観光地 -->
    </section>

    <!-- ニセコ -->
    <section class="city-section">
      <h2 data-lang-group="city4-title">
        <span class="lang-text lang-active" data-lang="en">Niseko</span>
        <span class="lang-text" data-lang="ja">ニセコ</span>
        <span class="lang-text" data-lang="zh">二世古</span>
        <span class="lang-text" data-lang="fr">Niseko</span>
        <span class="lang-text" data-lang="ru">Нисеко</span>
      </h2>
      <div class="spot">
        <img src="https://upload.wikimedia.org/wikipedia/commons/f/f0/Niseko_Mountain.jpg" alt="Niseko Mountain">
        <h3 data-lang-group="spot1-title">
          <span class="lang-text lang-active" data-lang="en">Niseko Mountain</span>
          <span class="lang-text" data-lang="ja">ニセコ山</span>
          <span class="lang-text" data-lang="zh">二世古山</span>
          <span class="lang-text" data-lang="fr">Mont Niseko</span>
          <span class="lang-text" data-lang="ru">Гора Нисеко</span>
        </h3>
        <p data-lang-group="spot1-desc">
          <span class="lang-text lang-active" data-lang="en">Famous for its ski resorts and stunning winter views.</span>
          <span class="lang-text" data-lang="ja">スキーリゾートと素晴らしい冬の景色で有名です。</span>
          <span class="lang-text" data-lang="zh">以滑雪胜地和美丽的冬季景色而闻名。</span>
          <span class="lang-text" data-lang="fr">Célèbre pour ses stations de ski et ses magnifiques vues d'hiver.</span>
          <span class="lang-text" data-lang="ru">Известен своими лыжными курортами и потрясающими зимними пейзажами.</span>
        </p>
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3240.689384284223!2d139.97415155968132!3d42.9302271371338!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x5f7a7a60ec59d13f%3A0x3b0a45e3bc7fc736!2sNiseko%20Mountain!5e0!3m2!1sja!2sjp!4v1713000000000!5m2!1sja!2sjp"></iframe>
      </div>
      <!-- ニセコ他の観光地 -->
    </section>
  </main>
  <footer class="footer">
    <p>&copy; 2025 Explore Hokkaido</p>
  </footer>
  <script>
    document.getElementById('language-selector').addEventListener('change', function(event) {
      const lang = event.target.value;
      const langTexts = document.querySelectorAll('.lang-text');
      langTexts.forEach(text => {
        text.classList.remove('lang-active');
        if (text.dataset.lang === lang) {
          text.classList.add('lang-active');
        }
      });
    });
  </script>
</body>
</html>
