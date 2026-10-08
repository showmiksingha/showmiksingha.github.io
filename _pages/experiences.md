---
title: "Experiences"
permalink: /experiences/
layout: default
author_profile: false
classes: wide
---

<div class="wrap experience-page">

<style>

/* =========================================
   GLOBAL PAGE DESIGN
========================================= */

.experience-page {
  --exp-navy: #142b4a;
  --exp-blue: #2563eb;
  --exp-text: #152238;
  --exp-muted: #64748b;
  --exp-border: #e2e8f0;
  --exp-surface: #f8fafc;
}

.experience-page * {
  box-sizing: border-box;
}

.experience-page .edu-layout {
  display: grid;
  grid-template-columns: 260px minmax(0, 1fr);
  gap: 28px;
  align-items: start;
}

@media(max-width:900px) {
  .experience-page .edu-layout {
    grid-template-columns: 1fr;
  }
}

/* =========================================
   LEFT AUTHOR PROFILE
========================================= */

.experience-page .author-card {
  position: sticky;
  top: 90px;
  border: 1px solid #e5e7eb;
  border-radius: 14px;
  padding: 16px;
  background: #fff;
}

@media(max-width:900px) {
  .experience-page .author-card {
    position: static;
  }
}

.experience-page .author-avatar {
  width: 110px;
  height: 110px;
  border-radius: 999px;
  object-fit: cover;
  display: block;
  margin: 0 auto 14px;
  border: 3px solid #f1f5f9;
}

.experience-page .author-name {
  font-size: 1.35rem;
  font-weight: 800;
  text-align: center;
  margin: 0 0 6px;
  color: #111827;
}

.experience-page .author-bio {
  font-size: 0.9rem;
  color: #64748b;
  text-align: center;
  margin-bottom: 18px;
  line-height: 1.6;
}

.experience-page .author-links {
  display: flex;
  flex-direction: column;
  gap: 11px;
}

.experience-page .author-links a {
  display: flex;
  align-items: center;
  gap: 10px;
  color: #334155;
  font-size: 0.9rem;
  text-decoration: none;
  transition: color 0.2s;
}

.experience-page .author-links a:hover {
  color: #2563eb;
}

.experience-page .author-links i {
  width: 18px;
  text-align: center;
  color: #64748b;
}

/* =========================================
   MAIN CONTENT
========================================= */

.experience-page .exp-content {
  min-width: 0;
}

/* =========================================
   HERO BANNER
========================================= */

.experience-page .exp-hero {
  position: relative;
  overflow: hidden;
  padding: 36px 32px;
  border-radius: 19px;
  background: linear-gradient(
    125deg,
    #10233d 0%,
    #1a4169 65%,
    #265b94 100%
  );
  color: white;
  margin-bottom: 27px;
}

.experience-page .exp-hero::before {
  content: "";
  position: absolute;
  width: 250px;
  height: 250px;
  border: 1px solid rgba(255,255,255,0.13);
  border-radius: 50%;
  right: -75px;
  top: -125px;
  pointer-events: none;
}

.experience-page .exp-hero::after {
  content: "";
  position: absolute;
  width: 180px;
  height: 180px;
  border: 1px solid rgba(255,255,255,0.1);
  border-radius: 50%;
  right: 25px;
  bottom: -115px;
  pointer-events: none;
}

.experience-page .exp-eyebrow {
  display: block;
  font-size: 0.68rem;
  font-weight: 800;
  letter-spacing: 2px;
  color: #b7d5ff;
  margin-bottom: 13px;
}

.experience-page .exp-hero h1 {
  color: white !important;
  font-size: clamp(1.7rem,3vw,2.35rem);
  font-weight: 800;
  letter-spacing: -0.8px;
  margin: 0 0 12px;
  line-height: 1.2;
}

.experience-page .exp-hero p {
  color: #d6e4f4;
  font-size: 0.93rem;
  line-height: 1.85;
  max-width: 620px;
  margin: 0;
}

.experience-page .hero-tags {
  display: flex;
  gap: 9px;
  flex-wrap: wrap;
  margin-top: 22px;
}

