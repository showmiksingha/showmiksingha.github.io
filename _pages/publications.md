---
title: "Publications"
permalink: /publications/
layout: default
author_profile: false
classes: wide
---

<div class="wrap" markdown="1">

<style>
/* =========================================
   PAGE LAYOUT
========================================= */
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

/* =========================================
   LEFT AUTHOR PROFILE
========================================= */
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

/* =========================================
   MAIN PUBLICATION CONTENT
========================================= */
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
  line-height: 1.75;
  margin-bottom: 25px;
}

/* =========================================
   PUBLICATION SUMMARY CARDS
========================================= */
.pub-stats {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 12px;
  margin: 20px 0 32px;
}

.pub-stat {
  border: 1px solid #e5e7eb;
  border-radius: 12px;
  padding: 18px 10px;
  text-align: center;
  background: #fafafa;
  transition:
    transform 0.25s ease,
    box-shadow 0.25s ease,
    border-color 0.25s ease;
}

.pub-stat:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 22px rgba(0,0,0,0.07);
  border-color: #93c5fd;
}

.pub-stat-icon {
  font-size: 1.15rem;
  color: #64748b;
  margin-bottom: 10px;
}

.pub-stat strong {
  display: block;
  font-size: 1.7rem;
  color: #2563eb;
  line-height: 1.2;
  margin-bottom: 6px;
}

.pub-stat span {
  font-size: 0.83rem;
  color: #555;
}

/* =========================================
   APPLE-INSPIRED SCHOLAR BENTO GRID
========================================= */
.apple-scholar {
  margin: 35px 0 45px;
}

.apple-scholar-heading {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 14px;
  margin-bottom: 20px;
}

.apple-scholar-heading h2 {
  font-size: 1.5rem;
  font-weight: 800;
  letter-spacing: -0.5px;
  border: none !important;
  padding: 0 !important;
  margin: 0 0 5px !important;
  color: #111827;
}

.apple-scholar-heading p {
  font-size: 0.9rem;
  color: #64748b;
  margin: 0;
}

.apple-scholar-heading > i {
  font-size: 1.6rem;
  color: #94a3b8;
}

.apple-bento-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 14px;
}

/* Base Bento Tile */
.apple-tile {
  position: relative;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  min-width: 0;
  min-height: 170px;
  padding: 22px;
  border-radius: 20px;
  overflow: hidden;
  box-sizing: border-box;
  transition:
    transform 0.3s ease,
    box-shadow 0.3s ease;
}

.apple-tile:hover {
  transform: translateY(-5px);
  box-shadow: 0 16px 35px rgba(0,0,0,0.09);
}

.apple-tile-top {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 8px;
  font-size: 0.82rem;
  font-weight: 600;
}

.apple-tile-top i {
  font-size: 1.15rem;
}

.apple-tile-bottom strong {
  display: block;
  font-size: clamp(2.5rem, 5vw, 4rem);
  font-weight: 800;
  letter-spacing: -2px;
  line-height: 1.05;
}

.apple-tile-bottom p {
  margin: 9px 0 0;
  font-size: 0.82rem;
  line-height: 1.5;
}

/* Total citations */
.apple-citations {
  grid-column: span 2;
  min-height: 230px;
  background: #eaf1ff;
  color: #111827;
}

.apple-citations .apple-tile-top {
  color: #475569;
}

.apple-citations .apple-tile-top i {
  color: #2563eb;
}

.apple-citations .apple-tile-bottom p {
  color: #64748b;
}

/* h-index */
.apple-hindex {
  background: #f1f5f9;
  color: #111827;
  min-height: 230px;
}

.apple-hindex .apple-tile-top {
  color: #64748b;
}

.apple-hindex .apple-tile-bottom p {
  color: #64748b;
}

/* i10-index */
.apple-i10 {
  background: #f1f5f9;
  color: #111827;
}

.apple-i10 .apple-tile-top {
  color: #64748b;
}

