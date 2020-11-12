<template>
  <div id="app">
    <b-navbar toggleable="md" type="dark" variant="info">
      <b-container>
        <b-navbar-brand href="#">LOGO</b-navbar-brand>
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        <b-collapse is-nav id="nav-collapse">
          <b-navbar-nav>
            <b-nav-item href="/">Home</b-nav-item>
            <b-nav-item href="About">About</b-nav-item>
            <b-nav-item href="Services">Services</b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-container>
    </b-navbar>

    <b-container>
      <router-view />
    </b-container>
  </div>
</template>

