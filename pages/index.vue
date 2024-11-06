<script setup lang="ts">
const route = useRoute();
</script>

<template>
  <div>
    <h1>Page: 首頁</h1>
    目前路由的路徑 - route.fullPath 為：{{ route.fullPath }}
    <br />
    <button class="btn btn-primary">Primary</button>
    <button class="btn btn-secondary">Secondary</button>
    <button class="btn btn-success">Sucess</button>
    <button class="btn btn-danger">Danger</button>
    <button class="btn btn-warning">Warning</button>
    <button class="btn btn-info">Info</button>
    <button class="btn btn-light">Light</button>
    <button class="btn btn-dark">Dark</button>
    <button class="btn btn-link">Link</button>
  </div>
</template>

<style scoped></style>
