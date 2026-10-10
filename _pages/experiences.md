---
title: "Experiences"
permalink: /experiences/
layout: default
author_profile: false
classes: wide
---

<div class="wrap" markdown="1">

<style>

/* ==========================================
   PAGE LAYOUT
========================================== */

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

/* ==========================================
   AUTHOR PROFILE
========================================== */

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
  color: #1e293b;
  font-size: 1.25rem;
}

.author-bio {
  text-align: center;
  color: #6b7280;
  margin: 6px 0 12px 0;
  font-size: 0.95rem;
  line-height: 1.6;
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
  color: #475569;
  font-size: 0.9rem;
  transition: color 0.2s ease;
}

.author-links a:hover {
  color: #2563eb;
}

.author-links i {
  width: 17px;
  text-align: center;
}

/* ==========================================
   MAIN EXPERIENCE CONTENT
========================================== */

.exp-content {
  min-width: 0;
  color: #242424;
}

.exp-content > h1 {
  font-size: 2rem;
  font-weight: 800;
  color: #1e293b;
  margin: 0 0 16px;
  padding-bottom: 13px;
  border-bottom: 2px solid #e5e7eb;
  letter-spacing: -0.5px;
}

/* ==========================================
   QUICK SECTION NAVIGATION
========================================== */

.exp-navigation {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin: 23px 0 38px;
}

.exp-navigation a {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  padding: 9px 15px;
  border: 1px solid #e2e8f0;
  border-radius: 30px;
  background: #fff;
  color: #475569;
  font-size: 0.81rem;
  font-weight: 650;
  text-decoration: none;
  transition: all 0.25s ease;
}

.exp-navigation a:hover {
  background: #eff6ff;
  color: #1d4ed8;
  border-color: #bfdbfe;
  transform: translateY(-2px);
}

.exp-navigation i {
  color: #2563eb;
  font-size: 0.85rem;
}

/* ==========================================
   EXPERIENCE SECTIONS
========================================== */

.exp-section {
  margin-bottom: 48px;
  scroll-margin-top: 110px;
}

.section-heading {
  display: flex;
  align-items: center;
  gap: 13px;
  margin-bottom: 23px;
  padding-bottom: 13px;
  border-bottom: 1px solid #e5e7eb;
}

.section-icon {
  width: 43px;
  height: 43px;
  flex-shrink: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 12px;
  background: #eff6ff;
  color: #2563eb;
  font-size: 1.1rem;
}

.section-heading h2 {
  font-size: 1.32rem;
  font-weight: 800;
  color: #1e293b;
  margin: 0;
  letter-spacing: -0.25px;
}

.section-description {
  font-size: 0.9rem;
  color: #64748b;
  line-height: 1.75;
  margin: -7px 0 25px;
}

/* ==========================================
   VERTICAL EXPERIENCE TIMELINE
========================================== */

.exp-timeline {
  position: relative;
  padding-left: 28px;
  margin-left: 9px;
  border-left: 2px solid #dbeafe;
}

/* ==========================================
   EXPERIENCE CARDS
========================================== */

.exp-card {
  position: relative;
  background: #fff;
  border: 1px solid #e5e7eb;
  border-radius: 15px;
  padding: 24px;
  margin-bottom: 23px;
  transition:
    transform 0.25s ease,
    box-shadow 0.25s ease,
    border-color 0.25s ease;
}

.exp-card:last-child {
  margin-bottom: 0;
}

.exp-card:hover {
  transform: translateY(-3px);
  border-color: #bfdbfe;
  box-shadow: 0 9px 27px rgba(15,23,42,0.065);
}

/* Timeline Nodes */

.exp-card::before {
  content: "";
  position: absolute;
  width: 12px;
  height: 12px;
  border-radius: 50%;
  background: #2563eb;
  border: 3px solid #fff;
  box-shadow: 0 0 0 2px #bfdbfe;
  left: -39px;
  top: 28px;
  box-sizing: content-box;
}

/* Featured Ongoing Positions */

.exp-card.featured {
  border-top: 3px solid #2563eb;
  background: linear-gradient(
    155deg,
    #fff 78%,
    #f7faff 100%
  );
}

.exp-card.featured::before {
  background: #10b981;
  box-shadow: 0 0 0 2px #a7f3d0;
}

