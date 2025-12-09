<template>
  <nav class="nav">
    <h1 class="logo">3D Print Hub</h1>

    <ul class="links">
      <li>Home</li>
      <li>Services</li>
      <li>Upload</li>
      <li>Contact</li>
    </ul>
  </nav>
</template>

<style>
.nav {
  background: #111;
  color: white;
  padding: 20px;
  display: flex;
  justify-content: space-between;
}
.links {
  list-style: none;
  display: flex;
  gap: 20px;
}
.links li {
  cursor: pointer;
}
.logo {
  font-size: 24px;
  font-weight: bold;
}
</style>
