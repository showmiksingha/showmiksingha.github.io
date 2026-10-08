---
title: "Projects"
permalink: /projects/
layout: default
author_profile: false
classes: wide
---

<div class="wrap" markdown="1">

<style>
/* ===================================== */
/* PAGE LAYOUT */
/* ===================================== */
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

/* ===================================== */
/* AUTHOR PROFILE */
/* ===================================== */
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
  margin: 0 auto 12px;
}

.author-name {
  font-size: 1.25rem;
  font-weight: 700;
  text-align: center;
  margin-bottom: 6px;
}

.author-title {
  font-size: 0.9rem;
  text-align: center;
  color: #555;
  margin-bottom: 12px;
}

.author-bio {
  font-size: 0.88rem;
  line-height: 1.6;
  color: #555;
  text-align: center;
}

.author-links {
  margin-top: 16px;
  font-size: 0.9rem;
}

.author-links a {
  display: block;
  margin-bottom: 9px;
  text-decoration: none;
  color: #334155;
}

.author-links a:hover {
  color: #2563eb;
  text-decoration: none;
}

/* ===================================== */
/* PROJECT CONTENT */
/* ===================================== */
.project-content {
  min-width: 0;
}

.project-content h1 {
  margin-top: 0;
  margin-bottom: 12px;
  font-size: 1.85rem;
}

.project-intro {
  color: #555;
  line-height: 1.75;
  margin-bottom: 28px;
}

/* ===================================== */
/* SECTION HEADINGS */
/* ===================================== */
.project-category {
  display: flex;
  align-items: center;
  gap: 10px;
  margin-top: 32px;
  margin-bottom: 18px;
  padding-bottom: 11px;
  border-bottom: 2px solid #e5e7eb;
  font-size: 1.28rem;
  font-weight: 700;
  line-height: 1.4;
}

.project-category i {
  color: #2563eb;
  font-size: 1.05rem;
}

/* ===================================== */
/* PROJECT CARDS */
/* ===================================== */
.project-item {
  background: #ffffff;
  border: 1px solid #e5e7eb;
  border-radius: 14px;
  padding: 22px;
  margin-bottom: 18px;

  transition:
    border-color 0.25s ease,
    box-shadow 0.25s ease,
    transform 0.25s ease;
}

.project-item:hover {
  border-color: #bfdbfe;
  box-shadow: 0 8px 24px rgba(15, 23, 42, 0.07);
  transform: translateY(-2px);
}

.project-title {
  font-size: 1.13rem;
  font-weight: 700;
  line-height: 1.5;
  margin: 0 0 8px;
  color: #172033;
}

.project-meta {
  font-size: 0.85rem;
  color: #64748b;
  margin-bottom: 15px;
}

.project-meta i {
  margin-right: 5px;
  color: #64748b;
}

/* ===================================== */
/* PROJECT DESCRIPTION LIST */
/* ===================================== */
.project-list {
  margin: 10px 0 16px;
  padding-left: 20px;
}

.project-list li {
  margin-bottom: 10px;
  line-height: 1.7;
  color: #475569;
  font-size: 0.94rem;
}

.project-list li:last-child {
  margin-bottom: 0;
}

.project-list li::marker {
  color: #2563eb;
}

/* ===================================== */
/* TECHNOLOGY KEYWORD PILLS */
/* ===================================== */
.project-tags {
  display: flex !important;
  flex-wrap: wrap !important;
  gap: 9px !important;
  margin-top: 18px;
  margin-bottom: 2px;
}

.project-tag {
  display: inline-flex !important;
  align-items: center;
  justify-content: center;

  padding: 7px 14px !important;

  border: 1px solid #dbe3ed !important;
  border-radius: 999px !important;

  background-color: #f1f5f9 !important;
  color: #334155 !important;

  font-size: 0.8rem !important;
  font-weight: 500 !important;
  line-height: 1.4 !important;

  white-space: normal;
  text-align: center;
  cursor: default;

  transition:
    background-color 0.25s ease,
    color 0.25s ease,
    border-color 0.25s ease,
    box-shadow 0.25s ease,
    transform 0.25s ease !important;
}

