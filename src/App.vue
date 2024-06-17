<template>
  <div class="main-container">
    <div class="main">
      <h1>My Website</h1>
      <h2>Kitty Crafts</h2>
    </div>
    <TheFooter />
  </div>
</template>

<script setup>
import TheFooter from "./views/TheFooter.vue";
</script>

<style lang="scss" scoped>
.main {
  height: 100vh;
  h1,
  h2 {
    font-size: 98px;
    color: #111;
  }
}
.main-container {
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}
</style>
