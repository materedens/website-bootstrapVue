<template>
  <div>

    <b-navbar toggleable="lg" id="header" type="dark" class="d-flex align-items-center fixed-top">
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
        <div class="title">
          <h2>About</h2>
          <h3>Find Out More <span>About Us</span></h3>
          <p>
            A card is a flexible and extensible content container.
            It includes options for headers and footers, a wide
            variety of content, contextual background colors,
            and powerful display options.
          </p>
        </div>
        <div class="row">
          <div class="col-lg-6">
            <img src="./assets/background1.jpeg" class="img-fluid" alt="" />
          </div>
          <div class="col-lg-6 pt-4 pt-lg-0 content d-flex flex-column justify-content-center">
            <h3>
              A card is a flexible and extensible content container.
            </h3>
            <p class="fst-italic">
              A card is a flexible and extensible content container.
              It includes options for headers and footers, a wide
              variety of content, contextual background colors,
              and powerful display options.
            </p>
            <ul class="list">
              <li>
                <b-icon icon="camera" style="font-size: 4rem;"></b-icon>
                <div>
                  <h5>
                    A card is a flexible and extensible content container.
                  </h5>
                  <p>A card is a flexible and extensible content container.
                    It includes options for headers and footers, a wide
                    variety of content, contextual background colors,
                    and powerful display options.
                  </p>
                </div>
              </li>
              <li>
                <b-icon icon="bar-chart-fill" style="font-size: 4rem;"></b-icon>
                <div>
                  <h5>
                    A card is a flexible and extensible content container.
                  </h5>
                  <p>A card is a flexible and extensible content container.
                    It includes options for headers and footers, a wide
                    variety of content, contextual background colors,
                    and powerful display options.
                  </p>
                </div>
              </li>
            </ul>
            <p>A card is a flexible and extensible content container.
              It includes options for headers and footers, a wide
              variety of content, contextual background colors,
              and powerful display options.
            </p>
          </div>
        </div>
      </b-container>

    </div>
  </div>

</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@1,300;1,400&display=swap');

body {
  background: #ffffff !important;
  font-family: 'Roboto', sans-serif;
  list-style: none;
  text-decoration: none;
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
  position: relative;
}

.scrolled-offset {
  margin-top: 70px;
}

.about-me {
  background: #f6f9fe;
  padding: 60px 0;
  overflow: hidden;
  list-style: none;
}

.title {
  text-align: center;
  padding-bottom: 30px;
}

.title h2 {
  font-size: 13px;
  letter-spacing: 1px;
  font-weight: 700;
  padding: 8px 20px;
  margin: 0;
  background: #e7f1fd;
  color: #106eea;
  display: inline-block;
  text-transform: uppercase;
  border-radius: 50px;
}

.title h3 {
  margin: 15px 0 0 0;
  font-size: 32px;
  font-weight: 700;
}

.title h3 span {
  color: #106eea;
}

.title p {
  margin: 15px auto 0 auto;
  font-weight: 600;
}

@media(min-width: 1024px) {
  .title p {
    width: 50%;
  }
}

.list {
  list-style: none;
  text-decoration: none;
}
</style>
