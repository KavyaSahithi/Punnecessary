<template>
  <section class="container pricing">
    <b-tabs
      v-model="activeTab"
      position="is-centered"
      class="block"
      type="is-info"
      size="is-medium"
      expanded
    >
      <b-tab-item label="Pricing" class="has-text-left">
        <div class="has-text-weight-semibold is-size-1 is-size-3-mobile">Caricature</div>
        <div class="subtext">
          <div class="columns">
            <div class="column is-half">
              <ul class="is-size-4 is-size-6-mobile">
                <li>Single person: 850 ₹</li>
                <li>2 people: 1550 ₹</li>
                <li>3 people: 1850 ₹</li>
                <li>Group: 2000 ₹ onwards</li>
              </ul>
            </div>
            <div
              class="column right-text has-text-info is-one-quarter is-size-4 is-size-6-mobile"
            >(With colour/textured background and caption)</div>
          </div>
          <p
            class="is-size-4 is-size-6-mobile"
          >Customisation for activity, poses, props or background is 200 ₹ per person onwards</p>
        </div>
        <br />

        <div class="has-text-weight-semibold is-size-1 is-size-3-mobile">Portraits</div>
        <div class="subtext">
          <div class="columns">
            <div class="column is-half">
              <ul class="is-size-4 is-size-6-mobile">
                <li>Single person: 1000 ₹</li>
                <li>2 people: 1550 ₹</li>
                <li>3 people: 1850 ₹</li>
                <li>Group: 2200 ₹ onwards</li>
              </ul>
            </div>
            <div
              class="column right-text has-text-info is-one-quarter is-size-4 is-size-6-mobile"
            >(With colour/textured background and caption)</div>
          </div>
          <p
            class="is-size-4 is-size-6-mobile"
          >Customisation of background/clothing from references is 200 ₹ per person onwards, based on design and level of details</p>
        </div>
        <br />

        <div class="has-text-weight-semibold is-size-1 is-size-3-mobile">Logos/Flyers</div>
        <div class="subtext">
          <ul class="is-size-4 is-size-6-mobile">
            <li>500 ₹ per session of discussion (sketches + set of options)</li>
            <li>500 ₹ for final render files</li>
          </ul>
        </div>
        <br />

        <div class="has-text-weight-semibold is-size-1">Greeting cards</div>
        <div class="subtext">
          <ul class="is-size-4 is-size-6-mobile">
            <li>350 ₹ onwards</li>
          </ul>
        </div>
        <br />

        <div class="has-text-weight-semibold is-size-1 is-size-3-mobile">Wedding invites, book covers, etc</div>
        <div class="subtext">
          <ul class="is-size-4 is-size-6-mobile">
            <li>As per request</li>
          </ul>
        </div>
        <br />
      </b-tab-item>

      <b-tab-item label="Terms and Conditions">
          <div>
              <div class="is-size-2 is-size-4-mobile has-text-left">Thankyou for checking us out!! </div>
              <br/>
              
            <div class="is-size-3 is-size-5-mobile"> Here are some things to note, so you can love our creation for you as much as we love creating it for you!</div>
            <br/>
            <ol class="is-size-4 is-size-6-mobile">
                <li>Order atleast 10 days prior (or more) as urgent orders may lead to extra charge or may have to be declined.</li>
                <li>Please pick clear, front facing pictures of the person, to provide as reference for caricatures or portraits. And make sure you love the picture, as the artwork will be based on the image provided, unless changes specified while ordering.</li>
                <li>Please share full information regarding requirements, while placing order. Last minute additions or major changes may vary the promised delivery date and will be charged extra.</li>
                <li>Payment can be made online via. bank transfer, UPI (GooglePay, PhonePe). 50% advance while placing order and 50% upon delivery.</li>
                <li>The final renders will be shared as high quality soft copy (.png/.jpg/.pdf), ready to be printed or share as E-cards.</li>
            </ol>

            <br/>
            <p class="is-size-3 is-size-5-mobile">We are currently not undertaking printing or merchandise due to the pandemic situation, keeping your safety in mind. You will be notified if this changes! 😊</p>
          </div>
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
  padding-bottom: 2vh;
}

.tabs li.is-active a {
  border-bottom-color: $info !important;
  color: $info !important;
}

.pricing {
  padding-top: 8vh;
}

.subtext {
  padding-left: 7vw;
}

</style>
