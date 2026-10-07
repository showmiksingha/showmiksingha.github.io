---
title: "Skills"
permalink: /skills/
layout: default
author_profile: false
classes: wide
---

<div class="wrap" markdown="1">

<style>
/* ===== Layout ===== */
.page-grid{
  display:grid;
  grid-template-columns:260px 1fr;
  gap:28px;
  align-items:start;
}

@media(max-width:900px){
  .page-grid{
    grid-template-columns:1fr;
  }
}

/* ===== Author Card ===== */
.author-card{
  position:sticky;
  top:90px;
  border:1px solid #e5e7eb;
  border-radius:14px;
  padding:16px;
  background:#fff;
}

@media(max-width:900px){
  .author-card{
    position:static;
  }
}

.author-avatar{
  width:110px;
  height:110px;
  border-radius:999px;
  object-fit:cover;
  display:block;
  margin:0 auto 10px;
}

.author-name{
  text-align:center;
  font-weight:800;
  margin:0;
}

.author-bio{
  text-align:center;
  color:#6b7280;
  margin:6px 0 12px;
  font-size:.95rem;
}

.author-links{
  list-style:none;
  padding:0;
  margin:0;
}

.author-links li{
  margin:8px 0;
}

.author-links a{
  display:inline-flex;
  gap:8px;
  align-items:center;
  text-decoration:none;
}

/* ===== Skills ===== */
.skills-intro{
  margin-bottom:28px;
  color:#4b5563;
  line-height:1.65;
  font-size:1rem;
}

.skill-category{
  margin-bottom:32px;
}

.skill-category h2{
  font-size:1.35rem;
  font-weight:800;
  margin:0 0 14px;
  padding-bottom:8px;
  border-bottom:2px solid #e5e7eb;
}

.skill-card{
  padding:15px 0;
  border-bottom:1px solid #f1f5f9;
}

.skill-card:last-child{
  border-bottom:none;
}

.skill-title{
  font-weight:700;
  font-size:1.02rem;
  margin:0 0 5px;
}

.skill-desc{
  margin:0;
  color:#6b7280;
  line-height:1.55;
}
</style>


<div class="page-grid">

<!-- ========================= -->
<!-- LEFT: AUTHOR PROFILE      -->
<!-- ========================= -->

<aside class="author-card">

  <img class="author-avatar"
       src="/assets/images/profile.JPG"
       alt="Showmik Singha">

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
         target="_blank"
         rel="noopener">
        <i class="fab fa-fw fa-github"></i>
        <span>GitHub</span>
      </a>
    </li>

    <li>
      <a href="https://www.linkedin.com/in/showmiksingha/"
         target="_blank"
         rel="noopener">
        <i class="fab fa-fw fa-linkedin"></i>
        <span>LinkedIn</span>
      </a>
    </li>

  </ul>

</aside>


<!-- ========================= -->
<!-- RIGHT: SKILLS             -->
<!-- ========================= -->

<main>




<!-- Semiconductor Device Modeling -->

<section class="skill-category">

<h2>Semiconductor Device Modeling & TCAD</h2>

<div class="skill-card">
  <p class="skill-title">Silvaco TCAD</p>
  <p class="skill-desc">
    Physics-based semiconductor device modeling, electrical characterization,
    transient simulation, radiation-effect analysis, parametric studies,
    and extraction of device characteristics from simulated I–V responses.
  </p>
</div>

<div class="skill-card">
  <p class="skill-title">Sentaurus TCAD</p>
  <p class="skill-desc">
    Semiconductor device simulation and physics-based modeling of
    wide-bandgap and ultra-wide-bandgap electronic devices.
  </p>
</div>

<div class="skill-card">
  <p class="skill-title">SPICE & Compact Modeling</p>
  <p class="skill-desc">
    Device-model parameter extraction, SPICE model development,
    simulation-based validation, and integration of semiconductor
    device behavior into circuit-level analysis.
  </p>
</div>

</section>


<!-- IC Design -->

<section class="skill-category">

<h2>Analog & Mixed-Signal IC Design</h2>

<div class="skill-card">
  <p class="skill-title">Cadence Virtuoso / Spectre / ADE</p>
  <p class="skill-desc">
    Analog and mixed-signal IC design including schematic capture,
    circuit simulation, DC/AC/transient analysis, layout, and DRC/LVS.
  </p>
</div>

<div class="skill-card">
  <p class="skill-title">LTspice</p>
  <p class="skill-desc">
    Analog and power circuit simulation, transient and frequency-domain analysis,
  
  </p>
</div>

</section>


<!-- Power Electronics -->

<section class="skill-category">

<h2>Power Electronics & Circuit Simulation</h2>



