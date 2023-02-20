<template>
  <h2>About Page</h2>
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusantium ad, architecto dolore eaque, eius et, ex fugiat iure labore obcaecati officiis perspiciatis placeat quae quaerat repellat sequi totam unde vitae!</p>
  <div>{{ data }}</div>
</template>

<script setup>
  const { data } = await useFetch('/api/currency/AMD')
</script>

<style scoped>

</style>
