<template>
  <div id="app">
    <div>
        <Navigation/>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
.navbar-brand {
  z-index: 10;
}
  @import "../node_modules/bootstrap/dist/css/bootstrap.min.css";
</style>

<script>
// @ is an alias to /src
import Navigation from '@/components/Navigation.vue'

export default {
  name: 'navigation',
  components: {
    Navigation
  }
}
</script>
