<!-- GLOBAL STYLING ENGINE -->
<style>
  :root {
    --bg-dark: #000000;
    --card-bg: #2f4550;
    --blue-slate: #586f7c;
    --accent-mint: #b8dbd9;
    --accent-gold: #f4f4f9;
    --text-light: #ffffff;
    --text-gray: #b8dbd9;
  }

  /* Structural Alignment Layouts */
  .custom-container {
    font-family: 'Segoe UI', Arial, sans-serif;
    color: var(--text-light);
    line-height: 1.6;
    max-width: 1100px;
    margin: 0 auto;
    padding: 10px;
  }

  .nav-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 0;
    border-bottom: 2px solid var(--blue-slate);
    margin-bottom: 30px;
  }

  .hero-layout {
    display: flex;
    flex-wrap: wrap;
    gap: 30px;
    align-items: center;
    margin-bottom: 40px;
  }

  .hero-info {
    flex: 1;
    min-width: 300px;
  }

  .hero-frame {
    flex: 0 0 280px;
    margin: 0 auto;
    background-color: var(--card-bg);
    padding: 15px;
    border-radius: 15px;
    text-align: center;
    border: 1px solid var(--blue-slate);
  }

  .hero-frame img {
    width: 100%;
    border-radius: 10px;
    border: 2px solid var(--blue-slate);
    object-fit: cover;
  }

  .tech-tags span {
    display: inline-block;
    background-color: var(--card-bg);
    color: var(--accent-mint);
    padding: 5px 12px;
    border-radius: 15px;
    font-size: 12px;
    margin-right: 6px;
    margin-bottom: 6px;
    border: 1px solid var(--blue-slate);
  }

  .grid-timeline {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(450px, 1fr));
    gap: 25px;
    margin-bottom: 30px;
  }

  .card-block {
    background-color: var(--card-bg);
    padding: 25px;
    border-radius: 12px;
    border: 1px solid var(--blue-slate);
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }

  .badge-label {
    display: inline-block;
    background-color: var(--accent-mint);
    color: var(--bg-dark);
    padding: 3px 10px;
    font-size: 11px;
    font-weight: bold;
    border-radius: 4px;
    margin-bottom: 12px;
    align-self: flex-start;
    text-transform: uppercase;
  }

  .img-row-equal {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(110px, 1fr));
    gap: 10px;
    margin-top: 15px;
    width: 100%;
  }

  .img-row-equal img {
    width: 100%;
    height: 140px;
    border-radius: 6px;
    border: 2px solid var(--blue-slate);
    object-fit: cover;
  }

  .wide-showcase {
    background-color: var(--card-bg);
    padding: 30px;
    border-radius: 12px;
    border: 1px solid var(--blue-slate);
    margin-bottom: 40px;
  }

  .sub-grid-three {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 15px;
    margin-top: 20px;
  }

  .sub-card-mini {
    background-color: rgba(0,0,0,0.3);
    border: 1px solid var(--blue-slate);
    border-radius: 8px;
    padding: 15px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }

  .sub-card-mini img {
    width: 100%;
    height: 150px;
    border-radius: 6px;
    border: 1px solid var(--blue-slate);
    object-fit: cover;
    margin-bottom: 10px;
  }

  .box-highlight {
    background-color: var(--bg-dark);
    padding: 20px;
    border-radius: 8px;
    border-left: 4px solid var(--accent-mint);
    border: 1px solid var(--blue-slate);
  }

  .footer-flex-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(450px, 1fr));
    gap: 30px;
    border-top: 2px solid var(--blue-slate);
    padding-top: 30px;
    margin-top: 30px;
  }

  .gallery-layout-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 12px;
  }

  .gallery-layout-grid img {
    width: 100%;
    height: 130px;
    border-radius: 6px;
    border: 2px solid var(--blue-slate);
    object-fit: cover;
  }

  @media (max-width: 768px) {
    .hero-layout, .grid-timeline, .footer-flex-grid { grid-template-columns: 1fr; }
  }
</style>

