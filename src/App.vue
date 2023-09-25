<script>
import AppHeader from './components/AppHeader.vue';
import AppHero from './components/AppHero.vue';
import AppProducts from './components/AppProducts.vue';
import AppServices from './components/AppServices.vue';
import AppFooterTop from './components/AppFooterTop.vue';
import AppFooterBot from './components/AppFooterBot.vue';

export default {
  
  data() {
    return {

    }
  },
  components: {
    AppHeader,
    AppHero,
    AppProducts,
    AppServices,
    AppFooterTop,
    AppFooterBot
  }

}
</script>

<template>
  <AppHeader />
  <!-- /#app_header -->
  <main id="app_main" class="position-relative z-3">
    <AppHero />
    <AppProducts />
    <AppServices />
    
  </main>
  <!-- /#app_main -->
  <AppFooterTop />
  <AppFooterBot />
  <!-- /#app_footer -->
</template>


<style lang="scss">
@use './assets/scss/app.scss';
</style>
