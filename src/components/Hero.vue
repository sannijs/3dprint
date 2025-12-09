<template>
  <section class="hero">
    <div class="text">
      <div class="headder">
        <h2 id="alfa">3D Printing</h2>
        <h2>3D Printing</h2>
      </div>
      <h3>Night Creature Solutions</h3>
      <p>Night Creature Solutions operates at the intersection of cutting-edge technology and “mad physics” innovation. </p>
      <form action="/search" method="GET">
        <input type="text" name="q" placeholder="Search for 3D models..." />
      </form>
    </div>
  </section>
</template>

<style>
.hero {
  height: 100vh;
  color: rgb(255, 255, 255);

}
.headder {
    margin-bottom: -10%;
    font-size: 5vw;
  width: 50vw;

}

.headder #alfa{
  color: blue;
  position: absolute;
  margin-top: -1vh;
}
.text {
  max-width: 40%;
  border-radius: 10px;
}
form input {
    background-color: rgba(0, 0, 0, 0.7);
    border: 2px solid white;
    border-radius: 5px;
    width: 100%;
    max-width: 350px;
    height: 30px;
    margin-top: 2vh;
    padding: 0 15px;
    color: white;
    font-size: 1rem;
    transition: all 0.3s ease;
}

form input:focus {
    outline: none;
    background-color: rgba(0, 0, 0, 0.9);
    box-shadow: 0 0 10px rgba(255, 255, 255, 0.3);
}

form input::placeholder {
    color: rgb(255, 255, 255);
}

@media screen and (min-width: 1163px) {
   
.headder #alfa{
}
}

</style>
