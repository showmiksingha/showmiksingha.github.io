---
title: "Projects"
permalink: /projects/
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
}

.author-links a:hover {
  text-decoration: underline;
}

/* ===== Projects Content ===== */
.project-content {
  min-width: 0;
}

.project-content h1 {
  margin-top: 0;
  margin-bottom: 12px;
}

.project-intro {
  color: #555;
  line-height: 1.7;
  margin-bottom: 26px;
}

/* ===== Project Categories ===== */
.project-category {
  margin-top: 30px;
  margin-bottom: 18px;
  padding-bottom: 9px;
  border-bottom: 2px solid #e5e7eb;
  font-size: 1.35rem;
  font-weight: 700;
}

/* ===== Individual Projects ===== */
.project-item {
  margin-bottom: 30px;
  padding-bottom: 22px;
  border-bottom: 1px solid #e5e7eb;
}

.project-item:last-child {
  border-bottom: none;
}

.project-title {
  font-size: 1.12rem;
  font-weight: 700;
  margin-bottom: 8px;
  line-height: 1.5;
}

.project-meta {
  font-size: 0.88rem;
  color: #64748b;
  margin-bottom: 12px;
}

.project-description {
  line-height: 1.7;
  margin-bottom: 12px;
}

.project-list {
  margin: 10px 0 12px 0;
  padding-left: 22px;
}

.project-list li {
  margin-bottom: 9px;
  line-height: 1.65;
}

/* ===== Technology Tags ===== */
.project-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 7px;
  margin-top: 15px;
}

.project-tag {
  display: inline-block;
  background: #f1f5f9;
  color: #334155;
  padding: 5px 10px;
  border-radius: 6px;
  font-size: 0.78rem;
  font-weight: 500;
}

/* ===== Responsive ===== */
@media (max-width: 600px) {
  .project-category {
    font-size: 1.2rem;
  }

  .project-title {
    font-size: 1.05rem;
  }

  .project-list {
    padding-left: 19px;
  }
}
</style>

