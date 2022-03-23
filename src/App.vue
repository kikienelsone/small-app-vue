<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from '@/components/HelloWorld.vue'
</script>

<template>
  <header class="header">
    <div class="wrapper">

      <nav>
        <RouterLink to="/">Home</RouterLink> |
        <RouterLink to="/about">About</RouterLink> |
        <RouterLink to="/todos">Todo List</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style>
body{
  max-width: 1440px;
  display: flex;
  justify-content: center;
  padding-top: 30px;
}

.header{
  margin-bottom: 20px;
}
</style>
