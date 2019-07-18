<template>
  <section class="container">
    <ProductList/>
  </section>
</template>

<script>
  import ProductList from "../components/ProductList";

  export default {
    components: { ProductList },
    head () {
      return {
        title: 'Catalog',
      }
    },
  }
</script>