.experience-page .hero-tags span {
  font-size: 0.74rem;
  color: #e1ecfc;
  border: 1px solid rgba(255,255,255,0.24);
  background: rgba(255,255,255,0.08);
  border-radius: 30px;
  padding: 7px 12px;
}

/* =========================================
   STATISTICS
========================================= */

.experience-page .exp-stats {
  display: grid;
  grid-template-columns: repeat(3,minmax(0,1fr));
  gap: 12px;
  margin-bottom: 39px;
}

.experience-page .stat-card {
  background: #fff;
  border: 1px solid var(--exp-border);
  border-radius: 13px;
  padding: 19px 12px;
  text-align: center;
  transition: all 0.25s ease;
}

.experience-page .stat-card:hover {
  transform: translateY(-3px);
  border-color: #bfdbfe;
  box-shadow: 0 9px 24px rgba(15,23,42,0.06);
}

.experience-page .stat-number {
  display: block;
  font-size: 1.9rem;
  font-weight: 850;
  color: var(--exp-navy);
  line-height: 1.2;
}

.experience-page .stat-label {
  display: block;
  font-size: 0.74rem;
  color: var(--exp-muted);
  line-height: 1.5;
  margin-top: 7px;
}

/* =========================================
   QUICK NAVIGATION
========================================= */

.experience-page .exp-navigation {
  display: flex;
  flex-wrap: wrap;
  gap: 9px;
  margin-bottom: 39px;
}

.experience-page .exp-navigation a {
  font-size: 0.78rem;
  font-weight: 650;
  border: 1px solid var(--exp-border);
  border-radius: 30px;
  padding: 9px 13px;
  text-decoration: none;
  color: #475569;
  background: white;
  transition: all 0.2s;
}

.experience-page .exp-navigation a:hover {
  background: #eff6ff;
  border-color: #93c5fd;
  color: #1d4ed8;
}

.experience-page .exp-navigation i {
  margin-right: 5px;
}

/* =========================================
   SECTION HEADINGS
========================================= */

.experience-page .exp-section {
  margin-bottom: 49px;
  scroll-margin-top: 110px;
}

.experience-page .section-heading {
  display: flex;
  align-items: center;
  gap: 13px;
  margin-bottom: 9px;
}

.experience-page .section-icon {
  width: 41px;
  height: 41px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 11px;
  background: #eff6ff;
  color: #2563eb;
  flex-shrink: 0;
}

.experience-page .section-heading h2 {
  font-size: 1.32rem;
  font-weight: 800;
  color: var(--exp-text);
  margin: 0;
}

.experience-page .section-description {
  font-size: 0.85rem;
  color: var(--exp-muted);
  line-height: 1.7;
  margin: 0 0 28px 54px;
}

/* =========================================
   VERTICAL TIMELINE
========================================= */

.experience-page .exp-timeline {
  position: relative;
  padding-left: 28px;
  margin-left: 10px;
  border-left: 2px solid #dbeafe;
}

.experience-page .exp-card {
  position: relative;
  border: 1px solid #e2e8f0;
  border-radius: 15px;
  background: #fff;
  padding: 24px;
  margin-bottom: 23px;
  transition:
    transform 0.25s ease,
    box-shadow 0.25s ease,
    border-color 0.25s ease;
}

.experience-page .exp-card:last-child {
  margin-bottom: 0;
}

.experience-page .exp-card:hover {
  transform: translateY(-3px);
  border-color: #bfdbfe;
  box-shadow: 0 12px 32px rgba(20,43,74,0.07);
}

.experience-page .exp-card::before {
  content: "";
  position: absolute;
  width: 12px;
  height: 12px;
  background: #2563eb;
  border: 3px solid #fff;
  box-shadow: 0 0 0 2px #bfdbfe;
  border-radius: 50%;
  box-sizing: content-box;
  left: -39px;
  top: 28px;
}

.experience-page .exp-card.featured {
  border-top: 3px solid #2563eb;
  background: linear-gradient(
    155deg,
    #fff 75%,
    #f6faff
  );
}

.experience-page .exp-card-header {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 10px;
  margin-bottom: 10px;
}

.experience-page .exp-role {
  font-size: 1.09rem;
  font-weight: 800;
  line-height: 1.45;
  color: #152238;
  margin: 0;
}

