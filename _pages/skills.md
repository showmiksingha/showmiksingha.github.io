---
title: "Skills"
permalink: /skills/
layout: default
author_profile: false
classes: wide
---

<div class="wrap" markdown="1">

<style>
/* ===== Page Layout ===== */
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

/* ===== Author Card ===== */
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

/* ===== Publications Content ===== */
.pub-content {
  min-width: 0;
  color: #242424;
}

.pub-content h1 {
  font-size: 2rem;
  margin: 0 0 14px;
  padding-bottom: 12px;
  border-bottom: 2px solid #e5e7eb;
}

.pub-intro {
  font-size: 0.96rem;
  color: #555;
  margin-bottom: 25px;
}

.pub-stats {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 12px;
  margin: 20px 0 32px;
}

.pub-stat {
  border: 1px solid #e5e7eb;
  border-radius: 10px;
  padding: 15px;
  text-align: center;
  background: #fafafa;
}

.pub-stat strong {
  display: block;
  font-size: 1.65rem;
  color: #2563eb;
}

.pub-stat span {
  font-size: 0.83rem;
  color: #555;
}

.pub-content h2 {
  font-size: 1.35rem;
  margin: 36px 0 18px;
  padding-bottom: 8px;
  border-bottom: 1px solid #e5e7eb;
}

/* ===== Publication List ===== */
.publication-list {
  list-style-type: decimal;
  padding-left: 28px;
  margin: 0;
}

.publication-list li {
  padding-left: 5px;
  margin-bottom: 19px;
  font-size: 0.94rem;
  line-height: 1.75;
  overflow-wrap: anywhere;
}

.publication-list li::marker {
  color: #64748b;
  font-weight: 600;
}

.publication-list strong {
  font-weight: 700;
  color: #111827;
}

.publication-list em {
  color: #444;
}

.pub-year {
  color: #64748b;
  font-weight: 600;
}

.pub-tag {
  display: inline-block;
  font-size: 0.72rem;
  font-weight: 600;
  color: #1d4ed8;
  background: #eff6ff;
  padding: 2px 8px;
  border-radius: 5px;
  margin-left: 5px;
}

@media (max-width: 600px) {
  .pub-stats {
    gap: 7px;
  }

  .pub-stat {
    padding: 12px 5px;
  }

  .pub-stat strong {
    font-size: 1.3rem;
  }

  .publication-list li {
    font-size: 0.9rem;
  }
}

/* ===== Skills: Icons and Bullet Lists ===== */
.skills-content {
  min-width: 0;
}

.skill-category h2 i {
  color: #2563eb;
  margin-right: 10px;
}

.skill-list {
  list-style-type: disc;
  padding-left: 28px;
  margin: 10px 0 24px;
}

.skill-list li {
  font-size: 0.94rem;
  line-height: 1.75;
  margin-bottom: 5px;
  padding-left: 4px;
}

.skill-list li::marker {
  color: #64748b;
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
        <a href="https://www.linkedin.com/in/showmik-singha-293967147"
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

  <!-- RIGHT: Technical Skills -->
  <main class="skills-content">

    <h1>Technical Skills</h1>

    <!-- Programming -->
    <section class="skill-category">
      <h2>
        <i class="fas fa-code"></i>
        Programming
      </h2>
      <ul class="skill-list">
        <li>C</li>
        <li>Python</li>
      </ul>
    </section>

    <!-- Modeling and Simulation -->
    <section class="skill-category">
      <h2>
        <i class="fas fa-laptop-code"></i>
        Modeling &amp; Simulation
      </h2>
      <ul class="skill-list">
        <li>Silvaco TCAD</li>
        <li>Sentaurus TCAD</li>
        <li>Cadence</li>
        <li>LTSpice</li>
        <li>OrCAD</li>
        <li>MATLAB</li>
        <li>Simulink</li>
        <li>Lumerical</li>
        <li>Quantum ESPRESSO</li>
        <li>PowerWorld</li>
        <li>AutoCAD</li>
      </ul>
    </section>

    <!-- Semiconductor Processing -->
    <section class="skill-category">
      <h2>
        <i class="fas fa-microchip"></i>
        Semiconductor Processing
      </h2>
      <ul class="skill-list">
        <li>Wafer Preparation</li>
        <li>Spin Coating</li>
        <li>Photolithography</li>
        <li>Wet Etching</li>
        <li>Doping</li>
        <li>Oxidation</li>
        <li>Metallization</li>
        <li>Thin-Film Processing</li>
        <li>Thermal Annealing</li>
      </ul>
    </section>

    <!-- Electrical Characterization -->
    <section class="skill-category">
      <h2>
        <i class="fas fa-bolt"></i>
        Electrical Characterization
      </h2>
      <ul class="skill-list">
        <li>Four-Point Probe</li>
        <li>Hall Measurement (Linseis HCS 1)</li>
        <li>
          Semiconductor Parameter Analyzer
          (I–V, C–V) (Keithley 4200 SCS)
        </li>
      </ul>
    </section>

    <!-- Materials/Physical Characterization -->
    <section class="skill-category">
      <h2>
        <i class="fas fa-microscope"></i>
        Materials/Physical Characterization
      </h2>
      <ul class="skill-list">
        <li>
          Scanning Electron Microscopy
          (Thermo Fisher VolumeScope 2)
        </li>
        <li>
          Fourier Transform Infrared Spectroscopy
          (Thermo Fisher Nicolet 4700)
        </li>
        <li>
          Optical Profilometry (Veeco NT 9109)
        </li>
        <li>
          Raman Spectroscopy
          (Renishaw inVia Microscope)
        </li>
        <li>Spectroscopic Ellipsometry</li>
      </ul>
    </section>

    <!-- Instrumentation -->
    <section class="skill-category">
      <h2>
        <i class="fas fa-tools"></i>
        Instrumentation
      </h2>
      <ul class="skill-list">
        <li>Mask Aligner (SUSS MA6)</li>
        <li>Nanoscribe Quantum X Shape</li>
        <li>Oscilloscope</li>
        <li>Signal Generator</li>
        <li>Multimeter</li>
        <li>Arduino</li>
        <li>Raspberry Pi</li>
      </ul>
    </section>

  </main>

</div>
</div>
