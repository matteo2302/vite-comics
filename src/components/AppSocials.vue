<script>
export default {
  data() {
    return {

    }
  }
}
</script>

<template>
  <div class="socials-footer">
    <div class="container">
      <button><a href="#">SIGN-UP NOW</a></button>
      <div class="socials-list">
        <h2>FOLLOW US</h2>
        <ul>
          <li><a href="#"><img src="../assets/img/footer-facebook.png" alt="Facebook"></a></li>
          <li><a href="#"><img src="../assets/img/footer-twitter.png" alt="Twitter"></a></li>
          <li><a href="#"><img src="../assets/img/footer-youtube.png" alt="Youtube"></a></li>
          <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt="Pinterest"></a></li>
          <li><a href="#"><img src="../assets/img/footer-periscope.png" alt="Preiscope"></a></li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.socials-footer {
  background-color: rgb(48, 48, 48);
  height: 90px;
}

.container {
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 90px;
}

.socials-list {
  display: flex;
  color: rgb(2, 130, 249);
  margin: 0;
  align-items: center;
}

ul {
  display: flex;

  li {
    margin: 0 10px;
  }
}

button {
  height: 50px;
  border: 2px solid rgb(2, 130, 249);

  background-color: transparent;
  margin: 0;
  padding: 5px;

  a {
    color: white;
  }
}
</style>
