<template>
  <nav class="nav">
    <h1 class="logo">NCS</h1>

    <ul class="links">
      <li>Home</li>
      <li>Services</li>
      <li>Features</li>
      <li><button class="signUp-button">Sign Up</button></li>
    </ul>
  </nav>
  <div class="glowing-ball">
  </div>
</template>

<style>

.signUp-button {
  background-color: white;
  border: none;
  padding: 10px 20px;
  border-radius: 5px;
  cursor: pointer;
  font-weight: bold;
}
  
.nav {
  background: #000000;
  color: white;
  padding: 20px;
  display: flex;
  justify-content: space-between;
}
.links {
  list-style: none;
  display: flex;
  gap: 20px;
  margin-right: 2vw;
}
.links li {
  cursor: pointer;
  justify-content: space-around;
  margin: auto;
}
.logo {
  font-size: 24px;
  font-weight: bold;
  height: 50%;
}
</style>
