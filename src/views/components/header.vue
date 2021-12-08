<template>
  <div class="color-content pa-4">
    <div class="my-6">
      <h3 class="head-title">Pineaple</h3>
      <span class="head-subtitle"
        >Uma solução inovadora para o seu aprendizado</span
      >
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
