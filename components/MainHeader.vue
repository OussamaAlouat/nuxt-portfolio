<template>
  <div class="main-header">
    <a class="active" href="#">Portfolio</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
.main-header {
  display: flex;
  flex-direction: row;
  justify-content: flex-end;
  padding: 2rem 4rem;
  a {
    margin-right: 8px;
    text-decoration: none;
    color: black;

    &.active {
      color: red;
      transform: rotate(25deg);
    }
  }

  a:hover {
    transform: rotate(15deg);
  }
}

</style>