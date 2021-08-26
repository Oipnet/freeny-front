<template>
  <header>
    <img src="@/assets/images/logo/logo_small_icon_only.png" alt="Logo FreeNy">
    <div class="content">
      <h1>FREE aNd You</h1>
      <h2>Libre et vous</h2>
      <div class="cta">
        <a href="#">Déjà inscrit</a>
        <a href="#">Inscription</a>
      </div>
    </div>
  </header>
</template>

<script setup lang="ts">
</script>

<style lang="scss" scoped>
  @import "@/assets/css/_variables";

  header {
    color: $color-orange;
    border: 1px solid $color-orange;
    border-radius: 50%;
    width: 625px;
    height: 625px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    margin: auto;
  }

  h1 {
    font-size: 4.1em;
    margin-bottom: 0.5em;
  }

  h2 {
    font-size: 1.5em;
    margin-bottom: 2.25em;
  }

  .cta {
    display: flex;
    justify-content: space-between;
  }

  .content {
    transform: translateY(-50px);
  }

  @media screen and (max-width: 1024px) {
    header {
      grid-row: 1;
      border: none;
      width: 100vw;
      height: 15em;
      flex-direction: row;
      justify-content: space-between;
    }

    header img {
      height: 180px;
      width: 180px;
    }

    .content {
      transform: translateY(0px);
    }
  }
</style>