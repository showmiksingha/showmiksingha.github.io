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

/* ===== Skills Content ===== */
.skills-content {
  min-width: 0;
}

.skills-content h1 {
  font-size: 2rem;
  margin-top: 0;
  margin-bottom: 24px;
  padding-bottom: 12px;
  border-bottom: 2px solid #e5e7eb;
}

.skill-category {
  margin-bottom: 25px;
}

.skill-category h2 {
  font-size: 1.2rem;
  font-weight: 700;
  margin-top: 0;
  margin-bottom: 10px;
  color: #222;
}

.skill-category p {
  font-size: 0.98rem;
  line-height: 1.8;
  color: #444;
  margin: 0;
}

.skill-category:not(:last-child) {
  padding-bottom: 20px;
  border-bottom: 1px solid #e5e7eb;
}
</style>

<div class="edu-layout">

  <!-- LEFT: Author Profile -->
  <aside class="author-card">

    <img
      class="author-avatar"
      src="{{ site.author.avatar | relative_url }}"
      alt="{{ site.author.name }}"
    >

    <h2 class="author-name">
      {{ site.author.name }}
    </h2>

    {% if site.author.bio %}
    <p class="author-bio">
      {{ site.author.bio }}
    </p>
    {% endif %}

    <ul class="author-links">

      {% if site.author.location %}
      <li>
        📍 {{ site.author.location }}
      </li>
      {% endif %}

      {% if site.author.email %}
      <li>
        ✉️
        <a href="mailto:{{ site.author.email }}">
          Email
        </a>
      </li>
      {% endif %}

      {% if site.author.googlescholar %}
      <li>
        🎓
        <a href="{{ site.author.googlescholar }}"
           target="_blank" rel="noopener noreferrer">
          Google Scholar
        </a>
      </li>
      {% endif %}

      {% if site.author.github %}
      <li>
        💻
        <a href="https://github.com/{{ site.author.github }}"
           target="_blank" rel="noopener noreferrer">
          GitHub
        </a>
      </li>
      {% endif %}

      {% if site.author.linkedin %}
      <li>
        🔗
        <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}"
           target="_blank" rel="noopener noreferrer">
          LinkedIn
        </a>
      </li>
      {% endif %}

    </ul>

  </aside>

  <!-- RIGHT: Technical Skills -->
  <main class="skills-content">

    <h1>Technical Skills</h1>

    <!-- Programming -->
    <section class="skill-category">
      <h2>Programming</h2>
      <p>
        C, Python
      </p>
    </section>

    <!-- Modeling and Simulation -->
    <section class="skill-category">
      <h2>Modeling &amp; Simulation</h2>
      <p>
        Silvaco TCAD, Sentaurus TCAD, Cadence,
        LTSpice, OrCAD, MATLAB, Simulink,
        Lumerical, Quantum ESPRESSO,
        PowerWorld, AutoCAD
      </p>
    </section>

    <!-- Semiconductor Processing -->
    <section class="skill-category">
      <h2>Semiconductor Processing</h2>
      <p>
        Wafer Preparation, Spin Coating,
        Photolithography, Wet Etching,
        Doping, Oxidation, Metallization,
        Thin-Film Processing, Thermal Annealing
      </p>
    </section>

    <!-- Electrical Characterization -->
    <section class="skill-category">
      <h2>Electrical Characterization</h2>
      <p>
        Four-Point Probe,
        Hall Measurement (Linseis HCS 1),
        Semiconductor Parameter Analyzer
        (I–V, C–V) (Keithley 4200 SCS)
      </p>
    </section>

    <!-- Materials/Physical Characterization -->
    <section class="skill-category">
      <h2>Materials/Physical Characterization</h2>
      <p>
        Scanning Electron Microscopy
        (Thermo Fisher VolumeScope 2),
        Fourier Transform Infrared Spectroscopy
        (Thermo Fisher Nicolet 4700),
        Optical Profilometry (Veeco NT 9109),
        Raman Spectroscopy
        (Renishaw inVia Microscope),
        Spectroscopic Ellipsometry
      </p>
    </section>

    <!-- Instrumentation -->
    <section class="skill-category">
      <h2>Instrumentation</h2>
      <p>
        Mask Aligner (SUSS MA6),
        Nanoscribe Quantum X Shape,
        Oscilloscope, Signal Generator,
        Multimeter, Arduino, Raspberry Pi
      </p>
    </section>

  </main>

</div>
</div>
