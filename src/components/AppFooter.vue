<script>
import appContacts from './appContacts.vue';
export default {
  data() {
    return {

    }
  },
  components: {
    appContacts
  }
}
</script>

<template>
  <div class="main-bg">
    <appContacts />
  </div>
</template>

<style lang="scss" scoped>
.main-bg {
  width: 100%;
  background-image: url('../assets/img/footer-bg.jpg');
  background-repeat: no-repeat;
  background-size: cover;

  height: 400px;
}
</style>