<div class="edu-layout">

  <!-- LEFT: Author Profile -->
  <aside class="author-card">

    <img
      src="{{ '/images/profile.png' | relative_url }}"
      alt="Showmik Singha"
      class="author-avatar"
    >

    <div class="author-name">Showmik Singha</div>

    <div class="author-title">
      Ph.D. Candidate<br>
      Electrical and Computer Engineering<br>
      University of Missouri–Columbia
    </div>

    <div class="author-bio">
      Semiconductor Device Modeling,
      Wide-Bandgap Power Electronics,
      Radiation Effects, and
      Machine Learning.
    </div>

    <div class="author-links">
      <a href="mailto:{{ site.author.email }}">
        <i class="fas fa-envelope"></i> Email
      </a>

      <a href="https://scholar.google.com/" target="_blank" rel="noopener noreferrer">
        <i class="ai ai-google-scholar"></i> Google Scholar
      </a>

      <a href="https://www.linkedin.com/" target="_blank" rel="noopener noreferrer">
        <i class="fab fa-linkedin"></i> LinkedIn
      </a>

      <a href="https://github.com/" target="_blank" rel="noopener noreferrer">
        <i class="fab fa-github"></i> GitHub
      </a>
    </div>

  </aside>

  <!-- RIGHT: Projects -->
  <main class="project-content">

    <h1>Research Projects</h1>

    <p class="project-intro">
      My research focuses on semiconductor device
      modeling, radiation-induced reliability,
      wide- and ultra-wide-bandgap power devices,
      machine learning-assisted device optimization,
      and experimental microfabrication.
      My work combines numerical simulation,
      computational analysis, and experimental
      techniques to advance next-generation
      electronic technologies.
    </p>

    <!-- ===================================== -->
    <!-- RADIATION EFFECTS -->
    <!-- ===================================== -->

    <h2 class="project-category">
      <i class="fas fa-atom"></i>
      Radiation Effects and Device Reliability
    </h2>

    <div class="project-item">

      <h3 class="project-title">
        Single-Event Transient Analysis of
        GaN High Electron Mobility Transistors
      </h3>

      <div class="project-meta">
        University of Missouri–Columbia
      </div>

      <ul class="project-list">
        <li>
          Developed TCAD models of enhancement-mode
          p-GaN/AlGaN/GaN HEMTs to investigate
          radiation-induced single-event transient
          responses.
        </li>

        <li>
          Simulated heavy-ion strikes under normal
          incidence across different drain biases
          and linear energy transfer conditions.
        </li>

        <li>
          Analyzed transient drain currents,
          charge collection, electric-field
          distributions, and dual-peak
          current responses.
        </li>

        <li>
          Evaluated device susceptibility and
          radiation reliability for applications
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

    <div class="project-item">

      <h3 class="project-title">
        Radiation Response of
        β-Ga<sub>2</sub>O<sub>3</sub> MOSFETs
        Under Oblique Heavy-Ion Irradiation
      </h3>

      <div class="project-meta">
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
          Evaluated heavy-ion irradiation at
          different incidence angles, drain
          voltages, and energy deposition levels.
        </li>

        <li>
          Investigated transient current peaks,
          charge collection, recovery behavior,
          and sensitive regions within the device.
        </li>

        <li>
          Identified the influence of particle
          trajectory and device bias on radiation
          sensitivity to support reliability
          assessment and device optimization.
        </li>
      </ul>

      <div class="project-tags">
        <span class="project-tag">β-Ga2O3 MOSFET</span>
        <span class="project-tag">TCAD</span>
        <span class="project-tag">Heavy-Ion Irradiation</span>
        <span class="project-tag">Device Reliability</span>
      </div>

    </div>

    <div class="project-item">

      <h3 class="project-title">
        Temperature-Dependent Single-Event
        Transient Analysis of
        β-Ga<sub>2</sub>O<sub>3</sub> MOSFETs
      </h3>

      <div class="project-meta">
        University of Missouri–Columbia
      </div>

      <ul class="project-list">
        <li>
          Investigated radiation-induced transient
          responses of β-Ga<sub>2</sub>O<sub>3</sub>
          MOSFETs over temperatures ranging
          from 300 K to 500 K.
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
          temperature and radiation on device
          reliability for extreme-environment
          power electronics.
        </li>
      </ul>

      <div class="project-tags">
        <span class="project-tag">β-Ga2O3</span>
        <span class="project-tag">Temperature Analysis</span>
        <span class="project-tag">SET</span>
        <span class="project-tag">Power MOSFET</span>
      </div>

    </div>

    <!-- ===================================== -->
    <!-- DEVICE MODELING -->
    <!-- ===================================== -->

    <h2 class="project-category">
      <i class="fas fa-microchip"></i>
      Semiconductor Device Modeling
    </h2>

    <div class="project-item">

      <h3 class="project-title">
        DC Characterization and Modeling of
        AlN/β-Ga<sub>2</sub>O<sub>3</sub> HEMTs
      </h3>

      <div class="project-meta">
        University of Missouri–Columbia
      </div>

      <ul class="project-list">
        <li>
          Developed numerical models of
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

    <div class="project-item">

      <h3 class="project-title">
        Machine Learning-Enabled Parameter
        Extraction of β-Ga<sub>2</sub>O<sub>3</sub>
        MOSFETs
      </h3>

      <div class="project-meta">
        University of Missouri–Columbia
      </div>

      <ul class="project-list">
        <li>
          Generated a TCAD-based dataset of
          semiconductor device configurations
          and electrical characteristics
          for machine learning applications.
        </li>

        <li>
          Developed inverse modeling techniques
          to predict oxide thickness, channel
          thickness, doping concentration,
          and gate dimensions from current-voltage
          characteristics.
        </li>

        <li>
          Evaluated XGBoost, convolutional
          neural networks, and Transformer-based
          architectures for device parameter
          extraction.
        </li>

        <li>
          Developed a hybrid prediction
          framework to improve parameter
          estimation accuracy and reduce
          iterative device design time.
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

    <div class="project-item">

      <h3 class="project-title">
        Machine Learning-Based Inverse Modeling
        of Semiconductor PIN Diodes
      </h3>

      <div class="project-meta">
        Semiconductor Device Modeling and Data Analysis
      </div>

      <ul class="project-list">
        <li>
          Investigated data-driven parameter
          extraction techniques for semiconductor
          PIN diode structures.
        </li>

        <li>
          Used simulated current-voltage
          characteristics to construct
          datasets for inverse device modeling.
        </li>

        <li>
          Explored Transformer-based learning
          and feature extraction techniques
          to estimate semiconductor doping
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
    <!-- EXPERIMENTAL FABRICATION -->
    <!-- ===================================== -->

    <h2 class="project-category">
      <i class="fas fa-flask"></i>
      Microfabrication and Experimental Research
    </h2>

    <div class="project-item">

      <h3 class="project-title">
        Carbonized Nanostructure Biosensor
        Fabrication Using Two-Photon Polymerization
      </h3>

      <div class="project-meta">
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

