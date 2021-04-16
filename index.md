<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Devin Brunk</title>
    <meta name="description" content="">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="robots" content="all,follow">
    <!-- Bootstrap CSS-->
    <link rel="stylesheet" href="vendor/bootstrap/css/bootstrap.min.css">
    <!-- Google fonts-->
    <link href="https://fonts.googleapis.com/css?family=Roboto+Condensed:300,700" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Open+Sans:300,400,700" rel="stylesheet">
    <!-- Lightbox-->
    <link rel="stylesheet" href="vendor/lightbox2/css/lightbox.min.css">
    <!-- theme stylesheet-->
    <link rel="stylesheet" href="css/style.default.css" id="theme-stylesheet">
    <!-- Custom stylesheet - for your changes-->
    <link rel="stylesheet" href="css/custom.css">
    <!-- Leaflet CSS - For the map-->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/leaflet/1.4.0/leaflet.css">
    <!-- Favicon-->
    <link rel="shortcut icon" href="favicon.png">
    <!-- Tweaks for older IEs--><!--[if lt IE 9]>
        <script src="https://oss.maxcdn.com/html5shiv/3.7.3/html5shiv.min.js"></script>
        <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script><![endif]-->
  </head>
  <body>
    <!-- Hero Section-->
    <section id="intro" style="background: url(img/startup-room.jpg)" class="hero bg-cover">
      <div class="overlay"></div>
      <div class="content h-100 d-flex align-items-center">
        <div class="container text-center text-white">
          <p class="headings-font-family text-uppercase lead">Welcome to my digital home</p>
          <h1 class="text-uppercase hero-text text-white"><span class="font-weight-bold d-block">Devin Brunk</span></h1>
          <p class="headings-font-family text-uppercase lead"><br><a href="#" class="text-white no-anchor-style"></a></p>
        </div>
      </div><a href="#about" class="scroll-btn link-scroll"><i class="fas fa-angle-double-down"></i></a>
    </section>
    <!-- Navbar-->
    <!-- navbar-->
    <header class="header sticky-top">
      <nav class="navbar navbar-expand-lg bg-white border-bottom py-0">
        <div class="container"><a href="#" class="navbar-brand py-1"><img src="img/logo.png" alt="" class="img-fluid"></a>
          <button type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation" class="navbar-toggler navbar-toggler-right"><span class="fas fa-bars"></span></button>
          <div id="navbarSupportedContent" class="collapse navbar-collapse">
            <ul class="navbar-nav ml-auto px-3">
              <li class="nav-item active"><a href="#intro" class="nav-link text-uppercase link-scroll">Home </a></li>
              <li class="nav-item"><a href="#about" class="nav-link text-uppercase link-scroll">About</a></li>

              <li class="nav-item"><a href="#portfolio" class="nav-link text-uppercase link-scroll">Portfolio</a></li>

              <li class="nav-item"><a href="#contact" class="nav-link text-uppercase link-scroll">Contact</a></li>
            </ul>
          </div>
        </div>
      </nav>
    </header>
    <!-- About Section-->
    <section id="about" class="about bg-gray">
      <div class="container">
        <div class="row mb-5">
          <div class="col-lg-6">
            <header class="text-center mb-5">
              <h2 class="lined text-uppercase">About me</h2>
            </header>
            <p class="lead">I am a developer</p>
            <p>Over the years I found that I have a passion for computers. I am a software engineer with a background in multimedia. During my pursuit of knowledge, I gained a wide range of skills when it comes to working digitally. Some of my work includes: back end and front end full stack development, graphic/motion design, video production, Unity game development.</p>
            <div class="row">
              <div class="col-lg-6">
                <ul class="mb-0">
                  <li>HTML / CSS / JS / Python</li>
                  <li>Django / EXPRESS / REACT</li>
                  <li>Postgres / SQL / MongoDB</li>
                </ul>
              </div>
              <div class="col-lg-6">
                <ul class="mb-0">
                  <li>Adobe Creative Suite</li>
                  <li>Unity3D Game Development</li>
                  <li>C# / ActionScript</li>
                </ul>
              </div>
            </div>
          </div>
          <div class="col-lg-6"><img src="img/profile.jpg" alt="..." class="img-fluid"></div>
        </div>
          
      </div>
    </section>

    <!-- Portfolio Section-->
    <section id="portfolio" class="pb-0">
      <header class="text-center mb-4">
        <h2 class="lined text-uppercase mb-5">Portfolio</h2>
        <p>My Projects</p>
      </header>
      <div class="row p-0">           
        <div class="col-lg-3 col-md-4 col-6 p-0"><a href="img/portfolio-1.jpg" data-lightbox="image-1" data-title="Pokemon Nuzlocke Tracker - Django PostgreSQL" class="d-block"><img src="img/portfolio-1.jpg" alt="..." class="img-fluid d-block mx-auto"></a></div>
        <div class="col-lg-3 col-md-4 col-6 p-0"><a href="img/portfolio-2.jpg" data-lightbox="image-1" data-title="Wayfarer - Django PostgreSQL - Collabrative Project" class="d-block"><img src="img/portfolio-2.jpg" alt="..." class="img-fluid d-block mx-auto"></a></div>
        
        
      </div>
    </section>



    <!-- Contact Section-->
    <section id="contact" class="bg-gray">
      <div class="container">
        <header class="text-center mb-5">
          <h2 class="text-uppercase lined">Contact</h2>
        </header>
        <div class="row">
          <div class="col-lg-6">
            <form action="" class="contact-form">
              <div class="row">
                <div class="form-group col-lg-6">
                  <label for="firstName">Your firstname *</label>
                  <input id="firstName" type="text" name="firstname" placeholder="Enter your firstname" class="form-control">
                </div>
                <div class="form-group col-lg-6">
                  <label for="lastName">Your lastname *</label>
                  <input id="lastName" type="text" name="lastname" placeholder="Enter your lastname" class="form-control">
                </div>
                <div class="form-group col-lg-12">
                  <label for="email">Your email *</label>
                  <input id="email" type="email" name="email" placeholder="Enter your email" class="form-control">
                </div>
                <div class="form-group col-lg-12">
                  <label for="message">Your message *</label>
                  <textarea id="message" name="message" placeholder="Enter your message" rows="4" class="form-control"></textarea>
                </div>
                <div class="form-group col-lg-12">
                  <button type="submit" class="btn btn-outline-primary w-100">Send message</button>
                </div>
              </div>
            </form>
          </div>
          <div class="col-lg-6">
            <p>Effects present letters inquiry no an removed or friends. Desire behind latter me though in. Supposing shameless am he engrossed up additions. My possible peculiar together to. Desire so better am cannot he up before points. Remember mistaken opinions it pleasure of debating. Court front maids forty if aware their at. Chicken use are pressed removed.</p>
            <p>Able an hope of body. Any nay shyness article matters own removal nothing his forming. Gay own additions education satisfied the perpetual. If he cause manor happy. Without farther she exposed saw man led. Along on happy could cease green oh.</p>
            <ul class="mb-0 list-inline text-center">
              <li class="list-inline-item"><a href="#" class="social-link social-link-facebook"><i class="fab fa-facebook-f"></i></a></li>
              <li class="list-inline-item"><a href="#" class="social-link social-link-twitter"><i class="fab fa-twitter"></i></a></li>
              <li class="list-inline-item"><a href="#" class="social-link social-link-google-plus"><i class="fab fa-google-plus-g"></i></a></li>
              <li class="list-inline-item"><a href="#" class="social-link social-link-instagram"><i class="fab fa-instagram"></i></a></li>
              <li class="list-inline-item"><a href="#" class="social-link social-link-email"><i class="fas fa-envelope"></i></a></li>
            </ul>
          </div>
        </div>
      </div>
    </section>
    <footer class="py-4">
      <div class="container">
        <div class="row">
          <div class="col-lg-6 text-center text-lg-left">
            <p class="mb-0 text-gray">&copy; 2021 Devin Brunk</p>
          </div>
          <div class="col-lg-6 text-center text-lg-right">
            <p class="mb-0 text-gray">&copy; Template by Bootstrapious — <a href="https://bootstrapious.com/" class="text-gray">Bootstrap Templates</a></p>
          </div>
        </div>
      </div>
    </footer>
    <!-- JavaScript files-->
    <script src="vendor/jquery/jquery.min.js"></script>
    <script src="vendor/bootstrap/js/bootstrap.bundle.min.js"></script>
    <script src="vendor/lightbox2/js/lightbox.min.js"></script>
    <script src="vendor/smooth-scroll/smooth-scroll.polyfills.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/leaflet/1.4.0/leaflet.js"> </script>
    <script src="js/front.js"></script>
    <!-- FontAwesome CSS - loading as last, so it doesn't block rendering-->
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.1/css/all.css" integrity="sha384-fnmOCqbTlWIlj8LyTjo7mOUStjsKC4pOpQbqyi7RrhN7udi9RwhKkMHpvLbHG9Sr" crossorigin="anonymous">
  </body>
</html>