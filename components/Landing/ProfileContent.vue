<template>
  <div class="content-profile">
    <div class="galerie">
      <img src="https://via.placeholder.com/150" alt="" class="img-principal">
      <div class="other-img">
        <img src="https://via.placeholder.com/150" alt="">
        <img src="https://via.placeholder.com/150" alt="">
        <img src="https://via.placeholder.com/150" alt="">
      </div>
    </div>
    <div class="head-content">
      <h2>Jane DOE <i class="ri-women-line"></i></h2>
      <div class="info-action">
        <span class="information"> 19 Ans Langon(39) - 25 km</span>
        <div class="action">
          <div class="like">
            <i class="ri-thumb-down-line"></i>
            <span>Like</span>
          </div>
          <div class="favoris">
            <i class="ri-star-line"></i>
            <span>Favoris</span>
          </div>
          <div class="lock">
            <i class="ri-lock-line"></i>
            <span>Bloquer</span>
          </div>
        </div>
      </div>
      <div class="body-content">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad aliquam aliquid, assumenda, consequatur consequuntur dolorum eius eum facilis fugiat hic id nostrum quisquam reiciendis repellat sed sequi sunt totam unde?
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ab accusantium ad amet animi dolores error, facere hic iure magni nostrum, officia quae quasi repudiandae temporibus ullam? Dolore libero placeat possimus?Aperiam commodi culpa dolores eius eos error eveniet excepturi fugit hic, ipsum itaque iure laboriosam maiores minus molestias nihil non officiis pariatur perferendis provident quibusdam quisquam similique tenetur voluptate voluptatum.
        </p>
        <div class="search">
          <h3>Je recherche</h3>
          <span>Homme</span>
          <span>Non fumeur</span>
        </div>
      </div>
      <div class="match">
        <button class="yes">C'est tout moi</button>
        <button class="no">Tant pis</button>
      </div>
    </div>
  </div>
</template>


<script setup lang="ts">
</script>

<style lang="scss" scoped>
@import "@/assets/css/_variables";

.content-profile{
  display: flex ;
  width: 100%;
}
.galerie{
  width: 90%;
  display: flex;
  flex-wrap: wrap;
  margin: 1rem;
  position: relative;
}
.galerie .img-principal{
  width: 100%;
  object-fit: contain;
  position: absolute;

}
.galerie .other-img{
  width: 100%;
  display: flex;
  justify-content: space-between;
  object-fit: contain;
  position: absolute;
  top: 46%;

}
.galerie .other-img img{
  width: 30%;
  object-fit: contain;
  margin: 1rem 0;
}
.head-content{
  margin: 1rem 2rem;
  color: $color-orange;
}
.head-content h2{
  font-size: 2rem;
  margin-bottom: 1rem;
}
.head-content i {
  font-size: 1.75rem;
}
.info-action{
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: baseline;
}
.action{
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  width: 60%;
}
.action div{
  display:  flex;
  flex-direction: column;
  margin: 0 1rem;
}
.action div i{
  font-size: 3rem;
}
.body-content p{
  margin: 1rem 0;
}
.search h3{
  color: $color-black;
  margin: 1rem;

}
.search span{
  color: $color-orange;
  border: 1px solid $color-orange;
  border-radius: 20px;
  font-weight: bold;
  padding: 0.5rem 1.5rem;
  margin: 3rem;
}
.match{
  margin: 4rem 0;
  display: flex;
  justify-content: center;
  width: 100%;

}
.match button{
  background: $color-white;
  color: $color-orange;
  border: 1px solid $color-orange;
  border-radius: 20px;
  font-weight: bold;
  padding: 0.5rem 1.5rem;
  margin: 1rem;
}


</style>
