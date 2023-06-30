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
  </div>

  <AppShopList />
</template>

<style lang="scss" scoped>
.cards-container {
  height: 600px;
  background-color: black;
}
</style>
