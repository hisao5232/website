---
layout: default
title: Go-out-into-PG-world
---

<!-- 🔧 カスタムスタイル -->
<style>
  /* ナビゲーションバー */
  .navbar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    background-color: #000;
    color: #fff;
    padding: 0.5rem 1rem;
  }

  .navbar img {
    height: 40px;
  }

  .nav-links {
    display: flex;
    gap: 1rem;
  }

  .nav-links a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
  }

  .nav-links a:hover {
    text-decoration: underline;
  }

  /* ヒーローイメージ */
  .hero {
    width: 100vw;
    height: 100vh;
    overflow: hidden;
  }

  .hero img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  /* カードレイアウト */
  .card-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 1.5rem;
    padding: 2rem;
  }

  .card {
    border: 1px solid #ddd;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    background-color: #fff;
    transition: transform 0.2s ease;
  }

  .card:hover {
    transform: translateY(-4px);
  }

  .card img {
    width: 100%;
    height: 180px;
    object-fit: cover;
  }

  .card-content {
    padding: 1rem;
  }

  .card-title {
    font-size: 1.2rem;
    font-weight: bold;
    margin-bottom: 0.5rem;
  }

  .card-description {
    font-size: 0.95rem;
    color: #555;
  }

  /* フッター */
  .footer {
    text-align: center;
    padding: 2rem;
    background-color: #f5f5f5;
  }

  .footer img {
    width: 120px;
    border-radius: 50%;
  }
</style>

<!-- 🧭 ナビゲーションバー -->
<div class="navbar">
  <img src="/assets/images/logo.png" alt="Logo">
  <div class="nav-links">
    <a href="/">Home</a>
    <a href="/about">About</a>
    <a href="/articles">Articles</a>
    <a href="/contact">Contact</a>
  </div>
</div>

<!-- 🌄 ヒーローイメージ -->
<div class="hero">
  <img src="/assets/images/hero.jpg" alt="Hero Image">
</div>

<!-- 📚 カード形式の記事 -->
<div class="card-grid">
  <div class="card">
    <img src="/assets/images/article1.jpg" alt="記事1">
    <div class="card-content">
      <div class="card-title">記事タイトル1</div>
      <div class="card-description">これは記事1の概要です。もっと読むにはリンクを追加できます。</div>
    </div>
  </div>

  <div class="card">
    <img src="/assets/images/article2.jpg" alt="記事2">
    <div class="card-content">
      <div class="card-title">記事タイトル2</div>
      <div class="card-description">これは記事2の概要です。内容の一部をここに表示します。</div>
    </div>
  </div>
</div>

<!-- 👤 フッター（プロフィール画像） -->
<div class="footer">
  <img src="/assets/images/profile.png" alt="プロフィール画像">
</div>
