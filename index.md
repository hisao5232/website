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
<div style="
  position: relative;
  width: 100%;
  height: 100vh;
  overflow: hidden;
  margin: 0; /* 余白をリセット */
">
  <img src="/assets/images/hero.jpg"
       alt="Hero Image"
       style="
         position: absolute;
         top: 0;
         left: 0;
         width: 100%;
         height: 100%;
         object-fit: cover;
         object-position: center;
       ">
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

  <img src="/assets/images/profile.jpg" alt="Profile" style="
    width: 50px;
    height: 50px;
    object-fit: cover; /* border-radius削除で丸くならない */
  ">

  <div>
    <p>サイト運営者: Your Name</p>
    <p>Python × 副業 × 自動化</p>
  </div>
</footer>