<div class="skill-card">
  <p class="skill-title">Power Semiconductor Devices</p>
  <p class="skill-desc">
    Modeling and analysis of GaN HEMTs, β-Ga₂O₃ MOSFETs,
    Schottky diodes, and other wide-bandgap and ultra-wide-bandgap
    semiconductor devices for power electronic applications.
  </p>
</div>

</section>


<!-- PCB -->

<section class="skill-category">

<h2>PCB Design & Hardware Development</h2>

<div class="skill-card">
  <p class="skill-title">Altium Designer</p>
  <p class="skill-desc">
    Multilayer PCB schematic and layout design, custom footprints,
    design-rule configuration, EMI-aware routing, and generation
    of manufacturing-ready fabrication files.
  </p>
</div>

<div class="skill-card">
  <p class="skill-title">KiCad</p>
  <p class="skill-desc">
    Multilayer PCB design including schematic capture, custom symbol
    and footprint library development, high-voltage design considerations,
    board layout, and fabrication output generation.
  </p>
</div>

</section>


<!-- Programming -->

<section class="skill-category">

<h2>Programming, Data Analysis & Automation</h2>

<div class="skill-card">
  <p class="skill-title">MATLAB</p>
  <p class="skill-desc">
    Numerical analysis, scientific computing, automated data processing,
    optimization and parameter sweeps, simulation post-processing,
    data visualization, and engineering analysis.
  </p>
</div>

<div class="skill-card">
  <p class="skill-title">Python</p>
  <p class="skill-desc">
    Scientific computing, data processing, simulation-output parsing,
    workflow automation, machine-learning model development,
    visualization, and research tooling.
  </p>
</div>

<div class="skill-card">
  <p class="skill-title">C Programming</p>
  <p class="skill-desc">
    Procedural programming, algorithm implementation,
    numerical problem solving, and embedded-oriented programming.
  </p>
</div>

</section>


<!-- Machine Learning -->

<section class="skill-category">

<h2>Machine Learning & Data-Driven Modeling</h2>

<div class="skill-card">
  <p class="skill-title">Machine Learning for Semiconductor Devices</p>
  <p class="skill-desc">
    Data-driven semiconductor parameter extraction and inverse modeling
    using electrical I–V characteristics, with applications to device
    characterization and design optimization.
  </p>
</div>

<div class="skill-card">
  <p class="skill-title">ML Methods</p>
  <p class="skill-desc">
    Experience with XGBoost, 1D convolutional neural networks (CNNs),
    Transformer-based models, regression analysis, feature engineering,
    model evaluation, and hyperparameter optimization.
  </p>
</div>

</section>


<!-- Computational Materials -->

<section class="skill-category">

<h2>Computational Materials & Optical Simulation</h2>

<div class="skill-card">
  <p class="skill-title">Quantum ESPRESSO</p>
  <p class="skill-desc">
    Density functional theory (DFT) calculations, electronic band-structure
    analysis, density-of-states analysis, and convergence studies.
  </p>
</div>

<div class="skill-card">
  <p class="skill-title">ANSYS Lumerical FDTD</p>
  <p class="skill-desc">
    Optical and photovoltaic device simulation, electromagnetic field
    analysis, and optoelectronic modeling.
  </p>
</div>

</section>


<!-- FPGA -->

<section class="skill-category">

<h2>Digital Design & FPGA</h2>

<div class="skill-card">
  <p class="skill-title">Intel Quartus Prime / Verilog</p>
  <p class="skill-desc">
    RTL design, Verilog implementation, finite-state-machine development,
    functional simulation, FPGA synthesis, and timing analysis.
  </p>
</div>

</section>


<!-- Experimental -->

<section class="skill-category">

<h2>Experimental & Laboratory Skills</h2>

<div class="skill-card">
  <p class="skill-title">Electrical Characterization</p>
  <p class="skill-desc">
    Semiconductor and circuit characterization using laboratory
    instrumentation, measurement setup development, waveform analysis,
    experimental troubleshooting, and data interpretation.
  </p>
</div>

<div class="skill-card">
  <p class="skill-title">Oscilloscope & Signal Generation</p>
  <p class="skill-desc">
    Signal probing, waveform characterization, transient measurements,
    frequency and timing analysis, function-generator configuration,
    and circuit debugging.
  </p>
</div>

<div class="skill-card">
  <p class="skill-title">High-Power DC Test Equipment</p>
  <p class="skill-desc">
    Operation of Magna-Power programmable DC supplies and MagnaLOAD
    electronic loads for high-voltage and high-power device and
    circuit characterization.
  </p>
</div>

</section>


</main>

</div>
</div>
