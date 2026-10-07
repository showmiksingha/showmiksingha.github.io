
---
title: "Publications"
permalink: /publications/
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
       RIGHT: PUBLICATIONS
  ====================================== -->

  <main class="pub-content">

    <h1>Publications</h1>

    <p class="pub-intro">
      Peer-reviewed journal articles, invited papers,
      and conference publications in semiconductor devices,
      power electronics, device modeling, and emerging technologies.
    </p>

    <!-- Publication Statistics -->
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

    <!-- =====================================
         JOURNAL PUBLICATIONS
    ====================================== -->

    <h2>Journal Publications</h2>

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

    <!-- =====================================
         INVITED PAPER
    ====================================== -->

    <h2>Invited Paper</h2>

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

    <!-- =====================================
         CONFERENCE PUBLICATIONS
    ====================================== -->

    <h2>Conference Publications</h2>

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
