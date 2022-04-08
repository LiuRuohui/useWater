<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>

<template>
<div class="h-12 w-12 bg-red-200"></div>
</template>

<style scoped>
a {
  color: #42b983;
}
</style>
