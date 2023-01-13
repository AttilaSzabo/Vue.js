<script setup>
    import welcome from './components/welcome.vue'
</script>

<template>
  <header></header>
  <main>
   <welcome />
  </main>
  <footer></footer>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Sofia+Sans:wght@100;200;300;400;500;600;700;800&display=swap');
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
