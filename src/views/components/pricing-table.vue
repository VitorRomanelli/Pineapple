<template>
  <div class="price-card pa-6 text-center">
    <h3 class="head-title">Um preço simples e flexivel construido para você</h3>

    <br />

    <span class="head-text"> Comece agora, cancele quando quiser. </span>

    <br />
    <br />

    <v-row class="ma-0">
      <v-col cols="12" sm="4" v-for="(n, index) in prices" :key="index">
        <PricingCard
          :title="n.title"
          :description="n.description"
          :price="n.price"
          :courses="n.courses"
          :others="n.others"
        />
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

  data: () => ({
    prices: [
      {
        title: "Combo Software",
        price: 200,
        description:
          "Nesse curso você irá aprender a utilizar bem os sistemas operacionais (Windows e linux), desenvolvendo os conhecimentos  adquiridos para otimizar seu aprendizado no curso de programação. ",
        courses: ["Programação", "Informática (dedicada)"],
        others: ["Inglês técnico", "Montagem e manutenção"],
      },
      {
        title: "Combo de redes",
        price: 275,
        description:
          "No Curso de Infra de redes você irá adquirir diversas habilidades novas para acrescentar no seu currículo desde aprendera projetar até conhecer sobre padrões de cabeamento e protocolos de rede, sem falar do inglês técnico que vai ajudar muito na sua jornada no mundo da tecnologia.",
        courses: ["Projetista em Infraestrutura de Redes ", "Inglês técnico"],
        others: ["Programação", "Informática (dedicada)"],
      },
      {
        title: "Combo técnico",
        price: 243,
        description:
          "Nesse curso você irá aprender sobre a arquitetura de um computador, como montar e desmontar, além de entender como os componentes do computador se comportam. Como alguns sabem o conhecimento de outra língua é um diferencial, na área de tecnologia é indispensável, foi pensando nisso que nesse combo implementamos o inglês técnico.",
        courses: ["Inglês técnico", "Montagem e manutenção"],
        others: ["Programação", "Informática (dedicada)"],
      },
    ],
  }),
};
</script>

<style></style>
