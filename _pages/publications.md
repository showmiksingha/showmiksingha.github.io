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
   PUBLICATION MAIN CONTENT
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
   MODERN GOOGLE SCHOLAR DASHBOARD
========================================= */
.scholar-dashboard {
  margin: 30px 0 44px;
  padding: 24px;
  border: 1px solid #e5e7eb;
  border-radius: 16px;
  background: #fff;
}

.scholar-heading {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 14px;
  flex-wrap: wrap;
  margin-bottom: 22px;
}

.scholar-heading h2 {
  margin: 0 !important;
  padding: 0 !important;
  border: none !important;
  font-size: 1.3rem;
}

.scholar-heading h2 i {
  color: #2563eb;
  margin-right: 7px;
}

.scholar-profile-link {
  display: inline-flex;
  align-items: center;
  gap: 7px;
  text-decoration: none !important;
  font-size: 0.8rem;
  font-weight: 600;
  color: #2563eb !important;
  background: #eff6ff;
  border: 1px solid #dbeafe;
  padding: 8px 12px;
  border-radius: 20px;
  transition: all 0.25s ease;
}

.scholar-profile-link:hover {
  background: #dbeafe;
  transform: translateY(-2px);
}

/* =========================================
   SCHOLAR METRIC CARDS
========================================= */
.scholar-metrics {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 12px;
  margin-bottom: 24px;
}

.scholar-metric {
  position: relative;
  overflow: hidden;
  text-align: center;
  border: 1px solid #e5e7eb;
  background: #f8fafc;
  border-radius: 13px;
  padding: 22px 10px 18px;
  transition:
    transform 0.25s ease,
    box-shadow 0.25s ease,
    border-color 0.25s ease;
}

.scholar-metric:hover {
  transform: translateY(-4px);
  border-color: #bfdbfe;
  box-shadow: 0 9px 22px rgba(37,99,235,0.08);
}

.metric-icon {
  width: 37px;
  height: 37px;
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 0 auto 13px;
  border-radius: 10px;
  background: #eaf1ff;
  color: #2563eb;
  font-size: 1rem;
}

.metric-number {
  display: block;
  font-size: 2rem;
  line-height: 1.15;
  font-weight: 800;
  color: #111827;
  margin-bottom: 7px;
}

.metric-label {
  display: block;
  font-size: 0.82rem;
  font-weight: 600;
  color: #475569;
}

.metric-description {
  display: block;
  font-size: 0.72rem;
  color: #94a3b8;
  margin-top: 5px;
}

/* =========================================
   SCHOLAR CITATION DISTRIBUTION
========================================= */
.scholar-distribution {
  display: grid;
  grid-template-columns: 170px minmax(0, 1fr);
  gap: 24px;
  align-items: center;
  padding: 22px;
  border: 1px solid #e5e7eb;
  border-radius: 13px;
  background: #fff;
}

.citation-donut {
  position: relative;
  width: 155px;
  height: 155px;
  margin: auto;
}

.citation-donut svg {
  width: 100%;
  height: 100%;
  display: block;
}

.donut-track {
  fill: none;
  stroke: #e5e7eb;
  stroke-width: 11;
}

.donut-progress {
  fill: none;
  stroke: #2563eb;
  stroke-width: 11;
  stroke-linecap: round;
  stroke-dasharray: 263.24 269.55;
  transform: rotate(-90deg);
  transform-origin: 50% 50%;
  transition: stroke 0.3s ease;
}

.citation-donut:hover .donut-progress {
  stroke: #1d4ed8;
}

.donut-text {
  position: absolute;
  inset: 0;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  pointer-events: none;
}

.donut-percentage {
  font-size: 1.65rem;
  font-weight: 800;
  line-height: 1.2;
  color: #111827;
}

.donut-caption {
  font-size: 0.72rem;
  color: #64748b;
  margin-top: 4px;
}

/* Distribution right section */
.distribution-details h3 {
  font-size: 1rem;
  margin: 0 0 9px;
  color: #111827;
}

.distribution-details p {
  font-size: 0.82rem;
  color: #64748b;
  line-height: 1.6;
  margin: 0 0 19px;
}

.distribution-row {
  margin-bottom: 14px;
}

.distribution-meta {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 10px;
  font-size: 0.82rem;
  margin-bottom: 8px;
}

.distribution-meta span {
  color: #64748b;
}

.distribution-meta strong {
  color: #111827;
  font-weight: 700;
}

.distribution-track {
  width: 100%;
  height: 8px;
  border-radius: 99px;
  background: #eef2f7;
  overflow: hidden;
}

.distribution-fill {
  height: 100%;
  border-radius: 99px;
  background: #2563eb;
  transition: width 0.7s ease;
}

.distribution-fill.early {
  background: #94a3b8;
}

/* =========================================
   SECONDARY SCHOLAR METRICS
========================================= */
.scholar-period {
  margin-top: 20px;
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 12px;
}

.period-card {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 10px;
  border: 1px solid #e5e7eb;
  border-radius: 10px;
  padding: 15px;
  background: #fafafa;
}

.period-card-label {
  display: flex;
  flex-direction: column;
  gap: 5px;
}

.period-card-label span {
  font-size: 0.78rem;
  color: #64748b;
}

.period-card-label strong {
  font-size: 0.94rem;
  color: #111827;
}

