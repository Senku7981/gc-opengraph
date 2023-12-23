<template>
  <AppHeader/>
  <WelcomeText/>
  <NuxtPage/>
  <AppFooter/>
</template>

<script>
import AppFooter from "./components/footer-component/index.vue";
import AppHeader from "./components/header-component/index.vue";
import WelcomeText from "./components/welcome-text/index.vue";

export default {
  components: {WelcomeText, AppFooter, AppHeader}
}

</script>

<style>

</style>

