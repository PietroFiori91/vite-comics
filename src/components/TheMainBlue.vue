<script>
export default {};
</script>

<template>
  <main>
    <div
      class="container mynavbar d-flex flex-row align-items-center justify-content-around"
    >
      <div class="d-flex align-items-center gap-3">
        <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
        <h5>DIGITAL COMICS</h5>
      </div>
      <div class="d-flex align-items-center gap-3">
        <img src="../assets/img/buy-comics-merchandise.png" alt="" />
        <h5>DC MERCHANDISE</h5>
      </div>
      <div class="d-flex align-items-center gap-3">
        <img src="../assets/img/buy-comics-subscriptions.png" alt="" />
        <h5>SUBSCRIPTION</h5>
      </div>
      <div class="d-flex align-items-center gap-3">
        <img src="../assets/img/buy-comics-shop-locator.png" alt="" />
        <h5>COMIC SHOP LOCATOR</h5>
      </div>
      <div class="d-flex align-items-center gap-3">
        <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
        <h5>PC POWER VISA</h5>
      </div>
    </div>
  </main>
</template>

<style lang="scss" scoped>
//installo sass sul componente + as * per utilizzarlo senza dichiarare variabile

@use "../styles/partials/variables" as *;

main {
  background-color: $color-primary;
  height: 8rem;
}
.mynavbar {
  padding: 2rem 0;
}

img {
  max-width: 50px;
}

h5 {
  color: white;
  font-size: 1rem;
}
</style>
