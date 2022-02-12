<template>
  <div class="h-100">
    <main-header id="app-header" />
    <home />
    <app-footer id="foot"/>
  </div>
</template>

<script>
import home from './home.vue'

import MainHeader from '~/components/MainHeader.vue'
import Footer from '~/components/Footer.vue'

export default {
  components: { home, 'app-footer': Footer, MainHeader }
}
</script>
<style lang="scss">
body {
  background: #f0efef;
}

#app-header {
  position: fixed;
  right: 0;
}

#foot {
  position: fixed;
  bottom: 1rem;
}
</style>
