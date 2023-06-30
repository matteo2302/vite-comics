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
@use '../assets/scss/vars' as *;

.main-bg {
  @include main-bg (url(../assets/img/footer-bg.jpg));
}
</style>
