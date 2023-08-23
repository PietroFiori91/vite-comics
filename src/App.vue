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
      <ul>
        <li v-for="products in productsArray">
          {{ products.type }}
        </li>
      </ul>
    </div>
  </main>
  <TheMainBlue />
  <ThePreFooter />
  <TheFooter />
</template>

<style>
body {
  background-color: black;
}
</style>
