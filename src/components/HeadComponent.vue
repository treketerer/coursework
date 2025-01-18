<template>
  <div class="head">
    <div class="logo">
      <img alt="Vue logo" class="logo_image" src="@/assets/logo.svg" width="125" height="125" />
      <div class="text">TRAVEL PLANE</div>
    </div>

    <div class="menu">
      <h3>МЕНЮ</h3>
      <h3 class="midleH">ПЛАН</h3>
      <h3 class="midleH">АККАУНТ</h3>
      <h3 class="midleH">ПОКУПКА</h3>
    </div>
  </div>
</template>

<style scoped>
.head {
  backdrop-filter: blur(5px);

  position: fixed; /* Фиксируем хедер на верху страницы */
  top: 0; /* Располагаем хедер в верхней части страницы */
  left: 2.25%;

  width: 95%; /* Растягиваем хедер на всю ширину страницы */
  height: 10%;
  border-bottom: 1px rgb(222, 222, 222) solid;
  /*background-color: #fff;  Фон хедера */

  z-index: 1000; /* Убедитесь, что хедер находится поверх других элементов */
  /* box-shadow: 0 2px 4px rgba(0, 0, 0, 0.3); Тень для хедера */

  display: flex;
  align-items: center;
}

h3 {
  font-weight: 500;
  font-family: century-gothic, sans-serif;
  transition: 0.2s;
  cursor: pointer;
}

h3:hover {
  transform: scale(1.1);
}

.menu {
  width: 60%;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  margin-left: auto;
  margin-right: auto;
  text-align: center;

  border-width: 0 2px 0 2px; /* top right bottom left */
  border-style: solid;
  border-color: rgb(222, 222, 222);
}

.midleH {
  border-left: 2px rgb(222, 222, 222) solid;
}

.logo {
  display: flex;
  align-items: center;
  margin: 0;
  padding-left: 2%;
  /* width: 30%; */
  height: 100%;
}
img {
  height: 70%;
  width: auto;
}

.text {
  font-size: 25px;
  font-weight: 500;
  padding: 5px;
  padding-bottom: 10px;
}
</style>
