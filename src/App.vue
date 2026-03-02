<script setup>
import { ref } from 'vue';
import ChildComponent from './ChildComponent.vue';

const sharedMessage = ref('');

</script>

<template>
 <ChildComponent v-model="sharedMessage" />
 <p>ik schrijf wel mee: {{ sharedMessage }}</p>
 <ChildComponent v-model="sharedMessage" />
 <p> ik ook: {{ sharedMessage }}</p>
</template>

<style scoped>

</style>