.apple-i10 .apple-tile-bottom p {
  color: #64748b;
}

/* Citations since 2021 */
.apple-recent {
  grid-column: span 2;
  background: #17253d;
  color: #fff;
}

.apple-recent .apple-tile-top {
  color: #cbd5e1;
}

.apple-recent .apple-tile-top i {
  color: #93c5fd;
}

.apple-recent .apple-tile-bottom p {
  color: #cbd5e1;
}

/* Google Scholar profile tile */
.apple-scholar-link {
  grid-column: span 3;
  min-height: 95px;
  padding: 19px 22px;
  background: #f8fafc;
  border: 1px solid #e5e7eb;
  text-decoration: none !important;
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 15px;
}

.apple-scholar-link:hover {
  border-color: #bfdbfe;
  text-decoration: none !important;
}

.apple-link-icon {
  width: 48px;
  height: 48px;
  flex-shrink: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 13px;
  background: #eaf1ff;
  color: #2563eb;
  font-size: 1.25rem;
}

.apple-link-text {
  flex: 1;
  min-width: 0;
  display: flex;
  flex-direction: column;
  gap: 5px;
}

.apple-link-text strong {
  font-size: 1rem;
  color: #111827;
}

.apple-link-text span {
  font-size: 0.8rem;
  color: #64748b;
}

.apple-scholar-link > i {
  color: #64748b;
  font-size: 1rem;
}

.apple-scholar-note {
  font-size: 0.75rem;
  color: #94a3b8;
  margin: 15px 0 0;
  line-height: 1.6;
}

/* =========================================
   PUBLICATION SECTIONS
========================================= */
.pub-content h2.pub-section-title {
  font-size: 1.35rem;
  margin: 38px 0 18px;
  padding-bottom: 10px;
  border-bottom: 1px solid #e5e7eb;
}

.pub-section-title i {
  color: #2563eb;
  margin-right: 8px;
}

/* =========================================
   PUBLICATION LISTS
========================================= */
.publication-list {
  list-style-type: decimal;
  padding-left: 28px;
  margin: 0;
}

.publication-list li {
  padding-left: 6px;
  margin-bottom: 20px;
  font-size: 0.94rem;
  line-height: 1.8;
  overflow-wrap: anywhere;
  transition: color 0.2s ease;
}

.publication-list li::marker {
  color: #64748b;
  font-weight: 600;
}

.publication-list li:hover {
  color: #1d4ed8;
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
  padding: 3px 9px;
  border-radius: 6px;
  margin-left: 5px;
}

/* =========================================
   RESPONSIVE DESIGN
========================================= */
@media (max-width: 650px) {

  .pub-content h1 {
    font-size: 1.7rem;
  }

  .pub-stats {
    gap: 7px;
  }

  .pub-stat {
    padding: 13px 5px;
  }

  .pub-stat strong {
    font-size: 1.4rem;
  }

  .pub-stat span {
    font-size: 0.72rem;
  }

  .pub-stat-icon {
    font-size: 0.95rem;
  }

  .apple-bento-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 10px;
  }

  .apple-citations {
    grid-column: span 2;
    min-height: 180px;
  }

  .apple-hindex,
  .apple-i10 {
    grid-column: span 1;
    min-height: 150px;
  }

  .apple-recent {
    grid-column: span 2;
    min-height: 170px;
  }

  .apple-scholar-link {
    grid-column: span 2;
    padding: 15px;
  }

  .apple-tile {
    padding: 17px;
    border-radius: 16px;
  }

  .apple-tile-bottom strong {
    font-size: 2.7rem;
  }

  .publication-list li {
    font-size: 0.9rem;
  }
}

@media (prefers-reduced-motion: reduce) {
  .apple-tile,
  .pub-stat,
  .publication-list li {
    transition: none;
  }

  .apple-tile:hover,
  .pub-stat:hover {
    transform: none;
  }
}
</style>

