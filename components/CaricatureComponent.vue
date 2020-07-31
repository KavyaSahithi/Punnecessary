<template>
  <div>
    <div class="tile is-ancestor">
      <div class="tile is-6 is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('payal')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-6 is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('world')"></cloudinary-component>
        </div>
      </div>
    </div>

    <div class="tile is-ancestor">
      <div class="tile is-4 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('dharma')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-4 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('varsha')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-4 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('jayant')"></cloudinary-component>
        </div>
      </div>
    </div>

    <div class="tile is-ancestor">
      <div class="tile is-6 is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('zaefin')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-6 is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('amsterdam')"></cloudinary-component>
        </div>
      </div>
    </div>

    <div class="tile is-ancestor">
      <div class="tile is-6 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('sunil')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-6 is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('swathiakka')"></cloudinary-component>
        </div>
      </div>
    </div>

    <div class="tile is-ancestor">
      <div class="tile is-6 is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('ragini')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('kavya')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-6 is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('payaltrek')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('paddu')"></cloudinary-component>
        </div>
      </div>
    </div>

    <div class="tile is-ancestor">
      <div class="tile is-vertical is-4 is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('ajitesh')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('sachin')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-vertical is-4 is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('bernie')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('jinal')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-vertical is-4 is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('aayush')"></cloudinary-component>
        </div>
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('indrajit')"></cloudinary-component>
        </div>
      </div>
    </div>

    <div class="tile is-ancestor">
      <div class="tile is-8 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('mohit')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-vertical is-4 is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('kaumudi')"></cloudinary-component>
        </div>
      </div>
    </div>

    <div class="tile is-ancestor">
      <div class="tile is-6 is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('poki')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-6 is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('amsHug')"></cloudinary-component>
        </div>
      </div>
    </div>

    <div class="tile is-ancestor">
      <div class="tile is-6 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('zishan')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-6 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('cat')"></cloudinary-component>
        </div>
      </div>
    </div>

    <div class="tile is-ancestor">
      <div class="tile is-4 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('deep')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-4 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('uncle')"></cloudinary-component>
        </div>
      </div>
      <div class="tile is-4 is-vertical is-parent">
        <div class="tile is-child">
          <cloudinary-component category="Caricatures" :id="images.get('kiran')"></cloudinary-component>
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
          ['ragini', '1_edupch'],
          ['payal', '2_xbjhdq'],
          ['swathiakka', '3_sgkjti'],
          ['dharma', '5_aevkmq'],
          ['jayant', '6_ljcvtv'],
          ['sunil', '7_r7kbji'],
          ['varsha', '8_dk9snl'],
          ['bernie', '9_bbxn2y'],
          ['kaumudi', '10_hn8bly'],
          ['payaltrek', '11_fmdbja'],
          ['aayush', '12_jqbrqn'],
          ['sachin', '13_my6ar2'],
          ['kavya', '14_voi0wx'],
          ['indrajit', '15_nlcbgc'],
          ['mohit', '17_lsqhou'],
          ['uncle', '18_ouheew'],
          ['paddu', 'IMG_0886_eart5a'],
          ['cat', '16_o4nvyy'],
          ['zishan', 'IMG_1632_gvh87l'],
          ['kiran', 'IMG_1636_cgdddn'],
          ['ajitesh', 'IMG_1638_xlufrj'],
          ['jinal', 'IMG_1639_vaows0'],
          ['deep', 'IMG_1643_ld9lxf'],
          ['world', 'IMG_1963_quznep'],
          ['poki', 'IMG_2231_wf6icm'],
          ['zaefin', 'IMG_2129-min_mmijsn'],
          ['amsterdam', 'IMG_2235_i78n5l'],
          ['amsHug', 'IMG_2216_mhqqqi'],
        ]),
      }
    },
  })
</script>
