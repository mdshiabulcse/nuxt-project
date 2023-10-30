<script setup>
import {useNuxtApp} from "#app";

const nuxt=useNuxtApp();
console.log(nuxt);
</script>
<template>
  <div>event id: {{$route.params.id}}</div>
</template>