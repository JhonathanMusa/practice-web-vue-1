<template>
  <div class="app">
    <Header />
    <h1 class="text-center">Products</h1>
    <Footer />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";
export default {
  name: "Products",
  components: {
    Header,
    Footer,
  },
};
</script>