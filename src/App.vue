<script setup>
// import { RouterLink, RouterView } from 'vue-router'
// import UserForm from '../components/UserForm.vue'
// рандом компонент для проверки юзаем тут
</script>

<template>
  <header>
    <div class="wrapper">
      <!-- <UserForm msg="You did it!" /> -->
      <!-- ЭТО ПРИМЕР ПРОПСА. ТЫ БУДЕШЬ ИСПОЛЬЗОВАТЬ ЭТО ПРИ ПЕРЕХОДЕ С ЮЗЕР ФОРМ В ЮЗЕРЛИСТ -->
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/user-form">About</RouterLink>
        <RouterLink to="/user-account">My account</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
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
nav a.router-link-exact-active {
  font-weight: bold;
  /* text-decoration: none; */
  color: hsla(160, 100%, 37%, 1);

  /* transition: 0.4s; */
  /* padding: 3px; */
}
</style>
