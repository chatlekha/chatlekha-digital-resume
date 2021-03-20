<!--DOCTYPE html-->
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- Bootstrap CSS -->
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta2/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-BmbxuPwQa2lc/FVzBcNJ7UAyJxM6wuqIj61tLrc4wSX0szH/Ev+nYRRuWlolflfl"
      crossorigin="anonymous"
    />
    <!-- Bootstrap JS -->
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta2/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-b5kHyXgcpbZJO/tY9Ul7kGkf1S0CWuKcCD38l8YkeH8z8QjE0GmW1gYU5S9FOnJ0"
      crossorigin="anonymous"
    ></script>
    <!-- Google fonts -->
    <link rel="preconnect" href="https://fonts.gstatic.com" />
    <link
      href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap"
      rel="stylesheet"
    />
    <!-- Fontawesome -->
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.2/css/all.min.css"
      integrity="sha512-HK5fgLBL+xu6dm/Ii3z4xhlSUyZgTT9tuc/hSrtw6uzJOvgRr2a9jyxxT1ely+B+xFAmJKVSTbpM/CuL7qxO8w=="
      crossorigin="anonymous"
    />
    <!-- CSS custom -->
    <link rel="stylesheet" href="style.css" />
    <title>Chatlekha Klamruang</title>
  </head>
  <body>
    <!-- Navbar -->
    <nav class="navbar shadow navbar-expand-lg navbar-light bg-light">
      <div class="container">
        <a class="navbar-brand" href="#">Chatlekha Klamruang</a>
        <div class="right-side-nav">
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarNav"
            aria-controls="navbarNav"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link active" href="#">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#about">About</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#skills">Skills</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#projects">Portfolio</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </nav>

    <!-- Launch screen -->
    <section class="first">
      <div class="container top-container">
        <img
          class="img-fluid profile-pic"
          src="june.jpg"
          alt="Profile"
        />
        <h1 class="name">Chatlekha Klamruang</h1>
        <h5>
          Hello I am a
          <span class="sd">certified AWS Cloud Practitioner</span>
        </h5>
        <div class="icon-container">
          <a href="https://www.linkedin.com/in/chatlekha-klamruang/"><i class="fab fa-linkedin"></i></a>
          <a href="https://github.com/chatlekha"><i class="fab fa-github"></i></a>
          <a href="mailto:chatlekhak@gmail.com"><i class="far fa-envelope"></i></a>
        </div>
        </div>
        <div id="about"></div>
      </div>
    </section>

    <!-- About section -->
    <section class="about">
      <div class="container">
        <h1 class="text-center">About me</h1>
        <div class="custom-hr"></div>
        <div class="row about-me">
          <div class="col-lg-6">
            <img
              class="img-fluid about-me-img"
              src="aboutMe.svg"
              alt=""
            />
          </div>
          <div class="col-lg-6 text-container">
            <p>
              I am a certified AWS cloud practitioner. Experienced in using MATLAB, SQL and Python 
              for data analysis, as well as seven years of experience in the engineering field, 
              focusing on energy industry and project management.
            </p>
            <p>
              My career has been driven by the desire to go above and beyond a clients expectations to achieve the best posssible result.
              I particularly enjoy the eureka moment when I can solve problems through data analysis.
              I love diversity, working in a multi-cultural environment allows me to enhance my communication skills.

            </p>
          </div>
        </div>
      </div>
      <div id="skills"></div>
    </section>

    <!-- Skills section -->
    <section class="skills">
      <div class="container">
        <h1 class="text-center">Skills</h1>
        <div class="custom-hr"></div>
        <div class="skills-container">
          <div class="skills-card shadow">
            <i class="fab fa-aws"></i>
            <p>Amazon Web Services</p>
          </div>
          <div class="skills-card shadow">
            <i class="fab fa-python"></i>
            <p>Python</p>
          </div>
          <div class="skills-card shadow">
            <i class="fas fa-database"></i>
            <p>SQL</p>
          </div>
          <div class="skills-card shadow">
            <i class="fas fa-file-excel"></i>
            <p>Excel</p>
          </div>
          <div class="skills-card shadow">
            <i class="fas fa-chart-area"></i>
            <p>MATLAB</p>
          </div>
          <div class="skills-card shadow">
            <i class="fab fa-linux"></i>
            <p>Linux</p>
          </div>
        </div>
        <div id="projects"></div>
      </div>
    </section>

    <section>
      <h1 class="text-center mt-5">Experience</h1>
      <ul class="timeline">
        <li>
          <div class="direction-l">
            <h4>System Logistics Asia</h4>
            <div class="flag-wrapper">
              <span class="hexa"></span>
              <span class="flag">Data Analyst</span>
              <span class="time-wrapper"
                ><span class="time">Jan 2017- Jul 2018</span></span
              >
            </div>
            <div class="desc">
              I was selected by the company to train in data analysis with SQL at Headquarters in Italy. 
              Upon returning to Thailand I was appointed to lead the training for my team. 
            </div>
          </div>
        </li>
      <!-- Item 1 -->
        <li>
          <div class="direction-r">
            <h4> System Logistics Asia</h4>
            <div class="flag-wrapper">
              <span class="hexa"></span>
              <span class="flag">Project Engineer</span>
              <span class="time-wrapper">
                  <span class="time">Oct 2015-Jul 2018</span>
              </span>
            </div>
            <div class="desc">
              
              Worked with Business Development Team to deliver suitable intralogistics solutions for clients, 
              including analysed data with SQL and excel and cost estimation, successfully attracted new 50 projects over 3 years.
              
            </div>
          </div>
        </li>

        <!-- Item 2 -->
        <li>
          <div class="direction-l">
            <h4>PT. Technip Indonesia</h4>
            <div class="flag-wrapper">
              <span class="hexa"></span>
              <span class="flag">Mechanical Engineer</span>
              <span class="time-wrapper"
                ><span class="time">Jan - May 2015</span></span
              >
            </div>
            <div class="desc">
              Collaborated with Indonesian team to effectively select vendors for electric heater, filters and rectangular tank 
              through Technical Bid Evaluation based on client specification and international standards.
            </div>
          </div>
        </li>

        <!-- Item 3 -->
        <li>
          <div class="direction-r">
            <h4>Technip Engineering (Thailand)</h4>
            <div class="flag-wrapper">
              <span class="hexa"></span>
              <span class="flag">Mechanical Engineer</span>
              <span class="time-wrapper"
                ><span class="time">May 2011 - Jul 2015</span></span
              >
            </div>
            <div class="desc">
              Mechanical design and stress analysis by PV-elite for static equipment and packages for offshore platform, petrochemical plants according to ASME standards and
            </div>
          </div>
        </li>
      </ul>
    </section>
      
    <!-- Projects container -->
    <section class="projects">
      <h1 class="text-center">Projects</h1>
      <div class="custom-hr"></div>
      <div class="container">
        <div class="card-container">
          <div class="project-card shadow">
            <img
              class="project-image img-fluid"
              src="assets/projects/project1.png"
              alt=""
            />
            <h3 class="text-center mt-4">Movie Database</h3>
            <div class="custom-hr mb-3 w-50"></div>
            <p class="text-center pb-3">
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Architecto, provident?
            </p>
          </div>
          <div class="project-card shadow">
            <img
              class="project-image img-fluid"
              src="assets/projects/project2.png"
              alt=""
            />
            <h3 class="text-center mt-4">GSAP Animation</h3>
            <div class="custom-hr mb-3 w-50"></div>
            <p class="text-center pb-3">
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Architecto, provident?
            </p>
          </div>
          <div class="project-card shadow">
            <img
              class="project-image img-fluid"
              src="assets/projects/project3.png"
              alt=""
            />
            <h3 class="text-center mt-4">Tic Tac Toe</h3>
            <div class="custom-hr mb-3 w-50"></div>
            <p class="text-center pb-3">
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Architecto, provident?
            </p>
          </div>
          <div class="project-card shadow">
            <img
              class="project-image img-fluid"
              src="assets/projects/project4.png"
              alt=""
            />
            <h3 class="text-center mt-4">Snake Game</h3>
            <div class="custom-hr mb-3 w-50"></div>
            <p class="text-center pb-3">
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Architecto, provident?
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <section class="footer">
      <div class="container">
        <div class="icon-container">
          <a href=""><i class="fab fa-linkedin"></i></a>
          <a href=""><i class="fab fa-github"></i></a>
          <a href=""><i class="far fa-envelope"></i></a>
        </div>
        <p class="text-footer">Chatlekha Klamruang © 2021</p>
      </div>
    </section>
  </body>
</html>
