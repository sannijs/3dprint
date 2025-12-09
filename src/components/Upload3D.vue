<template>
  <section class="upload">
    <h2>Upload 3D Model</h2>
    <p>Supported: STL, OBJ</p>

    <input type="file" @change="handleFile" />
    <p v-if="fileName">Selected: {{ fileName }}</p>
  </section>
</template>

<script setup>
import { ref } from 'vue'
const fileName = ref("")

function handleFile(e) {
  const file = e.target.files[0]
  if (file) fileName.value = file.name
}
</script>

<style>
.upload {
  background: #ffffff;
  padding: 40px;
  text-align: center;
  margin: 20px;
  border-radius: 10px;
}
</style>
