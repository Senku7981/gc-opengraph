<template>
  <AppHeader/>
  <WelcomeText/>
  <NuxtPage/>
  <AppFooter/>
</template>

<script>
import AppFooter from "./components/AppFooter/index.vue";
import AppHeader from "./components/AppHeader/index.vue";
import WelcomeText from "./components/WelcomeText/index.vue";

export default {
  components: {WelcomeText, AppFooter, AppHeader}
}

</script>

<style>

</style>

