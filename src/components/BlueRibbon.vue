<template>
  <div class="container-fluid">
    <div class="container">
      <ul>
        <li>
          <img src="../assets/buy-comics-digital-comics.png" alt="" />
          <span><a href="#">digital comics</a></span>
        </li>

        <li>
          <img src="../assets/buy-comics-merchandise.png" alt="" />
          <span><a href="#">dc merchandise</a></span>
        </li>

        <li>
          <img src="../assets/buy-comics-subscriptions.png" alt="" />
          <span><a href="#">subscription</a></span>
        </li>

        <li>
          <img src="../assets/buy-comics-shop-locator.png" alt="" />
          <span><a href="#">comic shop locator</a></span>
        </li>

        <li>
          <img src="../assets/buy-dc-power-visa.svg" alt="" />
          <span><a href="#">dc power visa</a></span>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "BlueRibbon",
};
</script>

<style lang="scss" scoped>
@import "../style/colors.scss";

.container-fluid {
  background-color: $blu-page;

  .container {
    padding: 50px;

    ul {
      display: flex;

      li {
        display: flex;
        align-items: center;
        text-transform: uppercase;
        color: white;
        font-size: 13px;
        margin-right: 50px;

        &:last-child img {
          max-height: 30px;
        }

        img {
          max-height: 50px;
          margin-right: 10px;
        }
      }
    }
  }
}
</style>