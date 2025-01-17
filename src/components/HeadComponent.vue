<template>
  <div class="head">
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />
  </div>
</template>

<style scoped>
.head {
  position: fixed; /* Фиксируем хедер на верху страницы */
  top: 0; /* Располагаем хедер в верхней части страницы */
  left: 0;

  width: 100%; /* Растягиваем хедер на всю ширину страницы */
  height: 20%;
  background-color: #fff; /* Фон хедера */

  z-index: 1000; /* Убедитесь, что хедер находится поверх других элементов */
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Тень для хедера */
}

img {
  line-height: normal;
  display: inline-block;
  vertical-align: middle;
  height: 60%;
}
</style>
