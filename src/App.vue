<template>
  <nav class="navbar navbar-expand-lg navbar navbar-dark bg-dark">
    <!-- Navbar content -->
    <div class="collapse navbar-collapse" id="navbarNavDropdown">
      <ul class="navbar-nav">
        <li class="nav-item active">
          <a class="nav-link" href="#">
            <span class="sr-only">Home</span>
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">About us</a>
        </li>
      </ul>
    </div>
  </nav>
  <ProductModal msg="Welcome to Your Vue.js App"/>
</template>

<script>
// import MainPage from './views/ProductPage.vue'
import ProductModal from './components/products/ProductModal.vue'

export default {
  name: 'App',
  components: {
    // MainPage,
    ProductModal
  }
}
</script>

<style>
body{
  padding: 10px;
}
</style>
