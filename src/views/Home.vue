<template>
  <div>
    <Header />

    <v-container class="d-flex justify-center my-4">
      <div class="content">
        <div class="my-4">
          <h3 class="section-title">Branding</h3>

          <span class="section-text my-4">
            This sounded nonsense to Alice, so she said nothing, but set off at
            once toward the Red Queen. To her surprise, she lost sight of her in
            a moment, and found herself walking in at the front-door again.
          </span>

          <br />
          <br />

          <span class="section-text my-4">
            For some minutes Alice stood without speaking, looking out in all
            directions over the country - and a most curious country it was.
            There were a number of tiny little brooks running straight across it
            from side to side, and the ground between was divided up into
            squares by a number of little.
          </span>
        </div>

        <div class="my-4">
          <h3 class="section-subtitle">Perfect for Your</h3>

          <span class="section-text">
            She gave my mother such a turn, that I have always been convinced I
            am indebted to Miss Betsey for having been born on a Friday. The
            word was appropriate to the moment.
          </span>
        </div>

        <v-img src="../assets/students1.jpg" class="image my-3"></v-img>

        <span class="image-legend ml-3">There have not been any since</span>

        <br />
        <br />

        <div class="my-4">
          <h3 class="section-subtitle">The Fall Report</h3>

          <span class="section-text">
            This sounded nonsense to Alice, so she said nothing, but set off at
            once toward the Red Queen. To her surprise, she lost sight of her in
            a moment, and found herself walking in at the front-door again.
          </span>
        </div>

        <div class="mb-6">
          <v-list>
            <v-list-item class="d-flex align-center" v-for="n in 3" :key="n">
              <v-icon class="mr-2" small color="#1E0E62">
                mdi-checkbox-blank-circle
              </v-icon>

              <v-list-item-content class="list-item-text">
                <v-list-item-title>
                  Thus much I thought proper to tell you in relation to
                  yourself, and to the trust I reposed in you.
                </v-list-item-title>
              </v-list-item-content>
            </v-list-item>
          </v-list>

          <span class="section-text mt-2">
            She gave my mother such a turn, that I have always been convinced I
            am indebted to Miss Betsey for having been born on a Friday. The
            word was appropriate to the moment.
          </span>
        </div>

        <PricingTable />

        <v-divider class="my-6"></v-divider>

        <h3 class="section-title my-4">Cursos</h3>

        <v-parallax
          style="width: 100%; border-radius: 20px"
          src="https://images.unsplash.com/photo-1521737711867-e3b97375f902?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxjb2xsZWN0aW9uLXBhZ2V8MXw0Nzg3Nzg2fHxlbnwwfHx8fA%3D%3D&w=1000&q=80"
        ></v-parallax>

        <v-divider class="my-6"></v-divider>

        <div
          class="
            mt-8
            d-flex
            flex-column
            justify-center
            align-center
            text-center
          "
        >
          <h3 class="section-title my-4">Testemunhos</h3>

          <v-icon x-large>mdi-format-quote-open-outline</v-icon>

          <v-carousel
            cycle
            :show-arrows="false"
            hide-delimiter-background
            delimiter-icon="mdi-minus"
            height="300"
          >
            <v-carousel-item v-for="test in 3" :key="test">
              <span class="my-4 list-item-text">
                asdlfjYou can decide whether to create your site using UI Kit
                blocks or samples. The blocks can merge together in various
                combinations.
              </span>

              <div class="d-flex flex-column align-center justify-center">
                <v-img
                  height="100"
                  width="100"
                  class="image-testimonial"
                ></v-img>

                <span class="mt-4 list-item-text">Jordan Bargeman</span>
                <span class="image-legend">Google</span>
              </div>
            </v-carousel-item>
          </v-carousel>
        </div>
      </div>
    </v-container>

    <Footer />
  </div>
</template>

<style scoped>
.content {
  margin-top: 40px;
  max-width: 70%;
}

.section-title {
  font-weight: bold;
  font-size: 42px;
  line-height: 52px;
  letter-spacing: -0.4px;
  color: #1e0e62;
}

.section-text {
  font-weight: normal;
  font-size: 16px;
  line-height: 26px;
  color: rgba(21, 20, 57, 0.4);
  mix-blend-mode: normal;
}

.section-subtitle {
  font-weight: 500;
  font-size: 22px;
  line-height: 32px;
  color: #1e0e62;
}

.image {
  border-radius: 20px;
}

.image-legend {
  font-weight: bold;
  font-size: 14px;
  line-height: 26px;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: rgba(21, 20, 57, 0.4);
  mix-blend-mode: normal;
}

.list-item-text {
  font-weight: 500;
  font-size: 18px;
  line-height: 28px;

  color: #1e0e62;
}

.image-testimonial {
  background: #ccc5;
  border-radius: 50%;
}

@media (max-width: 500px) {
  .content {
    max-width: 90%;
  }
}
</style>

<script>
import Header from "./components/header";
import PricingTable from "./components/pricing-table";
import Footer from "./components/footer";

export default {
  name: "Home",

  components: {
    Header,
    PricingTable,
    Footer,
  },
};
</script>
