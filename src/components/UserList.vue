<!-- отображение списка пользователей
 -->
<template>
  <div>
    <div v-for="user in users" class="user-container">
      <!-- Пользователь и инфа о нем -->
      <div>{{ user.firstName }} dsa{{ user.lastName }} {{ user.age }}</div>
    </div>
  </div>
  <template> </template>
</template>

<script>
export default {
  data() {
    return {
      user: {}
    }
  },
  methods: {}
  //   getting props
}
</script>

<style></style>
