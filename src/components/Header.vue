<template>
  <div class="container">
    <img src="../assets/dc-logo.png" alt="logo" />
    <ul>
      <li><a href="#">Characters</a></li>
      <li><a href="#">Comics</a></li>
      <li><a href="#">Movies</a></li>
      <li><a href="#">Tv</a></li>
      <li><a href="#">Games</a></li>
      <li><a href="#">Collectibles</a></li>
      <li><a href="#">Videos</a></li>
      <li><a href="#">Fans</a></li>
      <li><a href="#">News</a></li>
      <li><a href="#">Shop</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss" scoped>
@import "../style/colors.scss";

.container {
  display: flex;
  justify-content: space-between;
  margin-top: 20px;

  img {
    height: 60px;
  }

  ul {
    display: flex;

    li {
      height: 55px;
      margin: 20px 20px 0;
      font-size: 10px;
      font-weight: bold;
      text-transform: uppercase;

      &:hover {
        border-bottom: 4px solid $blu-page;
        cursor: pointer;
      }
    }
  }
}
</style>