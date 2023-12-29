<template>
  <header class="header">
    <div class="wrapper">
      <NuxtLink to="/" class="logo">
        <div class="gc">gc</div>
        <div class="opengraph">opengraph</div>
      </NuxtLink>
      <a href="#" class="login">
        <img
          src="/src/Door-icon.svg"
          alt="Login"
          class="icon-login"
          width="16"
          height="25"
        />
        Войти в аккаунт
      </a>
    </div>
  </header>
</template>

<script setup lang="ts"></script>

<style scoped>
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

.wrapper {
  display: flex;
  align-items: center;
  margin: 0 20vh;
  justify-content: space-between;
}

.logo {
  text-decoration: none;
  font-family: Gilroy;
  font-size: 28px;
  font-weight: 700;
  color: #2e3138;
}

.gc {
  display: inline-block;
}

.opengraph {
  display: inline-block;
  background: linear-gradient(93deg, #ffc000 0.24%, #f06966 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.login {
  position: relative;
  text-decoration: none;
  color: #2e3138;
  font-family: Gilroy;
  font-size: 14px;
  font-weight: 500;
}

.icon-login {
  position: absolute;
  left: -23px;
  top: -5px;
}
</style>
