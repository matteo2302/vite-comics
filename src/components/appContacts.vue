<script>
export default {
  data() {
    return {

    }
  }
}
</script>

<template>
  <div class="container">
    <div class="lists-container">
      <div class="list">
        <h3>DC COMICS</h3>
        <ul>
          <li>Characters</li>
          <li>Comics</li>
          <li>Movies</li>
          <li>TV</li>
          <li>Games</li>
          <li>Videos</li>
          <li>News</li>
        </ul>
        <h3>SHOP</h3>
        <ul>
          <li>Shop DC</li>
          <li>Shop DC Collectibles</li>
        </ul>
      </div>
      <div class="list">
        <h3>DC</h3>
        <ul>
          <li>Terms Of Use</li>
          <li>Privacy policy (New)</li>
          <li>Ad Choices</li>
          <li>Advertising</li>
          <li>Jobs</li>
          <li>Subscriptions</li>
          <li>Talent Workshops</li>
          <li>CPSC Certificates</li>
          <li>Ratings</li>
          <li>Shop Help</li>
          <li>Contact Us</li>
        </ul>
      </div>
      <div class="list">
        <h3>SITES</h3>
        <ul>
          <li>DC</li>
          <li>MAD Magazine</li>
          <li>DC Kids</li>
          <li>DC Universe</li>
          <li>DC Power Visa</li>
        </ul>
      </div>

    </div>
    <div class="img-container">
      <img src="../assets/img/dc-logo-bg.png" alt="">
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container {
  display: flex;
  align-items: center;
  height: 400px;
  overflow: hidden;
}


.lists-container {
  display: flex;
  width: 100%;
  justify-content: flex-start;
}

ul {
  color: rgb(125, 120, 103);

}

.list {
  margin: 0px;
  margin-right: 25px;
}

h3 {
  color: white;
  margin: 20px 0;
}
</style>
