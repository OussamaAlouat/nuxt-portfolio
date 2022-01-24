<template>
  <div>
    <header>
      <MainHeader/>
    </header>
    <main class="home">
      <div class="home__header">
        <h2 class="home__title">Oussama Alouat</h2>
        <p>{{ $t('hello') }}</p>
      </div>
    </main>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
.home {
  &__header {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-content: center;
    text-align: center;
  }
}


</style>