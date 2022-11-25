<template>
  <main>
    <div class="content">
      <div class="content-box">
        Here
      </div>
    </div>

    <div class="images">
      <div class="images-box">
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
  name: 'MainPage',
};
</script>

<style lang="scss" scoped>
.content {
  background-color: rgb(28, 28, 28);
  color: white;
  font-size: 2em;
  padding: 2rem 0;
}
.content-box {
  margin: auto;
  width: 1100px;
}

.images {
  background-color: rgb(2, 130, 249);
  color: white;
  font-size: .8em;
  padding: 2rem 0;
}

.images-box {
  margin: auto;
  width: 1100px;
  height: 60px;
  display: flex;
  align-items: center;
}

.images-box img{
  height: 100%;
}

span {
  margin-right: 2rem;
  margin-left: 1rem;
}
</style>
