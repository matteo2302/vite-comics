<script>
export default {
  data() {
    return {
      navComponents: [
        {
          text: 'Characters',
          url: '#',
          current: false,
        },
        {
          text: 'Comics',
          url: '#',
          current: true,
        },
        {
          text: 'Movies',
          url: '#',
          current: false,
        },
        {
          text: 'TV',
          url: '#',
          current: false,
        },
        {
          text: 'Games',
          url: '#',
          current: false,
        },
        {
          text: 'Collectibles',
          url: '#',
          current: false,
        },
        {
          text: 'Videos',
          url: '#',
          current: false,
        },
        {
          text: 'Fans',
          url: '#',
          current: false,
        },
        {
          text: 'News',
          url: '#',
          current: false,
        },
        {
          text: 'Shop',
          url: '#',
          current: false,
        },
      ],

    }
  }
}
</script>

<template>
  <div class="container">
    <nav>
      <img src="../assets/img/dc-logo.png" alt="logo">
      <ul>
        <li v-for="(component, i) in navComponents" :key="i" :class="{ active: component.current }"><a
            href="{{ component.url }}">{{
              component.text }}</a></li>
      </ul>
    </nav>
  </div>
  <div class="main-bg"></div>
</template>

<style lang="scss" scoped>
@use '../assets/scss/vars' as *;

.active {
  border-bottom: 7px solid rgb(2, 130, 249);
}

nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 140px;

  img {
    width: 100px;
    align-self: flex-start;
    margin: 20px 0;
  }

  ul {
    display: flex;
    align-items: center;
    justify-content: flex-end;
    width: 100%;

    li {
      margin: 0 8px;
      width: 70px;
      text-align: center;
      height: 140px;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }
  }
}

.main-bg {
  @include main-bg (url(../assets/img/jumbotron.jpg));
}
</style>
