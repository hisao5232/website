---
layout: default
title: ホーム
---

<!-- ✅ ナビゲーションバー -->
<nav style="
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background: rgba(0, 0, 0, 0.6);
  color: white;
  display: flex;
  justify-content: center;
  gap: 2rem;
  padding: 1rem 0;
  font-size: 1.1em;
  z-index: 10;
  backdrop-filter: blur(6px);
">
  <a href="/" style="color: white; text-decoration: none;">Home</a>
  <a href="/articles" style="color: white; text-decoration: none;">Articles</a>
  <a href="/about" style="color: white; text-decoration: none;">About</a>
  <a href="/contact" style="color: white; text-decoration: none;">Contact</a>
</nav>

<!-- ✅ フルスクリーン・レスポンシブ ヒーローイメージ -->
<div style="
  position: relative;
  width: 100%;
  height: 100vh;
  overflow: hidden;
">
  <img src="/assets/images/hero.jpg"
       alt="Hero Image"
       style="
         width: 100%;
         height: 100%;
         object-fit: cover;
         object-position: center;
       ">
</div>

## 最近のトピック

- WireGuard VPN の設定方法
- 家庭用フィルターのメンテナンス記録
- 金融商品の比較と活用法

---

何か気になることがあれば、[GitHub Issues](https://github.com/yourusername/your-repo/issues) からどうぞ。
