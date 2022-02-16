<template>
  <section>
    <div class="container">
      <div class="row text-center">
        <div class="col-12">
          <h1 class="header-caption">こんなお悩みありませんか？</h1>
        </div>
      </div>
      <div class="row text-center justify-content-center mt-5">
        <div class="col-12 col-sm-4 col-xl-3">
          <img class="image" src="@/node_modules/froala-design-blocks/src/imgs/icons/layers.svg" alt="">
          <h3 class="row-header">ゲイ仲間を作りたい</h3>
          <p>大人になってから仲間を作るというのは難しいものです。</p>
        </div>
        <div class="col-12 col-sm-4 col-xl-3">
          <img class="image" src="@/node_modules/froala-design-blocks/src/imgs/icons/layers.svg" alt="">
          <h3 class="row-header">本を読めるようになりたい</h3>
          <p>「本を読めるようになってみたい」「仕事で本を読まなくちゃ」でも、一人だと気力が続かなくて…。</p>
        </div>
        <div class="col-12 col-sm-4 col-xl-3">
          <img class="image" src="@/node_modules/froala-design-blocks/src/imgs/icons/layers.svg" alt="">
          <h3 class="row-header">会話する場が欲しい</h3>
          <p>ゆっくり誰かと会話したい。自分の考えを誰かに聞いて欲しい。</p>
        </div>
      </div>
    </div>
  </section>

</template>

<script>
    export default {
        name: "FdbBlock9"
    }
</script>

<style scoped lang="scss">
.container {
  margin: 30px auto 0;
}

.row-header {
  font-weight: bold;;
  font-size: 20px;
}
.header-caption {
  font-size: 30px;
  margin-bottom: -24px;
}

.image {
  width: 150px;
}
</style>
