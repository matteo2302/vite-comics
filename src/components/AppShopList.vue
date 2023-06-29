
<script>
export default {
  data() {
    return {

    }
  }
}
</script>
<template>
  <div class="shop-cont">
    <div class="container">
      <ul>
        <li>
          <img src="../assets/img/buy-comics-digital-comics.png" alt=" t-shirt">
          <a href="#">DIGITAL COMICS</a>
        </li>
        <li>
          <img src="../assets/img/buy-comics-merchandise.png" alt=" t-shirt">
          <a href="#">DC MERCHANDISE</a>
        </li>
        <li>
          <img src="../assets/img/buy-comics-subscriptions.png" alt=" t-shirt">
          <a href="#">SUBSCRIPTION</a>
        </li>
        <li>
          <img src="../assets/img/buy-comics-shop-locator.png" alt=" t-shirt">
          <a href="#">COMIC SHOP LOCATOR</a>
        </li>
        <li>
          <img src="../assets/img/buy-dc-power-visa.svg" alt=" t-shirt">
          <a href="#">DC POWER VISA</a>
        </li>

      </ul>
    </div>
  </div>
</template>
<style lang="scss" scoped>
.shop-cont {
  background-color: rgb(2, 130, 249);
  height: 120px;

}

.container {
  display: flex;
  align-items: center;
  height: 100%;
}

ul {
  display: flex;
  justify-content: space-between;
  width: 100%;

  li {
    display: flex;
    align-items: center;
    color: white;
  }
}

img {

  max-width: 60px;
  max-height: 70px;

}
</style>