<div class="edu-layout">

<!-- =========================================
     LEFT: AUTHOR PROFILE
========================================= -->

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
         target="_blank"
         rel="noopener">
        <i class="fab fa-fw fa-github"></i>
        <span>GitHub</span>
      </a>
    </li>

    <li>
      <a href="https://www.linkedin.com/in/showmik-singha-293967147"
         target="_blank"
         rel="noopener">
        <i class="fab fa-fw fa-linkedin"></i>
        <span>LinkedIn</span>
      </a>
    </li>

  </ul>

</aside>

<!-- =========================================
     RIGHT: PUBLICATIONS
========================================= -->

<main class="pub-content">

<h1>Publications</h1>



<!-- =========================================
     PUBLICATION SUMMARY
========================================= -->

<div class="pub-stats">

  <div class="pub-stat">
    <div class="pub-stat-icon">
      <i class="fas fa-book-open"></i>
    </div>
    <strong>4</strong>
    <span>Journal Articles</span>
  </div>

  <div class="pub-stat">
    <div class="pub-stat-icon">
      <i class="fas fa-microphone-alt"></i>
    </div>
    <strong>1</strong>
    <span>Invited Paper</span>
  </div>

  <div class="pub-stat">
    <div class="pub-stat-icon">
      <i class="fas fa-users"></i>
    </div>
    <strong>21</strong>
    <span>Conference Papers</span>
  </div>

</div>

<!-- =========================================
     APPLE-INSPIRED RESEARCH IMPACT GRID
========================================= -->

<section class="apple-scholar">

  <div class="apple-scholar-heading">

    <div>
      <h2>Research Impact</h2>
     
    </div>

    <i class="fas fa-graduation-cap"></i>

  </div>

  <div class="apple-bento-grid">

    <!-- Total Citations -->
    <div class="apple-tile apple-citations">

      <div class="apple-tile-top">
        <span>Total Citations</span>
        <i class="fas fa-quote-right"></i>
      </div>

      <div class="apple-tile-bottom">
        <strong>87</strong>
        <p>Lifetime Google Scholar citations</p>
      </div>

    </div>

    <!-- h-index -->
    <div class="apple-tile apple-hindex">

      <div class="apple-tile-top">
        <i class="fas fa-chart-line"></i>
      </div>

      <div class="apple-tile-bottom">
        <strong>5</strong>
        <p>h-index</p>
      </div>

    </div>

    <!-- i10-index -->
    <div class="apple-tile apple-i10">

      <div class="apple-tile-top">
        <i class="fas fa-book-open"></i>
      </div>

      <div class="apple-tile-bottom">
        <strong>3</strong>
        <p>i10-index</p>
      </div>

    </div>

    <!-- Citations since 2021 -->
    <div class="apple-tile apple-recent">

      <div class="apple-tile-top">
        <span>Citations Since 2021</span>
        <i class="fas fa-chart-line"></i>
      </div>

      <div class="apple-tile-bottom">
        <strong>85</strong>
        <p>Of 87 lifetime citations</p>
      </div>

    </div>

    <!-- Google Scholar Profile -->
    <a
      class="apple-tile apple-scholar-link"
      href="https://scholar.google.com/citations?user=B0llklQAAAAJ"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Open Google Scholar profile"
    >

      <div class="apple-link-icon">
        <i class="fas fa-graduation-cap"></i>
      </div>

      <div class="apple-link-text">
        <strong>Google Scholar</strong>
        <span>View publications and citation metrics</span>
      </div>

      <i class="fas fa-external-link-alt"></i>

    </a>

  </div>



</section>

<!-- =========================================
     JOURNAL PUBLICATIONS
========================================= -->

<h2 class="pub-section-title">
  <i class="fas fa-book-open"></i>
  Journals
</h2>

