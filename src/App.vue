<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
 
    

    <div class="wrapper">
      <nav>
        <RouterLink to="/">Personal</RouterLink>
        <RouterLink to="/skill">Skill</RouterLink>
      </nav>

    </div>


  <RouterView />
</template>

<style scoped>


nav {
  font-size: 15px;
  text-align: center;
  margin-top: -100px;
  margin-right: -650px;
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
