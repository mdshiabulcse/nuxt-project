
<template>
  <div class="Main container py-3 mx-auto">
       <h1 class="text-teal-500"> Hello Nuxt 3</h1>
  </div>
</template>
<script setup lang="ts">
definePageMeta({
  middleware:"auth",
})
</script>