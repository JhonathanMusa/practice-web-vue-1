<template>
  <div>
    <Header />
    <h1 class="text-center mb-5">Lifestyle</h1>
    <div class="row">
      <div class="col-lg-6 col-md-6" >
        <img src="../../public/upload/blog/home5/a3.jpg" alt="" />
        <h3>Title</h3>
        <p class="mb-0">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iure,
          nostrum ratione. Excepturi nesciunt rerum culpa impedit mollitia
          labore assumenda molestias eveniet totam a, perferendis et, minima
          ipsum eum necessitatibus dolores!
        </p>
        <p class="text-danger small">Read More</p>
      </div>
      <div class="col-lg--6 col-md-6" >
        <img src="../../public/upload/blog/home5/a4.jpg" alt="" />
        <h3>Title</h3>
        <p class="mb-0">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iure,
          nostrum ratione. Excepturi nesciunt rerum culpa impedit mollitia
          labore assumenda molestias eveniet totam a, perferendis et, minima
          ipsum eum necessitatibus dolores!
        </p>
        <p class="text-danger small">Read More</p>
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue"


export default {
  name: "Lifestyle",
  components: {
    Header,
    Footer,
  },
};
</script>