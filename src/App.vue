<template>
  <div>
    <HeaderPageVue />
    <MainPageVue />
    <FooterPageVue />
  </div>
</template>

<script>
import HeaderPageVue from './components/HeaderPage.vue';
import MainPageVue from './components/MainPage.vue';
import FooterPageVue from './components/FooterPage.vue';

export default {
  components: {
    HeaderPageVue,
    MainPageVue,
    FooterPageVue,
  },
};
</script>

<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  li {
    list-style: none;
  }
</style>
