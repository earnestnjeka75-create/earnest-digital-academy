<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Earnest Digital Academy | Learn Digital Skills</title>

  <meta name="description"
        content="Earnest Digital Academy offers practical online courses in digital marketing, affiliate marketing, web development, software development, professional writing and data analysis.">

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    body {
      background: #f5f7fb;
      color: #222;
      line-height: 1.6;
    }

    header {
      background: #071a3d;
      color: white;
      padding: 18px 6%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    .logo {
      font-size: 22px;
      font-weight: bold;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 18px;
      font-size: 14px;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      background: linear-gradient(135deg, #071a3d, #1261a0);
      color: white;
      text-align: center;
      padding: 90px 20px;
    }

    .hero h1 {
      font-size: 42px;
      margin-bottom: 15px;
    }

    .hero p {
      font-size: 19px;
      max-width: 700px;
      margin: auto;
      opacity: 0.95;
    }

    .buttons {
      margin-top: 30px;
    }

    .btn {
      display: inline-block;
      padding: 13px 24px;
      margin: 7px;
      border-radius: 7px;
      text-decoration: none;
      font-weight: bold;
    }

    .primary {
      background: #00c853;
      color: white;
    }

    .secondary {
      background: white;
      color: #071a3d;
    }

    section {
      padding: 65px 6%;
    }

    .section-title {
      text-align: center;
      margin-bottom: 35px;
    }

    .section-title h2 {
      font-size: 30px;
      color: #071a3d;
    }

    .section-title p {
      color: #666;
      margin-top: 8px;
    }

    .courses {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 22px;
    }

    .course {
      background: white;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.08);
      transition: 0.3s;
    }

    .course:hover {
      transform: translateY(-5px);
    }

    .course-icon {
      font-size: 38px;
      margin-bottom: 12px;
    }

    .course h3 {
      color: #071a3d;
      margin-bottom: 8px;
    }

    .course p {
      color: #666;
      font-size: 14px;
    }

    .course a {
      display: inline-block;
      margin-top: 15px;
      color: #1261a0;
      font-weight: bold;
      text-decoration: none;
    }

    .about {
      background: white;
      text-align: center;
    }

    .about-content {
      max-width: 800px;
      margin: auto;
    }

    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }

    .feature {
      padding: 20px;
      background: #f5f7fb;
      border-radius: 10px;
    }

    .contact {
      text-align: center;
      background: #071a3d;
      color: white;
    }

    .contact h2 {
      margin-bottom: 12px;
    }

    .whatsapp {
      display: inline-block;
      margin-top: 20px;
      padding: 14px 25px;
      background: #00c853;
      color: white;
      text-decoration: none;
      border-radius: 7px;
      font-weight: bold;
    }

    footer {
      background: #041027;
      color: #aaa;
      text-align: center;
      padding: 20px;
      font-size: 14px;
    }

    @media (max-width: 700px) {
      header {
        flex-direction: column;
        gap: 12px;
      }

      nav a {
        margin: 0 6px;
      }

      .hero h1 {
        font-size: 32px;
      }

      .hero p {
        font-size: 16px;
      }
    }
  </style>
</head>

