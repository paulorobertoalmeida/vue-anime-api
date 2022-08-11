<template>
  <div>
    <p class="card-heading">{{ title }}</p>
    <p class="card-sub-heading-genre">{{ type }}</p>
    <p class="card-sub-heading-genre">{{ score }}</p>
  </div>
</template>

<script>
export default {
  name: "Info",
  props: {
    title: String,
    type: String,
    score: Number,
},
};
</script>

<style></style>