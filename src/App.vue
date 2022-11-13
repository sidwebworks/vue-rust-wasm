<template>
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" width="200" class="logo" alt="Vite logo" />
    </a>
  </div>
</template>




<script setup lang="ts">
import init, { prompt } from 'crate';

init().then(() => {
  console.log('init wasm-pack');
  prompt("Hello Rust!")
});

</script>