.experience-page .exp-date {
  font-size: 0.75rem;
  font-weight: 700;
  color: #1d4ed8;
  background: #eff6ff;
  border: 1px solid #dbeafe;
  padding: 6px 10px;
  border-radius: 30px;
  white-space: nowrap;
}

.experience-page .exp-org {
  font-size: 0.94rem;
  font-weight: 700;
  color: #334155;
  margin-bottom: 6px;
  line-height: 1.55;
}

.experience-page .exp-location {
  display: flex;
  align-items: center;
  gap: 7px;
  font-size: 0.8rem;
  color: #94a3b8;
  margin-bottom: 20px;
}

.experience-page .exp-status {
  display: inline-flex;
  align-items: center;
  gap: 7px;
  background: #ecfdf5;
  border: 1px solid #bbf7d0;
  color: #047857;
  padding: 5px 10px;
  border-radius: 30px;
  font-size: 0.71rem;
  font-weight: 700;
  margin-bottom: 13px;
}

.experience-page .status-dot {
  width: 7px;
  height: 7px;
  border-radius: 50%;
  background: #10b981;
}

/* =========================================
   EXPERIENCE DESCRIPTION
========================================= */

.experience-page .exp-description ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

.experience-page .exp-description li {
  position: relative;
  padding-left: 19px;
  margin-bottom: 11px;
  font-size: 0.88rem;
  color: #475569;
  line-height: 1.8;
}

.experience-page .exp-description li::before {
  content: "";
  width: 6px;
  height: 6px;
  background: #60a5fa;
  border-radius: 50%;
  position: absolute;
  left: 1px;
  top: 11px;
}

.experience-page .exp-description li:last-child {
  margin-bottom: 0;
}

/* =========================================
   SKILL TAGS
========================================= */

.experience-page .exp-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 7px;
  margin-top: 20px;
  padding-top: 16px;
  border-top: 1px solid #f1f5f9;
}

.experience-page .exp-tag {
  font-size: 0.71rem;
  font-weight: 600;
  color: #475569;
  background: #f1f5f9;
  padding: 6px 10px;
  border-radius: 6px;
}

/* =========================================
   MENTORSHIP IMPACT
========================================= */

.experience-page .impact-grid {
  display: grid;
  grid-template-columns: repeat(3,minmax(0,1fr));
  gap: 10px;
  margin: 21px 0;
}

.experience-page .impact-box {
  padding: 17px 8px;
  background: #f8fafc;
  border: 1px solid #e2e8f0;
  border-radius: 11px;
  text-align: center;
}

.experience-page .impact-number {
  display: block;
  font-weight: 850;
  color: #2563eb;
  font-size: 1.8rem;
  line-height: 1.2;
}

.experience-page .impact-label {
  display: block;
  font-size: 0.73rem;
  color: #64748b;
  line-height: 1.5;
  margin-top: 5px;
}

/* =========================================
   REVIEW SUMMARY
========================================= */

.experience-page .review-count {
  display: inline-flex;
  align-items: center;
  gap: 7px;
  font-size: 0.74rem;
  color: #475569;
  font-weight: 650;
  background: #f1f5f9;
  border-radius: 7px;
  padding: 8px 11px;
  margin-top: 16px;
}

/* =========================================
   RESPONSIVE
========================================= */

@media(max-width:600px) {

  .experience-page .exp-hero {
    padding: 27px 21px;
  }

  .experience-page .exp-stats {
    gap: 7px;
  }

  .experience-page .stat-card {
    padding: 14px 6px;
  }

  .experience-page .stat-number {
    font-size: 1.5rem;
  }

  .experience-page .stat-label {
    font-size: 0.67rem;
  }

  .experience-page .exp-timeline {
    padding-left: 21px;
  }

  .experience-page .exp-card {
    padding: 19px;
  }

  .experience-page .exp-card::before {
    left: -31px;
  }

  .experience-page .exp-card-header {
    flex-direction: column;
    align-items: flex-start;
  }

  .experience-page .section-description {
    margin-left: 0;
  }

  .experience-page .impact-grid {
    gap: 7px;
  }

  .experience-page .impact-number {
    font-size: 1.5rem;
  }

}

