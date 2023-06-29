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
        <li v-for:"component in navComponents"><a href="{{ url }}">{{ text }}</a></li>
      </ul>
    </nav>
  </div>
</template>

<style lang="scss"></style>
