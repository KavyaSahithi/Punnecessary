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

<style lang="scss" scoped>
@import 'assets/scss/main.scss';
@import url('https://fonts.googleapis.com/css2?family=Gochi+Hand&display=swap');

.field {
  font-family: 'Gochi Hand', cursive;
  font-size: 3vw;
}

.container {
  padding-top: calc(15vh);
  display: flex;
  flex-direction: row;
  justify-content: center;
}

.top-level-fields {
  flex-direction: columns;
}

section {
  min-height: 100vh;
  background-color: $primary;
}
</style>