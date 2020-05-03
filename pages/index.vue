<template>
  <div>
    <Carousel />
    <!-- <TopCards /> -->
    <Cards />
    <Cards />
    <p>タグから探す</p>
    <GridImages />
  </div>
</template>

<script>
import Carousel from "~/components/Carousel.vue";
import TopCards from "~/components/TopCards.vue";
import Cards from "~/components/Cards.vue";
import GridImages from "~/components/GridImages.vue";

export default {
  components: {
    Carousel,
    TopCards,
    Cards,
    GridImages
  }
};
</script>
