<template>
  <div id="app">
    <b-navbar toggleable="md" type="dark" variant="danger">
      <b-container>
        <b-navbar-brand href="#">
          <img src="logo.png" alt="" />
        </b-navbar-brand>
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        <b-collapse is-nav id="nav-collapse">
          <b-navbar-nav class="ml-auto">
            <b-nav-item href="/">Home</b-nav-item>
            <b-nav-item-dropdown text="Features">
              <b-dropdown-item href="Lifestyle">CATEGORY PAGES</b-dropdown-item>
              <b-dropdown-item href="Lifestyle">POST STYLES</b-dropdown-item>
              <b-dropdown-item href="Lifestyle">PAGES</b-dropdown-item>
            </b-nav-item-dropdown>
            <b-nav-item href="Lifestyle">Lifestyle</b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-container>
    </b-navbar>

    <b-container>
      <router-view />
    </b-container>

    <b-img src="upload/blog/home5/sl2.jpg" fluid-grow></b-img>
  </div>
</template>
