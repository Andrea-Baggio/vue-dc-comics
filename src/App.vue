<template>
  <div>
    <header-page-vue></header-page-vue>
    <main-page-vue></main-page-vue>
    <footer-page-vue></footer-page-vue>
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

</style>