/* Blue hover effect */
.project-tag:hover {
  background-color: #2563eb !important;
  color: #ffffff !important;
  border-color: #2563eb !important;

  transform: translateY(-2px);

  box-shadow: 0 4px 12px rgba(37, 99, 235, 0.22);
}

/* ===================================== */
/* MOBILE RESPONSIVENESS */
/* ===================================== */
@media (max-width: 600px) {
  .project-content h1 {
    font-size: 1.6rem;
  }

  .project-category {
    font-size: 1.12rem;
  }

  .project-item {
    padding: 17px;
  }

  .project-title {
    font-size: 1.05rem;
  }

  .project-list {
    padding-left: 18px;
  }

  .project-list li {
    font-size: 0.9rem;
  }

  .project-tags {
    gap: 7px !important;
  }

  .project-tag {
    padding: 6px 11px !important;
    font-size: 0.76rem !important;
  }
}

@media (prefers-reduced-motion: reduce) {
  .project-item,
  .project-tag {
    transition: none !important;
  }
}
</style>

<div class="edu-layout">

  <!-- ===================================== -->
  <!-- LEFT: AUTHOR PROFILE -->
  <!-- ===================================== -->
  <aside class="author-card">

    <img
      src="{{ '/assets/images/profile.JPG' | relative_url }}"
      alt="Showmik Singha"
      class="author-avatar"
    >

    <div class="author-name">
      Showmik Singha
    </div>

    <div class="author-title">
      PhD Candidate, University of Missouri
    </div>

    <div class="author-bio">
      Semiconductor Device Modeling,
      Wide- and Ultra-Wide-Bandgap Power Devices,
      Radiation Effects, and Machine Learning.
    </div>

    <div class="author-links">

      <a href="mailto:ssqk4@umsystem.edu">
        <i class="fas fa-envelope"></i> Email
      </a>

      <a href="https://scholar.google.com/citations?user=B0llklQAAAAJ&hl=en"
         target="_blank" rel="noopener noreferrer">
        <i class="ai ai-google-scholar"></i> Google Scholar
      </a>

      <a href="https://github.com/showmiksingha"
         target="_blank" rel="noopener noreferrer">
        <i class="fab fa-github"></i> GitHub
      </a>

    </div>

  </aside>

  <!-- ===================================== -->
  <!-- RIGHT: RESEARCH PROJECTS -->
  <!-- ===================================== -->
  <main class="project-content">

    <h1>Research Projects</h1>

    <p class="project-intro">
      My research integrates semiconductor device
      physics, numerical simulation, radiation
      reliability, machine learning, and
      microfabrication. These projects investigate
      next-generation electronic devices for
      high-performance power conversion and
      operation in extreme environments.
    </p>

    <!-- ===================================== -->
    <!-- RADIATION EFFECTS -->
    <!-- ===================================== -->

    <h2 class="project-category">
      <i class="fas fa-atom"></i>
      Radiation Effects and Device Reliability
    </h2>

    <!-- Project 1 -->
    <div class="project-item">

      <h3 class="project-title">
        Single-Event Transient Analysis of
        GaN High Electron Mobility Transistors
      </h3>

      <div class="project-meta">
        <i class="fas fa-university"></i>
        University of Missouri–Columbia
      </div>

      <ul class="project-list">
        <li>
          Developed physics-based TCAD models of
          enhancement-mode p-GaN/AlGaN/GaN HEMTs
          to investigate radiation-induced
          single-event transient responses.
        </li>

        <li>
          Simulated heavy-ion irradiation under
          normal incidence across different
          drain biases and linear energy transfer
          conditions.
        </li>

        <li>
          Analyzed transient drain currents,
          charge collection, electric-field
          distributions, and dual-peak
          transient responses.
        </li>

        <li>
          Evaluated radiation susceptibility
          and device reliability for applications
          in space and other radiation-intensive
          environments.
        </li>
      </ul>

      <div class="project-tags">
        <span class="project-tag">GaN HEMT</span>
        <span class="project-tag">TCAD</span>
        <span class="project-tag">Radiation Effects</span>
        <span class="project-tag">Silvaco Atlas</span>
      </div>

    </div>

    <!-- Project 2 -->
    <div class="project-item">

      <h3 class="project-title">
        Radiation Response of
        β-Ga<sub>2</sub>O<sub>3</sub> MOSFETs
        Under Oblique Heavy-Ion Irradiation
      </h3>

      <div class="project-meta">
        <i class="fas fa-university"></i>
        University of Missouri–Columbia
      </div>

      <ul class="project-list">
        <li>
          Developed two-dimensional TCAD models
          of lateral β-Ga<sub>2</sub>O<sub>3</sub>
          MOSFETs to investigate single-event
          transient behavior.
        </li>

        <li>
          Evaluated heavy-ion strikes at different
          incidence angles, drain voltages,
          and energy deposition levels.
        </li>

        <li>
          Investigated transient current peaks,
          charge collection, recovery behavior,
          and radiation-sensitive regions
          within the device.
        </li>

        <li>
          Identified the influence of particle
          trajectory and device bias on
          radiation susceptibility and
          device performance.
        </li>
      </ul>

      <div class="project-tags">
        <span class="project-tag">β-Ga2O3 MOSFET</span>
        <span class="project-tag">TCAD</span>
        <span class="project-tag">Heavy-Ion Irradiation</span>
        <span class="project-tag">Device Reliability</span>
      </div>

    </div>

    <!-- Project 3 -->
    <div class="project-item">

      <h3 class="project-title">
        Temperature-Dependent Single-Event
        Transient Analysis of
        β-Ga<sub>2</sub>O<sub>3</sub> MOSFETs
      </h3>

      <div class="project-meta">
        <i class="fas fa-university"></i>
        University of Missouri–Columbia
      </div>

      <ul class="project-list">
        <li>
          Investigated radiation-induced
          transient responses of
          β-Ga<sub>2</sub>O<sub>3</sub> MOSFETs
          over temperatures ranging from
          300 K to 500 K.
        </li>

        <li>
          Performed heavy-ion simulations at
          different linear energy transfer
          values under high-voltage off-state
          operating conditions.
        </li>

        <li>
          Quantified temperature-dependent
          variations in peak transient current,
          pulse width, and device recovery.
        </li>

        <li>
          Assessed the combined influence of
          temperature and radiation on
          semiconductor reliability for
          extreme-environment power electronics.
        </li>
      </ul>

      <div class="project-tags">
        <span class="project-tag">β-Ga2O3</span>
        <span class="project-tag">Temperature Analysis</span>
        <span class="project-tag">Single-Event Transients</span>
        <span class="project-tag">Power MOSFET</span>
      </div>

    </div>

    <!-- ===================================== -->
    <!-- SEMICONDUCTOR DEVICE MODELING -->
    <!-- ===================================== -->

    <h2 class="project-category">
      <i class="fas fa-microchip"></i>
      Semiconductor Device Modeling
    </h2>

    <!-- Project 4 -->
    <div class="project-item">

      <h3 class="project-title">
        DC Characterization and Modeling of
        AlN/β-Ga<sub>2</sub>O<sub>3</sub> HEMTs
      </h3>

      <div class="project-meta">
        <i class="fas fa-university"></i>
        University of Missouri–Columbia
      </div>

      <ul class="project-list">
        <li>
          Developed numerical device models of
          AlN/β-Ga<sub>2</sub>O<sub>3</sub>
          high electron mobility transistors
          for power electronic applications.
        </li>

        <li>
          Investigated output and transfer
          characteristics to evaluate current
          conduction and device operation.
        </li>

        <li>
          Analyzed threshold voltage,
          transconductance, on-resistance,
          and current saturation behavior.
        </li>

        <li>
          Evaluated capacitance-voltage
          characteristics and key device
          parameters to assess performance
          and optimization opportunities.
        </li>
      </ul>

      <div class="project-tags">
        <span class="project-tag">AlN/β-Ga2O3</span>
        <span class="project-tag">HEMT</span>
        <span class="project-tag">DC Characterization</span>
        <span class="project-tag">TCAD</span>
      </div>

    </div>

    <!-- ===================================== -->
    <!-- MACHINE LEARNING -->
    <!-- ===================================== -->

    <h2 class="project-category">
      <i class="fas fa-brain"></i>
      Machine Learning for Semiconductor Devices
    </h2>

    <!-- Project 5 -->
    <div class="project-item">

      <h3 class="project-title">
        Machine Learning-Enabled Parameter
        Extraction of β-Ga<sub>2</sub>O<sub>3</sub>
        MOSFETs
      </h3>

      <div class="project-meta">
        <i class="fas fa-university"></i>
        University of Missouri–Columbia
      </div>

      <ul class="project-list">
        <li>
          Generated a TCAD-based dataset of
          600 device configurations and
          approximately 6,000 current-voltage
          curves for machine learning applications.
        </li>

        <li>
          Developed inverse modeling techniques
          to predict oxide thickness, channel
          thickness, doping concentration,
          and gate dimensions from electrical
          characteristics.
        </li>

        <li>
          Evaluated XGBoost, convolutional
          neural networks, and Transformer
          architectures for semiconductor
          parameter extraction.
        </li>

        <li>
          Developed a hybrid prediction framework
          achieving a mean R² of approximately
          0.942 across the modeled device
          parameters.
        </li>
      </ul>

      <div class="project-tags">
        <span class="project-tag">Machine Learning</span>
        <span class="project-tag">XGBoost</span>
        <span class="project-tag">CNN</span>
        <span class="project-tag">Python</span>
        <span class="project-tag">Inverse Modeling</span>
      </div>

    </div>

    <!-- Project 6 -->
    <div class="project-item">

      <h3 class="project-title">
        Machine Learning-Based Inverse Modeling
        of Semiconductor PIN Diodes
      </h3>

      <div class="project-meta">
        <i class="fas fa-microchip"></i>
        Semiconductor Device Modeling and Data Analysis
      </div>

      <ul class="project-list">
        <li>
          Investigated data-driven parameter
          extraction techniques for
          semiconductor PIN diode structures.
        </li>

        <li>
          Used simulated current-voltage
          characteristics to construct
          datasets for inverse device modeling.
        </li>

        <li>
          Explored Transformer-based learning
          and feature extraction techniques
          to estimate doping concentrations
          and structural parameters.
        </li>

        <li>
          Assessed machine learning approaches
          for accelerating device characterization
          and reducing repeated numerical
          simulation requirements.
        </li>
      </ul>

      <div class="project-tags">
        <span class="project-tag">PIN Diode</span>
        <span class="project-tag">Transformer</span>
        <span class="project-tag">Python</span>
        <span class="project-tag">Parameter Extraction</span>
      </div>

    </div>

    <!-- ===================================== -->
    <!-- MICROFABRICATION -->
    <!-- ===================================== -->

    <h2 class="project-category">
      <i class="fas fa-flask"></i>
      Microfabrication and Experimental Research
    </h2>

    <!-- Project 7 -->
    <div class="project-item">

      <h3 class="project-title">
        Carbonized Nanostructure Biosensor
        Fabrication Using Two-Photon Polymerization
      </h3>

      <div class="project-meta">
        <i class="fas fa-flask"></i>
        Microfabrication and Biosensor Development
      </div>

      <ul class="project-list">
        <li>
          Fabricated three-dimensional
          micro- and nanostructures using
          Nanoscribe two-photon polymerization
          on metallized silicon substrates.
        </li>

        <li>
          Performed substrate cleaning,
          metallization, and thermal
          carbonization processes for
          sensor fabrication.
        </li>

        <li>
          Investigated fabrication parameters,
          process repeatability, and
          troubleshooting strategies to
          improve structural quality.
        </li>

        <li>
          Contributed to the development of
          carbon-based electrochemical
          biosensing platforms for
          glucose detection.
        </li>
      </ul>

      <div class="project-tags">
        <span class="project-tag">Nanoscribe</span>
        <span class="project-tag">Two-Photon Polymerization</span>
        <span class="project-tag">Microfabrication</span>
        <span class="project-tag">Biosensors</span>
      </div>

    </div>

  </main>

</div>

</div>
