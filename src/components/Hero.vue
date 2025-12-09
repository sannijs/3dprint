<template>
  <section class="hero">
    <div class="text">
      <h2>Professional 3D Printing Services</h2>
      <p>Upload your model — we print it in highest quality.</p>
      <button>Start Now</button>
    </div>
  </section>
</template>

<style>
.hero {
  height: 70vh;
  background: url("https://images.unsplash.com/photo-1559703248-dcaaec9fab78?auto=format&fit=crop&w=1600&q=80") center/cover no-repeat;
  display: flex;
  justify-content: flex-start;
  align-items: center;
  padding: 40px;
  color: white;
}
.text {
  max-width: 400px;
  background: rgba(0,0,0,0.5);
  padding: 20px;
  border-radius: 10px;
}
button {
  margin-top: 15px;
  background: #ff9800;
  padding: 12px 20px;
  border: none;
  cursor: pointer;
  border-radius: 6px;
}
</style>
