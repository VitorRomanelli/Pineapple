<template>
  <div class="price-card pa-6 text-center">
    <h3 class="head-title">Simple & flexible pricing built for everyone</h3>

    <br />

    <span class="head-text">
      Start with 14-day free trial. No credit card needed. Cancel at anytime.
    </span>

    <br />
    <br />

    <v-row class="ma-0">
      <v-col cols="12" sm="4" v-for="n in 3" :key="n">
        <PricingCard title="Enterprise" />
      </v-col>
    </v-row>
  </div>
</template>

<style scoped>
.price-card {
  border-radius: 20px;
  background-color: #eee8;
}

.head-title {
  font-weight: bold;
  font-size: 42px;
  line-height: 52px;
  text-align: center;
  letter-spacing: -0.4px;

  color: #1e0e62;
}

.head-text {
  font-size: 16px;
  line-height: 26px;
  text-align: center;
  color: rgba(21, 20, 57, 0.4);
}
</style>

<script>
import PricingCard from "./pricing-card.vue";

export default {
  name: "PricingTable",

  components: {
    PricingCard,
  },
};
</script>

<style></style>
