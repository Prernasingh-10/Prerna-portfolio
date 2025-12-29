<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Prerna Singh | UI/UX Designer</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <!-- Bootstrap -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

  <!-- Icons -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons/font/bootstrap-icons.css" rel="stylesheet">

  <!-- Custom CSS -->
  <link rel="stylesheet" href="style.css">
</head>
<body>
    <style> body {
  font-family: 'Poppins', sans-serif;
  padding-top: 70px;
}

.hero {
  background: linear-gradient(135deg, #5f2c82, #49a09d);
  color: white;
  padding: 100px 0;
}

.profile-img {
  width: 140px;
  border-radius: 50%;
  margin-bottom: 20px;
}

.section {
  padding: 80px 0;
}

.section-title {
  text-align: center;
  margin-bottom: 40px;
}

#skills img {
  width: 60px;
  transition: transform 0.3s;
}

#skills img:hover {
  transform: scale(1.2);
}
</style>

<!-- NAVBAR -->
<nav class="navbar navbar-expand-lg fixed-top navbar-dark bg-dark">
  <div class="container">
    <a class="navbar-brand" href="#">Prerna Singh</a>
    <button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#nav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="nav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
        <li class="nav-item"><a class="nav-link" href="#experience">Experience</a></li>
        <li class="nav-item"><a class="nav-link" href="#skills">Tools</a></li>
        <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
        <li class="nav-item">
          <a class="btn btn-primary ms-3" href="assets/Prerna_Singh_CV.pdf" download>
            Download CV
          </a>
        </li>
      </ul>
    </div>
  </div>
</nav>

<!-- HERO -->
<section class="hero text-center">
  <div class="container">
    <img src="assets/profile.png" class="profile-img" alt="Prerna Singh">
    <h1>UI/UX Designer & Visual Computing Student</h1>
    <p>Designing user-centered digital experiences</p>
  </div>
</section>

<!-- ABOUT -->
<section id="about" class="section">
  <div class="container">
    <h2 class="section-title">Professional Summary</h2>
    <p>
      Master’s student in Computer Science specializing in <b>Human Computer Interaction and Visual Computing</b> at TU Darmstadt.
      Creative UX/UI Designer with <b>1.5+ years of freelance experience</b> and internship exposure.
      Strong in <b>User-Centered Design</b>, cross-functional collaboration, and visual communication.
      Fluent in English, familiar with German, and known for a proactive, can-do attitude.
    </p>
  </div>
</section>

<!-- EXPERIENCE -->
<section id="experience" class="section bg-light">
  <div class="container">
    <h2 class="section-title">Experience</h2>

    <div class="card mb-3">
      <div class="card-body">
        <h5>UX Researcher – Student Research Assistant</h5>
        <p class="text-muted">Fraunhofer IGD, Darmstadt | Oct 2025 – Present</p>
        <ul>
          <li>Conduct UX-focused research for visual computing applications</li>
          <li>Analyze interaction concepts and improve usability</li>
          <li>Create wireframes, user flows, and UX concepts</li>
        </ul>
      </div>
    </div>

    <div class="card mb-3">
      <div class="card-body">
        <h5>UX/UI Designer Intern</h5>
        <p class="text-muted">Enertics India Pvt. Ltd. | Jan 2024 – Jul 2024</p>
        <ul>
          <li>Designed web and mobile interfaces using UCD principles</li>
          <li>Created prototypes and presentations in Figma & Canva</li>
          <li>Collaborated with developers and stakeholders</li>
        </ul>
      </div>
    </div>

    <div class="card">
      <div class="card-body">
        <h5>Freelance UX/UI Designer</h5>
        <p class="text-muted">Remote | Aug 2022 – Jan 2024</p>
        <ul>
          <li>Delivered user-centered web & mobile designs</li>
          <li>Worked directly with international clients</li>
          <li>Managed multiple projects independently</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<!-- SKILLS -->
<section id="skills" class="section">
  <div class="container text-center">
    <h2 class="section-title">Tools & Technologies</h2>
    <div class="row g-4">
      <div class="col-4 col-md-2"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg"></div>
      <div class="col-4 col-md-2"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg"></div>
      <div class="col-4 col-md-2"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg"></div>
      <div class="col-4 col-md-2"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg"></div>
      <div class="col-4 col-md-2"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg"></div>
      <div class="col-4 col-md-2"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/blender/blender-original.svg"></div>
    </div>
  </div>
</section>

<!-- PROJECTS -->
<section id="projects" class="section bg-light">
  <div class="container">
    <h2 class="section-title">Projects</h2>

    <div class="row g-4">
      <div class="col-md-4">
        <div class="card">
          <img src="assets/wallet-ui.png" class="card-img-top">
          <div class="card-body">
            <h5>iOS E-Wallet App</h5>
            <p>Secure mobile banking UI design</p>
            <a href="https://www.figma.com/design/I7NXkMdiPvLgnzuwjeLAvl/E-Wallet-iOS-ui?node-id=0-1&t=9k8ZqwAoxxcfY36W-1" target="_blank" class="btn btn-outline-primary">
              View on Figma
            </a>
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card">
          <img src="assets/netflix-ui.png" class="card-img-top">
          <div class="card-body">
            <h5>Netflix Mobile UI</h5>
            <p>Design system & interaction study</p>
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card">
          <img src="assets/food-ui.png" class="card-img-top">
          <div class="card-body">
            <h5>Food Ordering Website</h5>
            <p>Responsive end-to-end UX</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer class="text-center p-4 bg-dark text-white">
  © 2025 Prerna Singh | UI/UX Designer
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
