<template>
  <main>
    <div class="link-container">
    <a href="#">--> Content goes here &#x3c;--</a>
    </div>
    <div class="icons-container">
      <div class="image-container">
        <img src="@/img/buy-comics-digital-comics.png" alt="">
        <img src="@/img/buy-comics-digital-comics.png" alt="">
      </div>
    </div>
  </main>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
  .link-container {
    background-color: rgb(28, 28, 28);
    padding: 2rem 0;
  }

  a {
    color: white;
    text-decoration: none;
    font-size: 2em;
    padding: 5rem;
  }
  .icons-container {
    background-color: rgb(2, 130, 249);
    padding: 2rem 0;
  }
  .image-container {
    height: 60px;
  }
  .image-container img {
    height: 100%;
  }

</style>
