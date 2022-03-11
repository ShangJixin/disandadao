<template>
  <div id="app">
    <nav-box></nav-box>
    <landing-box></landing-box>
    <story-box></story-box>
    <why-choose></why-choose>
    <player-say></player-say>
    <donate-box></donate-box>
    <footer-front></footer-front>
    <footer-box></footer-box>
    <mojang-box></mojang-box>
  </div>
</template>

<script>
import navBox from './components/nav-box.vue'
import landingBox from './components/landing-box.vue'
import storyBox from './components/story-box.vue'
import whyChoose from './components/why-choose.vue'
import playerSay from './components/player-say.vue'
import donateBox from './components/donate.vue'
import footerFront from './components/foot-front-top.vue'
import footerBox from './components/footer.vue'
import mojangBox from './components/mojang-box.vue'

export default {
  name: 'App',
  components: {
    navBox, landingBox, storyBox, whyChoose, playerSay, donateBox, footerFront, footerBox, mojangBox
  }
}
</script>

<style lang="less">
.sdblue {
    color: #637599;
}
/* 样式格式化*/

body,
ol,
ul,
h1,
h2,
h3,
h4,
h5,
h6,
p,
th,
td,
dl,
dd,
form,
fieldset,
legend,
input,
textarea,
select,
div,
figure {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: -apple-system,BlinkMacSystemFont,Helvetica Neue,PingFang SC,Microsoft YaHei,Source Han Sans SC,Noto Sans CJK SC,WenQuanYi Micro Hei,sans-serif;
}

::selection {
    background: #d3d3d3;
    color: inherit;
}
.container {
    _width:375px;
    max-width: 1000px;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
}

@media screen and (min-width: 2560px) {
    .container {
        max-width: 70vw;
    }
}

h2.title {
    margin: 40px 0 0 0;
    font-size: 25px;
    text-align: center;
    color: #333;
    text-transform: uppercase;
}

.subtitle {
    text-align: center;
    font-size: 16px;
    margin-bottom: 30px;
    letter-spacing: 3px;
    color: #666;
}

p.text {
    color: #555;
    font-size: 14px;
    letter-spacing: 2px;
    text-align: center;
    margin: 20px 0;
}
</style>
