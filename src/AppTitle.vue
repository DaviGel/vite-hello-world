<script>
import AppHero from './components/AppHero.vue';
export default {
  data() {
    return {
      title: 'La mia prima app con Vite!',
    };
  },
  components: {
    AppHero,
  },
};
</script>

<template>
  <header>
    <h1>{{ title }}</h1>
    <AppHero />
  </header>
</template>

<style scoped></style>
