<template>
  <div>
    <nav>
      <div class="logo">
        <h4>Juice Shop</h4>
      </div>
      <ul class="nav-links">
        <li><a href="#">Juices</a></li>
        <li><a href="#">Fruits</a></li>
        <li><a href="#">About</a></li>
      </ul>
      <div class="burger">
        <div class="line1"></div>
        <div class="line2"></div>
        <div class="line3"></div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "AppNav",
};
</script>

<style lang="scss" scoped>
@import "../assets/scss/global";

nav {
  width: 100%;
  min-height: 8vh;
  background-color: white;
  box-shadow: 0 2px 4px 0 rgb(0 0 0 / 20%);
  @include flex-row();

  .logo {
    font-family: "Lobster Two", sans-serif;
  }
}
</style>
