<template>
  <section>
    <figure class="container">
      <div class="top-level-fields">
        <div class="field">
          <a href="https://www.instagram.com/_punnecessary/" target="_blank">
          <span>
            <b-icon icon="instagram" size="is-large" type="is-white"></b-icon>
          </span>
          <span class="has-text-white">@_punnecessary</span>
          </a>
        </div>
        <div class="field">
          <a href="https://www.facebook.com/punnecessary" target="_blank">
          <span>
            <b-icon icon="facebook" size="is-large" type="is-white"></b-icon>
          </span>
          <span class="has-text-white">fb.com/punnecessary</span>
          </a>
        </div>
        <div class="field">
          <a href="/">
          <span>
            <b-icon icon="google-chrome" size="is-large" type="is-white"></b-icon>
          </span>
          <span class="has-text-white">www.kavyasahithi.com</span>
          </a>
        </div>
        <div class="field">
          <a href="mailto:kavya.lily@gmail.com" target="_blank">
          <span>
            <b-icon icon="email" size="is-large" type="is-white"></b-icon>
          </span>
          <span class="has-text-white">kavya.lily@gmail.com</span>
          </a>
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
 
  font-size: calc(3.5vh + 1vw);
}

.top-level-fields {
  flex-direction: columns;
}
</style>