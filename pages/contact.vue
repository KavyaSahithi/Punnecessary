<template>
  <section>
    <figure class="container">
      <div class="top-level-fields">
        <div class="field has-text-white">
          <span>
            <b-icon icon="instagram" size="is-large" type="is-white"></b-icon>
          </span>
          <span>@_punnecessary</span>
        </div>
        <div class="field has-text-white">
          <span>
            <b-icon icon="facebook" size="is-large" type="is-white"></b-icon>
          </span>
          <span>fb.com/punnecessary</span>
        </div>
        <div class="field has-text-white">
          <span>
            <b-icon icon="google-chrome" size="is-large" type="is-white"></b-icon>
          </span>
          <span>www.kavyasahithi.com</span>
        </div>
        <div class="field has-text-white">
          <span>
            <b-icon icon="whatsapp" size="is-large" type="is-white"></b-icon>
          </span>
          <span>9620388230 / 9741104864</span>
        </div>
        <div class="field has-text-white">
          <span>
            <b-icon icon="email" size="is-large" type="is-white"></b-icon>
          </span>
          <span>kavya.lily@gmail.com</span>
        </div>
      </div>
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

.container {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.field {
  font-family: 'Gochi Hand', cursive;
  font-size: 3vw;
}

.top-level-fields {
  flex-direction: columns;
}
</style>