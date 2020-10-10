<template>
  <div class="container">
    <!-- <div>
      <Logo />
      <h1 class="title">
        h2.studio
      </h1>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          Documentation
        </a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          GitHub
        </a>
      </div>

    </div> -->
    <div class="g">
        <div class="left">左</div>
        <div class="center">中央</div>
        <div class="right">右</div>
      </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
<!-- .container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
} -->

.container {
  width: 100%;
  height: 1000px;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
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

.g{
  width: 100%;
  height: 100%;
  background-color: #35495e;
  text-align: center;
}

.left{
  width: 33%;
  height: 100%;
  float: left;
  background-color: #d6e29b;
}

.center{
  width: 33%;
  height: 100%;
  float: left;
  background-color: #e9ab5b;
}

.right{
  width: 33%;
  height: 100%;
  float: left;
  background-color: #8e8ca0;
}
</style>
