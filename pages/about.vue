<template>
  <div>
    <h2>About</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Distinctio, doloribus est hic magni obcaecati odio possimus sapiente sequi velit voluptate?</p>
    <div>{{ data }}</div>
  </div>
</template>

<script setup lang="ts">
// const { data } = await useFetch('/api/ninja?name=mario');
// const { data } = await useFetch('/api/ninja?name=mario', {
//   method: 'post',
//   body: {age: 30}
// });

// const { data } = await useFetch('/api/ninja');

const { data } = await useFetch('/api/currency/GBP');
</script>

<style scoped>
h2 {
  margin-bottom: 20px;
  font-size: 36px;
}
p {
  margin: 20px 0;
}
</style>
