<template>
  <section>
    <figure class="image container">
      <img src="~/assets/logo.PNG"/>
    </figure>
  </section>
</template>

<style lang="scss" scoped>
@import 'assets/scss/main.scss';

.image {
  padding-top: calc(15vh);
  width: calc(350px + 8vw);
}

section {
  min-height: 100vh;
  background-color: $primary;
}
</style>