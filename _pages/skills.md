---
title: "Skills"
permalink: /skills/
layout: default
author_profile: false
classes: wide
---

<div class="wrap" markdown="1">

<style>

/* ==========================================
   PAGE LAYOUT
========================================== */

.edu-layout {
  display: grid;
  grid-template-columns: 260px minmax(0, 1fr);
  gap: 28px;
  align-items: start;
}

@media (max-width: 900px) {
  .edu-layout {
    grid-template-columns: 1fr;
  }
}

/* ==========================================
   LEFT: AUTHOR PROFILE
========================================== */

.author-card {
  position: sticky;
  top: 90px;
  border: 1px solid #e5e7eb;
  border-radius: 14px;
  padding: 16px;
  background: #fff;
}

@media (max-width: 900px) {
  .author-card {
    position: static;
  }
}

.author-avatar {
  width: 110px;
  height: 110px;
  border-radius: 999px;
  object-fit: cover;
  display: block;
  margin: 0 auto 10px auto;
}

.author-name {
  text-align: center;
  font-weight: 800;
  margin: 0;
}

.author-bio {
  text-align: center;
  color: #6b7280;
  margin: 6px 0 12px 0;
  font-size: 0.95rem;
}

.author-links {
  list-style: none;
  padding: 0;
  margin: 0;
}

.author-links li {
  margin: 8px 0;
}

.author-links a {
  text-decoration: none;
  display: inline-flex;
  gap: 8px;
  align-items: center;
}

/* ==========================================
   RIGHT: TECHNICAL SKILLS
========================================== */

.skills-content {
  min-width: 0;
  width: 100%;
  color: #242424;
}

.skills-content h1 {
  font-size: 2rem;
  font-weight: 700;
  margin: 0 0 28px;
  padding-bottom: 12px;
  border-bottom: 2px solid #e5e7eb;
}

/* Individual categories */

.skills-content .skill-category {
  margin-bottom: 34px;
  padding-bottom: 26px;
  border-bottom: 1px solid #e5e7eb;
}

.skills-content .skill-category:last-child {
  border-bottom: none;
}

/* Category headings */

.skills-content .skill-category h2 {
  display: flex;
  align-items: center;
  gap: 10px;

  font-size: 1.25rem;
  font-weight: 700;
  line-height: 1.4;

  margin: 0 0 18px;
  padding: 0;
  border: none;

  color: #242424;
}

/* Category icons */

.skills-content .skill-category h2 i {
  color: #2563eb;
  font-size: 1.15rem;
  width: 24px;
  text-align: center;
  flex-shrink: 0;
}

/* ==========================================
   SKILL TAG CONTAINER
========================================== */

.skills-content .skill-tags {
  display: flex !important;
  flex-wrap: wrap !important;
  align-items: center;
  gap: 11px;
  margin: 0;
  padding: 0;
}

/* ==========================================
   INDIVIDUAL SKILL TAG
========================================== */

.skills-content .skill-tags .skill-tag {
  display: inline-flex !important;
  align-items: center;
  justify-content: center;

  padding: 10px 17px !important;

  background-color: #f8fafc !important;
  color: #334155 !important;

  border: 1px solid #dbe3ed !important;
  border-radius: 999px !important;

  font-family: inherit;
  font-size: 0.88rem !important;
  font-weight: 500 !important;
  line-height: 1.4;

  text-align: center;
  text-decoration: none !important;

  cursor: default;
  user-select: none;

  box-shadow: 0 1px 2px rgba(0,0,0,0.03);

  transform: translateY(0) scale(1);

  transition:
    background-color 0.25s ease,
    color 0.25s ease,
    border-color 0.25s ease,
    transform 0.25s ease,
    box-shadow 0.25s ease !important;
}

/* ==========================================
   HOVER EFFECT
========================================== */

.skills-content .skill-tags .skill-tag:hover {
  background-color: #2563eb !important;
  color: #ffffff !important;

  border-color: #2563eb !important;

  transform: translateY(-4px) scale(1.04) !important;

  box-shadow:
    0 8px 20px rgba(37,99,235,0.28) !important;
}

/* Keyboard focus, if tags become interactive */

.skills-content .skill-tags .skill-tag:focus-visible {
  outline: 2px solid #2563eb;
  outline-offset: 3px;
}

/* ==========================================
   MOBILE RESPONSIVENESS
========================================== */

@media (max-width: 600px) {

  .skills-content h1 {
    font-size: 1.75rem;
  }

  .skills-content .skill-category h2 {
    font-size: 1.12rem;
  }

  .skills-content .skill-tags {
    gap: 8px;
  }

  .skills-content .skill-tags .skill-tag {
    padding: 8px 13px !important;
    font-size: 0.82rem !important;
  }

}

/* Accessibility: reduce motion when requested */

@media (prefers-reduced-motion: reduce) {
  .skills-content .skill-tags .skill-tag {
    transition: none !important;
  }

  .skills-content .skill-tags .skill-tag:hover {
    transform: none !important;
  }
}

</style>


