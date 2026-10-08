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
   PUBLICATION CONTENT
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
  margin-bottom: 25px;
  line-height: 1.75;
}

/* =========================================
   PUBLICATION STATISTICS
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
  transition: transform 0.25s ease,
              box-shadow 0.25s ease,
              border-color 0.25s ease;
}

.pub-stat:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 22px rgba(0,0,0,0.07);
  border-color: #93c5fd;
}

.pub-stat strong {
  display: block;
  font-size: 1.7rem;
  color: #2563eb;
}

.pub-stat span {
  font-size: 0.83rem;
  color: #555;
}

/* =========================================
   CITATION IMPACT INFOGRAPHIC
========================================= */
.citation-impact {
  margin: 28px 0 40px;
  padding: 24px;
  border: 1px solid #e5e7eb;
  border-radius: 14px;
  background: #fff;
}

.citation-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  gap: 12px;
  margin-bottom: 22px;
}

.citation-header h2 {
  margin: 0 !important;
  padding: 0 !important;
  border: none !important;
  font-size: 1.3rem;
}

.citation-header h2 i {
  color: #2563eb;
  margin-right: 7px;
}

.citation-source {
  display: inline-block;
  font-size: 0.75rem;
  font-weight: 600;
  color: #1d4ed8;
  background: #eff6ff;
  padding: 6px 12px;
  border-radius: 20px;
}

/* Citation table */
.citation-table {
  width: 100%;
  border-collapse: collapse;
  margin-bottom: 34px;
  font-size: 0.95rem;
}

.citation-table thead {
  border-bottom: 1px solid #e5e7eb;
}

.citation-table th,
.citation-table td {
  padding: 11px 8px;
  border: none;
  background: transparent;
}

.citation-table th {
  font-weight: 600;
  color: #64748b;
  text-align: center;
}

.citation-table td:first-child {
  font-weight: 500;
  color: #374151;
}

.citation-table td:not(:first-child) {
  text-align: center;
  font-weight: 600;
  color: #111827;
}

/* Citation chart */
.citation-chart-title {
  font-size: 0.94rem;
  font-weight: 600;
  color: #374151;
  margin-bottom: 16px;
}

.citation-chart {
  display: flex;
  height: 230px;
  gap: 14px;
  margin-bottom: 16px;
}

.citation-plot {
  position: relative;
  display: flex;
  justify-content: space-around;
  align-items: flex-end;
  flex: 1;
  min-width: 0;
  height: 200px;
  border-bottom: 1px solid #cbd5e1;
  background-image:
    linear-gradient(to bottom,
      #e5e7eb 0,
      #e5e7eb 1px,
      transparent 1px),
    linear-gradient(to bottom,
      transparent calc(50% - 1px),
      #e5e7eb 50%,
      transparent calc(50% + 1px));
}

.citation-bar-group {
  width: 12%;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: flex-end;
  flex-direction: column;
  position: relative;
}

.citation-bar {
  width: 60%;
  max-width: 38px;
  min-height: 2px;
  background: #64748b;
  border-radius: 4px 4px 0 0;
  position: relative;
  transform-origin: bottom;
  transition: background 0.25s ease,
              transform 0.25s ease;
  cursor: pointer;
}

.citation-bar:hover {
  background: #2563eb;
  transform: scaleX(1.15);
}

.citation-tooltip {
  position: absolute;
  bottom: calc(100% + 8px);
  left: 50%;
  transform: translateX(-50%);
  background: #111827;
  color: #fff;
  padding: 6px 9px;
  border-radius: 6px;
  font-size: 0.75rem;
  white-space: nowrap;
  opacity: 0;
  visibility: hidden;
  transition: opacity 0.2s ease;
  z-index: 3;
  pointer-events: none;
}

.citation-bar:hover .citation-tooltip,
.citation-bar:focus .citation-tooltip {
  opacity: 1;
  visibility: visible;
}

.citation-year {
  position: absolute;
  top: calc(100% + 8px);
  font-size: 0.75rem;
  color: #64748b;
}

.citation-axis {
  height: 200px;
  min-width: 24px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-end;
  font-size: 0.75rem;
  color: #64748b;
}

.citation-footnote {
  font-size: 0.76rem;
  color: #94a3b8;
  margin: 14px 0 0;
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
  padding: 3px 9px;
  border-radius: 6px;
  margin-left: 5px;
}

/* Subtle hover effect */
.publication-list li {
  transition: color 0.2s ease;
}

.publication-list li:hover {
  color: #1d4ed8;
}

