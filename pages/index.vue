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
  padding-top: calc(5vh);
  width: calc(250px + 20vw);
}

section {
  min-height: 95vh;
  background-color: $primary;
}
</style>