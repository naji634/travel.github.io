# 再度HTMLテンプレートを生成して保存（セッションリセットにより再生成）
html_template = """
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
    <section class="city-section">
      <h2>Sapporo</h2>
      <div class="spot">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4d/Sapporo_Clock_Tower_2018.jpg/800px-Sapporo_Clock_Tower_2018.jpg" alt="Sapporo Clock Tower">
        <h3 data-lang-group="spot1-title">
          <span class="lang-text lang-active" data-lang="en">Sapporo Clock Tower</span>
          <span class="lang-text" data-lang="ja">札幌時計台</span>
          <span class="lang-text" data-lang="zh">札幌钟楼</span>
          <span class="lang-text" data-lang="fr">Tour de l'horloge de Sapporo</span>
          <span class="lang-text" data-lang="ru">Башня с часами Саппоро</span>
        </h3>
        <p data-lang-group="spot1-desc">
          <span class="lang-text lang-active" data-lang="en">A historic clock tower built in 1878, symbolizing the city of Sapporo.</span>
          <span class="lang-text" data-lang="ja">1878年に建てられた歴史的な時計台で、札幌の象徴です。</span>
          <span class="lang-text" data-lang="zh">建于1878年的历史钟楼，是札幌的象征。</span>
          <span class="lang-text" data-lang="fr">Une tour de l'horloge historique construite en 1878, symbole de Sapporo.</span>
          <span class="lang-text" data-lang="ru">Историческая башня с часами, построенная в 1878 году, символ Саппоро.</span>
        </p>
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3240.1460912420575!2d141.35445127609378!3d43.062095371136196!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x5f0b2985c81c2231%3A0x88f71dbf83e5b45b!2z5LuZ6YO95pWZ5bqX5qCh5Lit5aSu5rC455Sw6ZaA!5e0!3m2!1sja!2sjp!4v1713000000000!5m2!1sja!2sjp"></iframe>
      </div>
    </section>
  </main>
  <footer class="footer">
    <p>&copy; 2025 Hokkaido Travel Guide</p>
  </footer>
  <script>
    const selector = document.getElementById('language-selector');
    selector.addEventListener('change', (e) => {
      const lang = e.target.value;
      document.querySelectorAll('.lang-text').forEach(el => {
        el.classList.remove('lang-active');
        if (el.dataset.lang === lang) {
          el.classList.add('lang-active');
        }
      });
    });
  </script>
</body>
</html>
"""

# 保存パス
html_path = "/mnt/data/explore-hokkaido-multilang.html"

# HTMLファイルとして保存
with open(html_path, "w", encoding="utf-8") as f:
    f.write(html_template)

html_path
