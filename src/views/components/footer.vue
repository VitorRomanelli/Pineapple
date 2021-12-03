<template>
  <v-footer class="flex-column py-6" color="#2F1893" padless>
    <div class="text-center">
      <div class="d-flex justify-space-between footer-list-text my-6">
        <span class="mx-2">Tour</span>
        <span class="mx-2">Features</span>
        <span class="mx-2">Pricing plans</span>
        <span class="mx-2">Our works</span>
        <span class="mx-2">brands</span>
        <span class="mx-2">contacts</span>
      </div>

      <v-divider class="my-4 grey"></v-divider>

      <span class="copy my-2">© 2016 Designmodo. All rights reserved.</span>
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
