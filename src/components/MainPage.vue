<template>
  <main>
    <div class="link-container">
    <a href="#">--> Content goes here &#x3c;--</a>
    </div>
    <div class="icons-container">
      <div class="image-container">
        <img src="@/img/buy-comics-digital-comics.png" alt="">
        <span>DIGITAL COMICS</span>
        <img src="@/img/buy-comics-merchandise.png" alt="">
        <span>MERCHANDISE</span>
        <img src="@/img/buy-comics-subscriptions.png" alt="">
        <span>SUBSCRIBTIONS</span>
        <img src="@/img/buy-comics-shop-locator.png" alt="">
        <span>COMICS SHOP LOCATOR</span>
        <img src="@/img/buy-dc-power-visa.svg" alt="">
        <span>DC POWER VISA</span>
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
    padding: 3rem 0;
  }
  .image-container {
    height: 50px;
    display: flex;
    align-items: center;
    color: white;
  }
  .image-container img {
    padding-left: 5rem;
    height: 100%;
  }

  span {
    margin-left: .6em;
    font-size: .8em;
  }

</style>
