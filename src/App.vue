<script>
import TheHeader from "./components/TheHeader.vue";
import TheFooter from "./components/TheFooter.vue";
import ThePreFooter from "./components/ThePreFooter.vue";
import TheMain from "./components/TheMain.vue";
import TheMainBlue from "./components/TheMainBlue.vue";

export default {
  components: {
    TheHeader,
    TheMain,
    TheMainBlue,
    ThePreFooter,
    TheFooter,
  },
};
</script>

<template>
  <TheHeader />
  <TheMain />
  <TheMainBlue />
  <ThePreFooter />
  <TheFooter />
</template>

<style></style>
