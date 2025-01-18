<script setup lang="ts">
import { RouterView } from 'vue-router'

import HeadComponent from './components/HeadComponent.vue'
import BgImageComponent from './components/ImageComponent.vue'
import ItemCardComponent from './components/ItemCardComponent.vue'

// RouterLink,
// import HelloWorld from './components/LeftComponent.vue'
</script>

<template>
  <HeadComponent />
  <BgImageComponent />

  <div class="main">
    <ItemCardComponent />
    <ItemCardComponent />
    <ItemCardComponent />
  </div>
  <!-- <RouterView /> -->
</template>

<style scoped>
.main {
  margin-top: 8%;
}
</style>
