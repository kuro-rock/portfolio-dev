<template>
  <main class="l-main">
    <div class="bl-top">
      <div class="bl-hero" style="flex:1;">
        <img class="bl-hero-img" src="~/assets/images/hero.png" />
      </div>
      <article class="bl-article">
        <section class="bl-section">
          <h2 class="el_heading2">About</h2>
          <p>
            デザイン出身のエンジニア。
          </p>
          <p>
            近年はリーダー職として開発チームの方針策定やメンバー教育にも力を入れています。
          </p>
          <footer>
            <nuxt-link to="./about" class="el-link-more">もっと見る</nuxt-link>
          </footer>
        </section>
        <section class="bl-section">
          <h2>Skill</h2>
          <p>
            Web系フロントエンド領域を中心として、デザイン・バックエンドまで幅広い業務を経験。
          </p>
          <footer>
            <nuxt-link to="./skill" class="el-link-more">もっと見る</nuxt-link>
          </footer>
        </section>
        <section class="bl-section">
          <h2>Work</h2>
          <p>
            仕事をするうえで大事にしているのは、個人プレーに走るのではなくチームとして取り組むことです。
          </p>
          <footer>
            <nuxt-link to="./work" class="el-link-more">もっと見る</nuxt-link>
          </footer>
        </section>
      </article>
    </div>
  </main>
</template>

<script>
export default {}
</script>

<style></style>
