<template>
  <header>
    <nav>
      <div class="logo-container">
        <img src="@/img/dc-logo.png" alt="">
      </div>

      <ul>
        <li>CHARACTERS</li>
        <li>COMICS</li>
        <li>MOVIES</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>COLLECTIBLES</li>
        <li>VIDEOS</li>
        <li>FANS</li>
        <li>NEWS</li>
        <li>SHOP</li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'HeaderPage',
};
</script>

<style lang="scss" scoped>
  nav {
    display: flex;
    justify-content: space-around;
  }
  .logo-container {
    flex: 0 0 auto;
    height: 100px;
  }
  .logo-container img {
    height: 100%;
    padding: .5rem;
  }

  ul {
    display: flex;
    justify-content: space-evenly;
    flex: 0 0 70%;
    list-style: none;
  }

  li {
    display: flex;
    align-items: center;
    font-weight: bold;
    font-size: .9em;
  }

  li:hover {
    cursor: pointer;
    color: rgb(2, 130, 249);
    border-bottom: 5px solid rgb(2, 130, 249);
  }
</style>
