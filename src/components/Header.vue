<template>
  <div class="app">
    <nav class="navbar navbar-expand-lg navbar-ligth bg-ligth">
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <a class="nav-link" href="/"
              >Home <span class="sr-only">(current)</span></a
            >
          </li>

          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle"
              href="#"
              id="navbarDropdown"
              role="button"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              Features
            </a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
              <a class="dropdown-item" href="Cards"
                ><small> Cards </small></a
              >
              <a class="dropdown-item" href="#"><small>Services</small></a>
              <!-- <div class="dropdown-divider"></div> -->
              <a class="dropdown-item" href="#"><small>Pages</small></a>
            </div>
          </li>
          <li class="nav-item active">
            <a class="nav-link" href="Lifestyle"
              >Lyfestile <span class="sr-only">(current)</span></a
            >
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>