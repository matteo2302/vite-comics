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
  <div class="title-content">
    <div class="container">
      <h1>content goes here</h1>
    </div>
  </div>
</template>

<style lang="scss">
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
  }

  ul {
    display: flex;
    height: 140px;
    align-items: center;

    li {
      margin: 0 8px;

      height: 140px;

      width: 50px;
    }
  }
}

.title-content {
  height: 150px;
  background-color: black;
  color: white;

}

h1 {
  height: 100%;
  vertical-align: middle;
}
</style>
