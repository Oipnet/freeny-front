<template>
  <aside>
    <div class="search">
      <h2>Ma recherche</h2>
      <i class="ri-arrow-left-s-line"></i>
    </div>
    <div class="localisation">
      <span class="bold">Localisation :</span>
      <div class="distance">
        <span class="rounded-pils">+5Km</span>
        <span class="rounded-pils">+25Km</span>
        <span class="rounded-pils">+100Km</span>
      </div>
      <p>
        Ma position: <br>
        7rue de la liberté 2271 langon
      </p>
    </div>
    <a href="#">Modifier ma postion </a>
    <div class="recherche">
      <p class="bold">Sexe</p>
      <div class="genre">
        <span class="rounded-pils">Homme</span>
        <span class="rounded-pils">Femme</span>
      </div>
      <div>
        <span class="rounded-pils">Hetero</span>
        <span class="rounded-pils">Homo</span>
        <span class="rounded-pils bi">Bi</span>
      </div>
      <p class="more-option">Plus d'option</p>
      <button> Lancer la recherche</button>
    </div>
      <h2>Mes chats</h2>
    <div class="conversation">
      <p>Jane Doe</p>
    </div>
  </aside>
</template>

<script  setup lang="ts">
</script>

<style lang="scss" scoped>
@import "@/assets/css/_variables";

div{
  color: $color-orange;
  display: flex;
  align-items: center;
  flex-direction: column;
}
aside{
  width: 16%;
  display: flex;
  height: 86vh;
  flex-direction: column;
  align-items: center;
  border-right: 1px solid $color-yellow;
}
.search{
  width: 100%;
  justify-content: space-between;
  margin-bottom: 1rem;
  flex-direction: row;
}
h2{
  width: 100%;
  font-size: 2rem;
  color: $color-black;
  font-weight: bold;
  line-height: 2em;
  padding-left: 2rem;
}
.distance{
  flex-direction: row;

}
p{
  text-align: center;
  margin: 1em 0;
}
.recherche div{
  flex-direction: row;
}
.recherche div span{
  margin: 0.5em 0.5em;
}
.rounded-pils
{
  border: solid 1px $color-orange;
  border-radius: 20px;
  margin: 1rem;
  padding: 0.5em;
}
.bi{
  padding-left: 1.5rem;
  padding-right: 1.5rem;
}
.genre span{
  padding: 0.25rem 2rem;
}
.more-option{
  width: 100%;
  color: $color-black;
  text-decoration: underline;
  text-align: right;
}

.bold{
  font-weight: bold;
}
button{
  background: $color-white;
  color: $color-orange;
  border: 1px solid $color-orange;
  border-radius: 20px;
  font-weight: bold;
  padding: 0.5rem 1.5rem;
  margin: 1rem;
}
.conversation{
  font-weight: bold;
}
</style>
