<script>
export default{
  name: 'App',
  data(){
    return {

    }
  },
//   components: {
//     AppHeader,
//     AppMain,
//     AppLink,
//     AppFooter
// }

}
</script>

<template>

  <header id="app_header"></header>
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
