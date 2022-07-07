<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>
  <p>워크플로 실행시간이 2분이 넘는건 너무한데????</p>
</template>

<style scoped>
a {
  color: #42b983;
}
</style>