/* Accessibility */
@media(prefers-reduced-motion: reduce) {
  .experience-page *,
  .experience-page *::before,
  .experience-page *::after {
    transition: none !important;
  }
}

</style>


<div class="edu-layout">

<!-- =====================================
     LEFT: AUTHOR PROFILE
===================================== -->

<aside class="author-card">

  <img
    src="/assets/images/profile.JPG"
    alt="Showmik Singha"
    class="author-avatar"
  >

  <h2 class="author-name">Showmik Singha</h2>

  <p class="author-bio">
    PhD Candidate<br>
    University of Missouri
  </p>

  <div class="author-links">

    <a href="mailto:ssqk4@umsystem.edu">
      <i class="fas fa-envelope"></i>
      Email
    </a>

    <a href="https://github.com/showmiksingha"
       target="_blank" rel="noopener noreferrer">
      <i class="fab fa-github"></i>
      GitHub
    </a>

    <a href="https://www.linkedin.com/in/showmiksingha/"
       target="_blank" rel="noopener noreferrer">
      <i class="fab fa-linkedin"></i>
      LinkedIn
    </a>

    <a href="https://scholar.google.com/"
       target="_blank" rel="noopener noreferrer">
      <i class="fas fa-graduation-cap"></i>
      Google Scholar
    </a>

    <a href="/files/Showmik_Singha_CV.pdf"
       target="_blank" rel="noopener noreferrer">
      <i class="fas fa-file-pdf"></i>
      Download CV
    </a>

  </div>

</aside>


<!-- =====================================
     RIGHT: EXPERIENCE
===================================== -->

<main class="exp-content">

<!-- =====================================
     HERO SECTION
===================================== -->

<div class="exp-hero">

  <span class="exp-eyebrow">
    MY PROFESSIONAL JOURNEY
  </span>

  <h1>Experience &amp; Impact</h1>

  <p>
    Bridging semiconductor research,
    engineering education, and mentorship.
    My experience spans advanced device modeling,
    university teaching, collaborative research,
    and academic service across multiple institutions.
  </p>

  <div class="hero-tags">
    <span>Semiconductor Research</span>
    <span>Engineering Education</span>
    <span>Research Mentorship</span>
  </div>

</div>


<!-- =====================================
     KEY STATISTICS
===================================== -->

<div class="exp-stats">

  <div class="stat-card">
    <span class="stat-number">3</span>
    <span class="stat-label">
      Academic<br>Institutions
    </span>
  </div>

  <div class="stat-card">
    <span class="stat-number">4</span>
    <span class="stat-label">
      Undergraduate<br>Researchers Mentored
    </span>
  </div>

  <div class="stat-card">
    <span class="stat-number">6</span>
    <span class="stat-label">
      Mentorship Research<br>Outputs
    </span>
  </div>

</div>


<!-- =====================================
     QUICK NAVIGATION
===================================== -->

<nav class="exp-navigation" aria-label="Experience sections">

  <a href="#research">
    <i class="fas fa-microscope"></i>
    Research
  </a>

  <a href="#teaching">
    <i class="fas fa-chalkboard-teacher"></i>
    Teaching
  </a>

  <a href="#mentorship">
    <i class="fas fa-user-graduate"></i>
    Mentorship
  </a>

  <a href="#service">
    <i class="fas fa-clipboard-check"></i>
    Service
  </a>

</nav>


<!-- =====================================
     1. RESEARCH EXPERIENCE
===================================== -->

