<template>
  <div class="">
    <h1>Welcome to the City Chooser</h1>
    <p>Choose a city from the list below:</p>
    <ul>
      <li v-for="city in cities" :key="city.id">{{ city.name }}</li>
    </ul>
  </div>
</template>

<script setup>

</script>

<style scoped></style>
