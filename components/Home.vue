<!-- Please remove this file from your project -->
<template>
  <div
    class=""
  >
    <link
      href="https://cdn.jsdelivr.net/npm/tailwindcss@2.1.2/dist/tailwind.min.css"
      rel="stylesheet"
    />

    <div class="header h-screen">
      <NavBar/>
      <Header/>
    </div>

    <main>
      <Features/>
      <ProductsView/>
    </main>

  </div>

</template>

<script>
import NavBar from "~/components/Nav";
import ProductsView from "~/components/Products";
export default {
  name: 'HomeView',
  components: {ProductsView, NavBar},
}
</script>

<style>
.header {
  background: url(~/static/hero-bg.png) no-repeat;
}
</style>
