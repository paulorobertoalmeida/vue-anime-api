<template>
  <div>
    <img :src="image_url" alt="" class="card-image" />
  </div>
</template>

<script>
export default {
  name: "Image",
  props: {
    image_url: String,
  },
};
</script>

<style></style>