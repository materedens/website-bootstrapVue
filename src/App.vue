<template>
  <div>

    <b-navbar toggleable="lg" type="dark" class="nav">
      <b-navbar-brand href="#">Navbar</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="a">
          <b-nav-item href="/">Home</b-nav-item>
          <b-nav-item href="/about">About</b-nav-item>
          <b-nav-item href="/services">Services</b-nav-item>
          <b-nav-item href="/contact">Contact</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
    <v-main>
      <!--  -->
      <router-view></router-view>
    </v-main>
    <div class="about-me">
      <b-container fluid>
        <h1>About Me.</h1>
        <p>
          This gives the input the behavior of a combo box or auto-complete,
          allowing existing values to be chosen, or
          new values to be entered.
        </p>
      </b-container>
    </div>
  </div>
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@1,300;1,400&display=swap');

body {
  background: #ffffff !important;
  font-family: 'Roboto', sans-serif;
}

nav {
  padding: 0px;
  background: #2c3e50 !important;
  display: inline-block;
  text-transform: uppercase;
  border-radius: 2px;
  margin: 0px;
  font-weight: 500;
  box-shadow: 0 1px 1px #ccc;
  position: fixed;

}

nav a {
  display: inline-block;
  padding: 18px 30px;
  color: #fff !important;
  font-size: 16px;
  line-height: 1;
  text-decoration: none !important;
  align-items: center;

}

.about-me {
  background: #ccc;
}
</style>
