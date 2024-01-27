<!-- json-server --watch db.json --port 3333 -->
<script setup>
import { RouterView } from "vue-router";
</script>

<template>
  <div class="bg-slate-600 p-5">
    <h1 class="text-3xl md:text-3xl font-bold text-center text-white">
      Vue3 Composition CRUD with API Call
    </h1>
  </div>
  <RouterView />
</template>

<style scoped></style>