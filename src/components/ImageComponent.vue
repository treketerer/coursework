<script setup lang="ts"></script>

<template>
  <hello>
    <main>
      <h1>Легкое планирование путешествий</h1>
      <!-- <buttonBase msg="Начать планировать" /> -->
    </main>

    <div class="overflow">
      <img alt="Vue logo" class="logo" src="@/assets/orig.webp" />
    </div>
  </hello>
</template>

<style scoped>
hello {
  z-index: -1;
  background-color: red;
}

main {
  max-width: 800px;
  font-size: 48px;
  font-weight: 700;
  line-height: 55px;
  letter-spacing: -0.02em;
  text-align: center;
  color: #fff;
  z-index: 1;
  margin: 0 auto;

  margin-top: 11%;
}

h1 {
  font-size: 65px;
  font-weight: 700;
}

.overflow {
  position: absolute;
  top: 0;
  left: 0;
  overflow: hidden;
  width: 100%;
  height: 65%;

  z-index: -1000; /* Убедитесь, что хедер находится поверх других элементов */
}
img {
  width: 100%;
  filter: brightness(85%);
}
</style>
