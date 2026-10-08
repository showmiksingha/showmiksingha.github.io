---
title: "Experiences"
permalink: /experiences/
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

/* ===== Main Content ===== */
.awards-content {
  min-width: 0;
  color: #242424;
}

.awards-content h1 {
  font-size: 2rem;
  margin: 0 0 14px;
  padding-bottom: 12px;
  border-bottom: 2px solid #e5e7eb;
}

.awards-intro {
  font-size: 0.96rem;
  color: #555;
  line-height: 1.75;
  margin-bottom: 25px;
}

/* ===== Statistics ===== */
.awards-stats {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 12px;
  margin: 20px 0 32px;
}

.awards-stat {
  border: 1px solid #e5e7eb;
  border-radius: 10px;
  padding: 15px;
  text-align: center;
  background: #fafafa;
}

.awards-stat strong {
  display: block;
  font-size: 1.65rem;
  font-weight: 800;
  color: #2563eb;
}

.awards-stat span {
  font-size: 0.83rem;
  color: #555;
}

/* ===== Section Titles ===== */
.awards-heading {
  font-size: 1.35rem;
  margin: 36px 0 18px;
  padding-bottom: 8px;
  border-bottom: 1px solid #e5e7eb;
}

.awards-heading i {
  color: #2563eb;
  margin-right: 9px;
}

/* ===== Featured Awards ===== */
.featured-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 15px;
}

.featured-card {
  position: relative;
  border: 1px solid #f0d99b;
  border-radius: 14px;
  padding: 22px;
  background: linear-gradient(
    135deg,
    #fffbeb 0%,
    #ffffff 85%
  );
  overflow: hidden;
  transition: transform 0.25s, box-shadow 0.25s;
}

.featured-card:first-child {
  grid-column: 1 / -1;
}

.featured-card::before {
  content: "";
  position: absolute;
  left: 0;
  top: 0;
  bottom: 0;
  width: 4px;
  background: #d97706;
}

.featured-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 24px rgba(0,0,0,0.07);
}

.featured-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 12px;
  margin-bottom: 15px;
}

.featured-icon {
  width: 48px;
  height: 48px;
  border-radius: 12px;
  background: #fef3c7;
  color: #b45309;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.3rem;
}

.featured-date {
  font-size: 0.75rem;
  font-weight: 700;
  color: #92400e;
  background: #fef3c7;
  padding: 5px 11px;
  border-radius: 20px;
  white-space: nowrap;
}

.featured-title {
  font-size: 1.05rem;
  font-weight: 750;
  color: #1f2937;
  line-height: 1.5;
  margin-bottom: 8px;
}

.featured-org {
  font-size: 0.87rem;
  color: #475569;
  line-height: 1.65;
}

.featured-description {
  font-size: 0.85rem;
  line-height: 1.7;
  color: #64748b;
  margin-top: 10px;
}

/* ===== Timeline ===== */
.awards-timeline {
  position: relative;
  margin-top: 22px;
  padding-left: 28px;
  border-left: 2px solid #e2e8f0;
}

.timeline-year {
  position: relative;
  margin: 30px 0 17px;
}

.timeline-year:first-child {
  margin-top: 0;
}

.timeline-year::before {
  content: "";
  position: absolute;
  left: -36px;
  top: 5px;
  width: 12px;
  height: 12px;
  background: #2563eb;
  border: 3px solid #fff;
  border-radius: 50%;
  box-shadow: 0 0 0 2px #bfdbfe;
}

.timeline-year h3 {
  font-size: 1.2rem;
  font-weight: 800;
  color: #1e293b;
  margin: 0;
}

/* ===== Award Cards ===== */
.award-card {
  display: flex;
  gap: 15px;
  padding: 19px;
  margin-bottom: 14px;
  border: 1px solid #e5e7eb;
  border-radius: 12px;
  background: #fff;
  transition: transform 0.2s,
              border-color 0.2s,
              box-shadow 0.2s;
}

.award-card:hover {
  transform: translateX(4px);
  border-color: #bfdbfe;
  box-shadow: 0 5px 18px rgba(0,0,0,0.055);
}

.award-icon {
  flex-shrink: 0;
  width: 44px;
  height: 44px;
  border-radius: 11px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.15rem;
}

.award-icon.gold {
  background: #fef3c7;
  color: #b45309;
}

.award-icon.blue {
  background: #dbeafe;
  color: #2563eb;
}

.award-icon.green {
  background: #dcfce7;
  color: #15803d;
}

.award-icon.purple {
  background: #f3e8ff;
  color: #9333ea;
}

.award-details {
  flex: 1;
  min-width: 0;
}

.award-title {
  font-size: 0.99rem;
  font-weight: 750;
  color: #1e293b;
  line-height: 1.5;
  margin: 0 0 6px;
}

.award-organization {
  font-size: 0.87rem;
  color: #475569;
  line-height: 1.65;
}

.award-description {
  color: #64748b;
  font-size: 0.85rem;
  line-height: 1.7;
  margin-top: 8px;
}

/* ===== Labels ===== */
.award-labels {
  display: flex;
  flex-wrap: wrap;
  gap: 7px;
  margin-top: 11px;
}

.award-tag {
  display: inline-block;
  padding: 4px 10px;
  border-radius: 20px;
  background: #eff6ff;
  color: #1d4ed8;
  font-size: 0.73rem;
  font-weight: 600;
}

.award-tag.gold {
  background: #fef3c7;
  color: #92400e;
}

.award-tag.green {
  background: #dcfce7;
  color: #166534;
}

.award-tag.purple {
  background: #f3e8ff;
  color: #7e22ce;
}

.award-tag.date {
  background: #f1f5f9;
  color: #475569;
}

/* ===== Responsive ===== */
@media (max-width: 700px) {
  .featured-grid {
    grid-template-columns: 1fr;
  }

  .featured-card:first-child {
    grid-column: auto;
  }
}

@media (max-width: 600px) {
  .awards-content h1 {
    font-size: 1.65rem;
  }

  .awards-stats {
    gap: 7px;
  }

  .awards-stat {
    padding: 12px 5px;
  }

  .awards-stat strong {
    font-size: 1.3rem;
  }

  .awards-stat span {
    font-size: 0.72rem;
  }

  .awards-timeline {
    padding-left: 20px;
  }

  .timeline-year::before {
    left: -28px;
  }

  .award-card {
    padding: 14px;
    gap: 11px;
  }

  .award-icon {
    width: 38px;
    height: 38px;
  }

  .featured-card {
    padding: 18px;
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
     RIGHT: EXPERIENCE
===================================== -->

<main class="exp-content">
<h1>Professional Experiences</h1>
<!-- =====================================
     HERO SECTION
===================================== -->



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
    <h2>Research Experiences</h2>
  </div>



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
            Evaluated technical submissions
            and provided constructive
            feedback to support
            the peer-review process.
          </li>

        </ul>
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
            Contributed to the independent
            technical assessment of
            conference manuscripts,
            providing constructive
            reviewer feedback.
          </li>

        </ul>
      </div>

    

    </article>

  </div>

</section>


</main>
</div>
</div>
