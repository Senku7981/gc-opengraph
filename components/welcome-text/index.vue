<template>
  <div class="container">
    <h1 class="main-text">Проверь свой <strong class="gradient">Open Graph</strong></h1>
    <p class="description">OpenGraph-карточка, сниппет или превью — это карточка с заголовком, изображением и <br>
      описанием для ссылки. Она автоматически формируется, когда вы делитесь ссылкой в соцсетях.</p>
    <a href="https://ogp.me/" class="more-info">Больше информации об опенграфе</a>
  </div>
</template>

<script>
export default {
  name: "WelcomeText"
}
</script>

<style scoped>
.container {
  display: flex;
  align-items: center;
  margin: 0 20vh;
  flex-direction: column;
}

.main-text {
  margin-top: 10vh;
  color: #222222;
  font-family: Gilroy;
  font-size: 46px;
  font-weight: 600;
  line-height: 56px; /* 121.739% */
}

.gradient {
  background: linear-gradient(93deg, #FFC000 0.24%, #F06966 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.description {
  margin-top: 10px;
  color: #868686;
  font-family: Gilroy;
  font-size: 18px;
  font-weight: 500;
  line-height: 30px; /* 166.667% */
}

.more-info {
  color: #868686;
  font-family: Gilroy;
  font-size: 14px;
  font-weight: 500;
  text-decoration-line: underline;
}

</style>