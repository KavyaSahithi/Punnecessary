<template>
  <div>
    <div class="tile is-ancestor">
      <div class="tile is-12 is-parent">
        <cloudinary-component category="Portraits" :id="images.get('kaumudi')"></cloudinary-component>
      </div>
    </div>

    <div class="tile is-ancestor">
      <div class="tile is-6 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Portraits" :id="images.get('neelima')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Portraits" :id="images.get('kirikparty')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Portraits" :id="images.get('pooja')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Portraits" :id="images.get('mona')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-6 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Portraits" :id="images.get('sarojaaunty')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Portraits" :id="images.get('yellowbaby')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Portraits" :id="images.get('anne')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Portraits" :id="images.get('ariana')"></cloudinary-component>
        </div>
      </div>
    </div>
    <div class="tile is-ancestor">
      <div class="tile is-12 is-parent">
        <cloudinary-component category="Portraits" :id="images.get('varshafriends')"></cloudinary-component>
      </div>
    </div>
    <div class="tile is-ancestor">
      <div class="tile is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Portraits" :id="images.get('sans')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Portraits" :id="images.get('ragini')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Portraits" :id="images.get('amazinggirl')"></cloudinary-component>
        </div>
      </div>
    </div>
    <div class="tile is-ancestor">
      <div class="tile is-8 is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Portraits" :id="images.get('kavya')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-4 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Portraits" :id="images.get('kids')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Portraits" :id="images.get('syed')"></cloudinary-component>
              </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.tile .is-child {
  display: flex;
  flex-direction: column;
  justify-content: center;
}
</style>

<script lang="ts">
import Vue from 'vue'
import CloudinaryComponent from '@/components/CloudinaryComponent.vue'

export default Vue.extend({
  components: {
    CloudinaryComponent,
  },
  data() {
    return {
      images: new Map([
        ['kaumudi', 'IMG_1359_uhfhxi'],
        ['neelima', 'IMG_0938_mxpczy'],
        ['varshafriends', 'IMG_1526_s5rjmp'],
        ['ariana', 'IMG_1028_ydlfzp'],
        ['anne', 'IMG_0594_gexi3n'],
        ['mona', 'IMG_1262_fwdfdb'],
        ['sarojaaunty', 'IMG_1470_g2ejdl'],
        ['kirikparty', 'IMG_1118_djabd7'],
        ['yellowbaby', '4_daaud4'],
        ['ragini', '13_qrucdt'],
        ['pooja', 'IMG_0889_zfd7xl'],
        ['sans', 'IMG_1354_qrqbhb'],
        ['amazinggirl', '5695EF4D-33AD-4A1F-B52B-0EB45CCD608B_ox3vxu'],
        ['kids', 'IMG_1074_hayc1g'],
        ['kavya', 'IMG_1784_lwev3j'],
        ['syed', 'IMG_0790_ntxlfn']
      ]),
    }
  },
})
</script>