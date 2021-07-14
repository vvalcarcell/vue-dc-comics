<template>
  <div class="container-fluid">
    <div class="container">
      <Card
        v-for="(element, index) in comics"
        :key="index"
        :thumb="element.thumb"
        :price="element.price"
        :title="element.series"
        :type="element.type"
      />
    </div>
  </div>
</template>

<script>
import comicsJson from "../jsons/dc-comics.json";
import Card from "./Card.vue";

export default {
  name: "Main",
  data: function () {
    return {
      comics: comicsJson,
    };
  },
  components: {
    Card,
  },
};
</script>

<style lang="scss" scoped>
.container-fluid {
  height: 100px;
  background-color: black;
}
</style>