<!-- js -->
<script>
// importo i componenti
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  data() {
    return {

    };
  },
  components: { AppHeader, AppMain, AppFooter }
};
</script>

<!-- html -->
<template>
  <header>
    <app-header />
  </header>

  <main>
    <app-main />
  </main>

  <footer>
    <app-footer />
  </footer>
</template>

<!-- css -->
<style lang ="scss">
@use "./styles/general.scss";
</style>