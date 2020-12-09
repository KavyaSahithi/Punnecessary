<template>
  <div class="top-level">
    <b-navbar fixed-top type="is-primary">
      <template slot="brand">
        <b-navbar-item class="has-text-white" href="/">Punnecessary</b-navbar-item>
      </template>
      <template slot="end">
        <b-navbar-item class="has-text-white" href="/art">Art</b-navbar-item>
        <b-navbar-item class="has-text-white" href="/contact">Contact Us</b-navbar-item>
      </template>
    </b-navbar>
    <nuxt />
  </div>
</template>

<style lang="scss">
@import 'assets/scss/main.scss';

.navbar {
  font-size: 30px;
}

.navbar-brand {
  margin-left: 4vw;
}

.navbar-end {
  margin-right: 4vw;
}

.navbar-item {
  margin-left: 2vw;
}

.navbar-burger span {
  background-color: $white !important;
}

.navbar {
  background-color: rgb(100, 202, 189) !important;
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
