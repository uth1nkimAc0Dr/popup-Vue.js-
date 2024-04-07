<template>
  <div class="popup-form">
    form for adding user
    <div class="popup__header">
      Hey, fill in da details
      <div class="popup__box">
        <div class="popup__col">dsa</div>
        <div class="popup__col"></div>
        <button @click="addUser" class="popup__submit-button">home</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      user: {}
    }
  },
  methods: {
    addUser() {
      // добавляешь в локалстораж нового юзера
      this.$router.push('/')
    }
  }
}
</script>

<style></style>
