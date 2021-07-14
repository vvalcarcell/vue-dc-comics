<template>
  <div class="single-card">
    <img :src="thumb" alt="" />
    <h3>{{ title }}</h3>
    <h4>{{ price }}</h4>
    <h4>{{ type }}</h4>
  </div>
</template>

<script>
export default {
  name: Card,
  props: {
    thumb: String,
    price: Number,
    title: String,
    type: String,
  },
};
</script>

<style lang="sass" scoped>
</style>