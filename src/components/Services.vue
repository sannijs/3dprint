<script setup>
const services = [
  { name: "FDM Printing", desc: "Fast and affordable plastic parts.", icon: "🧱" },
  { name: "SLA Resin Printing", desc: "Ultra high detail resin prints.", icon: "🧊" },
  { name: "Metal Printing", desc: "Strong, durable metal components.", icon: "⚙️" },
  { name: "CNC Cutting", desc: "Wood, metal, carbon fiber cutting.", icon: "🔧" },
]
</script>

<template>
  <section class="services">
    <h2>Our Services</h2>

    <div class="cards">
      <div class="card" v-for="s in services" :key="s.name">
        <div class="icon">{{ s.icon }}</div>
        <h3>{{ s.name }}</h3>
        <p>{{ s.desc }}</p>
      </div>
    </div>
  </section>
</template>

<style>
.services {
  padding: 40px;
  text-align: center;
}

.cards {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 20px;
}

.card {
  width: 250px;
  background: white;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}
.icon {
  font-size: 40px;
}
</style>
