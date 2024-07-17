<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="wrapper">
      <nav>
        <RouterLink to="/">Jogo</RouterLink>
        <RouterLink to="/howtoplay">Como jogar</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>
/* header {
  line-height: 1.5;
  max-height: 100vh;
} */

/* nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
} */

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

header {
  display: flex;
  align-items: center;
  place-items: center;
  padding: 1rem 2rem;
}

.logo {
  margin: 0 2rem 0 0;
}

header .wrapper {
  display: flex;
  place-items: flex-start;
  flex-wrap: wrap;
  margin: auto;
}

nav {
  text-align: left;
  margin-left: -1rem;
  font-size: 1rem;
}
</style>
