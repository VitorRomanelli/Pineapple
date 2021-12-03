<template>
  <v-app>
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=DM+Sans:ital,wght@0,400;0,500;0,700;1,400;1,500&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,700&display=swap");

*,
html,
body {
  font-family: "DM Sans", sans-serif;
}

body::-webkit-scrollbar {
  background-color: #fff;
  width: 12px;
}

body::-webkit-scrollbar-thumb {
  background: linear-gradient(39.97deg, #2f1893 0.79%, #7834be 79.29%);
  border-radius: 20px;
}
</style>

<script>
export default {
  name: "App",

  data: () => ({
    //
  }),
};
</script>
