<template>
  <section class="pricing">
    <h2>Pricing</h2>

    <div class="plans">
      <div class="plan">
        <h3>Standard</h3>
        <p>€0.10 / gram</p>
      </div>

      <div class="plan">
        <h3>Resin</h3>
        <p>€0.25 / gram</p>
      </div>

      <div class="plan">
        <h3>Metal</h3>
        <p>€0.80 / gram</p>
      </div>
    </div>
  </section>
</template>

<style>
.pricing {
  text-align: center;
  padding: 30px;
}
.plans {
  display: flex;
  justify-content: center;
  gap: 20px;
}
.plan {
  background: white;
  padding: 20px;
  width: 200px;
  border-radius: 10px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}
</style>
