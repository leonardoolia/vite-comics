<script >
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  name: 'DCComics',
  data: () => ({
    items: [
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
    ]

  }),

  components: { AppHeader, AppMain, AppFooter }
}
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppFooter />
</template>

<style></style>