/* =========================================
   MOBILE RESPONSIVENESS
========================================= */
@media (max-width: 600px) {
  .pub-content h1 {
    font-size: 1.7rem;
  }

  .pub-stats {
    gap: 7px;
  }

  .pub-stat {
    padding: 12px 5px;
  }

  .pub-stat strong {
    font-size: 1.35rem;
  }

  .pub-stat span {
    font-size: 0.72rem;
  }

  .citation-impact {
    padding: 16px 10px;
  }

  .citation-chart {
    gap: 6px;
  }

  .citation-year {
    font-size: 0.63rem;
  }

  .citation-table {
    font-size: 0.85rem;
  }

  .publication-list li {
    font-size: 0.9rem;
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

<!-- =========================================
     RIGHT: PUBLICATIONS
========================================= -->

<main class="pub-content">

<h1>Publications</h1>

<p class="pub-intro">
  Peer-reviewed journal articles, invited papers,
  and conference publications in semiconductor devices,
  wide and ultrawide bandgap materials, power electronics,
  device modeling, radiation effects, and emerging technologies.
</p>

<!-- =========================================
     PUBLICATION STATISTICS
========================================= -->

<div class="pub-stats">

  <div class="pub-stat">
    <strong>4</strong>
    <span>Journal Articles</span>
  </div>

  <div class="pub-stat">
    <strong>1</strong>
    <span>Invited Paper</span>
  </div>

  <div class="pub-stat">
    <strong>21</strong>
    <span>Conference Papers</span>
  </div>

</div>

<!-- =========================================
     GOOGLE SCHOLAR CITATION IMPACT
========================================= -->

<section class="citation-impact">

  <div class="citation-header">

    <h2>
      <i class="fas fa-chart-bar"></i>
      Citation Impact
    </h2>

    <span class="citation-source">
      Google Scholar
    </span>

  </div>

  <!-- Citation Metrics -->
  <table class="citation-table">

    <thead>
      <tr>
        <th></th>
        <th>All</th>
        <th>Since 2021</th>
      </tr>
    </thead>

    <tbody>

      <tr>
        <td>Citations</td>
        <td>87</td>
        <td>85</td>
      </tr>

      <tr>
        <td>h-index</td>
        <td>5</td>
        <td>5</td>
      </tr>

      <tr>
        <td>i10-index</td>
        <td>3</td>
        <td>3</td>
      </tr>

    </tbody>

  </table>

  <div class="citation-chart-title">
    Citations per Year
  </div>

  <div class="citation-chart"
       role="img"
       aria-label="Annual citation bar chart from 2020 to 2026.
       Yearly citation counts are approximate.">

    <div class="citation-plot">

      <!-- 2020 -->
      <div class="citation-bar-group">
        <div class="citation-bar"
             style="height:6.67%"
             tabindex="0">
          <span class="citation-tooltip">
            2 citations
          </span>
        </div>
        <span class="citation-year">2020</span>
      </div>

      <!-- 2021 -->
      <div class="citation-bar-group">
        <div class="citation-bar"
             style="height:13.33%"
             tabindex="0">
          <span class="citation-tooltip">
            4 citations
          </span>
        </div>
        <span class="citation-year">2021</span>
      </div>

      <!-- 2022 -->
      <div class="citation-bar-group">
        <div class="citation-bar"
             style="height:16.67%"
             tabindex="0">
          <span class="citation-tooltip">
            5 citations
          </span>
        </div>
        <span class="citation-year">2022</span>
      </div>

      <!-- 2023 -->
      <div class="citation-bar-group">
        <div class="citation-bar"
             style="height:53.33%"
             tabindex="0">
          <span class="citation-tooltip">
            16 citations
          </span>
        </div>
        <span class="citation-year">2023</span>
      </div>

      <!-- 2024 -->
      <div class="citation-bar-group">
        <div class="citation-bar"
             style="height:56.67%"
             tabindex="0">
          <span class="citation-tooltip">
            17 citations
          </span>
        </div>
        <span class="citation-year">2024</span>
      </div>

      <!-- 2025 -->
      <div class="citation-bar-group">
        <div class="citation-bar"
             style="height:100%"
             tabindex="0">
          <span class="citation-tooltip">
            30 citations
          </span>
        </div>
        <span class="citation-year">2025</span>
      </div>

      <!-- 2026 -->
      <div class="citation-bar-group">
        <div class="citation-bar"
             style="height:43.33%"
             tabindex="0">
          <span class="citation-tooltip">
            13 citations
          </span>
        </div>
        <span class="citation-year">2026</span>
      </div>

    </div>

    <!-- Chart Axis -->
    <div class="citation-axis">
      <span>30</span>
      <span>15</span>
      <span>0</span>
    </div>

  </div>

  <p class="citation-footnote">
    Source: Google Scholar. Metrics reflect the provided
    citation snapshot. Annual counts are approximate.
  </p>

</section>

<!-- =========================================
     JOURNAL PUBLICATIONS
========================================= -->

<h2 class="pub-section-title">
  <i class="fas fa-book-open"></i>
  Journal Publications
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
  Conference Publications
</h2>

<ol class="publication-list">

  <li>
    <strong>S. Singha</strong>, M. H. Rayhan, T. P. H. Nguyen,
    M. Y. Rahman, M. M. Hossain, and S. K. Islam,
    "Machine Learning Enabled Parameter Extraction of
    β-Ga<sub>2</sub>O<sub>3</sub> MOSFETs,"
    <em>84th Device Research Conference (DRC)</em>,
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
