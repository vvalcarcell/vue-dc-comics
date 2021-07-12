<template>
  <div class="container-fluid">
    <div class="container">
      <div class="links-space">
        <div class="column">
          <ul>
            <li>DC COMICS</li>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>
          <ul>
            <li>DC SHOP</li>
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC Collectibles</a></li>
          </ul>
        </div>

        <div class="column">
          <ul>
            <li>DC</li>
            <li><a href="#">Terms Of Use</a></li>
            <li><a href="#">Privacy Policy (New)</a></li>
            <li><a href="#">Ad Choices</a></li>
            <li><a href="#">Advertising</a></li>
            <li><a href="#">Jobs</a></li>
            <li><a href="#">Subscriptions</a></li>
            <li><a href="#">CPSC Certificates</a></li>
            <li><a href="#">Ratings</a></li>
            <li><a href="#">Shop Help</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
        </div>

        <div class="column">
          <ul>
            <li>SITES</li>
            <li><a href="#">DC</a></li>
            <li><a href="#">DC UNIVERSE INFINITE</a></li>
            <li><a href="#">DC Kids</a></li>
            <li><a href="#">DC Shop</a></li>
            <li><a href="#">MAD Magazine</a></li>
          </ul>
        </div>
      </div>

      <img src="../assets/dc-logo-bg.png" alt="" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style lang="scss" scoped>
.container-fluid {
  background-image: url("../assets/footer-bg.jpg");
  color: white;

  .container {
    max-height: 300px;
    display: flex;
    justify-content: space-between;
    overflow: hidden;

    img {
      margin-top: -80px;
      height: 450px;
    }

    .links-space {
      display: flex;

      .column {
        padding-top: 30px;
        margin-right: 30px;
        font-size: 12px;

        li {
          margin: 5px 0;
          &:first-child {
            font-size: 16px;
            font-weight: bold;
            margin: 10px 0;
          }

          &:hover {
            text-decoration: underline;
          }
        }
      }
    }
  }
}
</style>