<section class="exp-section" id="research">

  <div class="section-heading">
    <div class="section-icon">
      <i class="fas fa-microscope"></i>
    </div>
    <h2>Research Experience</h2>
  </div>

  <p class="section-description">
    Computational modeling, semiconductor
    device physics, reliability analysis,
    and data-driven device optimization.
  </p>

  <div class="exp-timeline">


    <!-- ONGOING DOCTORAL RESEARCH -->

    <article class="exp-card featured">

      <div class="exp-card-header">
        <h3 class="exp-role">
          Doctoral Researcher
        </h3>

        <span class="exp-date">
          Jan 2024 – Present
        </span>
      </div>

      <div class="exp-status">
        <span class="status-dot"></span>
        Ongoing Ph.D. Research
      </div>

      <div class="exp-org">
        University of Missouri–Columbia
      </div>

      <div class="exp-location">
        <i class="fas fa-map-marker-alt"></i>
        Columbia, Missouri, USA
      </div>

      <div class="exp-description">
        <ul>

          <li>
            Conducting doctoral research on
            radiation-induced reliability of
            wide-bandgap and ultra-wide-bandgap
            semiconductor power devices.
          </li>

          <li>
            Investigating single-event transient
            responses in GaN HEMTs and
            β-Ga<sub>2</sub>O<sub>3</sub> MOSFETs
            under heavy-ion irradiation,
            varying incidence angles,
            operating bias, and temperature.
          </li>

          <li>
            Applying physics-based TCAD
            simulations to analyze charge
            collection, electric-field
            distribution, and transient
            device responses.
          </li>

          <li>
            Developing machine learning-based
            inverse modeling frameworks for
            semiconductor parameter extraction
            and design optimization.
          </li>

          <li>
            Disseminating research through
            peer-reviewed publications,
            international conferences,
            and technical presentations.
          </li>

        </ul>
      </div>

      <div class="exp-tags">
        <span class="exp-tag">GaN HEMT</span>
        <span class="exp-tag">Ga₂O₃ MOSFET</span>
        <span class="exp-tag">Radiation Effects</span>
        <span class="exp-tag">TCAD</span>
        <span class="exp-tag">Machine Learning</span>
      </div>

    </article>


    <!-- MIZZOU GRA -->

    <article class="exp-card">

      <div class="exp-card-header">
        <h3 class="exp-role">
          Graduate Research Assistant
        </h3>

        <span class="exp-date">
          Aug 2024 – Jul 2025
        </span>
      </div>

      <div class="exp-org">
        University of Missouri–Columbia
      </div>

      <div class="exp-location">
        <i class="fas fa-map-marker-alt"></i>
        Columbia, Missouri, USA
      </div>

      <div class="exp-description">
        <ul>

          <li>
            Developed and calibrated
            physics-based TCAD models
            of GaN HEMTs and other
            wide-bandgap power devices;
            analyzed electrical characteristics,
            electric-field distribution,
            carrier transport, and
            high-field behavior.
          </li>

          <li>
            Executed parametric sweeps
            across device geometry,
            material properties, bias,
            temperature, and radiation
            conditions to evaluate
            design sensitivities.
          </li>

          <li>
            Extracted SPICE-compatible
            device models for device-
            and circuit-level evaluation.
          </li>

          <li>
            Investigated performance-
            and reliability-limiting
            mechanisms through electrical
            data analysis to guide
            device-design optimization.
          </li>

        </ul>
      </div>

      <div class="exp-tags">
        <span class="exp-tag">TCAD</span>
        <span class="exp-tag">SPICE</span>
        <span class="exp-tag">Device Modeling</span>
        <span class="exp-tag">Parametric Sweeps</span>
        <span class="exp-tag">Reliability</span>
      </div>

    </article>


    <!-- BOSTON UNIVERSITY GRA -->

    <article class="exp-card">

      <div class="exp-card-header">
        <h3 class="exp-role">
          Graduate Research Assistant
        </h3>

        <span class="exp-date">
          Sep 2022 – Dec 2023
        </span>
      </div>

      <div class="exp-org">
        Boston University
      </div>

      <div class="exp-location">
        <i class="fas fa-map-marker-alt"></i>
        Boston, Massachusetts, USA
      </div>

      <div class="exp-description">
        <ul>

          <li>
            Conducted computational modeling
            and optimization of infrared
            HgCdTe photodetectors.
          </li>

          <li>
            Analyzed dark current,
            photocurrent, reflectance,
            and quantum efficiency to
            evaluate detector performance.
          </li>

          <li>
            Performed structural and
            material parameter sweeps
            to identify design tradeoffs
            and improve quantum efficiency.
          </li>

          <li>
            Interpreted simulation findings
            to support photodetector
            design and performance optimization.
          </li>

        </ul>
      </div>

      <div class="exp-tags">
        <span class="exp-tag">HgCdTe</span>
        <span class="exp-tag">Photodetectors</span>
        <span class="exp-tag">Simulation</span>
        <span class="exp-tag">Quantum Efficiency</span>
      </div>

    </article>

  </div>

