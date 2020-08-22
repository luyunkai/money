<template>
  <div class="nav-wrapper">
    <div class="content">
      <slot />
    </div>
    <Nav />
  </div>
</template>

<script>
import Nav from "@/components/Nav.vue";
export default {
  components: { Nav },
};
</script>

<style lang='scss' scoped>
.nav-wrapper {
  display: flex;
  border: 1px solid green;
  flex-direction: column;
  height: 100vh;
}
.content {
  border: 1px solid blue;
  flex-grow: 1;
  overflow: auto;
}
</style>