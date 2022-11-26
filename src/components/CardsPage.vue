<template>
  <div class="container">
    <div class="card">
      <img
      :src="imgUrl"
      alt="">
      <h5>{{ title }}</h5>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CardsPage',
  props: {
    imgUrl: String,
    title: String,
  },
};
</script>

<style lang="scss" scoped>

</style>
