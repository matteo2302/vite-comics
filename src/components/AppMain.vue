<script>
import AppShopList from './AppShopList.vue';
export default {
  data() {
    return {
    }

  },
  components: {
    AppShopList,
  },
}
</script>

<template>
  <div class="title-content">
    <div class="container">
      <h1>content goes here</h1>
    </div>
  </div>
  <AppShopList />
</template>

<style lang="scss" scoped>
.title-content {
  height: 150px;
  background-color: black;
  color: white;


  .container {
    height: 100%;
    display: flex;
    align-items: center;
  }
}

h1 {
  width: 100%
}
</style>
