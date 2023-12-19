<template>
  <AppHeader/>
  <NuxtPage />
  <AppFooter/>
</template>

<script>
import AppFooter from "./components/AppFooter/index.vue";
import AppHeader from "./components/AppHeader/index.vue";

export default {
  components: {AppFooter,AppHeader}
}

</script>

