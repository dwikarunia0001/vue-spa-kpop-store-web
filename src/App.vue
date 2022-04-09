<template>

  <!-- Navbar -->
    <header class="p-3 bg-dark text-white">

      <div class="container">
        <div class="d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start">
          <a href="/" class="d-flex align-items-center mb-2 mb-lg-0 text-white text-decoration-none">
            <span class="fs-5 me-5">K-Pop Store</span>
          </a>

          <ul class="nav col-12 col-lg-auto me-lg-auto mb-2 justify-content-center mb-md-0">
            <li><a href="#/" class="nav-link px-2 text-white">Home</a></li>
            <li><a href="#/collection" class="nav-link px-2 text-white">Collection</a></li>
            <li><a href="#/mycart" class="nav-link px-2 text-white">Cart</a></li>
            <li><a href="#/category" class="nav-link px-2 text-white">Category</a></li>
            <li><a href="#/testimonial" class="nav-link px-2 text-white">Testimonial</a></li>
          </ul>

          <form class="col-12 col-lg-auto mb-3 mb-lg-0 me-lg-3">
            <input type="search" class="form-control form-control-dark" placeholder="Search..." aria-label="Search">
          </form>

          <div class="text-end">
            <a href="#/sign-in"><button type="button" class="btn btn-warning me-2">Login</button></a>
            <a href="#/sign-up"><button type="button" class="btn btn-outline-light">Sign-Up</button></a>
          </div>
        </div>
      </div>
    </header>
  <!--End Navbar-->

    <component :is="currentView" />
  
</template>

<script>
import Home from './components/Home.vue'
import Collection from './components/Collection.vue'
import NotFound from './components/NotFound.vue'
import HelloWorld from './components/HelloWorld.vue'
import SignIn from './components/SignIn.vue'
import SignUp from './components/SignUp.vue'
import Testimonial from './components/Testimonial.vue'
import MyCart from './components/MyCart.vue'
import Category from './components/Category.vue'


const routes = {
  '/': Home,
  '/collection': Collection,
  '/helloworld': HelloWorld,
  '/sign-in': SignIn,
  '/sign-up': SignUp,
  '/testimonial': Testimonial,
  '/mycart': MyCart,
  '/category': Category
}

export default {
  data() {
    return {
      currentPath: window.location.hash
    }
  },
  computed: {
    currentView() {
      return routes[this.currentPath.slice(1) || '/'] || NotFound
    }
  },
  mounted() {
    window.addEventListener('hashchange', () => {
		this.currentPath = window.location.hash
		})
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

a {
  text-decoration: none;
}
</style>
