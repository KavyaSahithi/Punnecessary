<template>
  <div>
    <div class="tile is-ancestor">
      <div class="tile is-6 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Comics" :id="images.get('marriage')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Comics" :id="images.get('towel')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Comics" :id="images.get('angry')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Comics" :id="images.get('ac')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-6 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Comics" :id="images.get('sleep')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Comics" :id="images.get('pizza')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Comics" :id="images.get('magic')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Comics" :id="images.get('slice')"></cloudinary-component>
        </div>
      </div>
    </div>

    <div class="tile is-ancestor">
      <div class="tile is-4 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Comics" :id="images.get('salad')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Comics" :id="images.get('rat')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-4 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Comics" :id="images.get('moon')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Comics" :id="images.get('momeat')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-4 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Comics" :id="images.get('deserve')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Comics" :id="images.get('netflix')"></cloudinary-component>
        </div>
      </div>
    </div>

    <div class="tile is-ancestor">
      <div class="tile is-3 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Comics" :id="images.get('candy')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Comics" :id="images.get('comb')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-3 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Comics" :id="images.get('donut')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Comics" :id="images.get('tshirt')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-3 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Comics" :id="images.get('bubblewrap')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Comics" :id="images.get('birthday')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-3 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Comics" :id="images.get('cheerleader')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Comics" :id="images.get('sorrow')"></cloudinary-component>
        </div>
      </div>
    </div>

    <div class="tile is-ancestor">
      <div class="tile is-4 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Comics" :id="images.get('ready')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-4 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Comics" :id="images.get('soap')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-4 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Comics" :id="images.get('icecream')"></cloudinary-component>
        </div>
      </div>
    </div>
  </div>
</template>

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
        ['pizza', '1_csnlia'],
        ['marriage', '2__vjgjyf'],
        ['towel', '3__zygxgy'],
        ['angry', '4_qe13z8'],
        ['ac', '5_uhnyte'],
        ['magic', '6_wv3m2n'],
        ['sleep', '7_k3kieo'],
        ['slice', '8_hubymt'],
        ['salad', '9_mmojs2'],
        ['deserve', '10_j1ze49'],
        ['moon', '11_l3jukn'],
        ['rat', 'IMG_0360_mwyrlx'],
        ['momeat', 'IMG_0411_dvbdrs'],
        ['netflix', 'IMG_0653_tm47zr'],
        ['candy', 'IMG_0800_yovtsl'],
        ['donut', 'IMG_0802_xmatby'],
        ['bubblewrap', 'IMG_0807_psvnnv'],
        ['cheerleader', 'IMG_1292_wbjjnw'],
        ['comb', 'IMG_1305_sgohss'],
        ['tshirt', 'IMG_1307_shxg4u'],
        ['birthday', 'IMG_1347_myjnzl'],
        ['sorrow', 'IMG_1443_vtkga4'],
        ['ready', 'IMG_1571_em5dqt'],
        ['soap', 'IMG_1793_ovkpz5'],
        ['icecream', 'IMG_1623_obkscq'],
      ]),
    }
  },
})
</script>
