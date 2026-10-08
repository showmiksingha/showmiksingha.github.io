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
        <a href="https://github.com/showmiksingha"
           target="_blank" rel="noopener">
          <i class="fab fa-fw fa-github"></i>
          <span>GitHub</span>
        </a>
      </li>

      <li>
        <a href="https://www.linkedin.com/in/showmik-singha-293967147"
           target="_blank" rel="noopener">
          <i class="fab fa-fw fa-linkedin"></i>
          <span>LinkedIn</span>
        </a>
      </li>

    </ul>
  </aside>


  <!-- RIGHT: Projects -->
  <main class="project-content">

    <h1>Research Projects</h1>



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

