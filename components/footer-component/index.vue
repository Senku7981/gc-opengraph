<template>
  <footer>
    <div class="wrapper">
      <div class="footer-text-item">
        Карточка - инструмент создания карточек предприятия
      </div>
      <div class="footer-text-item">
        Инструмент <img src="/src/g.svg" alt="company" width="13" height="22" />
      </div>
    </div>
  </footer>
</template>
<script setup lang="ts"></script>

<style scoped>
.wrapper {
  display: flex;
  align-items: center;
  margin: 0 20vh;
  justify-content: space-between;
}

.footer-text-item {
  color: #ccc;
  font-family: Gilroy;
  font-size: 13px;
  font-weight: 500;
  line-height: 13px; /* 100% */
}
</style>
