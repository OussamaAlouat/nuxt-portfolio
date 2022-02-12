<template>
  <div class="h-100">
    <MainHeader id="app-header" />
    <home />
  </div>
</template>

<script>
import home from './home.vue'
export default {
  components: { home }
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
</style>
