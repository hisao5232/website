---
layout: default
title: Article
---

<style>
.navbar {
  display: flex;
  justify-content: space-around;
  align-items: center;
  padding: 1rem 0;
  background-color: #000;
  font-family: "Segoe UI", "Hiragino Sans", sans-serif;
}
.navbar a {
  text-decoration: none;
  color: #fff;
  font-weight: 600;
  letter-spacing: 0.5px;
  transition: color 0.2s, transform 0.2s;
}
.navbar a:hover {
  color: #00bfff;
  transform: translateY(-2px);
}
.page-container {
  max-width: 900px;
  margin: 2rem auto;
  padding: 0 1rem;
  line-height: 1.8;
  font-size: 1.05rem;
}

/* カード一覧 */
.article-list {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.5rem;
  margin-top: 2rem;
}
.article-card {
  background: #fff;
  border-radius: 12px;
  box-shadow: 0 3px 8px rgba(0,0,0,0.1);
  padding: 1.2rem;
  transition: transform 0.2s, box-shadow 0.2s;
}
.article-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 6px 14px rgba(0,0,0,0.15);
}
.article-card h3 {
  margin-top: 0;
  color: #007acc;
}
.article-card p {
  color: #444;
}
.article-card a {
  text-decoration: none;
  color: #007acc;
  font-weight: 600;
}
.article-card a:hover {
  text-decoration: underline;
}
</style>

<div class="navbar">
  <a href="/">Home</a>
  <a href="/about">About</a>
  <a href="/article">Article</a>
  <a href="/contact">Contact</a>
</div>

<div class="page-container">

# 📝 Article

ここでは、Python・JavaScriptを中心にした  
**業務効率化、Webアプリ開発、スクレイピング** に関する記事・学習記録をまとめています。

---

## 📚 学習・制作記事一覧

<div class="article-list">

  <div class="article-card">
    <h3>Pythonで業務自動化スクリプトを作る</h3>
    <p>日々の作業を効率化するための自動化ツール開発手法を紹介。</p>
    <a href="https://zenn.dev/hisao5232/articles/python-automation" target="_blank">▶ 記事を読む（Zenn）</a>
  </div>

  <div class="article-card">
    <h3>Playwrightを使ったスクレイピング</h3>
    <p>ブラウザ自動操作ライブラリPlaywrightを活用したスクレイピング実例。</p>
    <a href="https://zenn.dev/hisao5232/articles/playwright-scraping" target="_blank">▶ 記事を読む（Zenn）</a>
  </div>

  <div class="article-card">
    <h3>Streamlitで作るデータ可視化アプリ</h3>
    <p>データ分析を簡単に共有できるWebアプリをStreamlitで構築。</p>
    <a href="https://zenn.dev/hisao5232/articles/streamlit-dashboard" target="_blank">▶ 記事を読む（Zenn）</a>
  </div>

  <div class="article-card">
    <h3>GitHub Actionsで自動デプロイ</h3>
    <p>Pythonスクリプトやサイトの自動更新をGitHub Actionsで実現。</p>
    <a href="https://zenn.dev/hisao5232/articles/github-actions-deploy" target="_blank">▶ 記事を読む（Zenn）</a>
  </div>

</div>

---

## 🧩 関連リンク

- 📰 [Zenn 記事一覧](https://zenn.dev/hisao5232)  
- 💻 [GitHub リポジトリ](https://github.com/hisao5232)

---

© 2025 Go-out-into-PG-world

</div>
