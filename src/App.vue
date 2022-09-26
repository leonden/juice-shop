<template>
  <body>
    <AppNav />
    <main>
      <ProductTile />
    </main>
  </body>
</template>

<script>
import AppNav from "./components/AppNav.vue";
import ProductTile from "./components/ProductTile.vue";

export default {
  name: "App",
  components: {
    AppNav,
    ProductTile,
  },
};
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background-color: whitesmoke;
}
</style>
