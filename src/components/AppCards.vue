<script>
export default {
  data() {
    return {
    }
  },

  promps: {
    comic: array,
  }
}
</script>

<template>
  <div class="container">
    <div class="card" v-for="fumetto in comic">
      <img :src="fumetto.thumb" alt="comic">
      <h1>ciao</h1>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container {
  height: 500px;
}

.card {
  height: 150px;
  width: 100px;

  img {
    height: 100%;
  }
}

h1 {
  color: white;
}
</style>
