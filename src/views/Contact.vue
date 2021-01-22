<template>
  <div class="app">
    <Header />
    <h1 style="text-align: center">Contact Form</h1>
    <form>
      <p>
        Name:
        <input class="form-control" type="text" name="fullName" />
      </p>
      <p>
        Email:
        <input class="form-control" type="email" name="email" />
      </p>
      <p>
        Message:
        <textarea
          class="form-control"
          name="message"
          cols="30"
          rows="5"
        ></textarea>
      </p>
      <button class="btn btn-success w-100">Send</button>
    </form>
  </div>
</template>

<script>
import Header from "@/components/Header.vue";

export default {
  name: "Contact",
  components: {
    Header,
  },
};
</script>