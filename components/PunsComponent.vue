<template>
  <div>
    <div class="tile is-ancestor">
      <div class="tile is-12 is-parent">
        <cloudinary-component category="Puns" :id="images.get('punscards')"></cloudinary-component>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import CloudinaryComponent from '@/components/CloudinaryComponent.vue'

export default Vue.extend({
    components: {
        CloudinaryComponent
    },
      data() {
    return {
      images: new Map([
        ['punscards', 'final2_vl076r'],
      ]),
    }
  },
})
</script>