<ol class="publication-list">

  <li>
    <strong>S. Singha</strong>, M. M. Hossain, and S. K. Islam,
    "Numerical Analysis of Single Event Transient Effects in
    Enhancement-Mode p-GaN/AlGaN/GaN High Electron Mobility Transistors,"
    <em>International Journal of High Speed Electronics and Systems</em>,
    vol. 35, no. 01, 2640009,
    <span class="pub-year">2025</span>.
  </li>

  <li>
    M. M. Hossain, <strong>S. Singha</strong>, T. Titirsha,
    and S. K. Islam,
    "Optimizing TCAD Model and Temperature-Dependent Analysis of
    Pt/AlN Schottky Barrier Diodes for High-Power and High-Temperature
    Applications,"
    <em>International Journal of High Speed Electronics and Systems</em>,
    vol. 33, no. 02n03, 2440065,
    <span class="pub-year">2024</span>.
  </li>

  <li>
    J. Debnath, M. E. H. Sikder, and <strong>S. Singha</strong>,
    "Comparative Analysis of Gate-Oxide Engineering in Charge Plasma
    Based Nanowire Transistor,"
    <em>Engineering Research Express</em>,
    vol. 5, 035028,
    <span class="pub-year">2023</span>.
  </li>

  <li>
    M. F. Rahman, M. M. Ahmad, T. A. Chowdhury,
    and <strong>S. Singha</strong>,
    "Performance Improvement of Three Terminal Heterojunction Bipolar
    Transistor Based Hybrid Solar Cell Using Nano-Rods,"
    <em>Solar Energy</em>,
    vol. 240, pp. 1–12,
    <span class="pub-year">2022</span>.
  </li>

</ol>

<!-- =========================================
     INVITED PAPER
========================================= -->

<h2 class="pub-section-title">
  <i class="fas fa-microphone-alt"></i>
  Invited Paper
</h2>

<ol class="publication-list">

  <li>
    <strong>S. Singha</strong>, M. M. Hossain, and S. K. Islam,
    "Simulation Analysis of Single Event Transient Effects in
    Enhancement-Mode p-GaN-AlGaN/GaN High Electron Mobility Transistor,"
    <em>33rd Connecticut Symposium on Microelectronics
    and Optoelectronics</em>,
    <span class="pub-year">2025</span>.
    <span class="pub-tag">Invited Paper</span>
  </li>

</ol>

<!-- =========================================
     CONFERENCE PUBLICATIONS
========================================= -->

<h2 class="pub-section-title">
  <i class="fas fa-users"></i>
  Conferences
</h2>