</section>


<!-- =====================================
     2. TEACHING EXPERIENCE
===================================== -->

<section class="exp-section" id="teaching">

  <div class="section-heading">
    <div class="section-icon">
      <i class="fas fa-chalkboard-teacher"></i>
    </div>
    <h2>Teaching Experience</h2>
  </div>

  <p class="section-description">
    University-level instruction,
    laboratory development,
    curriculum improvement,
    and undergraduate education.
  </p>

  <div class="exp-timeline">


    <!-- MIZZOU GTA -->

    <article class="exp-card featured">

      <div class="exp-card-header">
        <h3 class="exp-role">
          Graduate Teaching Assistant
        </h3>

        <span class="exp-date">
          Jan 2024 – Present
        </span>
      </div>

      <div class="exp-status">
        <span class="status-dot"></span>
        Current Appointment
      </div>

      <div class="exp-org">
        Department of Electrical Engineering
        and Computer Science<br>
        University of Missouri–Columbia
      </div>

      <div class="exp-location">
        <i class="fas fa-map-marker-alt"></i>
        Columbia, Missouri, USA
      </div>

      <div class="exp-description">
        <ul>

          <li>
            Assisting undergraduate students
            in Circuit Theory, Logic Systems,
            and Signals &amp; Linear Systems
            through instructional support,
            laboratory sessions,
            office hours, and grading.
          </li>

          <li>
            Improved laboratory manuals
            for Circuit Theory I and II
            to enhance clarity and
            instructional consistency.
          </li>

          <li>
            Developed Cadence-based
            assignment manuals for
            Introduction to Logic System
            Design to strengthen hands-on
            digital circuit design skills.
          </li>

          <li>
            Supporting faculty in
            student assessment,
            laboratory instruction,
            and course material development.
          </li>

        </ul>
      </div>

      <div class="exp-tags">
        <span class="exp-tag">Circuit Theory</span>
        <span class="exp-tag">Logic Systems</span>
        <span class="exp-tag">Signals &amp; Systems</span>
        <span class="exp-tag">Cadence</span>
        <span class="exp-tag">Course Materials</span>
      </div>

    </article>


    <!-- SUST FACULTY -->

    <article class="exp-card">

      <div class="exp-card-header">
        <h3 class="exp-role">
          Faculty Member
        </h3>

        <span class="exp-date">
          Sep 2018 – Aug 2022
        </span>
      </div>

      <div class="exp-org">
        Department of Electrical
        &amp; Electronic Engineering<br>
        Shahjalal University of Science
        and Technology (SUST)
      </div>

      <div class="exp-location">
        <i class="fas fa-map-marker-alt"></i>
        Sylhet, Bangladesh
      </div>

      <div class="exp-description">
        <ul>

          <li>
            Delivered undergraduate
            engineering instruction
            through lectures, tutorials,
            laboratory sessions,
            and student assessments.
          </li>

          <li>
            Developed teaching materials,
            course assignments,
            examinations, and laboratory
            exercises to strengthen
            theoretical and practical
            understanding.
          </li>

          <li>
            Mentored students in
            technical problem-solving,
            academic development,
            and engineering projects.
          </li>

          <li>
            Participated in departmental
            academic activities,
            course coordination,
            and continuous improvement
            of engineering education.
          </li>

        </ul>
      </div>

      <div class="exp-tags">
        <span class="exp-tag">University Teaching</span>
        <span class="exp-tag">Curriculum Development</span>
        <span class="exp-tag">Student Mentorship</span>
        <span class="exp-tag">Electrical Engineering</span>
      </div>

    </article>

  </div>

</section>


<!-- =====================================
     3. RESEARCH MENTORSHIP
===================================== -->

