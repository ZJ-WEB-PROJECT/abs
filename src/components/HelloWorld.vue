<script setup>
import { ref } from 'vue'
</script>

<template>
  <div class="error">
    <div>The page cannot load. Please copy the URL to the Safari browser to open it</div>
    <div>ページをロードできませんでしたSafariブラウザにWebアドレスをコピーして開いてください</div>
  </div>
</template>

<style>
.error {
  padding: 0 20px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  height: 100vh;
}

.error div {
  margin-bottom: 20px;
  font-size: 18px;
  text-align: left;
  color: #000;
  font-family: 'Times New Roman', Times, serif;
  /* font-family: Arial, sans-serif; */
}
</style>