<ol class="publication-list">

  <li>
    <strong>S. Singha</strong>, M. H. Rayhan, T. P. H. Nguyen,
    M. Y. Rahman, M. M. Hossain, and S. K. Islam,
    "Machine Learning Enabled Parameter Extraction of
    β-Ga<sub>2</sub>O<sub>3</sub> MOSFETs,"
    <em>84th Device Research Conference (DRC) (Presented)</em>,
    <span class="pub-year">2026</span>.
  </li>

  <li>
    M. Y. Rahman, <strong>S. Singha</strong>, and S. K. Islam,
    "A 1 MHz GaN-Based Transformerless Resonant Superimposed
    Quadratic Converter for 48 V-to-Point of Load High-Current
    AI Power Delivery,"
    <em>34th Connecticut Symposium on Microelectronics
    and Optoelectronics</em>,
    <span class="pub-year">2026</span>.
  </li>

  <li>
    T. P. H. Nguyen, <strong>S. Singha</strong>, and S. K. Islam,
    "Channel Length and Temperature Dependence of
    HfO<sub>2</sub>/SiO<sub>2</sub> Gate-All-Around Silicon
    Nanowire Field-Effect Transistor-Based Biosensor for Rapid
    Point-of-Care SARS-CoV-2 Detection,"
    <em>34th Connecticut Symposium on Microelectronics
    and Optoelectronics</em>,
    <span class="pub-year">2026</span>.
  </li>

  <li>
    G. Taylor, M. Y. Rahman, M. M. Hossain,
    <strong>S. Singha</strong>, and S. K. Islam,
    "PDK-Accurate MOSFET Width Optimization for Efficient Integrated
    DC-DC Converters Using Spectre-MATLAB Co-Simulation,"
    <em>19th IEEE Dallas Circuits and Systems Conference</em>,
    <span class="pub-year">2026</span>.
  </li>

  <li>
    T. P. H. Nguyen, <strong>S. Singha</strong>, and S. K. Islam,
    "Low-Power GS-GAA-JL-SiNW FET-Based Biosensor for Rapid
    Point-of-Care Viral Detection,"
    <em>56th IEEE Semiconductor Interface Specialists
    Conference (SISC)</em>,
    San Diego, CA,
    <span class="pub-year">2025</span>.
  </li>

  <li>
    <strong>S. Singha</strong>, M. M. Hossain, and S. K. Islam,
    "Modeling Single-Event Transient Responses in
    Ga<sub>2</sub>O<sub>3</sub> MOSFETs Under Oblique
    Particle Irradiation,"
    <em>2025 IEEE 12th Workshop on Wide Bandgap Power Devices
    and Applications (WiPDA)</em>,
    pp. 1–5,
    <span class="pub-year">2025</span>.
  </li>

  <li>
    M. M. Hossain, <strong>S. Singha</strong>,
    S. A. Eliza, and S. K. Islam,
    "Simulation and Performance Evaluation of
    AlN/β-Ga<sub>2</sub>O<sub>3</sub> HEMTs for
    Next-Generation Ultrawide Bandgap Power Devices,"
    <em>8th U.S. Workshop on Gallium Oxide</em>,
    <span class="pub-year">2025</span>.
  </li>

  <li>
    T. Titirsha, <strong>S. Singha</strong>,
    M. M. Hossain, S. A. Eliza, and S. K. Islam,
    "A Surface Potential Based Analytical C-V Model of a Double-Gate
    Vertical Fin-Shaped Ga<sub>2</sub>O<sub>3</sub>
    Power Transistor,"
    <em>8th U.S. Workshop on Gallium Oxide</em>,
    <span class="pub-year">2025</span>.
  </li>

  <li>
    M. M. Hossain, <strong>S. Singha</strong>,
    S. A. Eliza, and S. K. Islam,
    "Numerical Modeling and DC Performance Analysis of
    AlN/β-Ga<sub>2</sub>O<sub>3</sub> HEMTs for
    High-Power and High-Speed Switching Applications,"
    <em>33rd Connecticut Symposium on Microelectronics
    and Optoelectronics</em>,
    <span class="pub-year">2025</span>.
  </li>

  <li>
    Z. Bari, G. Taylor, A. I. Shimul, M. M. Hossain,
    <strong>S. Singha</strong>, and S. Eliza,
    "Exploring the Impact of Various Organic and Inorganic Electron
    Transport Layers in Highly Stable Perovskite Solar Cells,"
    <em>17th IEEE Green Technologies Conference</em>,
    <span class="pub-year">2025</span>.
  </li>

  <li>
    G. Taylor, M. M. Hossain, <strong>S. Singha</strong>,
    A. I. Shimul, S. A. Dipa, and S. Eliza,
    "Performance Optimization and Bandgap Tuning of Perovskite
    Solar Cells Via Titanium Alloying for High-Efficiency
    Photovoltaic Systems,"
    <em>17th IEEE Green Technologies Conference</em>,
    <span class="pub-year">2025</span>.
  </li>

  <li>
    M. M. Hossain, <strong>S. Singha</strong>,
    T. Titirsha, S. A. Eliza, and S. K. Islam,
    "Optimizing TCAD Model for Aluminum Nitride (AlN) Schottky
    Diode: Exploring Forward Diode Characteristics with Different
    Schottky Metals,"
    <em>32nd Connecticut Symposium on Microelectronics
    and Optoelectronics</em>,
    <span class="pub-year">2024</span>.
  </li>

  <li>
    M. R. Haider, A. Farr, <strong>S. Singha</strong>,
    and S. K. Islam,
    "An Energy-Efficient Analog-to-Pulse Encoding for Short-Range
    High-Density Wireless Telemetry,"
    <em>2024 IEEE 67th International Midwest Symposium
    on Circuits and Systems (MWSCAS)</em>,
    pp. 198–202,
    <span class="pub-year">2024</span>.
  </li>

  <li>
    T. Titirsha, M. M. H. Shuvo, M. M. Hossain,
    <strong>S. Singha</strong>, S. A. Eliza, and S. K. Islam,
    "Analytical Current-Voltage (I-V) Modeling of Double-Gate
    Vertical Fin-Shaped Ga<sub>2</sub>O<sub>3</sub>
    Power Transistors,"
    <em>7th U.S. Workshop on Gallium Oxide</em>,
    <span class="pub-year">2024</span>.
  </li>

  <li>
    J. Debnath, M. Anjum, M. H. Akhyear,
    and <strong>S. Singha</strong>,
    "DC and RF Performance Analysis of Junctionless Gate All Around
    Nanosheet MOSFET,"
    <em>2023 IEEE 9th International Women in Engineering
    Conference on Electrical and Computer Engineering</em>,
    <span class="pub-year">2023</span>.
  </li>

  <li>
    N. Hosen, A. Rahman, <strong>S. Singha</strong>,
    and T. A. Chowdhury,
    "A Comparative Analysis of Two Dielectric Nanostructures to
    Enhance Efficiency of Perovskite Solar Cells,"
    <em>2022 International Conference on Advancement
    in Electrical and Electronic Engineering</em>,
    <span class="pub-year">2022</span>.
  </li>

  <li>
    F. Ahmed, R. Paul, M. M. Ahmad, A. Ahammad,
    and <strong>S. Singha</strong>,
    "Design and Development of a Smart Wheelchair for the Disabled
    People,"
    <em>2021 International Conference on Information
    and Communication Technology for Sustainable Development</em>,
    <span class="pub-year">2021</span>.
  </li>

  <li>
    S. Hussain, N. Mustakim, <strong>S. Singha</strong>,
    and J. K. Saha,
    "A Comprehensive Study on Tunneling Field Effect Transistor
    Using Non-local Band-to-Band Tunneling Model,"
    <em>Journal of Physics: Conference Series</em>,
    vol. 1432, 012028,
    <span class="pub-year">2020</span>.
  </li>

  <li>
    R. Saha, R. Uddin Ahmed, P. Das,
    <strong>S. Singha</strong>, and M. M. Rahman Adnan,
    "Effect of High-K Dielectrics in Different Doping Concentrations
    in a Junctionless GAA Nanowire Transistor Structure,"
    <em>2019 2nd International Conference on Innovation
    in Engineering and Technology</em>,
    <span class="pub-year">2019</span>.
  </li>

  <li>
    M. M. Islam, M. F. Islam, and <strong>S. Singha</strong>,
    "Design and Implementation of Raspberry Pi Based Real Time
    Industrial Energy Analyzer,"
    <em>2019 International Conference on Electrical,
    Computer and Communication Engineering</em>,
    <span class="pub-year">2019</span>.
  </li>

  <li>
    M. M. Islam, <strong>S. Singha</strong>,
    M. M. R. Adnan, and T. Dev,
    "Design and Characterization of Two Different Structure of
    Junctionless Nanowire Transistor Considering Quantum Ballistic
    Transport Model,"
    <em>2018 International Conference on Advancement
    in Electrical and Electronic Engineering</em>,
    <span class="pub-year">2018</span>.
  </li>

</ol>

</main>

</div> <!-- /.edu-layout -->

</div> <!-- /.wrap -->
