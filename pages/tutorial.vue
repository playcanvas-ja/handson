<template>
  <div class="container">
    <div>
      <h2 class="subtitle">チュートリアルについて</h2>

      <div class="tutorials">
        <div class="3d">
          <span class="name">3Dハンズオン</span>
          <a
            href="https://support.playcanvas.jp/hc/ja/articles/224163827-%E3%83%81%E3%83%A5%E3%83%BC%E3%83%88%E3%83%AA%E3%82%A2%E3%83%AB-PlayCanvas%E3%81%AE%E5%9F%BA%E6%9C%AC%E6%93%8D%E4%BD%9C-1-7"
          >チュートリアル - PlayCanvasの基本操作 -</a>
          <iframe src="https://playcanv.as/p/ONIG8RhE/?overlay=false"></iframe>
        </div>
        <div class="2d">
          <span class="name">2Dハンズオン</span>
          <a
            href="https://support.playcanvas.jp/hc/ja/articles/360001824487-%E3%83%81%E3%83%A5%E3%83%BC%E3%83%88%E3%83%AA%E3%82%A2%E3%83%AB-2D%E3%82%A2%E3%82%AF%E3%82%B7%E3%83%A7%E3%83%B3%E3%82%B2%E3%83%BC%E3%83%A0-1-8"
          >チュートリアル -2Dアクションゲーム- 1/8</a>

          <iframe src="https://playcanv.as/index/3WkPrlrc"></iframe>
        </div>
        <div class="web">
          <span class="name">ウェブサイト</span>
          <a
            href="https://support.playcanvas.jp/hc/ja/sections/360004631354-%E3%83%81%E3%83%A5%E3%83%BC%E3%83%88%E3%83%AA%E3%82%A2%E3%83%AB-3D%E7%A9%BA%E9%96%93%E3%82%92%E4%BD%BF%E3%81%A3%E3%81%9F%E7%B0%A1%E5%8D%98web%E3%82%B5%E3%82%A4%E3%83%88"
          >チュートリアル - 3D空間を使った簡単webサイト</a>

          <iframe src="https://playcanv.as/p/uQN2hNcm/"></iframe>
        </div>
        <div class="coin">
          <span class="name">コインドーザー</span>
          <a href="https://playcanvas-cedec.gitbook.io/coin-dozer/">コインドーザーの作成</a>

          <iframe src="https://yushimatenjin.github.io"></iframe>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.tutorials .name {
  font-weight: 300;
  font-size: 1.5rem;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.tutorials iframe {
  width: 500px;
  height: 300px;
}
.tutorials {
  display: grid;
  grid-template-columns: 40vw 40vw;
  grid-gap: 3rem;
}
.links {
  padding-top: 15px;
}
iframe{
  border: none;
  padding: 1rem;
  margin: 1rem;
}
</style>
