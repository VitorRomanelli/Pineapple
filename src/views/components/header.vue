<template>
  <div class="color-content pa-4">
    <div class="my-6">
      <h3 class="head-title">How To Protect Computer.</h3>
      <h3 class="head-title">Very Useful Tips</h3>
      <span class="head-subtitle">Splashproof Design</span>
    </div>

    <div class="d-flex my-6">
      <div class="mx-3">
        <v-img height="100" width="100" class="image"></v-img>
      </div>

      <div>
        <span class="head-subtitle">Samuel Audley</span>
        <br />
        <span class="head-text"> Saving the world. Shaping the world. </span>
        <div class="d-flex justify-space-around my-4">
          <v-icon color="white">mdi-facebook</v-icon>
          <v-icon color="white">mdi-twitter</v-icon>
          <v-icon color="white">mdi-linkedin</v-icon>
          <v-icon color="white">mdi-instagram</v-icon>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.color-content {
  height: 650px;
  background: #2f1893;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  align-items: center;
}

.head-title {
  font-family: DM Sans;
  font-style: normal;
  font-weight: bold;
  font-size: 58px;
  line-height: 70px;
  letter-spacing: -1px;
  color: #ffffff;
}

.head-subtitle {
  font-family: DM Sans;
  font-style: normal;
  font-weight: bold;
  font-size: 14px;
  line-height: 26px;
  letter-spacing: 2px;
  text-transform: uppercase;

  color: #ffffff;
}

.head-text {
  font-family: DM Sans;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 26px;
  color: #ffffff;
  mix-blend-mode: normal;
  opacity: 0.7;
}

.image {
  background: #ccc5;
  border-radius: 50%;
}

@media (max-width: 500px) {
  .head-title {
    font-size: 38px;
    line-height: 50px;
  }
}
</style>

<script>
export default {
  name: "Header",
};
</script>

<style></style>
