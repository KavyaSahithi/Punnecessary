<template>
  <div class="top-level">
    <b-navbar fixed-top type="is-primary">
      <template slot="brand">
        <b-navbar-item class="has-text-white" href="/">Punnecessary</b-navbar-item>
      </template>
      <template slot="end">
        <b-navbar-item class="has-text-white" href="/art">Art</b-navbar-item>
        <b-navbar-item class="has-text-white" href="/about">About Me</b-navbar-item>
        <b-navbar-item class="has-text-white" href="/pricing">Pricing</b-navbar-item>
        <b-navbar-item class="has-text-white" href="/contact">Contact Us</b-navbar-item>
      </template>
    </b-navbar>
    <nuxt />
  </div>
</template>

<style lang="scss">
@import 'assets/scss/main.scss';

.navbar {
  font-family: 'Gochi Hand', cursive;
  font-size: 30px;
}

.navbar-brand {
  margin-left: 4vw;
}

.navbar-end {
  margin-right: 4vw;
}

.navbar-burger span {
  background-color: $white !important;
}

.navbar-menu {
  background-color: $primary !important;
}

a.navbar-item:hover {
  background-color: darken($color: $primary, $amount: 5%) !important;
}

a.navbar-item:focus-within {
  background-color: $primary !important;
  color: $white !important;
}

</style>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({})
</script>