<div class="edu-layout">

  <!-- =====================================
       LEFT: AUTHOR PROFILE
  ====================================== -->

  <aside class="author-card">

    <img
      class="author-avatar"
      src="/assets/images/profile.JPG"
      alt="Showmik Singha"
    >

    <p class="author-name">Showmik Singha</p>

    <p class="author-bio">
      PhD Candidate, University of Missouri
    </p>

    <ul class="author-links">

      <li>
        <a href="mailto:ssqk4@umsystem.edu">
          <i class="fas fa-fw fa-envelope"></i>
          <span>Email</span>
        </a>
      </li>

      <li>
        <a href="https://github.com/showmiksingha"
           target="_blank" rel="noopener">
          <i class="fab fa-fw fa-github"></i>
          <span>GitHub</span>
        </a>
      </li>

      <li>
        <a href="https://www.linkedin.com/in/showmiksingha/"
           target="_blank" rel="noopener">
          <i class="fab fa-fw fa-linkedin"></i>
          <span>LinkedIn</span>
        </a>
      </li>

    </ul>

  </aside>


  <!-- =====================================
       RIGHT: TECHNICAL SKILLS
  ====================================== -->

  <main class="skills-content">

    <h1>Technical Skills</h1>


    <!-- =====================================
         PROGRAMMING
    ====================================== -->

    <section class="skill-category">

      <h2>
        <i class="fas fa-code"></i>
        Programming
      </h2>

      <div class="skill-tags">
        <span class="skill-tag">C</span>
        <span class="skill-tag">Python</span>
        <span class="skill-tag">MATLAB</span>
      </div>

    </section>


    <!-- =====================================
         MODELING & SIMULATION
    ====================================== -->

    <section class="skill-category">

      <h2>
        <i class="fas fa-laptop-code"></i>
        Modeling &amp; Simulation
      </h2>

      <div class="skill-tags">

        <span class="skill-tag">Silvaco TCAD</span>
        <span class="skill-tag">Sentaurus TCAD</span>
        <span class="skill-tag">Cadence</span>
        <span class="skill-tag">LTSpice</span>
        <span class="skill-tag">OrCAD</span>
        <span class="skill-tag">Simulink</span>
        <span class="skill-tag">Lumerical</span>
        <span class="skill-tag">Quantum ESPRESSO</span>
        <span class="skill-tag">PowerWorld</span>
        <span class="skill-tag">AutoCAD</span>

      </div>

    </section>


    <!-- =====================================
         SEMICONDUCTOR PROCESSING
    ====================================== -->

    <section class="skill-category">

      <h2>
        <i class="fas fa-microchip"></i>
        Semiconductor Processing
      </h2>

      <div class="skill-tags">

        <span class="skill-tag">Wafer Preparation</span>
        <span class="skill-tag">Spin Coating</span>
        <span class="skill-tag">Photolithography</span>
        <span class="skill-tag">Wet Etching</span>
        <span class="skill-tag">Doping</span>
        <span class="skill-tag">Oxidation</span>
        <span class="skill-tag">Metallization</span>
        <span class="skill-tag">Thin-Film Processing</span>
        <span class="skill-tag">Thermal Annealing</span>

      </div>

    </section>


    <!-- =====================================
         ELECTRICAL CHARACTERIZATION
    ====================================== -->

    <section class="skill-category">

      <h2>
        <i class="fas fa-bolt"></i>
        Electrical Characterization
      </h2>

      <div class="skill-tags">

        <span class="skill-tag">
          Four-Point Probe
        </span>

        <span class="skill-tag">
          Hall Measurement (Linseis HCS 1)
        </span>

        <span class="skill-tag">
          Semiconductor Parameter Analyzer
          (I–V, C–V) (Keithley 4200 SCS)
        </span>

      </div>

    </section>


    <!-- =====================================
         MATERIALS / PHYSICAL CHARACTERIZATION
    ====================================== -->

    <section class="skill-category">

      <h2>
        <i class="fas fa-microscope"></i>
        Materials/Physical Characterization
      </h2>

      <div class="skill-tags">

        <span class="skill-tag">
          Scanning Electron Microscopy
          (Thermo Fisher VolumeScope 2)
        </span>

        <span class="skill-tag">
          Fourier Transform Infrared Spectroscopy
          (Thermo Fisher Nicolet 4700)
        </span>

        <span class="skill-tag">
          Optical Profilometry (Veeco NT 9109)
        </span>

        <span class="skill-tag">
          Raman Spectroscopy
          (Renishaw inVia Microscope)
        </span>

        <span class="skill-tag">
          Spectroscopic Ellipsometry
        </span>

      </div>

    </section>


    <!-- =====================================
         INSTRUMENTATION
    ====================================== -->

    <section class="skill-category">

      <h2>
        <i class="fas fa-tools"></i>
        Instrumentation
      </h2>

      <div class="skill-tags">

        <span class="skill-tag">
          Mask Aligner (SUSS MA6)
        </span>

        <span class="skill-tag">
          Nanoscribe Quantum X Shape
        </span>

        <span class="skill-tag">Oscilloscope</span>
        <span class="skill-tag">Signal Generator</span>
        <span class="skill-tag">Multimeter</span>
        <span class="skill-tag">Arduino</span>
        <span class="skill-tag">Raspberry Pi</span>

      </div>

    </section>

  </main>

</div>

</div>
