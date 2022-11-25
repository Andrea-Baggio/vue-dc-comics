<template>
  <footer>
    <div class="list-bg">
      <div class="list-container">
        <div class="first-col">
          <h3>DC COMICS</h3>
          <ul>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Collectibles</li>
            <li>Videos</li>
            <li>Fans</li>
            <li>News</li>
          </ul>

          <h3>SHOP</h3>
          <ul>
            <li>Shop DC</li>
            <li>Shop DC collectibles</li>
          </ul>
        </div>

        <div class="second-col">
          <h3>DC</h3>
            <ul>
              <li>Term Of Use</li>
              <li>Privacy policy (New)</li>
              <li>Ad Choices</li>
              <li>Advertising</li>
              <li>Jobs</li>
              <li>Subscriptions</li>
              <li>Talent Workshops</li>
              <li>CPSC Certificates</li>
              <li>Ratings</li>
              <li>Shop Help</li>
              <li>Contacr Us</li>
            </ul>
        </div>

        <div class="third-col">
          <h3>SITES</h3>
          <ul>
            <li>DC</li>
            <li>MAD Magazine</li>
            <li>DC Kids</li>
            <li>DC Universe</li>
            <li>DC Power Visa</li>
          </ul>
        </div>
      </div>
    </div>

    <div class="socials-container">
      <div class="socials-box">
        <div class="button-box">
          <button>SIGN-UP NOW!</button>
        </div>
        <div class="socials">
          FOLLOW US
          <img src="@/img/footer-facebook.png" alt="">
          <img src="@/img/footer-twitter.png" alt="">
          <img src="@/img/footer-youtube.png" alt="">
          <img src="@/img/footer-pinterest.png" alt="">
          <img src="@/img/footer-periscope.png" alt="">
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'FooterPage',
};
</script>

<style lang="scss" scoped>
.list-bg {
  background-image: url('@/img/footer-bg.jpg');
  padding: 3rem 0;
}

.list-container {
  width: 1100px;
  margin: auto;
  color: gray;
  display: flex;
  gap: 5rem;
}

h3 {
  color: white;
  font-weight: bold;
  padding-bottom: .5rem;
}

li {
  font-size: .9em;
  font-weight: lighter;
  padding-bottom: .3rem;
}

.socials-container {
  background-color: rgb(48, 48, 48);
  padding: 1rem 0;
}

.socials-box {
  width: 1100px;
  margin: auto;
  display: flex;
}

.button-box {
  flex-basis: 50%;
}

button {
  background-color: rgb(48, 48, 48);
  border: 2px solid rgb(2, 130, 249);
  color: white;
  white-space: nowrap;
  padding: .7rem;
}

button:hover {
  cursor: pointer;
  background-color: rgb(66, 66, 66);
}

.socials {
  color: rgb(2, 130, 249);
  font-weight: bold;
  display: flex;
  justify-content: end;
  align-items: center;
  flex-basis: 50%;
  gap: .8rem;
}
</style>
