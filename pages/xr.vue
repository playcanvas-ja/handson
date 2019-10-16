
<template>
  <div class="container">
    <h2 class="subtitle">AR / VRについて</h2>
        <span style="font-size:0.9rem">貸し出し可能なOculus QuestとOculus Goが２台の合計４台ございます</span>

    <p>PlayCanvasでARとVRの開発をする際に便利なリンク集</p>

    <p>AR</p>
    
    <ul>
      <li>
        <a target="_blank" href="https://playcanvas.com/the8thwall">THE8THWALL</a>
        <span>
          マーカーを使用したARとマーカーを使用しないARのプロジェクトです。
          このプロジェクトをフォークすることで簡単に開発をすることができます。
        </span>
      </li>
    </ul>
    <p>VR</p>
    <ul>
      <li>
        <a
          target="_blank"
          href="https://developer.playcanvas.com/ja/tutorials/webvr-lab/"
        >PlayCanvas VR Labs</a>
        <span>PlayCanvasのこのプロジェクトをフォークすることで、簡単にVRの開発ができます。</span>
      </li>
      <li>
        <a
          target="_blank"
          href="https://qiita.com/murati111/items/7d24bc2f970bcc961c26"
        >PlayCanvasでWebVRで使える視線選択について</a>
        <span>PlayCanvasを使用してVR開発をする方法が紹介されています。</span>
      </li>
      <li>
        <a
          target="_blank"
          href="https://qiita.com/yushimatenjin/items/5803ac4cc65339f69737"
        >Google Chromeから接続しているOculus Questのコントローラーの情報を取得する。</a>
        <span>WebでOculusの開発をする方法が紹介されています。</span>
      </li>
      <li>
        <a
          target="_blank"
          href="https://qiita.com/yushimatenjin/items/344d86b3d193e0a88567"
        >【iOS13】新しくなったWebVRの使い方 [PlayCanvas]</a>
      </li>
    </ul>
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
  flex-direction: column;
  font-size: 1.5rem;
  padding: 4rem;
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
  display: block;
}
ul span {
  font-size: 1rem;
  padding: 1rem;
  display: block;
  text-align: left;
}
p{
  font-size:.2.5rem;
  font-weight: 700;
}
ul li {
  text-decoration: none;
  list-style: none;
}
.links {
  padding-top: 15px;
}
</style>
