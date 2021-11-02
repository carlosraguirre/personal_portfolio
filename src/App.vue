<template>
  <div id="app">
    <!-- ======= Mobile nav toggle button ======= -->
    <i class="bi bi-list mobile-nav-toggle d-xl-none"></i>    
    <!-- ======= Header ======= -->
    <header id="header">
      <div class="d-flex flex-column">
        <div class="profile">
          <img
            src="assets/img/profile-small.jpg"
            alt=""
            class="img-fluid rounded-circle"
          />
          <h1 class="text-light"><a href="/index.html">Carlos Aguirre</a></h1>
          <div class="social-links mt-3 text-center">
            <a href="#" class="envelope"><i class="bi bi-envelope"></i></a>
            <a href="https://github.com/carlosraguirre" target="_blank"class="github"><i class="bi bi-github"></i></a>
            <a href="#" class="globe"><i class="bi bi-globe"></i></a>
            <!-- <a href="#" class="google-plus"><i class="bx bxl-skype"></i></a> -->
            <a href="https://www.linkedin.com/in/aguirre-carlos/" target="_blank" class="linkedin"><i class="bx bxl-linkedin"></i></a>
          </div>
        </div>

        <nav id="navbar" class="nav-menu navbar">
          <ul>
            <li>
              <a href="#hero" class="nav-link scrollto active"
                ><i class="bx bx-home"></i> <span>Home</span></a
              >
            </li>
            <li>
              <a href="#about" class="nav-link scrollto"
                ><i class="bx bx-user"></i> <span>About</span></a
              >
            </li>
            <li>
              <a href="#resume" class="nav-link scrollto"
                ><i class="bx bx-file-blank"></i> <span>Resume</span></a
              >
            </li>
            <li>
              <a href="#portfolio" class="nav-link scrollto"
                ><i class="bx bx-book-content"></i> <span>Portfolio</span></a
              >
            </li>
          </ul>
        </nav>
        <!-- .nav-menu -->
      </div>
    </header>
    <!-- End Header -->

    <router-view/>
      <!-- ======= Footer ======= -->
      <footer id="footer">
        <div class="container">
          <div class="copyright">
            &copy; Copyright <strong><span>iPortfolio</span></strong>
          </div>
          <div class="credits">
            <!-- All the links in the footer should remain intact. -->
            <!-- You can delete the links only if you purchased the pro version. -->
            <!-- Licensing information: https://bootstrapmade.com/license/ -->
            <!-- Purchase the pro version with working PHP/AJAX contact form: https://bootstrapmade.com/iportfolio-bootstrap-portfolio-websites-template/ -->
            Designed by <a href="https://bootstrapmade.com/">BootstrapMade</a>
          </div>
        </div>
      </footer>
      <!-- End  Footer -->
  </div>
</template>

<style>

</style>
