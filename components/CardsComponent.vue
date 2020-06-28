<template>
  <div>
    <div class="tile is-ancestor">
      <div class="tile is-4 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Cards" :id="images.get('eid')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Cards" :id="images.get('birthdaygif')"></cloudinary-component>
        </div>
        <div class="title is-child">
          <cloudinary-component category="Cards" :id="images.get('dad')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-4 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Cards" :id="images.get('bdaysiri')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Cards" :id="images.get('friends')"></cloudinary-component>
        </div>
        <div class="title is-child">
          <cloudinary-component category="Cards" :id="images.get('easter')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-4 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Cards" :id="images.get('mom')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Cards" :id="images.get('ram')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Cards" :id="images.get('anni')"></cloudinary-component>
        </div>
      </div>
    </div>
    <div class="tile is-ancestor">
      <div class="tile is-8 is-vertical is-parent">
        <div class="title is-child">
          <cloudinary-component category="Cards" :id="images.get('polar')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-4 is-vertical is-parent">
        <div class="title is-child">
          <cloudinary-component category="Cards" :id="images.get('monkey')"></cloudinary-component>
        </div>
        <div class="title is-child">
          <cloudinary-component category="Cards" :id="images.get('bear')"></cloudinary-component>
        </div>
      </div>
    </div>
    <div class="tile is-ancestor">
      <div class="tile is-parent">
        <div class="title is-child">
          <cloudinary-component category="Cards" :id="images.get('proudof')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-parent">
        <div class="title is-child">
          <cloudinary-component category="Cards" :id="images.get('weirdoletgo')"></cloudinary-component>
        </div>
      </div>
    </div>

    <div class="tile is-ancestor">
      <div class="tile is-4 is-vertical is-parent">
        <div class="title is-child">
          <cloudinary-component category="Cards" :id="images.get('hangheart')"></cloudinary-component>
        </div>
        <div class="title is-child">
          <cloudinary-component category="Cards" :id="images.get('panda')"></cloudinary-component>
        </div>
        <div class="title is-child">
          <cloudinary-component category="Cards" :id="images.get('santa')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-8 is-vertical is-parent">
        <div class="title is-child">
          <cloudinary-component category="Cards" :id="images.get('valentine')"></cloudinary-component>
        </div>
      </div>
    </div>

    <div class="tile is-ancestor">
      <div class="tile is-4 is-vertical is-parent">
        <div class="title is-child">
          <cloudinary-component category="Cards" :id="images.get('newyear')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-4 is-vertical is-parent">
        <div class="title is-child">
          <cloudinary-component category="Cards" :id="images.get('castle')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-4 is-vertical is-parent">
        <div class="title is-child">
          <cloudinary-component category="Cards" :id="images.get('newyearback')"></cloudinary-component>
        </div>
      </div>
    </div>

    <div class="tile is-ancestor">
      <div class="tile is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Cards" :id="images.get('carona')"></cloudinary-component>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.tile .is-parent {
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
        ['birthdaygif', '1_ts0hoo'],
        ['ram', '2_esrgoi'],
        ['bdaysiri', '3_st8a9r'],
        ['easter', '4_ok0wjy'],
        ['friends', '5_sjifyc'],
        ['eid', '6_pcd6qm'],
        ['mom', '7_owgzrn'],
        ['dad', '8_sn07bw'],
        ['anni', '9_rp9pjs'],
        ['monkey', '10_uzmrhh'],
        ['weirdoletgo', '11_lgzcq1'],
        ['bear', '12_zlzw91'],
        ['proudof', '13_vcsne4'],
        ['panda', '14_rn4bkj'],
        ['santa', '15_d3crsq'],
        ['polar', '16_xzq0pg'],
        ['valentine', '17_clmu2g'],
        ['hangheart', '18_aapmo9'],
        ['castle', '19_z5ub45'],
        ['newyear', '20_c27jek'],
        ['newyearback', '21_a7qfzw'],
        ['carona', 'IMG_0469_kbmfu3'],
      ]),
    }
  },
})
</script>