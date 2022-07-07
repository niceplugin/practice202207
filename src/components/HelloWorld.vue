<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>
  <p>깃허브 배포 자동화 어렵구만</p>
</template>

<style scoped>
a {
  color: #42b983;
}
</style>
