<template>
  <v-footer class="flex-column py-6" color="#2F1893" padless>
    <div class="text-center">
      <div class="d-flex justify-space-between footer-list-text my-6">
        <v-btn text dark href="#general">
          <span class="mx-2">Visão geral</span>
        </v-btn>
        <v-btn text dark href="#prices">
          <span class="mx-2">Planos de preço</span>
        </v-btn>
        <v-btn text dark href="#courses">
          <span class="mx-2">Cursos</span>
        </v-btn>
        <v-btn text dark href="#witnesses">
          <span class="mx-2">Testemunhos</span>
        </v-btn>
      </div>

      <v-divider class="my-4 grey"></v-divider>

      <span class="copy my-2">© 2021. All rights reserved.</span>
    </div>
  </v-footer>
</template>

<style scoped>
.footer-list-text {
  font-weight: bold;
  font-size: 14px;
  line-height: 26px;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: #ffffff;
}

.copy {
  font-weight: normal;
  font-size: 16px;
  line-height: 26px;
  text-align: center;
  color: #ffffff;

  mix-blend-mode: normal;
}
</style>

<script>
export default {
  name: "Footer",
};
</script>

<style></style>