<body>

  <!-- HEADER -->
  <header>
    <div class="logo">🎓 Earnest Digital Academy</div>

    <nav>
      <a href="#home">Home</a>
      <a href="#courses">Courses</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>


  <!-- HERO -->
  <section class="hero" id="home">

    <h1>Earnest Digital Academy</h1>

    <p>
      Learn practical digital skills, build your career,
      start earning online and prepare yourself for the digital economy.
    </p>

    <div class="buttons">
      <a href="#courses" class="btn primary">Explore Courses</a>

      <a href="https://wa.me/254713834153"
         class="btn secondary">
         Enroll Now
      </a>
    </div>

  </section>


  <!-- COURSES -->
  <section id="courses">

    <div class="section-title">
      <h2>Our Courses</h2>
      <p>Choose a skill and start learning.</p>
    </div>

    <div class="courses">

      <div class="course">
        <div class="course-icon">📱</div>
        <h3>Online Marketing</h3>
        <p>
          Learn digital marketing, social media marketing,
          SEO, content creation and online advertising.
        </p>
        <a href="https://wa.me/254713834153">
          Enroll →
        </a>
      </div>


      <div class="course">
        <div class="course-icon">💰</div>
        <h3>Affiliate Marketing</h3>
        <p>
          Learn how affiliate marketing works, how to promote
          products and how commissions are generated.
        </p>
        <a href="https://wa.me/254713834153">
          Enroll →
        </a>
      </div>


      <div class="course">
        <div class="course-icon">📧</div>
        <h3>Professional Email Writing</h3>
        <p>
          Learn how to write professional emails,
          applications, proposals and business communication.
        </p>
        <a href="https://wa.me/254713834153">
          Enroll →
        </a>
      </div>


      <div class="course">
        <div class="course-icon">💻</div>
        <h3>Software Development</h3>
        <p>
          Learn programming fundamentals, software concepts,
          databases and practical software projects.
        </p>
        <a href="https://wa.me/254713834153">
          Enroll →
        </a>
      </div>


      <div class="course">
        <div class="course-icon">🌐</div>
        <h3>Web Development</h3>
        <p>
          Learn HTML, CSS and JavaScript and build
          professional websites from scratch.
        </p>
        <a href="https://wa.me/254713834153">
          Enroll →
        </a>
      </div>


      <div class="course">
        <div class="course-icon">✍️</div>
        <h3>Professional Writing</h3>
        <p>
          Learn article writing, blogging, reports,
          proposals and professional content creation.
        </p>
        <a href="https://wa.me/254713834153">
          Enroll →
        </a>
      </div>


      <div class="course">
        <div class="course-icon">📊</div>
        <h3>Data Analysis</h3>
        <p>
          Learn data organization, spreadsheets,
          analysis, visualization and reporting.
        </p>
        <a href="https://wa.me/254713834153">
          Enroll →
        </a>
      </div>


      <div class="course">
        <div class="course-icon">🤖</div>
        <h3>AI & Digital Tools</h3>
        <p>
          Learn how to use modern AI and digital tools
          to improve productivity and online work.
        </p>
        <a href="https://wa.me/254713834153">
          Enroll →
        </a>
      </div>


      <div class="course">
        <div class="course-icon">🎨</div>
        <h3>Graphic Design</h3>
        <p>
          Learn the fundamentals of digital design,
          branding and social media graphics.
        </p>
        <a href="https://wa.me/254713834153">
          Enroll →
        </a>
      </div>


      <div class="course">
        <div class="course-icon">💼</div>
        <h3>Freelancing & Online Work</h3>
        <p>
          Learn how to create a professional profile,
          find clients, communicate with clients and
          deliver online services.
        </p>
        <a href="https://wa.me/254713834153">
          Enroll →
        </a>
      </div>

    </div>

  </section>


  <!-- ABOUT -->
  <section class="about" id="about">

    <div class="about-content">

      <div class="section-title">
        <h2>About Earnest Digital Academy</h2>
      </div>

      <p>
        Earnest Digital Academy is an online learning platform
        focused on practical digital skills. Our goal is to help
        learners develop useful skills for education, employment,
        entrepreneurship and online work.
      </p>

      <div class="features">

        <div class="feature">
          🎯
          <h3>Practical Skills</h3>
          <p>Learn skills through practical lessons and projects.</p>
        </div>

        <div class="feature">
          📚
          <h3>Online Learning</h3>
          <p>Study from wherever you have an internet connection.</p>
        </div>

        <div class="feature">
          🚀
          <h3>Career Growth</h3>
          <p>Develop skills that can support your career journey.</p>
        </div>

      </div>

    </div>

  </section>


  <!-- CONTACT -->
  <section class="contact" id="contact">

    <h2>Ready to Start Learning?</h2>

    <p>
      Contact Earnest Digital Academy to learn more
      about our courses and enrollment.
    </p>

    <a
      class="whatsapp"
      href="https://wa.me/254713834153"
      target="_blank">
      💬 Chat on WhatsApp
    </a>

  </section>


  <!-- FOOTER -->
  <footer>

    <p>
      © 2026 Earnest Digital Academy.
      All Rights Reserved.
    </p>

    <p>
      Learn Digital Skills. Build Your Future.
    </p>

  </footer>

</body>
</html> earnest-digital-academy
