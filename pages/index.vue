<template>
  <section>
    <figure class="image container">
      <img src="~/assets/logo.PNG"/>
    </figure>
  </section>
</template>

<style lang="scss">
@import 'assets/scss/main.scss';

body {
  background-color: $primary;
  min-height: 100vh;
  max-height: 100vh;
  display: flex;
  flex-direction: column;
}

#__nuxt {
  display: flex;
  flex-direction: column;
  flex-grow: 1;
}

#__layout {
  display: flex;
  flex-direction: column;
  flex-grow: 1;
}

.top-level {
  
  display: flex;
  flex-direction: column;
  flex-grow: 1;
}

section {
  display: flex;
  flex-direction: column;
  flex-grow: 1;
  justify-content: center;
}

.image {
  width: calc(200px + 30vw);
  display: flex;
  flex-direction: column;
  justify-content: center;
  
}

</style>