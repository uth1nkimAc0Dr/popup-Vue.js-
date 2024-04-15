<script setup>
// import { RouterLink, RouterView } from 'vue-router'
// import UserForm from '../components/UserForm.vue'
// рандом компонент для проверки юзаем тут
</script>

<template>
  <div>
    <header>
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/user-form">About</RouterLink>
        <RouterLink to="/user-account">My account</RouterLink>
      </nav>
    </header>
    <main class="container">
      <RouterView />
    </main>
  </div>
</template>

<style scoped>
header {
  text-align: center;
}
nav {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  background-color: #00e6e6;
  padding: 10px;
}
.container {
  width: 1200px;
  margin: 10px auto;
  text-align: center;
}
a {
  text-decoration: none;
}
nav a.router-link-exact-active {
  font-weight: bold;
  color: hsla(160, 100%, 37%, 1);

  /* transition: 0.4s; */
  /* padding: 3px; */
}

/* без скоопед */
</style>
