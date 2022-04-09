<template>
    <div class="container">
    <div class="row justify-content-md-center mt-5">
      
      <div class="col-md-4">
        <main class="form-signin">
                    <form>
                        <h1 class="h3 mb-3 fw-normal">Please login</h1>

                        <div class="form-floating">
                        <input type="email" class="form-control" id="floatingInput" placeholder="name@example.com">
                        <label for="floatingInput">Email address</label>
                        </div>
                        <br>
                        <div class="form-floating">
                        <input type="password" class="form-control" id="floatingPassword" placeholder="Password">
                        <label for="floatingPassword">Password</label>
                        </div>
                        <br>
                        <div class="checkbox mb-3">
                        <label>
                            <a href="#">Forget your password?</a>
                        </label>
                        </div>
                        <button class="w-100 btn btn-lg btn-primary" type="submit">Login</button>
                        <p class="mt-5 mb-3 text-muted">&copy; 2017–2021</p>
                    </form>
                </main>
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

<style>
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