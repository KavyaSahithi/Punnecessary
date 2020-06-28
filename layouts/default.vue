<template>
  <div>
    <b-navbar fixed-top type="is-primary">
      <template slot="brand">
        <b-navbar-item>
          <nuxt-link class="has-text-white" to="/portfolio">Punnecessary</nuxt-link>
        </b-navbar-item>
      </template>
      <template slot="end">
        <b-navbar-item>
          <nuxt-link class="has-text-white" to="/portfolio">Portfolio</nuxt-link>
        </b-navbar-item>
        <b-navbar-item>
          <nuxt-link class="has-text-white" to="/contact">Contact</nuxt-link>
        </b-navbar-item>
      </template>
    </b-navbar>
    <nuxt />
  </div>
</template>

<style lang="scss">
@import 'assets/scss/main.scss';

.navbar-brand .has-text-white {
  font-weight: bold;
  padding-left: 4vw;
}

.navbar-end {
  padding-right: 4vw;
}

.navbar-burger span {
  background-color: $white;
}

.navbar-menu {
  background-color: $primary;
}
</style>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({})
</script>
