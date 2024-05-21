<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <router-view></router-view>

</template>

<style scoped>
/* 自定义顶部加载 Loading 颜色 */
#nprogress .bar {
  background: #409eff!important;
}
</style>
