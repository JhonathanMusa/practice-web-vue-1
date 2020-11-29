<template>
  <div class="home">
    <Header />
    <h1 class="text-center">Home page</h1>
    <div class="row mt-5">
      <div class="col-lg-8 col-md-12 text-center">
        <h3>Article</h3>
        <p class="text-justify">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Quae, debitis
          nobis et rem excepturi officia at vitae. Doloremque sequi, unde ipsa
          quam omnis libero at odit quasi deserunt a ea! Lorem ipsum dolor sit
          amet consectetur adipisicing elit. Quae, debitis nobis et rem
          excepturi officia at vitae. Doloremque sequi, unde ipsa quam omnis
          libero at odit quasi deserunt a ea! Lorem ipsum dolor sit amet
          consectetur adipisicing elit. Quae, debitis nobis et rem excepturi
          officia at vitae. Doloremque sequi, unde ipsa quam omnis libero at
          odit quasi deserunt a ea!
        </p>
      </div>
      <div class="col-lg-4 col-md-12 text-center">
        <h3>Aside</h3>
        <p class="text-justify">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Quae, debitis
          nobis et rem excepturi officia at vitae. Doloremque sequi, unde ipsa
          quam omnis libero at odit quasi deserunt a ea!
        </p>
      </div>
    </div>
    <div class="row mt-5">
      <div class="col-lg-6 col-md-6">
        <h3 class="text-center">Post</h3>
        <p class="text-justify">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi
          pariatur aliquid natus dolore obcaecati quidem blanditiis odit
          veritatis. Esse ea libero similique possimus fugiat repudiandae
          maiores labore tempore. Quidem, aliquam? Lorem ipsum dolor sit amet
          consectetur adipisicing elit. Quasi pariatur aliquid natus dolore
          obcaecati quidem blanditiis odit veritatis. Esse ea libero similique
          possimus fugiat repudiandae maiores labore tempore. Quidem, aliquam?
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi
          pariatur aliquid natus dolore obcaecati quidem blanditiis odit
          veritatis. Esse ea libero similique possimus fugiat repudiandae
          maiores labore tempore. Quidem, aliquam?
        </p>
      </div>
      <div class="col-lg-6 col-md-6">
        <h3 class="text-center">Post</h3>
        <p class="text-justify">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi
          pariatur aliquid natus dolore obcaecati quidem blanditiis odit
          veritatis. Esse ea libero similique possimus fugiat repudiandae
          maiores labore tempore. Quidem, aliquam? Lorem ipsum dolor sit amet
          consectetur adipisicing elit. Quasi pariatur aliquid natus dolore
          obcaecati quidem blanditiis odit veritatis. Esse ea libero similique
          possimus fugiat repudiandae maiores labore tempore. Quidem, aliquam?
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi
          pariatur aliquid natus dolore obcaecati quidem blanditiis odit
          veritatis. Esse ea libero similique possimus fugiat repudiandae
          maiores labore tempore. Quidem, aliquam?
        </p>
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    Header,
    Footer,
  },
};
</script>

