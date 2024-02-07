<template>
  <div v-for="race in races" :key="race.name">
    <h2>{{ race.name }}</h2>
  </div>
</template>

<script setup>


const races = [{ name: 'Lyon' }, { name: 'London' }];


</script>