<script>
import TheHeader from "./components/TheHeader.vue";
import TheFooter from "./components/TheFooter.vue";
import ThePreFooter from "./components/ThePreFooter.vue";
// import TheMain from "./components/TheMain.vue";
import TheMainBlue from "./components/TheMainBlue.vue";
import TheHero from "./components/TheHero.vue";
import productsArray from "./db/products";

export default {
  components: {
    TheHeader,
    TheHero,
    // TheMain,
    TheMainBlue,
    ThePreFooter,
    TheFooter,
  },
  data() {
    return {
      productsArray,
    };
  },
};
</script>

<template>
  <TheHeader />
  <TheHero />
  <!-- <TheMain /> -->
  <main>
    <div class="container text-center">
      <div class="row row-cols-6">
        <div
          class="card border-0 rounded-0 bg-black"
          v-for="products in productsArray"
        >
          <img class="myimg" :src="products.thumb" alt="" />
          {{ products.type }}
        </div>
      </div>
    </div>
  </main>
  <TheMainBlue />
  <ThePreFooter />
  <TheFooter />
</template>

<style lang="scss">
body {
  background-color: black;
}
.myimg {
  aspect-ratio: 1/1;
  max-width: 250px;
}
</style>
