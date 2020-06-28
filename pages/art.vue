<template>
  <section class="container art">
    <b-tabs
      v-model="activeTab"
      position="is-centered"
      class="block"
      type="is-info"
      size="is-medium"
      expanded
    >
      <b-tab-item v-for="category in categories" :key="category" :label="category">
        <image-component :category="category"></image-component>
      </b-tab-item>
    </b-tabs>
  </section>
</template>

<style lang="scss">
@import 'assets/scss/main.scss';

/* Hide scrollbar for Chrome */
.tabs::-webkit-scrollbar {
  display: none;
}

/* Hide scrollbar for IE, Edge and Firefox */
.tabs {
  -ms-overflow-style: none; /* IE and Edge */
  scrollbar-width: none; /* Firefox */
}

.tabs {
    padding-bottom: 5vh;
}

.tabs li.is-active a {
  border-bottom-color: $info !important;
  color: $info !important;
}

.art {
  padding-top: 10vh;
}
</style>

<script lang="ts">
import Vue from 'vue'
import ImageComponent from '@/components/ImageComponent.vue'

export default Vue.extend({
  components: {
    ImageComponent,
  },
  data() {
    return {
      activeTab: 0,
      categories: ['Caricatures', 'Portraits', 'Comics', 'Cards', 'Puns'],
    }
  },
})
</script>