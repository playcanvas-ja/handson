<template>
  <div class="container">
    <div>
      <h2 class="subtitle">PlayCanvas体験会</h2>

      <h2 class="description">10月24日（木曜日）</h2>
      <div class="links">
        <a-button type="danger" href="/playcanvas">PlayCanvasに登録をする</a-button>
        <a-button type="danger" href="/tutorial">チュートリアル</a-button>
        <a-button type="danger" href="/xr">AR/VR</a-button>
        <a-button
          type="default"
          href="https://developer.playcanvas.com/ja/tutorials/"
          target="_blank"
        >ドキュメント</a-button>
        <a-button
          type="default"
          href="https://developer.playcanvas.com/ja/user-manual/"
          target="_blank"
        >ユーザーマニュアル</a-button>
      </div>
    </div>
  </div>
</template>

<style>
.container {
  margin: 0 auto;
  min-height: 90vh;
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
.description {
  font-weight: 300;
  font-size: 18px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.links {
  padding-top: 15px;
  grid-template-columns: 1fr 1fr;
  display: grid;
  grid-gap: 3rem;
}
</style>
