<script>
export default {};
</script>

<template>
  <footer>
    <div
      class="container mynavbar d-flex flex-row align-items-center justify-content-between"
    >
      <button type="button" class="btn btn-outline-primary">
        SIGN-UP NOW!
      </button>

      <div>
        <ul class="d-flex flex-row">
          <li>
            <button type="button" class="mybutton btn btn-outline-primary">
              FOLLOW US
            </button>
          </li>
          <li>
            <a href="#"
              ><img src="../assets/img/footer-facebook.png" alt=""
            /></a>
          </li>
          <li>
            <a href="#"
              ><img src="../assets/img/footer-twitter.png" alt=""
            /></a>
          </li>
          <li>
            <a href="#"
              ><img src="../assets/img/footer-youtube.png" alt=""
            /></a>
          </li>
          <li>
            <a href="#"
              ><img src="../assets/img/footer-pinterest.png" alt=""
            /></a>
          </li>
          <li>
            <a href="#"
              ><img src="../assets/img/footer-periscope.png" alt=""
            /></a>
          </li>
        </ul>
      </div>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
//installo sass sul componente + as * per utilizzarlo senza dichiarare variabile

@use "../styles/partials/variables" as *;

footer {
  background-color: $color-secondary;
}
.mynavbar {
  padding: 2rem 0;
}

.mybutton {
  border: none;
  font-weight: 700;
  font-size: 1.3rem;
  margin-bottom: -1rem;
}

li {
  list-style: none;
  padding: 0 0.6rem;
}
</style>
