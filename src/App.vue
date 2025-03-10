<template>
  <div>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@600&display=swap" rel="stylesheet">
    
    <!-- Navbar -->
    <nav class="navbar">
      <div class="container">
        <h1 class="logo">UmarDevWorks</h1>
        <ul class="nav-links">
          <li><a href="#about">About</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero">
      <img src="/logo.png" alt="UmarDevWorks Logo">
      <h2>Welcome to UmarDevWorks</h2>
      <p>Hey there 👋 Welcome to my world of innovation, crafting code to empower ideas!</p>
      <a href="#projects" class="btn">View Projects</a>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div id="lottie-container"></div>
        <h2>About Me</h2>
      <p>I am currently a student in the second year of O-Levels with computer science as my elective subject along with Physics & Chemistry in the Science group. I have experience in developing html and javascript websites and now I am learning NodeJS. I also have a significant amount of experience in automation including Arduino and ESP family of microcontrollers. Tinkering with electronics to learn along the way is my hobby and have experience in designing home automation systems as further explained in the project section.</p>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="projects">
      <h2>Projects</h2>
      <div class="project-grid">
        <div class="project-card">
          <img src="/Time.jpg" alt="H&T Clock Project">
          <h3 style="color:black">H&T Clock
          </h3>
          <p>The ESP8266/ESP32 microcontroller connects to the OLED display and DHT11 sensor, displaying temperature, humidity, and synced time. Code handles data collection and display management. Proper wiring ensures functional communication between components.</p>
        </div>
        <div class="project-card">
          <img src="/New-Project.webp?url" alt="Makerbox.pk Project" >
            <h3 style="color:black">MakerBox.pk – Founder and Creator</h3>
          <p>Founder and Creator of MakerBox.pk, a STEM-focused business to provide educational kits for hands-on learning. The business model, including project ideas and execution plans, Ecommerce Website, was developed independently.

</p>
        </div>
      </div>
    </section>
   <!-- Skills Section -->
   <section id="skills" class="skills">
        <h2>My Skills</h2>
        <div class="skill-list">
            <div class="skill html">
                <h3>HTML</h3>
                <div class="skill-bar-container">
                    <div class="skill-bar"></div>
                </div>
            </div>
            <div class="skill css">
                <h3>CSS</h3>
                <div class="skill-bar-container">
                    <div class="skill-bar"></div>
                </div>
            </div>
            <div class="skill js">
                <h3>JavaScript</h3>
                <div class="skill-bar-container">
                    <div class="skill-bar"></div>
                </div>
            </div>
            <div class="skill arduino">
                <h3>Arduino</h3>
                <div class="skill-bar-container">
                    <div class="skill-bar"></div>
                </div>
            </div>
            <div class="skill automation">
                <h3>Automation</h3>
                <div class="skill-bar-container">
                    <div class="skill-bar"></div>
                </div>
            </div>
            <div class="skill ecommerce">
                <h3>Ecommerce Business</h3>
                <div class="skill-bar-container">
                    <div class="skill-bar"></div>
                </div>
            </div>
            <div class="skill marketing">
                <h3>Digital Marketing</h3>
                <div class="skill-bar-container">
                    <div class="skill-bar"></div>
                </div>
            </div>
        </div>
    </section>
    
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">

    <section id="contact" class="contact">
    <div class="container">
        <h2>Contact Me</h2>
        <p>If you would like to collaborate or just have a chat, feel free to reach out to me!</p>

        <div class="contact-links">
            <h4>
                <a href="mailto:umr6406@gmail.com" class="contact-link">
                    <i class="fa fa-envelope" aria-hidden="true"></i> Email Me
                </a>
            </h4>

            <h4>
                <a href="https://github.com/UmarDevWorks" target="_blank" class="contact-link">
                    <img src="https://github.com/favicon.ico" alt="GitHub Icon" class="contact-icon"> GitHub Profile
                </a>
            </h4>

          
           
        </div>
    </div>
</section>


    <!-- Footer -->
    <footer class="footer">
      <p><strong>&copy; 2025 UmarDevWorks.</strong> All rights reserved.</p>
    </footer>
  </div>


    
</template>

