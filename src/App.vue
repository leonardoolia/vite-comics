<script >
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  name: 'DCComics',
  data: () => ({
    sections: [
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

    mainList: [
      {
        img: '@/assets/img/buy-comics-digital-comics.png',
        text: 'DIGITAL COMICS'
      },
      {
        img: '@/assets/img/buy-comics-merchandise.png',
        text: 'DC MERCHANDISE'
      },
      {
        img: '@/assets/img/buy-comics-subscriptions.png',
        text: 'SUBSCRIPTION'
      },
      {
        img: '@/assets/img/buy-comics-shop-locator.png',
        text: 'COMIC SHOP LOCATOR'
      },
      {
        img: '@/assets/img/buy-dc-power-visa.svg',
        text: 'DC POWER VISA'
      }
    ]

  }),

  components: { AppHeader, AppMain, AppFooter }
}
</script>

<template>
  <AppHeader :sections="sections" />
  <AppMain />
  <AppFooter />
</template>

<style>
/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Generics */
img {
  max-width: 100%;
  height: auto;
}

a {
  color: black;
  text-decoration: none;
}

li {
  list-style-type: none;
}

body {
  min-height: 100vh;
}

/* Utils */
.container {
  margin: 0 auto;
  max-width: 1200px;
}
</style>
