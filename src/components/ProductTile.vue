<template>
  <div class="container">
    <div class="tile">
      <ProductDescription />
    </div>
  </div>
</template>

<script>
import ProductDescription from "./ProductDescription.vue";
export default {
  name: "ProductTile",
  components: { ProductDescription },
};
</script>

<style lang="scss" scoped>
.tile {
  width: 200px;
  height: 300px;
  background-color: white;
  box-shadow: 0 2px 7px -2px grey;
  border-radius: 25px;
  transition: 0.25s;
  &:hover {
    box-shadow: 0 2px 7px 0px grey;
    transition: 0.25s;
  }
}
</style>
