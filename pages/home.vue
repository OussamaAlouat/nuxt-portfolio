<template>
  <div class="home">
    <main class="home__main">
      <div class="home__main__header">
        <h1 class="home__main__title">Oussama Alouat</h1>
        <div class="home__main__container">
          Soy Desarrollador Front-End. Llevo desde el
          año 2018 en el mundo del desarrollo de manera profesional
        </div>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  data() {
    return {
      img: './../assets/images/experience.jpg',
    }
  },
}
</script>

<style lang="scss">
.home {
  height: 100%;

  &__main {
    display: flex;
    height: 100%;
    justify-content: center;
    &__header {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-content: center;
      text-align: center;
    }

    &__container {
      display: flex;
      justify-content: space-around;
      padding-top: 1rem;
    }
  }
}
</style>