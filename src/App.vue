<script>
export default {
  name: 'App',
  data() {
    return {

    }
  },
  components: {
    //     AppHeader,
    //     AppMain,
    //     AppLink,
    //     AppFooter
  }

}
</script>

<template>
  <header id="app_header">
    <nav class="navbar navbar-expand-lg">
      <div class="container d-flex justify-content-between">
        <div class="logo">
          <img src="./assets/img/dc-logo.png" alt="">
        </div>
        <div class="nav navbar-nav">
          <li class="nav-item">
            <a href="" class="nav-link active">CHARACTERS</a>
          </li>
          <li class="nav-item">
            <a href="" class="nav-link">COMICS</a>
          </li>
          <li class="nav-item">
            <a href="" class="nav-link">MOVIES</a>
          </li>
          <li class="nav-item">
            <a href="" class="nav-link">TV</a>
          </li>
          <li class="nav-item">
            <a href="" class="nav-link">GAMES</a>
          </li>
          <li class="nav-item">
            <a href="" class="nav-link">COLLECTIBLES</a>
          </li>
          <li class="nav-item">
            <a href="" class="nav-link">VIDEOS</a>
          </li>
          <li class="nav-item">
            <a href="" class="nav-link">FANS</a>
          </li>
          <li class="nav-item">
            <a href="" class="nav-link">NEWS</a>
          </li>
          <li class="nav-item">
            <a href="" class="nav-link">SHOP</a>
          </li>

        </div>

      </div>
    </nav>
  </header>
  <!-- /#app_header -->
  <main id="app_main">
    <section id="hero_section" class="py-5">
      <div class="container">

        <h2>==&gt;Content goes here&lt;==</h2>
      </div>
    </section>
    <section id="main_menu"></section>
  </main>
  <!-- /#app_main -->
  <footer id="app_footer">
    <section id="site_map"></section>
    <section id="social"></section>
  </footer>
  <!-- /#app_footer -->
</template>


<style lang="scss">
@use './assets/scss/app.scss';
</style>
