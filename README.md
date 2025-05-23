<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Olaoluwa John Adeleke - Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      background-color: #f5f5f5;
      color: #333;
    }

    header {
      background-color: #1e1e1e;
      color: #fff;
      padding: 2rem 1rem;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2rem;
    }

    header p {
      margin: 0.5rem 0 0;
      font-size: 1.1rem;
    }

    main {
      max-width: 900px;
      margin: 2rem auto;
      padding: 1rem;
      background: #fff;
      box-shadow: 0 0 8px rgba(0,0,0,0.1);
      border-radius: 10px;
    }

    section {
      margin-bottom: 2.5rem;
    }

    h2 {
      color: #1e1e1e;
      border-bottom: 2px solid #eee;
      padding-bottom: 0.3rem;
      margin-bottom: 1rem;
    }

    ul {
      padding-left: 1.2rem;
    }

    .button-section {
      text-align: center;
      margin: 2rem 0;
    }

    .social-btn {
      display: inline-flex;
      align-items: center;
      gap: 10px;
      padding: 10px 16px;
      margin: 10px;
      background-color: #0077B5;
      color: #fff;
      font-weight: bold;
      border-radius: 5px;
      text-decoration: none;
      transition: background-color 0.3s ease;
    }

    .social-btn.github {
      background-color: #333;
    }

    .social-btn.researchgate {
      background-color: #00CCBB;
    }

    .social-btn:hover {
      opacity: 0.9;
    }

    .icon {
      width: 20px;
      height: 20px;
    }

    .project, .publication {
      margin-bottom: 1rem;
    }

    .project-title {
      font-weight: bold;
      font-size: 1.1rem;
    }

    .contact-info p {
      margin: 0.3rem 0;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background-color: #1e1e1e;
      color: #fff;
      margin-top: 2rem;
    }

    a {
      color: #0073b1;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <header>
    <h1>Olaoluwa John Adeleke</h1>
    <p>PhD Student | Electrical Engineer | Power & Energy Researcher</p>
  </header>

  <main>
    <!-- About Section -->
    <section>
      <h2>About Me</h2>
      <p>
        I’m passionate about advancing sustainable energy systems through research, innovation, and practical engineering solutions. 
        I am currently pursuing a PhD in Electrical Engineering at the University of New Orleans, focusing on small-signal stability, power system modeling, and renewable energy integration.
      </p>
    </section>

    <!-- Social Links Section -->
    <section class="button-section">
      <a href="https://www.linkedin.com/in/olaoluwaadeleke" target="_blank" class="social-btn">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" alt="LinkedIn" class="icon">
        Connect on LinkedIn
      </a>
      <a href="https://github.com/olaoluwaadeleke" target="_blank" class="social-btn github">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub" class="icon">
        View GitHub
      </a>
      <a href="https://www.researchgate.net/profile/Olaoluwa-Adeleke-3?ev=hdr_xprf" target="_blank" class="social-btn researchgate">
        <img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/ResearchGate_icon_SVG.svg" alt="ResearchGate" class="icon">
        View ResearchGate
      </a>
    </section>

    <!-- Projects Section -->
    <section>
      <h2>Projects</h2>
      <div class="project">
        <div class="project-title">Design, Construction, and Implementation of AMI (Advanced Metering Infrastructure) connected to the Power Distribution Network in Nigeria</div>
        <p>Developed a smart Advanced Metering Infrastructure (AMI) framework with predictive analytics and IoT security for real-time energy monitoring in Nigeria.</p>
      </div>
      <div class="project">
        <div class="project-title">Small-Signal Stability Analysis on IEEE 39-Bus System</div>
        <p>Modeled and simulated power system dynamics using PSS/E with inverter-based resources for enhanced grid reliability.</p>
      </div>
    </section>

    <!-- Publications Section -->
    <section>
      <h2>Publications</h2>

      <div class="publication">
        <div class="project-title">Design and Implementation of AMI for Real-Time IoT Energy Monitoring System in Nigeria Power Distribution Network</div>
        <p>Proposed a smart, AI-enhanced Advanced Metering Infrastructure for Nigeria’s grid, integrating IoT security and predictive analytics for accurate monitoring and billing.</p>
      </div>

      <div class="publication">
        <div class="project-title">Comprehensive Exploration of Smart Cities</div>
        <p>Analyzed smart city technologies and their applications in sustainable urban development, focusing on telecommunications infrastructure and policy recommendations.</p>
      </div>

      <div class="publication">
        <div class="project-title">Design and Simulation of a Security and Surveillance UAV</div>
        <p>Engineered and simulated a UAV system for real-time surveillance, integrating onboard sensors, remote communication, and AI-powered threat detection capabilities.</p>
      </div>

      <div class="publication">
        <div class="project-title">Internet of Things (IoT) Weather Monitoring System</div>
        <p>Developed a cost-effective, remote IoT-based system for weather monitoring using embedded sensors and real-time data visualization for smart agriculture and environment tracking.</p>
      </div>

      <div class="publication">
        <div class="project-title">Design and Construction of an Automatic Change Over Switch</div>
        <p>Designed and built an electromechanical system to automatically switch between main power and generator supply, ensuring seamless power continuity for households and industries.</p>
      </div>

      <div class="publication">
        <div class="project-title">A Review of IoT Device Security</div>
        <p>Under review.</p>
      </div>

      <div class="publication">
        <div class="project-title">Enabling Collaborative Reinforcement Learning with Human Feedback</div>
        <p>Researching methods for safer and more interactive robot-human learning environments using feedback integration.</p>
      </div>
       <section>
       
    <!-- Skills Section -->
    <section>
      <h2>Skills</h2>
      <ul>
        <li>Power Systems Modeling & Stability (Small-signal, Voltage, and Transient)</li>
        <li>Renewable Energy Systems</li>
        <li>Internet of Things (IoT), & Smart Grid Security</li>
        <li>Blockchain for Energy Trading</li>
        <li>MATLAB, Simulink, PSS/E</li>
        <li>Python, C++,Git</li>
        <li>Data Analysis</li>
      </ul>
    </section>

    <!-- Contact Section -->
    <section class="contact-info">
      <h2>Contact</h2>
      <p>Email: adeleke.j.olaoluwa@gmail.com</p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/olaoluwaadeleke" target="_blank">olaoluwaadeleke</a></p>
      <p>GitHub: <a href="https://github.com/Olajesu-rebirth" target="_blank">Olajesu-rebirth</a></p>
      <p>ResearchGate: <a href="https://www.researchgate.net/profile/Olaoluwa-Adeleke-3?ev=hdr_xprf" target="_blank">Olaoluwa Adeleke</a></p>
    </section>
  </main>

  <footer>
    &copy; 2025 Olaoluwa John Adeleke. All rights reserved.
  </footer>

</body>
</html>
