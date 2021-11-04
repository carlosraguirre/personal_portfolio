<template>
  <div>
    <body>
      <!-- Google Fonts -->
      <link
        href="https://fonts.googleapis.com/css?family=Open+Sans:300,300i,400,400i,600,600i,700,700i|Raleway:300,300i,400,400i,500,500i,600,600i,700,700i|Poppins:300,300i,400,400i,500,500i,600,600i,700,700i"
        rel="stylesheet"
      />
      <link href="/assets/css/style.css" rel="stylesheet" />
    
      <!-- ======= Mobile nav toggle button ======= -->
      <i class="bi bi-list mobile-nav-toggle d-xl-none"></i>

      <!-- ======= Header ======= -->
      <header id="header">
        <div class="d-flex flex-column">
          <div class="profile">
            <img
              src="assets/img/Profile2.jpg"
              alt=""
              class="img-fluid rounded-circle"
            />
            <h1 class="text-light"><a href="/index.html">Carlos Aguirre</a></h1>
            <div class="social-links mt-3 text-center">
              <a
                href="mailto:craguirre952@gmail.com"
                target="_blank"
                class="envelope"
                ><i class="bi bi-envelope"></i
              ></a>
              <a
                href="https://github.com/carlosraguirre"
                target="_blank"
                class="github"
                ><i class="bi bi-github"></i
              ></a>
              <!-- <a href="#" class="globe"><i class="bi bi-globe"></i></a> -->
              <!-- <a href="#" class="google-plus"><i class="bx bxl-skype"></i></a> -->
              <a
                href="https://www.linkedin.com/in/aguirre-carlos/"
                target="_blank"
                class="linkedin"
                ><i class="bx bxl-linkedin"></i
              ></a>
            </div>
          </div>

          <!-- <nav id="navbar" class="nav-menu navbar">
            <ul>
              <li>
                <a href="#hero" class="nav-link scrollto"
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
          </nav> -->
          <!-- .nav-menu -->
        </div>
      </header>
      <!-- End Header -->

      <main id="main">
        <!-- ======= Breadcrumbs ======= -->
        <section id="breadcrumbs" class="breadcrumbs">
          <div class="container">
            <div class="d-flex justify-content-between align-items-center">
              <h2>YummyList Details</h2>
              <ol>
                <li><a href="/">Home</a></li>
                <!-- <li>Portfolio Details</li> -->
              </ol>
            </div>
          </div>
        </section>
        <!-- End Breadcrumbs -->

        <!-- ======= Portfolio Details Section ======= -->
        <section id="portfolio-details" class="portfolio-details">
          <div class="container">
            <div class="row gy-4">
              <div class="col-lg-8">
                <div class="portfolio-details-slider swiper">
                  <div class="swiper-wrapper align-items-center">
                    <div class="swiper-slide">
                      <img
                        src="/assets/img/portfolio/portfolio-details-1.jpg"
                        alt=""
                      />
                    </div>

                    <div class="swiper-slide">
                      <img
                        src="/assets/img/portfolio/portfolio-details-2.jpg"
                        alt=""
                      />
                    </div>

                    <div class="swiper-slide">
                      <img
                        src="/assets/img/portfolio/portfolio-details-3.jpg"
                        alt=""
                      />
                    </div>
                  </div>
                  <div class="swiper-pagination"></div>
                </div>
              </div>

              <div class="col-lg-4">
                <div class="portfolio-info">
                  <h3>Project information</h3>
                  <ul>
                    <li><strong>Category</strong>: Application development</li>
                    <li><strong>Project date</strong>: August 2021</li>
                    <li>
                      <strong>Project URL</strong>:
                      <a href="#">www.example.com</a>
                    </li>
                  </ul>
                </div>
                <div class="portfolio-description">
                  <h2>Customize your lists of favorite restaurants on YummyList</h2>
                  <p>
                    As part of my capstone for Actualize Coding Bootcamp, YummyList is an app where users can search for restaurants and save them to custom lists. I came up with this idea because I often struggle to remember my favorite restaurants for whatever occassion - breakfast, dinner with friends, date night, etc. Instead of saving my restaurants across multiple platforms, I can search, save and quickly access them on a single app. 
                    </br>
                    </br>
                    YummyList was built on a Rails backend and a Vue frontend. Restaurants data were integrated from the Documenu API and are specific to Washington, DC. The YummyList homepage is linked above and a recording of my capstone presentation is to the left. Enjoy!
                    </br>
                    </br>

                  </p>
                </div>
              </div>
            </div>
          </div>
        </section>
        <!-- End Portfolio Details Section -->
      </main>
      <!-- End #main -->

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
    </body>
  </div>
</template>