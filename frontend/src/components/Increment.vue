<script setup lang="ts">
import { ref, onMounted, type Ref } from 'vue'

// reactive state
const count = ref<number>(0)

// functions that mutate state and trigger updates
function increment() {
  count.value++
}

// lifecycle hooks
onMounted(() => {
  console.log(`The initial count is ${count.value}.`)
})
</script>

<template>
    <div>Count is at {{  count }}</div>
  <button @click="increment">Count is: {{ count }}</button>
</template>
