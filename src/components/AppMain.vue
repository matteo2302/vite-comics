<script>
import AppShopList from './AppShopList.vue';
import AppCards from './AppCards.vue';

export default {
  data() {
    return {
    }

  },
  props: {
    comic: Array,
  },
  components: {
    AppShopList,
    AppCards,
  },
}
</script>

<template>
  <div class="cards-container">
    <AppCards :comic="comic">
    </AppCards>
    <button>Load More</button>
  </div>

  <AppShopList />
</template>

<style lang="scss" scoped>
.cards-container {
  height: 800px;
  background-color: black;
  display: flex;
  flex-direction: column;
  align-items: center;
}

button {
  background-color: rgb(2, 130, 249);
  color: white;
  padding: 10px;
  margin-bottom: 40px;
}
</style>
