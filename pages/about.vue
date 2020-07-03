<template>
  <section>
    <div class="top">
      <div class="image">
        <img
          src="https://res.cloudinary.com/punnecessary/image/upload/q_auto,f_auto/kavya_tlv1la.png"
        />
      </div>
      <div class="text has-text-white">
        <p class="text-data" text-align="center" v-html="text"></p>
      </div>
    </div>
  </section>
</template>

<style lang="scss">
@import 'assets/scss/main.scss';

body {
  background-color: $primary;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
}

#__nuxt {
  display: flex;
  flex-direction: column;
  flex-grow: 1;
  padding-top: 10px;
  
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

.top {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  flex-wrap: wrap;
  gap: 20px;
}

.image {
  display: flex;
  flex-direction: column;
  justify-content: center;
  width: calc(250px + 10vw);
}

.text {
  display: flex;
  flex-direction: column;
  justify-content: center;
  width: 50vw;
}

.text-data {
  font-family: 'Gochi Hand', cursive;
  font-size: calc(1.8vh + 1vw);
}
</style>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  data() {
    return {
      text: `Hey, I am Kavya Sahithi,  Architect, designer and digital illustrator,
            currently based in Bangalore. I passed out from RVCE in 2017
            and had since then been working full time as an Architect, for a
            reputed firm. A few months ago, I quit my job to pursue higher
            studies abroad but my plans got disrupted due to the pandemic
            situation. To make the most of my free time, I decided to get
            back to my long lost love, of drawing. ❤️ <br/>
<br/>
            So I started drawing some comics and started an Instagram page
            to make sure I keep up with it 😋 and also started drawing some
            portraits for friends and family on the side. Soon, I started
            receiving lots of commissions and orders and so I started doing
            freelance digital illustration full time, and love every minute
            of it!`,
    }
  },
})
</script>