.period-card-value {
  font-size: 1.35rem;
  font-weight: 800;
  color: #2563eb;
}

.scholar-note {
  margin: 18px 0 0;
  font-size: 0.75rem;
  color: #94a3b8;
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
   PUBLICATION LIST
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

  .scholar-dashboard {
    padding: 17px 12px;
  }

  .scholar-metrics {
    gap: 7px;
  }

  .scholar-metric {
    padding: 16px 5px;
  }

  .metric-number {
    font-size: 1.5rem;
  }

  .metric-label {
    font-size: 0.72rem;
  }

  .metric-description {
    font-size: 0.64rem;
  }

  .metric-icon {
    width: 30px;
    height: 30px;
    font-size: 0.8rem;
  }

  .scholar-distribution {
    grid-template-columns: 1fr;
    gap: 16px;
    padding: 18px 14px;
  }

  .citation-donut {
    width: 145px;
    height: 145px;
  }

  .distribution-details {
    width: 100%;
  }

  .scholar-period {
    gap: 8px;
  }

  .period-card {
    padding: 12px 9px;
  }

  .period-card-value {
    font-size: 1.1rem;
  }

  .publication-list li {
    font-size: 0.9rem;
  }

}

@media (prefers-reduced-motion: reduce) {
  .pub-stat,
  .scholar-metric,
  .scholar-profile-link,
  .donut-progress,
  .distribution-fill {
    transition: none;
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
     GOOGLE SCHOLAR RESEARCH IMPACT
========================================= -->

<section class="scholar-dashboard">

  <!-- Heading -->
  <div class="scholar-heading">

    <h2>
      <i class="fas fa-chart-line"></i>
      Research Impact
    </h2>

    <a
      class="scholar-profile-link"
      href="https://scholar.google.com/citations?user=B0llklQAAAAJ"
      target="_blank"
      rel="noopener noreferrer"
    >
      <i class="fas fa-graduation-cap"></i>
      Google Scholar
      <i class="fas fa-external-link-alt"></i>
    </a>

  </div>

  <!-- =====================================
       PRIMARY CITATION METRICS
  ====================================== -->

  <div class="scholar-metrics">

    <!-- Total Citations -->
    <div class="scholar-metric">

      <div class="metric-icon">
        <i class="fas fa-quote-right"></i>
      </div>

      <span class="metric-number">87</span>

      <span class="metric-label">
        Total Citations
      </span>

      <span class="metric-description">
        All time
      </span>

    </div>

    <!-- h-index -->
    <div class="scholar-metric">

      <div class="metric-icon">
        <i class="fas fa-chart-line"></i>
      </div>

      <span class="metric-number">5</span>

      <span class="metric-label">
        h-index
      </span>

      <span class="metric-description">
        Research impact
      </span>

    </div>

    <!-- i10-index -->
    <div class="scholar-metric">

      <div class="metric-icon">
        <i class="fas fa-book"></i>
      </div>

      <span class="metric-number">3</span>

      <span class="metric-label">
        i10-index
      </span>

      <span class="metric-description">
        Papers with 10+ citations
      </span>

    </div>

  </div>

  <!-- =====================================
       CITATION DISTRIBUTION
  ====================================== -->

  <div class="scholar-distribution">

    <!-- Circular visualization -->
    <div class="citation-donut">

      <svg
        viewBox="0 0 120 120"
        role="img"
        aria-label="97.7 percent of citations are from 2021 onward"
      >

        <circle
          class="donut-track"
          cx="60"
          cy="60"
          r="42.9"
        />

        <circle
          class="donut-progress"
          cx="60"
          cy="60"
          r="42.9"
        />

      </svg>

      <div class="donut-text">

        <span class="donut-percentage">
          97.7%
        </span>

        <span class="donut-caption">
          Since 2021
        </span>

      </div>

    </div>

    <!-- Citation breakdown -->
    <div class="distribution-details">

      <h3>Citation Distribution</h3>

      <p>
        The majority of lifetime citations
        have been received since 2021.
      </p>

      <!-- Recent -->
      <div class="distribution-row">

        <div class="distribution-meta">
          <span>Since 2021</span>
          <strong>85 citations</strong>
        </div>

        <div class="distribution-track">
          <div
            class="distribution-fill"
            style="width:97.7%">
          </div>
        </div>

      </div>

      <!-- Earlier -->
      <div class="distribution-row">

        <div class="distribution-meta">
          <span>Before 2021</span>
          <strong>2 citations</strong>
        </div>

        <div class="distribution-track">
          <div
            class="distribution-fill early"
            style="width:2.3%; min-width:4px;">
          </div>
        </div>

      </div>

    </div>

  </div>

  <!-- =====================================
       RECENT PERIOD METRICS
  ====================================== -->

  <div class="scholar-period">

    <div class="period-card">

      <div class="period-card-label">
        <span>Since 2021</span>
        <strong>h-index</strong>
      </div>

      <div class="period-card-value">
        5
      </div>

    </div>

    <div class="period-card">

      <div class="period-card-label">
        <span>Since 2021</span>
        <strong>i10-index</strong>
      </div>

      <div class="period-card-value">
        3
      </div>

    </div>

  </div>

  <p class="scholar-note">
    Source: Google Scholar. Citation statistics are
    based on the provided snapshot and are updated manually.
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
