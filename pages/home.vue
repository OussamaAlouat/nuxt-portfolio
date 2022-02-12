<template>
  <div>
¡    <header>
      <MainHeader/>
    </header>
    <main class="home">
      <div class="home__header">
        <h1 class="home__title">Oussama Alouat</h1>
        <div class="home__container">
          <div class="home__img-container">
            <div class="">
              Me llamo Oussama Alouat, soy Desarrollador Front-End. Llevo desde el año 2018 en el mundo del desarrollo de manera profesional
            </div>
          </div>
        </div>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  data() {
    return {
      img: './../assets/images/experience.jpg'
    }
  }

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
  };

  &__container {
    display: flex;
    justify-content: space-around;
    img {
      border-radius: 50%;
      scale: 0.5;
      width: 300px;
      height: 300px;
    }

    img:hover {
      transition: ease-out .1s;
    }
  }
}

.box-description {
  background: white;
    margin-top: 10px;
    width: 50%;
    border-radius: 10px;
}

</style>