<template>
  <div class="card-background">
    <div class="main-container">
      <div class="card-container">
        <Image :image_url="image_url" />
        <div class="card-body-container">
          <Info :info="info" />
          <Synopsis :synopsis="synopsis" />
          <p class="card-sub-heading">Anime info</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Image from "./subcomponents/Image.vue";
import Info from "./subcomponents/Info.vue";
import Synopsis from "./subcomponents/Synopsis.vue";
export default {
  name: "Cards",
  components: {
    Image,
    Info,
    Synopsis,
  },
  props: {
    info: String,
    image_url: String,
    synopsis: String,
  },
};
</script>


<style>
</style>