/* ==========================================
   EXPERIENCE CARD HEADER
========================================== */

.exp-card-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  flex-wrap: wrap;
  gap: 10px;
  margin-bottom: 12px;
}

.exp-role {
  font-size: 1.1rem;
  font-weight: 800;
  color: #1e293b;
  line-height: 1.45;
  margin: 0;
}

.exp-date {
  display: inline-block;
  font-size: 0.76rem;
  font-weight: 700;
  color: #1d4ed8;
  background: #eff6ff;
  border: 1px solid #dbeafe;
  border-radius: 25px;
  padding: 6px 11px;
  white-space: nowrap;
}

/* ==========================================
   ONGOING STATUS
========================================== */

.exp-status {
  display: inline-flex;
  align-items: center;
  gap: 7px;
  font-size: 0.72rem;
  font-weight: 700;
  color: #047857;
  background: #ecfdf5;
  border: 1px solid #bbf7d0;
  padding: 6px 11px;
  border-radius: 25px;
  margin-bottom: 13px;
}

.status-dot {
  display: inline-block;
  width: 7px;
  height: 7px;
  border-radius: 50%;
  background: #10b981;
}

/* ==========================================
   ORGANIZATION AND LOCATION
========================================== */

.exp-org {
  font-size: 0.95rem;
  font-weight: 700;
  color: #334155;
  line-height: 1.65;
  margin-bottom: 6px;
}

.exp-location {
  display: flex;
  align-items: center;
  gap: 7px;
  font-size: 0.82rem;
  color: #94a3b8;
  margin-bottom: 19px;
}

.exp-location i {
  color: #94a3b8;
}

/* ==========================================
   RESPONSIBILITIES
========================================== */

.exp-description {
  font-size: 0.9rem;
  color: #475569;
  line-height: 1.8;
}

.exp-description ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

.exp-description li {
  position: relative;
  padding-left: 19px;
  margin-bottom: 12px;
}

.exp-description li:last-child {
  margin-bottom: 0;
}

.exp-description li::before {
  content: "";
  position: absolute;
  top: 11px;
  left: 1px;
  width: 6px;
  height: 6px;
  background: #60a5fa;
  border-radius: 50%;
}

/* ==========================================
   SKILL TAGS — BLUE HOVER PILLS
========================================== */

.exp-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 20px;
  padding-top: 16px;
  border-top: 1px solid #f1f5f9;
}

.exp-tag {
  display: inline-flex;
  align-items: center;
  padding: 9px 15px;
  background: #f8fafc;
  color: #334155;
  border: 1px solid #e2e8f0;
  border-radius: 999px;
  font-size: 0.88rem;
  font-weight: 500;
  line-height: 1.4;
  cursor: default;

  transition:
    background-color 0.25s ease,
    color 0.25s ease,
    border-color 0.25s ease,
    transform 0.25s ease,
    box-shadow 0.25s ease;
}

.exp-tag:hover {
  background: #2563eb;
  color: #ffffff;
  border-color: #2563eb;
  transform: translateY(-2px);
  box-shadow: 0 4px 12px rgba(37,99,235,0.18);
}

/* ==========================================
   MENTORSHIP IMPACT METRICS
========================================== */

.impact-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0,1fr));
  gap: 11px;
  margin: 20px 0 24px;
}

.impact-box {
  text-align: center;
  padding: 19px 9px;
  background: #f8fafc;
  border: 1px solid #e2e8f0;
  border-radius: 12px;
  transition: all 0.25s ease;
}

.impact-box:hover {
  background: #eff6ff;
  border-color: #bfdbfe;
  transform: translateY(-2px);
}

.impact-number {
  display: block;
  font-size: 1.85rem;
  font-weight: 850;
  color: #2563eb;
  line-height: 1.2;
}

.impact-label {
  display: block;
  font-size: 0.73rem;
  color: #64748b;
  line-height: 1.5;
  margin-top: 7px;
}

/* ==========================================
   REVIEWER DETAILS
========================================== */

.review-count {
  display: inline-flex;
  align-items: center;
  gap: 7px;
  padding: 7px 11px;
  border-radius: 7px;
  background: #eff6ff;
  color: #1d4ed8;
  font-size: 0.76rem;
  font-weight: 650;
  margin-top: 17px;
}

