<script>
export default {
  data() {
    return {
    }
  },

  props: {
    comic: Array,
  }
}
</script>

<template>
  <div class="container">
    <div class="card" v-for="fumetto in comic">
      <img :src="fumetto.thumb" alt="comic">
      <h4>{{ fumetto.series }}</h4>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container {
  height: 100%;
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;

}

.card {
  height: 200px;
  width: calc(100% / 6);
  padding: 20px;

  img {
    width: 100%;
    height: 100%;
  }
}

h4 {
  color: white;
}
</style>
