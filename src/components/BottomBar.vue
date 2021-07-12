<template>
  <div class="container-fluid">
    <div class="container">
      <button>sing-up now!</button>

      <div class="follow-us">
        <span>follow us</span>
        <a href="#"><img src="../assets/footer-facebook.png" alt="" /></a>
        <a href="#"><img src="../assets/footer-twitter.png" alt="" /></a>
        <a href="#"><img src="../assets/footer-youtube.png" alt="" /></a>
        <a href="#"><img src="../assets/footer-pinterest.png" alt="" /></a>
        <a href="#"><img src="../assets/footer-periscope.png" alt="" /></a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "BottomBar",
};
</script>

<style lang="scss" scoped>
@import "../style/colors.scss";

.container-fluid {
  background-color: #333;
  color: white;

  .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 0;
    text-transform: uppercase;

    button {
      border-color: $blu-page;
      padding: 10px;
      background-color: #333;
      color: white;
      text-transform: uppercase;
      cursor: pointer;
    }

    .follow-us {
      display: flex;
      align-items: center;
      font-size: 15px;
      color: $blu-page;

      span {
        margin-right: 20px;
      }
      img {
        max-height: 30px;
        margin-right: 20px;
      }
    }
  }
}
</style>