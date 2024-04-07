<template>
  <div class="about">
    <UserForm />
  </div>
</template>

<script setup>
import UserForm from '@/components/UserForm.vue'
</script>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
