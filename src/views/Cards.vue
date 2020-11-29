<template>
  <div class="app">
    <Header />
      <h1 class="text-center">Cards Page</h1>
    <div class="container">
      <div class="row">
        <div class="col-md-4">
          <div class="card" style="width: 18rem">
            <img src="upload/blog/c6.jpg" />
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
              <a href="#" class="btn btn-primary btn-block">Read more</a>
            </div>
          </div>
        </div>

        <div class="col-md-4">
          <div class="card" style="width: 18rem">
            <img src="upload/blog/c7.jpg" />
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
              <a href="#" class="btn btn-primary btn-block">Read more</a>
            </div>
          </div>
        </div>

        <div class="col-md-4">
          <div class="card" style="width: 18rem">
            <img src="upload/blog/c8.jpg" />
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
              <a href="#" class="btn btn-primary btn-block">Read more</a>
            </div>
          </div>
        </div>
      </div>

      <div class="row">
        <div class="col-md-4">
          <div class="card" style="width: 18rem">
            <img src="upload/blog/c8.jpg" />
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
              <a href="#" class="btn btn-primary btn-block">Read more</a>
            </div>
          </div>
        </div>

        <div class="col-md-4">
          <div class="card" style="width: 18rem">
            <img src="upload/blog/c8.jpg" />
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
              <a href="#" class="btn btn-primary btn-block">Read more</a>
            </div>
          </div>
        </div>

        <div class="col-md-4">
          <div class="card" style="width: 18rem">
            <img src="upload/blog/c8.jpg" />
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
              <a href="#" class="btn btn-primary btn-block">Read more</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
export default {
  name: "Cards",
  components: {
    Header,
  },
};
</script>