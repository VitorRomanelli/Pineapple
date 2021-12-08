<template>
  <div style="max-width: 370px">
    <v-card
      class="d-flex flex-column justify-center align-center pa-6 mb-4"
      style="border-radius: 10px"
      elevation="0"
      color="#2F1893"
    >
      <span class="head-title"> {{ title }} </span>

      <div class="d-flex justify-space-around my-4">
        <span class="description">R$</span>
        <strong class="price mx-2">{{ price }}</strong>
        <div>
          <span class="description">Por usuário</span>
          <br />
          <span class="description">Por mês</span>
        </div>
      </div>

      <div class="description">
        {{ description }}
      </div>
    </v-card>

    <div class="my-1" v-for="(course, index) in courses" :key="index">
      <v-icon class="mr-2" color="#25DAC5">mdi-check-bold</v-icon>
      <span class="list-active-text">{{ course }}</span>
    </div>

    <div class="my-1" v-for="(other, index) in others" :key="index + 'other'">
      <span class="list-inactive-text">{{ other }}</span>
    </div>

    <div class="mt-2">
      <v-btn
        color="#25DAC5"
        elevation="0"
        dark
        style="text-transform: none; border-radius: 10px"
      >
        Comprar
      </v-btn>
    </div>
  </div>
</template>

<style scoped>
.head-title {
  font-weight: bold;
  font-size: 14px;
  line-height: 26px;
  text-align: center;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: #ffffff;
}

.price {
  font-weight: bold;
  font-size: 58px;
  line-height: 70px;
  text-align: center;
  letter-spacing: -1px;
  color: #ffffff;
}

.description {
  font-weight: normal;
  font-size: 16px;
  line-height: 26px;
  text-align: center;
  color: #ffffff;
}

.list-active-text {
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 26px;
  color: rgba(21, 20, 57, 0.4);
}

.list-inactive-text {
  font-weight: normal;
  font-size: 16px;
  line-height: 26px;
  color: #dfdfdf;
}
</style>

<script>
export default {
  name: "PricingCard",

  props: {
    title: String,
    description: String,
    price: Number,
    courses: Array,
    others: Array,
  },
};
</script>

<style></style>
