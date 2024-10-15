<script setup>
import { reactive } from 'vue';
const greeting = reactive({ name: 'Hello World!' });
</script>

<template>
  <h1>
    {{ greeting.name }}
  </h1>
</template>