<div class="custom-container">

  <!-- HEADER NAVIGATION -->
  <div class="nav-header">
    <div style="font-size: 22px; font-weight: bold; color: var(--accent-mint);">Sarah Jean Dayagro</div>
    <div>
      <font size="3">
        <b><a href="#home" style="color: var(--text-light); text-decoration: none; margin-left: 20px;">Home</a></b>
        <b><a href="#timeline" style="color: var(--text-light); text-decoration: none; margin-left: 20px;">Works</a></b>
        <b><a href="#contact" style="color: var(--text-light); text-decoration: none; margin-left: 20px;">Contact</a></b>
      </font>
    </div>
  </div>

  <!-- HERO PRESENTATION MODULE -->
  <div class="hero-layout" id="home">
    <div class="hero-info">
      <h3 style="color: var(--accent-mint); font-size: 13px; letter-spacing: 2px; margin-bottom: 5px;">INFORMATION SYSTEMS STUDENT | SYSTEMS ANALYST</h3>
      <h1 style="font-size: 48px; color: var(--accent-gold); margin-bottom: 10px; line-height: 1.1;">Portfolio</h1>
      <h2 style="font-size: 18px; color: var(--text-gray); margin-bottom: 20px; font-weight: normal;">Hi, I'm Sarah Jean Dayagro!</h2>
      <p style="text-align: justify; color: var(--text-light); font-size: 15px; margin-bottom: 25px;">
        A 3rd-year Bachelor of Science in Information Systems student at Davao del Norte State College. 
        I specialize in analyzing complex technical requirements, formulating structural entity-relationship database schemas, and engineering comprehensive software configurations that optimize enterprise operational workflows.
      </p>
      <div class="tech-tags">
        <span>Systems Analysis / System Developer</span>
        <span>MySQL / phpMyAdmin</span>
      </div>
    </div>
    <div class="hero-frame">
      <img src="sarah.jpg" alt="Sarah Jean Dayagro Portrait Frame">
      <div style="color: var(--accent-gold); font-weight: bold; margin-top: 10px; font-size: 15px;">Sarah Jean Dayagro</div>
    </div>
  </div>

  <hr style="border: 0; border-top: 1px solid var(--blue-slate); margin: 35px 0;">

  <!-- MATRIX TIMELINE SECTION -->
  <div id="timeline">
    <h2 style="font-size: 26px; color: var(--accent-gold); margin-bottom: 5px;">Outputs from 1st Year to 3rd Year</h2>
    <p style="color: var(--text-gray); font-size: 14px; margin-bottom: 30px;">A systematic log detailing my technical training progress, interactive web developments, and data engineering projects at DNSC.</p>

    <!-- 1ST YEAR EXTENDED HUB -->
    <div class="wide-showcase">
      <span class="badge-label">1st Year Foundations</span>
      <h3 style="font-size: 22px; color: var(--accent-gold); margin-bottom: 10px;">Multimedia Short Films, Desktop Engineering & Early Web Architecture</h3>
      <p style="text-align: justify; font-size: 14px; color: var(--text-light); margin-bottom: 20px;">
        My first year centered on programming logic foundations, desktop UI modeling, introductory computing designs, and digital storytelling projects. I built a dynamic set of projects traversing software engineering and creative multimedia.
      </p>

      <div class="sub-grid-three">
        <!-- Short Films -->
        <div class="sub-card-mini">
          <img src="6.jpg" alt="LUCID Media Production">
          <h5 style="color: var(--accent-mint); font-size: 15px; margin-bottom: 5px;">Multimedia Production: LUCID</h5>
          <p style="font-size: 12px; color: var(--accent-gold);">Co-directed and edited **LUCID**, a student short film that earned a *Best Support Artist* award. Also produced **Part of Your World**, a detailed group music video recreation setup.</p>
        </div>
        <!-- Diwata Pares -->
        <div class="sub-card-mini">
          <img src="4.jpg" alt="Diwata Pares System Interface">
          <h5 style="color: var(--accent-mint); font-size: 15px; margin-bottom: 5px;">Diwata Pares Overload Order App</h5>
          <p style="font-size: 12px; color: var(--accent-gold);">Programmed a standalone food ordering application featuring intuitive menu navigation item matrix boxes, individual price controls, and real-time total checks generation tools.</p>
        </div>
        <!-- L&J Pastries -->
        <div class="sub-card-mini">
          <img src="1.jpg" alt="L&J Pastries Web Interface">
          <h5 style="color: var(--accent-mint); font-size: 15px; margin-bottom: 5px;">L&J Pastries Study Hub Platform</h5>
          <p style="font-size: 12px; color: var(--accent-gold);">Engineered a cafe platform mockup including specialized product grid displays for treats alongside spatial coordinate sections mapping quick-access internet connection areas.</p>
        </div>
      </div>

      <div class="sub-grid-three">
        <!-- Programming 1 Java -->
        <div class="sub-card-mini">
          <img src="2.jpg" alt="Java Source File">
          <h5 style="color: var(--accent-mint); font-size: 15px; margin-bottom: 5px;">Programming 1: Java Core Final</h5>
          <p style="font-size: 12px; color: var(--accent-gold);">Constructed programmatic console logic setups, syntax loops, and error exceptions checking while thoroughly mastering object testing and script debugging workflows.</p>
        </div>
        <!-- Vector Art -->
        <div class="sub-card-mini">
          <img src="3.jpg" alt="Vector Art Interface Illustration">
          <h5 style="color: var(--accent-mint); font-size: 15px; margin-bottom: 5px;">Introduction to Computing Designs</h5>
          <p style="font-size: 12px; color: var(--accent-gold);">Designed symmetrical vector illustration elements and digital graphical schemas inside foundational core classes, detailing robot shapes and pattern layouts.</p>
        </div>
        <!-- Programming 2 -->
        <div class="sub-card-mini">
          <img src="5.jpg" alt="OOP System Defense Team">
          <h5 style="color: var(--accent-mint); font-size: 15px; margin-bottom: 5px;">Programming 2 System Showcase</h5>
          <p style="font-size: 12px; color: var(--accent-gold);">Advanced interface implementation testing object-oriented design matrices. Completed full logic testing phases alongside a successful presentation board evaluation.</p>
        </div>
      </div>

      <h4 style="color: var(--accent-mint); font-size: 16px; margin-top: 25px; margin-bottom: 8px;">Local Database Architectures (XAMPP Environment)</h4>
      <p style="font-size: 14px; text-align: justify; color: var(--text-light); margin-bottom: 15px;">
        Provisioned local Apache hosting networks and crafted relational database tables. Compiled structural validation constraints and constructed clean entity metrics using target MySQL scripts.
      </p>
      <div class="img-row-equal" style="grid-template-columns: 1fr 1fr;">
        <img src="xamp.jpg" alt="XAMPP Local Server Port Routing">
        <img src="xampp.jpg" alt="phpMyAdmin MySQL Command Execution Dashboard">
      </div>
    </div>

    <!-- 2ND AND 3RD YEAR EQUAL GRID -->
    <div class="grid-timeline">
      
      <!-- SECOND YEAR CARD -->
      <div class="card-block">
        <div>
          <span class="badge-label">2nd Year Milestones</span>
          <h3 style="font-size: 20px; color: var(--accent-gold); margin-bottom: 8px;">Quantitative Research Poster Showcase</h3>
          <p style="text-align: justify; font-size: 13.5px; color: var(--text-light);">
            Co-authored, statistically modeled, and formulated a quantitative research project evaluating computing role trends and perceptions at DNSC. Successfully presented and defended the thesis project, securing <b>2nd Place Best Poster Design</b> at the Institute of Computing Symposium.
          </p>
          <h4 style="font-size: 15px; color: var(--accent-mint); margin-top: 15px; margin-bottom: 5px;">Code Layout Debugging & HCI</h4>
          <p style="text-align: justify; font-size: 13.5px; color: var(--text-light);">
            Analyzed underlying stylesheet layouts to master front-end error tracking protocols. Successfully resolved structural alignment flaws, parent container constraints, and complex grid-template boundaries.
          </p>
        </div>
        <div class="img-row-equal">
          <img src="wom.jpg" alt="Sympoline Empirical Research Poster">
          <img src="2nd win.jpg" alt="Symposium Winner Certificate">
          <img src="debuging.jpg" alt="CSS Grid Debug Window">
          <img src="debug.jpg" alt="Box Model Property Troubleshooting Layout">
        </div>
      </div>

      <!-- THIRD YEAR CARD -->
      <div class="card-block">
        <div>
          <span class="badge-label">3rd Year Enterprise Solutions</span>
          <h3 style="font-size: 20px; color: var(--accent-gold); margin-bottom: 8px;">RentScape: Mobile Space Allocation Platform</h3>
          <p style="text-align: justify; font-size: 13.5px; color: var(--text-light);">
            Co-engineered an end-to-end mobile application framework designed to automate property discovery, vacancy metrics tracking, and tenant data handling for apartments and boarding systems in Panabo City. Showcased at the <b>Startup Sundayag 2025 Exhibition</b>, receiving formal certification for its exceptional operational design strategy and requirements blueprinting.
          </p>
          <ul style="margin-left: 15px; font-size: 13px; color: var(--text-gray); margin-top: 10px;">
            <li><b>System Logic:</b> Enabled custom query filter routing and secure logging tracks.</li>
            <li><b>Technical Layout:</b> Designed stylized multi-page marketing flyers and technical data asset layouts.</li>
          </ul>
        </div>
        <div class="img-row-equal">
          <img src="rentscape.jpg" alt="RentScape Product Overview Panel A">
          <img src="rent.jpg" alt="RentScape Technical Features Panel B">
          <img src="scape.jpg" alt="Startup Sundayag Exhibition Booth">
        </div>
      </div>

    </div>

    <!-- PIPELINES SPECIFICATIONS AND ACTIVE DESIGNS -->
    <div class="wide-showcase">
      <h4 style="font-size: 16px; color: var(--accent-gold); text-transform: uppercase; letter-spacing: 1px; margin-bottom: 15px;">Active High-Tier System Proposals</h4>
      <div class="grid-timeline" style="grid-template-columns: repeat(auto-fit, minmax(380px, 1fr)); margin-bottom: 0;">
        <!-- Buzzify -->
        <div class="box-highlight">
          <h5 style="font-size: 16px; color: var(--accent-mint); margin-bottom: 8px;">Buzzify: Web Marketing Platform</h5>
          <p style="font-size: 13px; color: var(--text-light); text-align: justify; margin-bottom: 12px;">
            A specialized web-based application built to enhance digital marketing workflows and brand visibility metrics for the Greater RJ Appliance & Trading Corporation. Finalized requirements coordination and corporate stakeholder pitching modules.
          </p>
          <div class="img-row-equal">
            <img src="pitching.jpg" alt="Buzzify Field Requirement Gathering">
            <img src="out.jpg" alt="Appliance Corporation Strategy Pitch">
          </div>
        </div>
        <!-- E-Library -->
        <div class="box-highlight">
          <h5 style="font-size: 16px; color: var(--accent-mint); margin-bottom: 8px;">E-Library Portal & Registration</h5>
          <p style="font-size: 13px; color: var(--text-light); text-align: justify; margin-bottom: 12px;">
            An automated platform engineered for the Panabo City Library to streamline visitor registration and workstation monitoring. Integrates barcode/QR code authentication paths for seamless real-time usage data reports tracking.
          </p>
          <div class="img-row-equal">
            <img src="library.jpg" alt="Blade System Student Dashboard Mock">
            <img src="system.jpg" alt="E-Library Target File Directory Tree">
          </div>
        </div>
      </div>
    </div>

  </div>

  <!-- FOOTER REGISTRATION GRID -->
  <div class="footer-flex-grid" id="contact">
    
    <!-- CONTACT SECTION -->
    <div class="contact-card">
      <h3 style="font-size: 22px; color: var(--accent-gold); margin-bottom: 5px;">Get In Touch</h3>
      <h4 style="font-size: 16px; color: var(--accent-mint); margin-bottom: 15px; border-bottom: 1px solid var(--blue-slate); padding-bottom: 8px;">Contact & Networks</h4>
      <div class="contact-item"><b>📞 Phone Contact:</b> +63 965 083 8942</div>
      <div class="contact-item"><b>✉️ Email Address:</b> <a href="mailto:sarahjean.dayagro@gmail.com">sarahjean.dayagro@gmail.com</a></div>
      <div class="contact-item"><b>📍 Location Address:</b> Panabo City, Davao del Norte, Philippines</div>
      
      <h4 style="font-size: 16px; color: var(--accent-mint); margin-top: 25px; margin-bottom: 12px; border-bottom: 1px solid var(--blue-slate); padding-bottom: 8px;">Professional Channels</h4>
      <div class="contact-item"><b>💼 LinkedIn Profile:</b> <a href="#">linkedin.com/in/sarah-jean-dayagro</a></div>
      <div class="contact-item"><b>🏫 Institutional Site:</b> <a href="https://dnsc.edu.ph" target="_blank">Davao del Norte State College</a></div>
    </div>

    <!-- RUNNING ARCHIVES GALLERY -->
    <div>
      <h3 style="font-size: 18px; color: var(--accent-gold); margin-bottom: 15px;">Institutional Operations Gallery</h3>
      <div class="gallery-layout-grid">
        <img src="outline.jpg" alt="Systems Requirements Defense">
        <img src="defec.jpg" alt="Library Workstation Review Runs">
        <img src="lib.jpg" alt="Panabo City Library Field Coordination">
        <img src="library.jpg" alt="Appliance Center System Validation Iteration">
      </div>
    </div>

  </div>

  <!-- BOTTOM BAR FOOTER -->
  <div class="bottom-bar" style="margin-top: 30px; padding: 20px 0; text-align: center; font-size: 12px; color: var(--text-gray); border-top: 1px solid var(--blue-slate);">
    <p>© 2026 Sarah Jean Dayagro · Formatted via Integrated Custom Engines for GitHub README</p>
  </div>

</div>
