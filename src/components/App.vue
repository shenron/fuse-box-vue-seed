<template>
  <v-app id="example-1" toolbar footer>
    <navigation></navigation>
    <main>
      <v-container fluid class="content">
        <router-view></router-view>
      </v-container>
    </main>
  </v-app>
</template>
<style lang="scss">
  // FontAwesome
  $fa-font-path: '../../node_modules/font-awesome/fonts/';
  @import 'font-awesome';

  // Bootstrap
  $icon-font-path: '../../node_modules/bootstrap-sass/assets/fonts/bootstrap/';
  @import 'bootstrap';
</style>
<script>
  import Navigation from './Navigation.vue';

  export default {
    components: {
        Navigation
    }
  }
</script>
