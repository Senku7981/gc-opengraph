<template>
  <div class="container">
    <NuxtLink
      to="/"
      @click="showRout"
      class="link"
      :class="{ active: rout.path === '/' }"
      >Проверить ссылку</NuxtLink
    >
    <NuxtLink
      to="check-image"
      @click="showRout"
      class="link"
      :class="{ active: rout.path === '/check-image' }"
      >Проверить картинку</NuxtLink
    >
  </div>
  <!--  ToDo сделать изминение активной кнопки в зависимости от выбранной страницы-->
</template>

<script setup lang="ts">
import { useRoute } from "nuxt/app";

const rout = useRoute();

function showRout() {
  console.log(rout.path);
  console.log(typeof rout.path);
}
</script>

<style scoped>
.container {
  display: flex;
  margin: 7em 20vh 2em 20vh;
  justify-content: center;
  gap: 2em;

}

.link {
  text-decoration: none;
  box-sizing: border-box;
  border: none;
  background: none;
  color: #868686;
  font-family: Gilroy;
  font-size: 18px;
  font-weight: 600;
  cursor: pointer;
  transition: color 0.3s ease;
}
.link:hover {
  color: #222;
}

.active {
  color: #222222;
  text-decoration: underline;
  text-decoration-color: #ffae1f;
  text-underline-offset: 10px;
}
</style>
