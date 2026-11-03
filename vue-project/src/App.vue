<script setup>
import { ref } from 'vue'

const count = ref(0)
</script>

<template>
  <main>
    <h1>Hello, I'm Mehdi 👋</h1>

    <p>I'm a Software Engineering student learning Vue.js.</p>

    <p>My goal is to become a Cloud Security Engineer.</p>

    <h2>My first Vue application</h2>

    <button @click="count++">
      Click me: {{ count }}
    </button>
  </main>
</template>

<style>
body {
  font-family: Arial, sans-serif;
  background: #f1f5f9;
}

main {
  max-width: 600px;
  margin: 100px auto;
  padding: 30px;
  text-align: center;
  background: white;
  border-radius: 16px;
}

h1 {
  color: #16a34a;
}

button {
  padding: 12px 24px;
  background: #42b883;
  color: white;
  border: none;
  border-radius: 8px;
  cursor: pointer;
}
</style>