/* ==========================================
   RESPONSIVE DESIGN
========================================== */

@media (max-width: 700px) {

  .exp-navigation {
    gap: 7px;
  }

  .exp-navigation a {
    font-size: 0.75rem;
    padding: 8px 11px;
  }

}

@media (max-width: 600px) {

  .exp-content > h1 {
    font-size: 1.7rem;
  }

  .section-heading h2 {
    font-size: 1.15rem;
  }

  .section-icon {
    width: 38px;
    height: 38px;
  }

  .exp-timeline {
    padding-left: 20px;
  }

  .exp-card {
    padding: 18px;
  }

  .exp-card::before {
    left: -31px;
  }

  .exp-card-header {
    flex-direction: column;
    align-items: flex-start;
  }

  .exp-date {
    white-space: normal;
  }

  .exp-tags {
    gap: 8px;
  }

  .exp-tag {
    padding: 7px 12px;
    font-size: 0.8rem;
  }

  .impact-grid {
    gap: 7px;
  }

  .impact-box {
    padding: 13px 5px;
  }

  .impact-number {
    font-size: 1.45rem;
  }

  .impact-label {
    font-size: 0.67rem;
  }

}

/* ==========================================
   ACCESSIBILITY
========================================== */

@media (prefers-reduced-motion: reduce) {

  .exp-card,
  .impact-box,
  .exp-navigation a,
  .author-links a,
  .exp-tag {
    transition: none;
  }

  .exp-tag:hover {
    transform: none;
  }

}

</style>


<div class="edu-layout">

<!-- ======================================
     LEFT: AUTHOR PROFILE
====================================== -->

<aside class="author-card">

  <img
    class="author-avatar"
    src="/assets/images/profile.JPG"
    alt="Showmik Singha"
  >

  <p class="author-name">
    Showmik Singha
  </p>

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
         rel="noopener noreferrer">
        <i class="fab fa-fw fa-github"></i>
        <span>GitHub</span>
      </a>
    </li>

    <li>
      <a href="https://www.linkedin.com/in/showmik-singha-293967147"
         target="_blank"
         rel="noopener noreferrer">
        <i class="fab fa-fw fa-linkedin"></i>
        <span>LinkedIn</span>
      </a>
    </li>

  </ul>

</aside>


<!-- ======================================
     RIGHT: EXPERIENCE CONTENT
====================================== -->

<main class="exp-content">

<h1>Professional Experiences</h1>


<!-- ======================================
     QUICK NAVIGATION
====================================== -->

<nav class="exp-navigation"
     aria-label="Experience sections">

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


<!-- ======================================
     1. RESEARCH EXPERIENCE
====================================== -->

<section class="exp-section" id="research">

  <div class="section-heading">

    <div class="section-icon">
      <i class="fas fa-microscope"></i>
    </div>

    <h2>Research Experiences</h2>

  </div>

  <div class="exp-timeline">


    <!-- DOCTORAL RESEARCH -->

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


    <!-- BOSTON UNIVERSITY -->

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


<!-- ======================================
     2. TEACHING EXPERIENCE
====================================== -->

<section class="exp-section" id="teaching">

  <div class="section-heading">

    <div class="section-icon">
      <i class="fas fa-chalkboard-teacher"></i>
    </div>

    <h2>Teaching Experience</h2>

  </div>

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


    <!-- SUST FACULTY MEMBER -->

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


<!-- ======================================
     3. RESEARCH MENTORSHIP
====================================== -->

