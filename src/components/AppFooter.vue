<script>
import AppContacts from './appContacts.vue';
import AppSocials from './AppSocials.vue';
export default {
  data() {
    return {

    }
  },
  components: {
    AppContacts,
    AppSocials
  }
}
</script>

<template>
  <div class="main-bg">
    <appContacts />
    <AppSocials />
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
