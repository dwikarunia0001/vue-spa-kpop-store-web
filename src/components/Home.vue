<template>
  <div class="px-4 py-5 my-5 text-center">
    <h1 class="display-5 fw-bold">Welcome to K-Pop Store</h1>
    <div class="col-lg-6 mx-auto">
      <p class="lead mb-4">Temukan berbagai album Idol K-Pop kesayanganmu dan dapatkan berbagai BONUS Freebies gratis dari K-Pop Store jika beruntung</p>
      <div class="button d-grid gap-2 d-sm-flex justify-content-sm-center">
        <button type="button" class="btn album btn-warning btn-lg px-4 gap-3">Get Album</button>
        <button type="button" class="btn btn-outline-secondary btn-lg px-4">Sign In</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
      .b-example-divider {
        height: 3rem;
        background-color: rgba(0, 0, 0, .1);
        border: solid rgba(0, 0, 0, .15);
        border-width: 1px 0;
        box-shadow: inset 0 .5em 1.5em rgba(0, 0, 0, .1), inset 0 .125em .5em rgba(0, 0, 0, .15);
      }

      @media (min-width: 992px) {
        .rounded-lg-3 { border-radius: .3rem; }
      }

      .bd-placeholder-img {
        font-size: 1.125rem;
        text-anchor: middle;
        -webkit-user-select: none;
        -moz-user-select: none;
        user-select: none;
      }

      @media (min-width: 768px) {
        .bd-placeholder-img-lg {
          font-size: 3.5rem;
        }
      }

</style>