<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Arcana Archive</title>
    <link
      href="img/icon_light.ico"
      rel="icon"
      type="png/x-icon"
      media="(prefers-color-scheme: light)"
    />
    <link
      href="img/icon_dark.ico"
      rel="icon"
      type="png/x-icon"
      media="(prefers-color-scheme: dark)"
    />
    <!-- All CSS -->
    <link href="css/bootstrap.min.css" rel="stylesheet" />
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.7.2/font/bootstrap-icons.css"
    />
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css"
    />
    <link
      href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.2/animate.min.css"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="css/style.css" />
    <link rel="stylesheet" href="css/custom.css" />
    <link rel="stylesheet" href="css/transition.css" />
    <link rel="stylesheet" href="css/import_style.css" />
    <style>
      .navbar-dark .navbar-toggler-icon {
        background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 30 30'%3e%3cpath stroke='rgba%28255, 193, 7, 0.55%29' stroke-linecap='round' stroke-miterlimit='10' stroke-width='2' d='M4 7h22M4 15h22M4 23h22'/%3e%3c/svg%3e");
      }

      .navbar-dark .navbar-toggler-icon {
        border: 2px solid rgb(255, 193, 7);
      }
    </style>
    <!--All CSS--end-->

  </head>
  <body>
    <nav
      class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top text-light"
    >
      <div class="container">
        <a class="navbar-brand" href="home.html"
          ><img class="me-2" src="img/web_logo.png" width="40" height="40" />
          <span class="text-warning">ARC</span>ANA</a
        >
        <a
          class="text-warning nav-item ms-auto"
          id="user-icon"
          href="user.html"
          data-bs-toggle="tooltip"
          data-bs-placement="right"
          title="User Profile"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="30"
            height="30"
            fill="currentColor"
            class="bi bi-person-circle"
            viewBox="0 0 16 16"
          >
            <path d="M11 6a3 3 0 1 1-6 0 3 3 0 0 1 6 0z" />
            <path
              fill-rule="evenodd"
              d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8zm8-7a7 7 0 0 0-5.468 11.37C3.242 11.226 4.805 10 8 10s4.757 1.225 5.468 2.37A7 7 0 0 0 8 1z"
            />
          </svg>
        </a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link" href="home.html">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="home.html#about">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="home.html#services">Plans</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="library.html">Library</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="home.html#team">Team</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="home.html#contact">Contact</a>
            </li>
            <li class="nav-item">
              <a
                class="btn btn-warning ms-2 mt-1"
                href="signin.html"
                data-bs-toggle="tooltip"
                data-bs-placement="bottom"
                title="Log In"
                >Sign In</a
              >
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <div class="trans_container">
      <!--- Main Slide Carousel-->
      <section id="carousel_main">
        <div
          class="carousel slide"
          data-bs-ride="carousel"
          id="carouselExampleIndicators"
          data-bs-interval="3500"
        >
          <div class="carousel-indicators">
            <button
              aria-label="Slide 1"
              class="active"
              data-bs-slide-to="0"
              data-bs-target="#carouselExampleIndicators"
              type="button"
            ></button>
            <button
              aria-label="Slide 2"
              data-bs-slide-to="1"
              data-bs-target="#carouselExampleIndicators"
              type="button"
            ></button>
            <button
              aria-label="Slide 3"
              data-bs-slide-to="2"
              data-bs-target="#carouselExampleIndicators"
              type="button"
            ></button>
            <button
              aria-label="Slide 4"
              data-bs-slide-to="3"
              data-bs-target="#carouselExampleIndicators"
              type="button"
            ></button>
            <button
              aria-label="Slide 5"
              data-bs-slide-to="4"
              data-bs-target="#carouselExampleIndicators"
              type="button"
            ></button>
            <button
              aria-label="Slide 6"
              data-bs-slide-to="5"
              data-bs-target="#carouselExampleIndicators"
              type="button"
            ></button>
          </div>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img
                alt="Magical Photo on a fantasy world."
                class="d-block w-100"
                id="img_quality"
                src="img/wlop_art/castle_dusk.jpg"
              />
              <div class="carousel-caption">
                <h5 class="animated slideInRight" style="animation-delay: 0s">
                  Welcome Magus
                </h5>
                <h5 class="animated slideInLeft" style="animation-delay: 0s">
                  To the
                  <a href="library.html" id="arcana"
                    ><span class="text-warning">Arcana</span>
                    <span class="text-light">Archive.</span></a
                  >
                </h5>
              </div>
            </div>
            <div class="carousel-item">
              <img
                alt="Magical Photo on a fantasy world."
                class="d-block w-100"
                id="img_quality"
                src="img/wlop_art/repentance.jpg"
              />
              <div class="carousel-caption">
                <h5 class="animated slideInRight" style="animation-delay: 0s">
                  <a href="library.html" id="arcana"
                    ><span class="text-warning">IMMERSE...</span></a
                  >
                </h5>
                <p
                  class="animated slideInLeft"
                  style="animation-delay: 0s"
                  id="carousel_text"
                >
                  yourself to a whole different dimension through the works of
                  our finest authors.
                </p>
              </div>
            </div>
            <div class="carousel-item">
              <img
                alt="Magical Photo on a fantasy world."
                class="d-block w-100"
                id="img_quality"
                src="img/wlop_art/ashen_one.jpg"
              />
              <div class="carousel-caption">
                <h5 class="animated slideInRight" style="animation-delay: 0s">
                  <a href="library.html" id="arcana"
                    ><span class="text-warning">IMAGINE...</span></a
                  >
                </h5>
                <p
                  class="animated slideInLeft"
                  style="animation-delay: 0s"
                  id="carousel_text"
                >
                  thousands of worlds, lives. Limitless possibilities, all at
                  the comfort of your screen.
                </p>
              </div>
            </div>
            <div class="carousel-item">
              <img
                alt="Magical Photo on a fantasy world."
                class="d-block w-100"
                id="img_quality"
                src="img/wlop_art/mass_grave.jpg"
              />
              <div class="carousel-caption">
                <h5 class="animated slideInRight" style="animation-delay: 0s">
                  <a href="signin.html" id="arcana"
                    ><span class="text-warning">CREATE...</span></a
                  >
                </h5>
                <p
                  class="animated slideInLeft"
                  style="animation-delay: 0s"
                  id="carousel_text"
                >
                  a journey like no other, a quest of a life time between the
                  pages.
                </p>
              </div>
            </div>
            <div class="carousel-item">
              <img
                alt="Magical Photo on a fantasy world."
                class="d-block w-100"
                id="img_quality"
                src="img/wlop_art/paint_ocean.jpg"
              />
              <div class="carousel-caption">
                <h5 class="animated slideInRight" style="animation-delay: 0s">
                  Start your collection now..
                </h5>
                <p
                  class="animated slideInLeft"
                  style="animation-delay: 0s"
                  id="carousel_text"
                >
                  Get 3 months worth of PRIME for ₱149.00.
                </p>
                <p class="animated slideInRight" style="animation-delay: 0s">
                  <a href="home.html#services">Learn More</a>
                </p>
              </div>
            </div>
            <div class="carousel-item">
              <img
                alt="Magical Photo on a fantasy world."
                class="d-block w-100"
                id="img_quality"
                src="img/wlop_art/fireflies.jpg"
              />
              <div class="carousel-caption">
                <h5 class="animated slideInRight" style="animation-delay: 0s">
                  Set-up your account
                </h5>
                <p
                  class="animated slideInLeft"
                  style="animation-delay: 0s"
                  id="carousel_text"
                >
                  Sign-up and register to get started now.
                </p>
                <p class="animated slideInRight" style="animation-delay: 0s">
                  <a href="signup.html">Sign Up</a>
                </p>
              </div>
            </div>
          </div>
          <button
            class="carousel-control-prev"
            data-bs-slide="prev"
            data-bs-target="#carouselExampleIndicators"
            type="button"
          >
            <span aria-hidden="true" class="carousel-control-prev-icon"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button
            class="carousel-control-next"
            data-bs-slide="next"
            data-bs-target="#carouselExampleIndicators"
            type="button"
          >
            <span aria-hidden="true" class="carousel-control-next-icon"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
      </section>
      <!--- Main Slide Carousel--end-->

      <!-- immortal section starts-->
      <section id="top3" class="top3 section-padding">
        <h1 class="text-center mt-5 pt-5">IMMORTAL CODEX</h1>
        <p class="text-center">
          The ALL TIME TOP selling Books in the
          <span class="text-warning">ARCANA</span> ARCHIVE
        </p>
        <div class="top-box mt-5">
          <div class="top-team">
            <div class="profile-area">
              <div class="iso-team">
                <img src="img/horus_rising.jpg" alt="" />
                <div class="profile-info">
                  <h3>Horus Rising By Dan Abnett</h3>
                  <p>
                    One of the three immortal codexes, with an all time rating
                    of 4.5 ⭐ and 450238 reads.
                  </p>
                  <p>
                    <a
                      href="horus_rising.html"
                      class="btn btn-warning mt-2"
                      data-bs-toggle="tooltip"
                      data-bs-placement="bottom"
                      title="Go to Horus Rising page"
                      >Read More</a
                    >
                  </p>
                </div>
              </div>

              <div class="iso-team">
                <img src="img/kings_avatar.jpg" alt="" />
                <div class="profile-info">
                  <h3>The King's Avatar by Butterfly Blue</h3>
                  <p>
                    One of the three immortal codexes, with an all time rating
                    of 4.4 ⭐ and 440257 reads.
                  </p>
                  <p>
                    <a
                      href="#"
                      class="btn btn-warning mt-2"
                      data-bs-toggle="tooltip"
                      data-bs-placement="bottom"
                      title="Go to The King's Avatar page"
                      >Read More</a
                    >
                  </p>
                </div>
              </div>

              <div class="iso-team">
                <img src="img/way_of_kings.jpg" alt="" />
                <div class="profile-info">
                  <h3>Way of Kings by Brandon Sanderson</h3>
                  <p>
                    One of the three immortal codexes, with an all time rating
                    of 4.4 ⭐ and 430278 reads.
                  </p>
                  <p>
                    <a
                      href="#"
                      class="btn btn-warning mt-2"
                      data-bs-toggle="tooltip"
                      data-bs-placement="bottom"
                      title="Go to Way Of Kings page"
                      >Read More</a
                    >
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- immortal section ends-->
      <!-- about section starts -->
      <section id="about" class="about section-padding">
        <div class="container bg-dark text-white">
          <div class="row">
            <div class="col-lg-4 col-md-12 col-12">
              <div class="about-img">
                <img src="img/magical_books.jpg" alt="" class="img-fluid" />
              </div>
            </div>
            <div class="col-lg-8 col-md-12 col-12 ps-lg-5 mt-md-5">
              <div class="about-text">
                <h2>
                  Avail the Archive's resources <br />
                  to better your writing
                </h2>
                <p>
                  We have top notch editors which can help cater to your writing
                  needs. Our resident translators can team-up with you so your
                  works can reach more audiences. The
                  <span class="text-warning">Archive</span> can also, provide
                  voice actors for audiobook creation. These are just some of
                  the services available in The
                  <span class="text-warning">Archive</span>, we have more coming
                  soon. Join our community and be a part of our family as a
                  reader, writer, VA, translator.
                </p>
                <a
                  href="teams.html"
                  class="btn btn-warning"
                  data-bs-toggle="tooltip"
                  data-bs-placement="bottom"
                  title="Go to the Archive's team portfolios"
                  >Learn More</a
                >
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- about section Ends -->
      <!-- services section Starts -->
      <section class="services section-padding" id="services">
        <div class="container">
          <div class="row">
            <div class="col-md-12">
              <div class="section-header text-center pb-5">
                <h1>Select your PRIME</h1>
                <p>
                  Access and utilize the
                  <span class="text-warning">Arcana</span>
                  Archive without limits on your phone, speakers and other
                  devices.
                </p>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-12 col-md-12 col-lg-3">
              <div class="card text-white bg-dark pb-2 h-100">
                <div class="card-body">
                  <h4 class="card-title text-center">Basic</h4>
                  <p>
                    Free<br />
                    1 account
                  </p>
                  <hr class="bg-white border-2 border-top border-white" />
                  <p>✓ Ads while reading</p>
                  <p>✓ Access to free works only</p>
                  <p>✓ No translation or editing services available</p>
                  <p class="text-center">
                    <a href="signin.html" class="btn bg-warning text-dark"
                      >Get Started</a
                    >
                  </p>
                  <p>
                    <a href="t_c.html" id="footer_text"
                      >Terms and Conditions apply.</a
                    >
                  </p>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-12 col-lg-3">
              <div class="card text-white bg-dark pb-2 h-100">
                <div class="card-body">
                  <h4 class="card-title text-center">Apprentice</h4>
                  <a href="signin.html" class="btn btn-outline-warning">
                    One-time Payment available
                  </a>
                  <p>
                    ₱149/month after offer period<br />
                    1 account
                  </p>
                  <hr class="bg-white border-2 border-top border-white" />
                  <p>✓ First 3 months for ₱149 (offer)</p>
                  <p>✓ Ad-free on browsing and reading for all devices</p>
                  <p>✓ Access to updated translated works</p>
                  <p>✓ 150 words/month on translation and editing services</p>
                  <p class="text-center">
                    <a href="signin.html" class="btn bg-warning text-dark"
                      >Get Started</a
                    >
                  </p>
                  <p id="footer_text">
                    <a href="t_c.html" id="footer_text"
                      >Terms and Conditions apply.</a
                    >
                    Offer not available for users who have already tried PRIME.
                  </p>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-12 col-lg-3">
              <div class="card text-white bg-dark pb-2 h-100">
                <div class="card-body">
                  <h4 class="card-title text-center">Master</h4>
                  <a href="signin.html" class="btn btn-outline-warning">
                    One-time Payment available
                  </a>
                  <p>
                    ₱300/month after offer period<br />
                    2 accounts for reading simultaneously
                  </p>
                  <hr class="bg-white border-2 border-top border-white" />
                  <p>✓ First 3 months for ₱300 (offer)</p>
                  <p>✓ Ad-free on browsing and reading for all devices</p>
                  <p>✓ Access to updated translated works</p>
                  <p>✓ 500 words/month on translation and editing services</p>
                  <p>
                    ✓ 1 commision-free Artwork/month from our graphic designers.
                  </p>
                  <p class="text-center">
                    <a href="signin.html" class="btn bg-warning text-dark"
                      >Get Started</a
                    >
                  </p>
                  <p id="footer_text">
                    <a href="t_c.html" id="footer_text"
                      >Terms and Conditions apply.</a
                    >
                    Offer not available for users who have already tried PRIME.
                  </p>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-12 col-lg-3">
              <div class="card text-white bg-dark pb-2 h-100">
                <div class="card-body">
                  <h4 class="card-title text-center">Exalted</h4>
                  <a href="signin.html" class="btn btn-outline-warning">
                    One-time Payment available
                  </a>
                  <p>
                    ₱750/month after offer period<br />
                    3 accounts for reading simultaneously
                  </p>
                  <hr class="bg-white border-2 border-top border-white" />
                  <p>✓ First 3 months for ₱750 (offer)</p>
                  <p>✓ Ad-free on browsing and reading for all devices</p>
                  <p>✓ Access to updated translated works</p>
                  <p>✓ 1500 words/month on translation and editing services</p>
                  <p>
                    ✓ 2 commision-free Artwork/month from our graphic designers.
                  </p>
                  <p>
                    After 1 yr. of being consistently
                    <span class="text-warning">Exalted</span> you can apply for
                    the <span class="text-warning">GOD-TIER</span>(coming soon)
                    plan
                  </p>
                  <p class="text-center">
                    <a href="signin.html" class="btn bg-warning text-dark"
                      >Get Started</a
                    >
                  </p>
                  <p id="footer_text">
                    <a href="t_c.html" id="footer_text"
                      >Terms and Conditions apply.</a
                    >
                    Offer not available for users who have already tried PRIME.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- team starts -->
      <section class="team section-padding" id="team">
        <div class="container">
          <div class="row">
            <div class="col-md-12">
              <div class="section-header text-center pb-5">
                <h2>Our Team</h2>
                <p>
                  Here are some of our finest translators, industrious editors
                  and innovative authors.
                </p>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-12 col-md-6 col-lg-3">
              <div class="card text-center h-100">
                <div class="card-body">
                  <img
                    src="img/team-1.jpg"
                    alt=""
                    class="img-fluid rounded-circle"
                  />
                  <h3 class="card-title py-2">Author Jiggs</h3>
                  <p class="card-text">
                    Author Jiggs writer of QQB chronicles.
                  </p>

                  <p class="socials">
                    <a href="https://twitter.com"
                      ><i class="bi bi-twitter text-dark mx-1"></i
                    ></a>
                    <a href="https://www.facebook.com"
                      ><i class="bi bi-facebook text-dark mx-1"></i
                    ></a>
                    <a href="https://ph.linkedin.com"
                      ><i class="bi bi-linkedin text-dark mx-1"></i
                    ></a>
                    <a href="https://www.instagram.com"
                      ><i class="bi bi-instagram text-dark mx-1"></i
                    ></a>
                  </p>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6 col-lg-3">
              <div class="card text-center h-100">
                <div class="card-body">
                  <img
                    src="img/team-2.jpg"
                    alt=""
                    class="img-fluid rounded-circle"
                  />
                  <h3 class="card-title py-2">Editor Jiggs</h3>
                  <p class="card-text">
                    Worked with many great authors in polishing their works, he
                    had a hand in one of the Immortal Codexes "Way Of Kings" and
                    helped polish the work of the author.
                  </p>
                  <p class="socials">
                    <a href="https://twitter.com"
                      ><i class="bi bi-twitter text-dark mx-1"></i
                    ></a>
                    <a href="https://www.facebook.com"
                      ><i class="bi bi-facebook text-dark mx-1"></i
                    ></a>
                    <a href="https://ph.linkedin.com"
                      ><i class="bi bi-linkedin text-dark mx-1"></i
                    ></a>
                    <a href="https://www.instagram.com"
                      ><i class="bi bi-instagram text-dark mx-1"></i
                    ></a>
                  </p>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6 col-lg-3">
              <div class="card text-center h-100">
                <div class="card-body">
                  <img
                    src="img/team-3.jpg"
                    alt=""
                    class="img-fluid rounded-circle"
                  />
                  <h3 class="card-title py-2">Translator Jiggs</h3>
                  <p class="card-text">
                    Translated over 300 selections to Filipino, English and
                    Japanese
                  </p>
                  <p class="socials">
                    <a href="https://twitter.com"
                      ><i class="bi bi-twitter text-dark mx-1"></i
                    ></a>
                    <a href="https://www.facebook.com"
                      ><i class="bi bi-facebook text-dark mx-1"></i
                    ></a>
                    <a href="https://ph.linkedin.com"
                      ><i class="bi bi-linkedin text-dark mx-1"></i
                    ></a>
                    <a href="https://www.instagram.com"
                      ><i class="bi bi-instagram text-dark mx-1"></i
                    ></a>
                  </p>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6 col-lg-3">
              <div class="card text-center h-100">
                <div class="card-body">
                  <img
                    src="img/team-4.jpg"
                    alt=""
                    class="img-fluid rounded-circle"
                  />
                  <h3 class="card-title py-2">Administrator Jiggs</h3>
                  <p class="card-text">
                    Contact him for inquiries/reports about our website and
                    he'll reply ASAP.
                  </p>
                  <p class="socials">
                    <a href="https://twitter.com"
                      ><i class="bi bi-twitter text-dark mx-1"></i
                    ></a>
                    <a href="https://www.facebook.com"
                      ><i class="bi bi-facebook text-dark mx-1"></i
                    ></a>
                    <a href="https://ph.linkedin.com"
                      ><i class="bi bi-linkedin text-dark mx-1"></i
                    ></a>
                    <a href="https://www.instagram.com"
                      ><i class="bi bi-instagram text-dark mx-1"></i
                    ></a>
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="row mt-5">
            <p class="text-center">
              <a href="teams.html" class="btn bg-warning text-dark"
                >Learn More</a
              >
            </p>
          </div>
        </div>
      </section>
      <!-- team ends -->
      <!-- Contact starts -->
      <section id="contact" class="contact section-padding">
        <div class="container mt-5 mb-5">
          <div class="row">
            <div class="col-md-12">
              <div class="section-header text-center pb-5">
                <h2>Contact Us</h2>
                <p>
                  Send us a message for inquiries, <br />reports and reviews.
                  Anything to better our work it would be highly appreciated.
                </p>
              </div>
            </div>
          </div>
          <div class="row m-0">
            <div class="col-md-12 p-0 pt-4 pb-4">
              <form action="#" class="bg-light p-4 m-auto">
                <div class="row">
                  <div class="col-md-12">
                    <div class="mb-3">
                      <input
                        class="form-control"
                        placeholder="Full Name"
                        required=""
                        type="text"
                      />
                    </div>
                  </div>
                  <div class="col-md-12">
                    <div class="mb-3">
                      <input
                        class="form-control"
                        placeholder="Email"
                        required=""
                        type="email"
                      />
                    </div>
                  </div>
                  <div class="col-md-12">
                    <div class="mb-3">
                      <textarea
                        class="form-control"
                        placeholder="Message"
                        required=""
                        rows="3"
                      ></textarea>
                    </div>
                  </div>
                  <button
                    class="btn btn-warning btn-lg btn-block mt-3"
                    type="button"
                  >
                    Send Now
                  </button>
                </div>
              </form>
            </div>
          </div>
        </div>
      </section>
      <!-- contact ends -->
    </div>
    <!-- footer starts -->
    <footer class="bg-dark p-2 text-center">
      <div class="container">
        <p class="text-white">All Right Reserved By Arcana Archive © 2023</p>
        <p>
          <a href="https://www.amc.com/privacy" id="footer_text">Privacy</a>
          |
          <a
            href="
                  https://www.amc.com/cookies"
            id="footer_text"
            >Cookies</a
          >
          |
          <a href="https://www.amc.com/terms" id="footer_text">Terms of Use</a>
          |
          <a href="home.html" id="footer_text">Arcana Archive</a>
        </p>
      </div>
    </footer>
    <!-- footer ends -->

    <!-- All Js -->
    <script src="js/bootstrap.bundle.min.js"></script>
    <script src="js/script.js"></script>

  </body>
</html>
