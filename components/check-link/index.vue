<template>
  <form class="container" @submit.prevent>
    <div class="form">
      <input
          v-model="model"
          class="form__input"
          placeholder="http://названиесайта.ru"
          type="text"
      />
      <button class="form_button" @click="clearInput">Проверить</button>
    </div>
    <p style="color: brown">{{ model }}</p>
  </form>
</template>

<script setup lang="ts">
import {ref} from "vue";

let model = ref()


</script>

<style scoped>
.container {
  display: flex;
  margin: 1vh 20vh;
  flex-direction: row;
  justify-content: center;
}

.form {
  width: 90vh;
  height: 60px;
  border-radius: 10px;
  padding: 2em 5em;
  background: linear-gradient(45deg, #f7e394 0%, #f8d2a1 100%);
  display: flex;
}

.form__input {
  border-radius: 0.3em;
  flex-grow: 1;
  outline: none;
  border: none;
  padding-left: 1em;
}

.form__input::placeholder {
  color: #868686;
  font-family: Gilroy;
  font-size: 14px;
  font-weight: 500;
  padding-left: -1em;
}

.form_button {
  width: 25%;
  border-radius: 0.3em;
  background: linear-gradient(93deg, #ffc000 0.24%, #f06966 100%), #c4c4c4;
  border: none;
  color: #fff;
  text-align: center;
  font-family: Gilroy;
  font-size: 16px;
  font-weight: 600;
  transition: background 0.5s ease;
}

.form_button:hover {
  background: #f06966;
}
</style>
