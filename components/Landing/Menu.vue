<template>
  <ul>
    <li class="compare">
      <a href="#">On compare</a>
    </li>
    <li class="honetete">
      <a href="#">De l'honêteté</a>
    </li>
    <li class="discretion">
      <a href="#">De la discretion</a>
    </li>
    <li class="respect">
      <a href="#">Respect de la vie privé</a>
    </li>
    <li class="rencontre">
      <a href="#">Des rencontres autrement</a>
    </li>
    <li class="engagement">
      <a href="#">Pas d'engagement financier</a>
    </li>
  </ul>
</template>

<script setup lang="ts">

</script>

<style lang="scss" scoped>
@import "@/assets/css/_variables";

ul {
  text-align: right;
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: space-around;
  padding-top: 12em;
  padding-bottom: 12em;
  text-transform: uppercase;
  font-weight: 700;
  font-size: 1.5em;
}

.compare, .rencontre {
  color: $color-orange;
}

.discretion, .respect {
  color: $color-grey;
}

.engagement {
  color: $color-green;
}
</style>