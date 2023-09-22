<script>
export default{
  name: 'App',
  data(){
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
    <div class="logo">
      <img src="./assets/img/dc-logo.png" alt="">
    </div>
    <nav class="navbar navbar-expand navbar-light bg-light">
        <div class="nav navbar-nav">
            <a class="nav-item nav-link active" href="#" aria-current="page">Home <span class="visually-hidden">(current)</span></a>
            <a class="nav-item nav-link" href="#">Home</a>
        </div>
    </nav>
  </header>
  <!-- /#app_header -->
  <main id="app_main">
    <section id="hero_section"></section>
    <section id="menu"></section>
  </main>
  <!-- /#app_main -->
  <footer id="app_footer">
    <section id="site_map"></section>
    <section id="social"></section>
  </footer>
  <!-- /#app_footer -->
 
</template>


<style lang = "scss">
@use './assets/scss/app.scss';
</style>
