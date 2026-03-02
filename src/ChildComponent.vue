<script setup>
const message = defineModel();

</script>

<template>
  <div>
    <input type="text" v-model="message" placeholder="schrijf maar">
  </div>
</template>