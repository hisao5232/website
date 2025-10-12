---
layout: default
title: Home
---

<!-- ナビゲーションバー -->
<nav style="
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background: rgba(0, 0, 0, 0.6);
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0.5rem 1rem; /* 左右のパディングを狭くして文字を中央寄りに */
  z-index: 10;
  backdrop-filter: blur(6px);
">

  <!-- ロゴ画像 -->
  <div>
    <a href="/">
      <img src="/assets/images/logo.png" alt="Logo" style="height: 40px;">
    </a>
  </div>

  <!-- ナビ項目 -->
  <div style="display: flex; gap: 1.5rem; font-size: 1.1em;">
    <a href="/" style="color: white; text-decoration: none;">Home</a>
    <a href="/articles" style="color: white; text-decoration: none;">Articles</a>
    <a href="/about" style="color: white; text-decoration: none;">About</a>
    <a href="/contact" style="color: white; text-decoration: none;">Contact</a>
  </div>
</nav>

<!-- フルスクリーン・レスポンシブ ヒーローイメージ -->
<style>
  .hero-container {
    position: relative;
    width: 100vw;
    height: 100vh;
    margin: 0;
    padding: 0;
    overflow: hidden;
  }

  .hero-container img {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: center;
  }

  / Slateの中央寄せを打ち消す /
  .page {
    max-width: none;
    padding: 0;
    margin: 0;
  }
</style>

<div class="hero-container">
  <img src="/assets/images/hero.jpg" alt="Hero Image">
</div>

---


## 最近のトピック

- WireGuard VPN の設定方法
- 金融商品の比較と活用法

---

<!-- フッター -->
<footer style="
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 2rem 0;
  background: #f2f2f2;
  gap: 1rem;
">

  <img src="/assets/images/profile.png" alt="Profile" style="
    width: 50px;
    height: 50px;
    object-fit: cover; /* border-radius削除で丸くならない */
  ">

  <div>
    <p>サイト運営者: hisao</p>
    <p>Python × 副業 × 自動化</p>
  </div>
</footer>
