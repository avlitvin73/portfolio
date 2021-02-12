<template>
  <div class="container">
    <div>
      <a href="/" class="td-none">
        <h1 class="title">
          portfolio
        </h1>
      </a> 
      <div class="links">
        <nuxt-link to="/profile" class="button--grey">profile</nuxt-link>
        <nuxt-link to="/projects" class="button--grey">projects</nuxt-link>
      </div>
    </div>
  </div>
</template>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  user-select: none; 
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
  color: #35495e;
  letter-spacing: 1px;
  font-size: calc(0.75em + 10vmin);
  
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
</style>
