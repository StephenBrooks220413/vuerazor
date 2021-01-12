<template>
  <div id="nav">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">VueRazors</a>
        <button
          class="navbar-toggler"
          type="button"
          data-mdb-toggle="collapse"
          data-mdb-target="#navbarText"
          aria-controls="navbarText"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <i class="fas fa-bars"></i>
        </button>
        <div class="collapse navbar-collapse" id="navbarText">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <router-link class="nav-link active" to="/">Home</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link active" to="/about"
                >About</router-link
              >
            </li>
            <li class="nav-item">
              <router-link class="nav-link active" to="/catalog"
                >Ordering</router-link
              >
            </li>
            <li class="nav-item">
              <router-link class="nav-link active" to="/contact"
                >Contact</router-link
              >
            </li>
          </ul>
          <span class="navbar-text">
            <a href="#">Accounts</a>
          </span>
        </div>
      </div>
    </nav>
  </div>
  <router-view /><br /><br /><br /><br />
    <footer class="bg-primary text-white text-center text-lg-start">
      <!-- Grid container -->
      <div class="container p-4">
        <!--Grid row-->
        <div class="row">
          <!--Grid column-->
          <div class="col-lg-6 col-md-12 mb-4 mb-md-0">
            <h5 class="text-uppercase">Footer Content</h5>

            <p>
              Lorem ipsum dolor sit amet consectetur, adipisicing elit. Iste
              atque ea quis molestias. Fugiat pariatur maxime quis culpa
              corporis vitae repudiandae aliquam voluptatem veniam, est atque
              cumque eum delectus sint!
            </p>
          </div>
          <!--Grid column-->

          <!--Grid column-->
          <div class="col-lg-3 col-md-6 mb-4 mb-md-0">
            <h5 class="text-uppercase">Navigation</h5>

            <ul class="list-unstyled mb-0">
                <li>
                    <router-link class="text-white" to="/">Home</router-link>
                </li>
                <li>
                    <router-link class="text-white" to="/about">About</router-link>
                </li>
                <li>
                    <router-link class="text-white" to="/contact">Contact</router-link>
                </li>
                <li>
                    <router-link class="text-white" to="/catalog">Ordering</router-link>
                </li>
            </ul>
          </div>
          <!--Grid column-->

          <!--Grid column-->
          <div class="col-lg-3 col-md-6 mb-4 mb-md-0">
            <h5 class="text-uppercase mb-0">Follow Us</h5>

            <ul class="list-unstyled">
              <li>
                <a href="#!" class="text-white"><i class="fab fa-twitter"></i></a>
              </li>
              <li>
                <a href="#!" class="text-white"><i class="fab fa-facebook"></i></a>
              </li>
              <li>
                <a href="#!" class="text-white"><i class="fab fa-linkedin-in"></i></a>
              </li>
              <li>
                <a href="#!" class="text-white"><i class="fas fa-images"></i></a>
              </li>
            </ul>
          </div>
          <!--Grid column-->
        </div>
        <!--Grid row-->
      </div>
      <!-- Grid container -->

      <!-- Copyright -->
      <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2)">
        © 2020 Copyright:
        <a class="text-white" href="#">clientexample.com</a>
      </div>
      <!-- Copyright -->
    </footer>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
