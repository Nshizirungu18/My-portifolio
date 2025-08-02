<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Portfolio</title>
  <!-- Link to external CSS stylesheet -->
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- ========== Navigation Bar ========== -->
  <header>
    <nav>
      <div class="logo-nav">
        <!-- Logo image in the navbar -->
        <img src="https://share.google/t7Xy4L4hGKG2LNFW5" alt="My logo" class="logo">

        <!-- Navigation links for scrolling to page sections -->
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#skills">Skills</a></li>
          <li><a href="#education">Education</a></li>
          <li><a href="#interests">Interests</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </div>
    </nav>
  </header>

  <!-- ========== Hero Section (Home) ========== -->
  <section id="home" class="section-light">
    <h1>Hi, I'm NSHIZIRUNGU Emmanuel</h1>
    <p>
      Aspiring Web Developer<br>
      | UI/UX Designer<br>
      | EdTech Entrepreneur<br>
      | Passionate About Tech
    </p>

    <!-- Profile image -->
    <img src="images/me.png" alt="My Profile Photo" class="profile-pic">
  </section>

  <!-- ========== About Me Section ========== -->
  <section id="about" class="section-dark">
    <h2>About Me</h2>
    <p>
      Hi! I'm Nshizirungu — a relentless problem solver, emerging builder, and proud Rwandan thinker on a mission to make technology work for people.
      <br><br>
      Driven by a passion for impact and innovation, I joined the Power Learn Project to deepen my coding skills and lay the foundation for a career in software engineering. My goal is to harness the power of technology to solve real-world challenges — especially in education, where I believe access, guidance, and opportunity should be available to every learner.
      <br><br>
      This vision led to the creation of <strong>MenyaAfrica</strong>, an initiative focused on building tools that empower students and educators across the continent. Whether it's automating college admissions support or developing intuitive learning platforms, I'm committed to crafting solutions that make a difference.
      <br><br>
      I'm currently advancing my skills in HTML, CSS, and Python, while applying project planning and system design to prepare for a future in entrepreneurship. Every line of code I write is a step closer to building a smarter, more inclusive Africa — and I'm just getting started.
    </p>
  </section>

  <!-- ========== Skills Section ========== -->
  <section id="skills" class="section-light">
    <h2>Programming Languages</h2>
    <ul>
      <li>
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/61/HTML5_logo_and_wordmark.svg" 
             alt="HTML Logo" width="80" height="80"> HTML
      </li>
      <li>
        <img src="https://upload.wikimedia.org/wikipedia/commons/d/d5/CSS3_logo_and_wordmark.svg" 
             alt="CSS Logo" width="80" height="80"> CSS
      </li>
      <li>
        <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" 
             alt="Python Logo" width="80" height="80"> Python
      </li>
    </ul>
  </section>

  <!-- ========== Education Section ========== -->
  <section id="education" class="section-dark">
    <h2>Education</h2>
    <p>
      A2 degree in Physics, Chemistry, Biology & Entrepreneurship - Groupe Scolaire Officiel de Butare (2021–2024)
    </p>

    <!-- Downloadable CV file -->
    <a href="cv/nshizirungu_cv.pdf" download>Download My CV</a>
  </section>

  <!-- ========== Interests Section ========== -->
  <section id="interests" class="section-light">
    <h2>Interests</h2>
    <p>
      I'm passionate about entrepreneurship and leveraging innovation to create scalable impact. This mindset drives projects like MenyaAfrica, where I aim to transform how learners access guidance, mentorship, and opportunity across the continent.
      <br><br>
      As I grow my skills in AI, I'm focused on designing agent-based tools that support educational access, automate decision-making, and bring intelligent systems closer to real-world utility. My work blends data, logic, and empathy to help communities navigate complexity.
      <br><br>
      I care deeply about the intersection of healthcare and education — two areas where thoughtful technology can save lives, shift futures, and create equity. Whether it's streamlining information flow for educators or optimizing processes in medical environments, I envision tools that are simple, intuitive, and empowering.
    </p>
  </section>

  <!-- ========== Projects Section ========== -->
  <section id="projects" class="section-dark">
    <h2>My Projects</h2>

    <!-- Project Card: MenyaAfrica -->
    <div class="project" style="background-color: #1a1c24; padding: 20px; border-radius: 8px; margin-bottom: 30px;">
      <img src="https://app.landingsite.ai/assets/images/preview.png" alt="MenyaAfrica Website Preview" 
           style="width: 100%; max-width: 600px; border-radius: 6px; box-shadow: 0 0 10px rgba(0,0,0,0.4);">
      <h3 style="color: #00ff99;">MenyaAfrica Website</h3>
      <p>A prototype platform designed to improve educational access across Africa. Built with a vision to guide students and educators through localized, tech-powered learning tools.</p>
      <a href="https://app.landingsite.ai/website-preview?id=6ae876b5-9950-4a4a-b954-7bf9c4ec379f" target="_blank" 
         style="color: #00ffff; text-decoration: none;">🔗 View Website Preview</a>
    </div>
  </section>

  <!-- ========== Contact Section ========== -->
  <section id="contact" class="section-light">
    <h2>Contact Me</h2>

    <!-- Embedded Google Form -->
    <iframe 
      src="https://docs.google.com/forms/d/e/1FAIpQLSeOisdpS2ZOtGJxeBgGvgZClZdw0WuL_HrdI2QUJ-D3uVPB_Q/viewform?embedded=true" 
      width="100%" 
      height="719" 
      frameborder="0" 
      marginheight="0" 
      marginwidth="0">
      Loading…
    </iframe>
  </section>

  <!-- ========== Footer Section ========== -->
  <footer>
    <p>Connect with me:</p>

    <!-- Social Media Links -->
    <ul class="social-links">
      <li><a href="https://github.com/Nshizirungu18" target="_blank">GitHub</a></li>
      <li><a href="https://www.linkedin.com/in/Nshizirungu18" target="_blank">LinkedIn</a></li>
      <li><a href="https://x.com/nshizirunguem16?t=aPeRUUypftFwrlCdIuXUkg&s=09" target="_blank">Twitter</a></li>
      <li><a href="mailto:enshizirungu18@gmail.com">Email</a></li>
    </ul>

    <p>© 2025 NSHIZIRUNGU Emmanuel. All rights reserved.</p>
  </footer>

</body>
</html>
