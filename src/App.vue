<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Personal from './components/Personal.vue'
import Footer from './components/Footer.vue'
</script>

<template>
 
    

    <div class="wrapper">
      <nav>
        <RouterLink to="/">Personal</RouterLink>
        <RouterLink to="/skill">Skill</RouterLink>
      </nav>

    </div>
    

  <RouterView />
  <Footer />
</template>

<style scoped>


nav {
  font-size: 20px;
  margin-top: 40px;
  margin-right: 550px;
}

nav a{
  margin-left: 9px;
}

nav a.router-link-exact-active {
  color: cornflowerblue;
}

nav a.router-link-exact-active:hover {
  background-color: lightskyblue;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  
}

nav a:first-of-type {
  border: 0;
}

.footer{
  background-color: cornflowerblue;
  color: white;
  width: 1225px;
  border-radius: 10px;
  margin-right: -1225px;
  margin-top: 10px;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    align-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  nav {
    text-align: right;
    margin-left: 1rem;
    font-size: 1rem;
    padding: 1rem 0;
  }
}
</style>
