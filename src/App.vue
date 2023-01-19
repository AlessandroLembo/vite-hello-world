<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
export default {
  data() {
    return {
    }
  },
  components: {
    AppTitle,
    AppHero
  }
}
</script>

<template>
  <div class="first-app">
    <app-title></app-title>
    <app-hero></app-hero>
  </div>
</template>

<style>
.first-app {
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>