---
layout: default
---

<!-- Menü başlatılıyor -->
<style>
  /* Menü kapsayıcısını ortalamak için */
  nav {
    text-align: center; /* Menü kapsayıcıyı ortalar */
  }

  /* Menü elemanlarını yatay sıraya dizmek için */
  nav ul {
    display: inline-block;
    padding: 0;
    margin: 0;
  }

  /* Menü elemanları */
  nav ul li {
    display: inline;
    margin-right: 20px; /* Menü elemanları arasında boşluk bırak */
  }

  /* Menü linklerinin stilini düzenlemek için */
  nav ul li a {
    text-decoration: none;
    font-size: 18px;
    color: #333; /* Linklerin rengi */
  }

  /* Üzerine gelindiğinde linkin rengi */
  nav ul li a:hover {
    color: #007acc; /* Mavi renk hover stili */
  }
</style>

<nav>
  <ul>
    <li><a href="{{ site.baseurl }}/projects">Projects</a></li>
    <li><a href="{{ site.baseurl }}/documentation">Documentation</a></li>
    <li><a href="{{ site.baseurl }}/swift">Swift</a></li>
    <li><a href="{{ site.baseurl }}/about">About</a></li>
  </ul>
</nav>

<!-- İçerik Başlangıcı -->
<div>
  <h1>Welcome to My GitHub Page</h1>
  <p>Click the menu items above to navigate to different sections.</p>
</div>
