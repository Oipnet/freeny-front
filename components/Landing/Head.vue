<template>
  <header>
    <link href="https://cdn.jsdelivr.net/npm/remixicon@2.5.0/fonts/remixicon.css" rel="stylesheet">
    <img src="@/assets/images/logo/logo_large.png" class="logo" alt="logo Freeny">
    <div>
      <a href="#">
        <i class="ri-group-line"></i>
        <span>Visites</span>
      </a>
      <a href="#">
      <i class="ri-thumb-up-line"></i>
        <span>likes</span>
      </a>
      <a href="#">
      <i class="ri-thumb-up-line"></i>
        <span>Match</span>
      </a>
      <a href="#">
        <i class="ri-ink-bottle-line"></i>
        <span>Messages</span>
      </a>
      <img src="https://via.placeholder.com/150" class="profile" alt="photo de profile">
    </div>
  </header>
</template>


<script setup lang="ts">
</script>

<style lang="scss" scoped>
@import "@/assets/css/_variables";

header{
  display: flex;
  justify-content: space-between;
  color: $color-orange;
  padding: 2rem;
}

img{
  width: 15%;
}
header div{
  display: flex;
  justify-content: end;
}
header div a {
  display: flex;
  flex-direction: column;
  margin: 0 0.5rem;
  align-items: center;
  text-decoration: none;
}
header div a span{
  text-decoration: underline;
}

.profile{
  border-radius: 50%;
  width: 40px;
  height: 40px;

}
</style>
