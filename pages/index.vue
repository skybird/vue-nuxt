<template>
  <div class="wrap">
    <div class="main">
      <comLogo />
      <com-logo></com-logo>
      <h1 class="title">vue-nuxt</h1>
      <h2 class="subtitle">Nuxt.js project</h2>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

// require('~/assets/scss/index.scss')  // 不推荐这种方式，存在闪屏，在页面渲染完成后再加载css
export default {
  components: {
    comLogo: Logo
  }
}
</script>

<style lang="scss">
@import "~assets/scss/index";
</style>
