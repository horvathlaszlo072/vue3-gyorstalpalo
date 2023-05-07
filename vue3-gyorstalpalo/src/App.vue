<script setup>
  import Welcome from './components/Welcome.vue'</script>
<template>
  <header></header>
  <main>
    <Welcome />
  </main>
  <footer></footer>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Quicksand:wght@300&family=Rubik:wght@400;500;600;700&display=swap");
:root {
  --blue: #576ca8;
  --inputBg: #444b67;
  --cr1: #c94277;
  --cr2: #1b998b;
  --cr3: #ffd046;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background-color: #302b27;
  color: #fff;
}
#app {
  font-family: Quicksand, sans-serif;
}

main {
  padding: 0.5rem;
}

input {
  border: none;
  border-radius: 0.5rem;
  background-color: var(--inputBg);
  padding: 0.5rem;
}

.df {
  display: flex;
  gap: 1rem;
}
</style>
