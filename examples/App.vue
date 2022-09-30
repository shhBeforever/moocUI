<template>
  <div id="app">
    <Demo />
    <m-card
      imgSrc="01.png"
      summary="深度学习入门：初探Google新宠JAX"
    />
    <br>
    <m-card
      imgSrc="02.png"
      summary="SpringBoot2.x进阶 基于云服务器的中间件整合与应用"
    >
      <template v-slot:footer>
        <div class="footer">
          <div class="level">初阶 · 83人报名</div>
          <div class="price">免费</div>
        </div>
      </template>
    </m-card>
    <br>
    <m-card
      imgSrc="03.png"
      width="370"
      imgHeight="90"
    >
      软件测试岗位认知及职业发展
      <template v-slot:footer>
        <div class="footer-spring">
          <div class="level">零基础 · 553人报名</div>
          <div class="level">免费</div>
        </div>
      </template>
    </m-card>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.footer{
  padding: 0 8px;
  font-size:12px;
  text-align: left;
}
.level{
  color:#9199A1;
  margin-bottom:8px;
}
.price{
  color:#F01414;
}
.footer-spring{
  display: flex;
  justify-content: space-between;
  padding:0 8px;
  font-size:12px;
}
</style>