<section class="exp-section" id="mentorship">

  <div class="section-heading">

    <div class="section-icon">
      <i class="fas fa-user-graduate"></i>
    </div>

    <h2>Research Mentorship</h2>

  </div>

  <p class="section-description">
    Mentoring undergraduate researchers
    in thesis research, academic projects,
    technical analysis, scientific writing,
    and research dissemination.
  </p>

  <div class="exp-timeline">


    <!-- MIZZOU RESEARCH MENTORSHIP -->

    <article class="exp-card">

      <div class="exp-card-header">

        <h3 class="exp-role">
          Undergraduate Research Mentor
        </h3>

        <span class="exp-date">
          Jan 2024 – Present
        </span>

      </div>

      <div class="exp-org">
        University of Missouri–Columbia
      </div>

      <div class="exp-location">
        <i class="fas fa-map-marker-alt"></i>
        Columbia, Missouri, USA
      </div>


      <!-- MIZZOU MENTORSHIP IMPACT -->

      <div class="impact-grid">

        <div class="impact-box">

          <span class="impact-number">
            4
          </span>

          <span class="impact-label">
            Undergraduate<br>
            Students
          </span>

        </div>

        <div class="impact-box">

          <span class="impact-number">
            5
          </span>

          <span class="impact-label">
            Conference<br>
            Presentations
          </span>

        </div>

        <div class="impact-box">

          <span class="impact-number">
            1
          </span>

          <span class="impact-label">
            Additional Accepted<br>
            Manuscript
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

        <span class="exp-tag">
          Undergraduate Research
        </span>

        <span class="exp-tag">
          Mentorship
        </span>

        <span class="exp-tag">
          Research Communication
        </span>

        <span class="exp-tag">
          Student Development
        </span>

      </div>

    </article>


    <!-- SUST RESEARCH MENTORSHIP -->

    <article class="exp-card">

      <div class="exp-card-header">

        <h3 class="exp-role">
          Undergraduate Thesis &amp;
          Project Mentor
        </h3>

        <span class="exp-date">
          Sep 2018 – Aug 2022
        </span>

      </div>

      <div class="exp-org">
        Shahjalal University of Science
        and Technology (SUST)
      </div>

      <div class="exp-location">
        <i class="fas fa-map-marker-alt"></i>
        Sylhet, Bangladesh
      </div>


      <!-- SUST MENTORSHIP IMPACT -->

      <div class="impact-grid">

        <div class="impact-box">

          <span class="impact-number">
            12
          </span>

          <span class="impact-label">
            Undergraduate<br>
            Students
          </span>

        </div>

        <div class="impact-box">

          <span class="impact-number">
            6
          </span>

          <span class="impact-label">
            Conference<br>
            Papers
          </span>

        </div>

        <div class="impact-box">

          <span class="impact-number">
            2
          </span>

          <span class="impact-label">
            Journal<br>
            Papers
          </span>

        </div>

      </div>


      <div class="exp-description">

        <ul>

          <li>
            Supervised and mentored
            12 undergraduate students
            in thesis research and academic
            projects at Shahjalal University
            of Science and Technology (SUST).
          </li>

          <li>
            Provided guidance in research
            methodology, experimental design,
            data analysis, technical writing,
            and engineering project development.
          </li>

          <li>
            Mentorship and collaborative research
            activities resulted in
            six conference papers and
            two journal papers.
          </li>

          <li>
            Supported students in developing
            independent research skills,
            critical thinking, technical
            problem-solving, and scientific
            communication.
          </li>

        </ul>

      </div>

      <div class="exp-tags">

        <span class="exp-tag">
          Thesis Supervision
        </span>

        <span class="exp-tag">
          Undergraduate Mentorship
        </span>

        <span class="exp-tag">
          Experimental Design
        </span>

        <span class="exp-tag">
          Research Publications
        </span>

        <span class="exp-tag">
          Technical Writing
        </span>

      </div>

    </article>

  </div>

</section>


<!-- ======================================
     4. PROFESSIONAL SERVICE
====================================== -->

<section class="exp-section" id="service">

  <div class="section-heading">

    <div class="section-icon">
      <i class="fas fa-clipboard-check"></i>
    </div>

    <h2>Professional Service</h2>

  </div>

  <div class="exp-timeline">


    <!-- BATS 2025 REVIEWER -->

    <article class="exp-card">

      <div class="exp-card-header">

        <h3 class="exp-role">
          Conference Reviewer
        </h3>

        <span class="exp-date">
          2025
        </span>

      </div>

      <div class="exp-org">
        International Workshop on
        Biomedical Applications,
        Technologies and Sensors (BATS)
      </div>

      <div class="exp-description">

        <ul>

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


    <!-- Q-BATS 2024 REVIEWER -->

    <article class="exp-card">

      <div class="exp-card-header">

        <h3 class="exp-role">
          Conference Reviewer
        </h3>

        <span class="exp-date">
          2024
        </span>

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
