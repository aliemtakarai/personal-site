<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">
        Aliem Arif Perkasa
      </h1>
      <span class="title">
        Sofware Engineer | Web Enthusiast | Fullstack Web Developer
      </span>
      <div class="links">
        <a href="https://twitter.com/aliemtakarai" target="blank"><i class="fa fa-twitter fa-2x" aria-hidden="true"></i></a>
        <a href="https://github.com/aliemtakarai" target="blank"><i class="fa fa-github fa-2x" aria-hidden="true"></i></a>
        <a href="https://www.linkedin.com/in/aliem-arif-perkasa/" target="blank"><i class="fa fa-linkedin fa-2x" aria-hidden="true"></i></a>
        <a href="https://www.instagram.com/aliemtakarai/" target="blank"><i class="fa fa-instagram fa-2x" aria-hidden="true"></i></a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  head:{
    title: 'aliemtakarai'
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Permanent Marker', cursive;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

a{
  color: black !important;
}
</style>