<section class="exp-section" id="mentorship">

  <div class="section-heading">
    <div class="section-icon">
      <i class="fas fa-user-graduate"></i>
    </div>
    <h2>Research Mentorship</h2>
  </div>

  <p class="section-description">
    Supporting undergraduate researchers
    in developing technical expertise,
    independent research skills,
    and scientific communication.
  </p>

  <div class="exp-timeline">

    <article class="exp-card">

      <div class="exp-card-header">
        <h3 class="exp-role">
          Undergraduate Research Mentor
        </h3>

        <span class="exp-date">
          University of Missouri
        </span>
      </div>

      <div class="exp-org">
        University of Missouri–Columbia
      </div>

      <div class="exp-location">
        <i class="fas fa-map-marker-alt"></i>
        Columbia, Missouri, USA
      </div>

      <!-- Mentorship Impact -->

      <div class="impact-grid">

        <div class="impact-box">
          <span class="impact-number">4</span>
          <span class="impact-label">
            Undergraduate<br>Students
          </span>
        </div>

        <div class="impact-box">
          <span class="impact-number">5</span>
          <span class="impact-label">
            Conference<br>Presentations
          </span>
        </div>

        <div class="impact-box">
          <span class="impact-number">1</span>
          <span class="impact-label">
            Additional Accepted<br>Manuscript
          </span>
        </div>

      </div>

      <div class="exp-description">
        <ul>

          <li>
            Mentored four undergraduate
            students in engineering research
            at the University of Missouri.
          </li>

          <li>
            Guided research methodology,
            technical analysis,
            interpretation of results,
            manuscript preparation,
            and conference presentations.
          </li>

          <li>
            Mentorship contributed to
            five conference presentations
            and one additional manuscript
            accepted for presentation.
          </li>

          <li>
            Encouraged independent
            problem-solving, collaboration,
            scientific communication,
            and professional development.
          </li>

        </ul>
      </div>

      <div class="exp-tags">
        <span class="exp-tag">Undergraduate Research</span>
        <span class="exp-tag">Mentorship</span>
        <span class="exp-tag">Research Communication</span>
        <span class="exp-tag">Student Development</span>
      </div>

    </article>

  </div>

</section>


<!-- =====================================
     4. PROFESSIONAL SERVICE
===================================== -->

<section class="exp-section" id="service">

  <div class="section-heading">
    <div class="section-icon">
      <i class="fas fa-clipboard-check"></i>
    </div>
    <h2>Professional Service</h2>
  </div>

  <p class="section-description">
    Contributing to the scientific
    community through technical
    manuscript evaluation and peer review.
  </p>

  <div class="exp-timeline">


    <!-- BATS 2025 -->

    <article class="exp-card">

      <div class="exp-card-header">
        <h3 class="exp-role">
          Conference Reviewer
        </h3>

        <span class="exp-date">2025</span>
      </div>

      <div class="exp-org">
        International Workshop on
        Biomedical Applications,
        Technologies and Sensors (BATS)
      </div>

      <div class="exp-description">
        <ul>

          <li>
            Completed one peer review
            for the 2025 International
            Workshop on Biomedical
            Applications, Technologies
            and Sensors.
          </li>

          <li>
            Evaluated technical submissions
            and provided constructive
            feedback to support
            the peer-review process.
          </li>

        </ul>
      </div>

      <div class="review-count">
        <i class="fas fa-check-circle"></i>
        1 Completed Review
      </div>

    </article>


    <!-- Q-BATS 2024 -->

    <article class="exp-card">

      <div class="exp-card-header">
        <h3 class="exp-role">
          Conference Reviewer
        </h3>

        <span class="exp-date">2024</span>
      </div>

      <div class="exp-org">
        International Workshop on
        Quantum &amp; Biomedical
        Applications, Technologies,
        and Sensors (Q-BATS)
      </div>

      <div class="exp-description">
        <ul>

          <li>
            Completed two peer reviews
            for the 2024 International
            Workshop on Quantum &amp;
            Biomedical Applications,
            Technologies, and Sensors.
          </li>

          <li>
            Contributed to the independent
            technical assessment of
            conference manuscripts,
            providing constructive
            reviewer feedback.
          </li>

        </ul>
      </div>

      <div class="review-count">
        <i class="fas fa-check-circle"></i>
        2 Completed Reviews
      </div>

    </article>

  </div>

</section>


</main>
</div>
</div>
