<template>
  <nav>
    <router-link to="/money">
    记账</router-link>
    <router-link to="/labels">标签</router-link>
    <router-link to="/statistics">统计</router-link>
  </nav>
</template>

<script lang = 'ts'>
import x from "@/assets/iocns/label.svg";
console.log(x)
export default {};
</script>

<style lang = 'scss' scoped>
nav {
  border: 1px solid red;
}
</style>