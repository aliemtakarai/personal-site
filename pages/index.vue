<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">
        Aliem Arif Perkasa
      </h1>
      <span class="title">
        Sofware Engineer | Web Enthusiast | Fullstack Web Developer <br>
        <a to="/blog">Read Blog</a>
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
html {
  font-family:
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}

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
