<template>
  <div class="home">
    <HomeHeader />
    <div class="main">
      <div class="menus">
        <HomeMenus />
      </div>
      <div class="pages">
        <div class="content">

        </div>
        <div class="footer">
          <HomeFooter />
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import HomeHeader from './components/header'
import HomeMenus from './components/menus'
import HomeFooter from './components/footer.vue'
</script>

<style scoped>
  .main {
    display: flex;
  }
</style>