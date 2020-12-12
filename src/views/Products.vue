<template>
  <div class="app">
    <Header />
    <div class="container">
      <h1 class="text-center mb-5">Products</h1>
      <div class="row">
        <div class="col-lg-3 col-md-3">
          <div class="card rounded" style="width: 15rem">
            <img src="../../public/laptop.jpg" alt="" />
            <div class="card-body">
              <div class="card-title">
                <h5>Laptop Rog</h5>
                <div class="card-text">
                  <p><del>$ 650 </del> / <ins>$ 550</ins></p>
                  <a href="#" class="btn btn-success btn-block">
                    <i class="fas fa-shopping-cart"></i> Buy Now</a
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-3">
          <div class="card rounded" style="width: 15rem">
            <img src="../../public/laptop.jpg" alt="" />
            <div class="card-body">
              <div class="card-title">
                <h5>Laptop Rog</h5>
                <div class="card-text">
                  <p><del>$ 650 </del> / <ins>$ 550</ins></p>
                  <a href="#" class="btn btn-success btn-block">
                    <i class="fas fa-shopping-cart"></i> Buy Now</a
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-3">
          <div class="card rounded" style="width: 15rem">
            <img src="../../public/laptop.jpg" alt="" />
            <div class="card-body">
              <div class="card-title">
                <h5>Laptop Rog</h5>
                <div class="card-text">
                  <p><del>$ 650 </del> / <ins>$ 550</ins></p>
                  <a href="#" class="btn btn-success btn-block">
                    <i class="fas fa-shopping-cart"></i> Buy Now</a
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-3">
          <div class="card rounded" style="width: 15rem">
            <img src="../../public/laptop.jpg" alt="" />
            <div class="card-body">
              <div class="card-title">
                <h5>Laptop Rog</h5>
                <div class="card-text">
                  <p><del>$ 650 </del> / <ins>$ 550</ins></p>
                  <a href="#" class="btn btn-success btn-block">
                    <i class="fas fa-shopping-cart"></i> Buy Now</a
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
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