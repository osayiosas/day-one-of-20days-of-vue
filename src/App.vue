<template>
  <main>
    <div>
      <h4>count is....</h4>
      <h1>{{ count }}</h1>
      <button @click="count++">Increment</button>
      <button @click="count--">Decrement</button>
    </div>
  </main>
</template>

<script setup>
import {ref} from 'vue';

const count = ref(0);
</script>

<style scoped>
main {
  background-color: rgb(232, 241, 238);
  height: 100vh;
  width: 100vw;
  display: flex;
  justify-content: center;
  align-items: center;
}

div {
  text-align: center;
}
</style>
