<template>
  <header>
    <div class="content">
      <img src="~/assets/images/logo/logo_small_icon_only.png" alt="Logo FreeNy">
      <h1>FREE aNd You</h1>
      <h2>Libre et vous ?</h2>
      <form id="connexion" @submit="checkForm" action="" method="post">
        <input type="email" placeholder="Login">
        <input type="password" placeholder="password">
        <div class="cta w-100 mt-20">
          <a href="#">s'inscrire</a>
          <input type="submit" value="Se connecter">
        </div>
      </form>
    </div>
  </header>
</template>

<script setup lang="ts">
</script>

<style lang="scss" scoped>
@import "@/assets/css/_variables";

header {
  color: $color-orange;
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
}

h2 {
  font-size: 1.5em;
}
form{
  display: flex;
  flex-direction: column;
}

input[type=password], input[type=email]{
  border: $color-orange solid 1px ;
  padding: 15px;
  border-radius: 5px;
  margin-top: 10px;
}
input[type=submit]{
  border: $color-orange solid 1px;
  background: $color-white;
  border-radius: 4px;
  padding: 10px;
  font-weight: bold;
  color: $color-orange;

}
form a {
  text-decoration: none;
  font-weight: bold;
}
.mt-20{
  margin-top: 20px;
}

.w-100{
  width: 100%;
}

</style>
