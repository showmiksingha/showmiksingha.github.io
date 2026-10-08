---
title: "Experiences"
permalink: /experiences/
layout: default
author_profile: false
classes: wide
---

<div class="wrap">

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
  margin: 0 auto 14px;
  border: 3px solid #f1f5f9;
}

.author-name {
  font-size: 1.35rem;
  font-weight: 800;
  text-align: center;
  margin: 0 0 6px;
  color: #111827;
}

.author-bio {
  font-size: 0.9rem;
  color: #64748b;
  text-align: center;
  margin-bottom: 18px;
  line-height: 1.6;
}

.author-links {
  display: flex;
  flex-direction: column;
  gap: 11px;
}

.author-links a {
  display: flex;
  align-items: center;
  gap: 10px;
  color: #334155;
  font-size: 0.9rem;
  text-decoration: none;
  transition: color 0.2s;
}

.author-links a:hover {
  color: #2563eb;
}

.author-links i {
  width: 18px;
  text-align: center;
  color: #64748b;
}

/* ===== Main Content ===== */
.exp-content {
  min-width: 0;
}

.exp-header {
  margin-bottom: 36px;
}

.exp-header h1 {
  font-size: 2.15rem;
  font-weight: 800;
  color: #0f172a;
  margin: 0 0 12px;
  letter-spacing: -0.6px;
}

.exp-intro {
  color: #64748b;
  font-size: 1rem;
  line-height: 1.8;
  max-width: 760px;
  margin: 0;
}

/* ===== Section Headings ===== */
.exp-section {
  margin-bottom: 44px;
}

.exp-section-title {
  display: flex;
  align-items: center;
  gap: 12px;
  font-size: 1.3rem;
  font-weight: 750;
  color: #0f172a;
  margin: 0 0 26px;
}

.exp-section-title i {
  color: #2563eb;
  font-size: 1.15rem;
}

/* ===== Timeline ===== */
.exp-timeline {
  position: relative;
  padding-left: 29px;
  border-left: 2px solid #e2e8f0;
  margin-left: 9px;
}

/* ===== Experience Cards ===== */
.exp-card {
  position: relative;
  background: #fff;
  border: 1px solid #e5e7eb;
  border-radius: 15px;
  padding: 24px;
  margin-bottom: 24px;
  transition:
    box-shadow 0.25s ease,
    transform 0.25s ease,
    border-color 0.25s ease;
}

.exp-card:hover {
  transform: translateY(-3px);
  border-color: #bfdbfe;
  box-shadow: 0 10px 28px rgba(15,23,42,0.07);
}

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
  top: 29px;
  box-sizing: content-box;
}

.exp-card:last-child {
  margin-bottom: 0;
}

.exp-card-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  flex-wrap: wrap;
  gap: 10px;
  margin-bottom: 10px;
}

.exp-role {
  font-size: 1.12rem;
  font-weight: 750;
  color: #111827;
  margin: 0;
  line-height: 1.45;
}

.exp-date {
  font-size: 0.78rem;
  font-weight: 650;
  color: #2563eb;
  background: #eff6ff;
  border: 1px solid #dbeafe;
  padding: 6px 11px;
  border-radius: 30px;
  white-space: nowrap;
}

.exp-organization {
  font-size: 0.98rem;
  font-weight: 650;
  color: #334155;
  margin-bottom: 6px;
  line-height: 1.6;
}

.exp-location {
  font-size: 0.85rem;
  color: #64748b;
  margin-bottom: 17px;
}

.exp-location i {
  margin-right: 5px;
}

.exp-description {
  font-size: 0.91rem;
  color: #475569;
  line-height: 1.8;
}

.exp-description ul {
  padding-left: 19px;
  margin: 0;
}

.exp-description li {
  margin-bottom: 9px;
  padding-left: 3px;
}

.exp-description li:last-child {
  margin-bottom: 0;
}

.exp-description li::marker {
  color: #3b82f6;
}

/* ===== Skill Tags ===== */
.exp-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 7px;
  margin-top: 18px;
}

.exp-tag {
  display: inline-block;
  font-size: 0.74rem;
  font-weight: 550;
  color: #475569;
  background: #f1f5f9;
  padding: 5px 10px;
  border-radius: 6px;
}

/* ===== Responsive Layout ===== */
@media (max-width: 600px) {
  .exp-header h1 {
    font-size: 1.8rem;
  }

  .exp-timeline {
    padding-left: 21px;
  }

  .exp-card {
    padding: 19px;
  }

  .exp-card::before {
    left: -31px;
  }

  .exp-card-header {
    flex-direction: column;
    align-items: flex-start;
  }
}
</style>

<div class="edu-layout">

  <!-- ================================== -->
  <!-- LEFT: AUTHOR PROFILE -->
  <!-- ================================== -->

  <aside class="author-card">

    <img
      src="/assets/images/profile.JPG"
      alt="Showmik Singha"
      class="author-avatar"
    >

    <h2 class="author-name">
      Showmik Singha
    </h2>

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
         target="_blank"
         rel="noopener noreferrer">
        <i class="fab fa-github"></i>
        GitHub
      </a>

      <a href="https://www.linkedin.com/in/showmiksingha/"
         target="_blank"
         rel="noopener noreferrer">
        <i class="fab fa-linkedin"></i>
        LinkedIn
      </a>

      <a href="https://scholar.google.com/"
         target="_blank"
         rel="noopener noreferrer">
        <i class="fas fa-graduation-cap"></i>
        Google Scholar
      </a>

      <a href="/files/Showmik_Singha_CV.pdf"
         target="_blank"
         rel="noopener noreferrer">
        <i class="fas fa-file-pdf"></i>
        Download CV
      </a>

    </div>

  </aside>

  <!-- ================================== -->
  <!-- RIGHT: EXPERIENCE -->
  <!-- ================================== -->

  <main class="exp-content">

    <header class="exp-header">

      <h1>Professional Experience</h1>

      <p class="exp-intro">
        My professional experience spans semiconductor
        device research, university teaching,
        undergraduate research mentorship, and
        academic peer review. Through these roles,
        I have developed expertise in semiconductor
        device physics, numerical simulation,
        engineering education, scientific communication,
        and student development while contributing
        to collaborative research and professional service.
      </p>

    </header>


    <!-- ================================== -->
    <!-- RESEARCH EXPERIENCE -->
    <!-- ================================== -->

    <section class="exp-section">

      <h2 class="exp-section-title">
        <i class="fas fa-microscope"></i>
        Research Experience
      </h2>

      <div class="exp-timeline">

        <article class="exp-card">

          <div class="exp-card-header">

            <h3 class="exp-role">
              Graduate Research Assistant
            </h3>

            <span class="exp-date">
              Jan 2024 – Present
            </span>

          </div>

          <div class="exp-organization">
            University of Missouri–Columbia
          </div>

          <div class="exp-location">
            <i class="fas fa-map-marker-alt"></i>
            Columbia, Missouri, USA
          </div>

          <div class="exp-description">
            <ul>

              <li>
                Conducting research on the reliability
                and performance of wide-bandgap and
                ultra-wide-bandgap semiconductor devices,
                including GaN HEMTs and
                β-Ga<sub>2</sub>O<sub>3</sub> MOSFETs.
              </li>

              <li>
                Developing physics-based TCAD simulation
                frameworks to investigate single-event
                transient responses under heavy-ion
                irradiation, varying operating conditions,
                and elevated temperatures.
              </li>

              <li>
                Investigating device characteristics,
                electric-field distributions, charge
                collection mechanisms, and
                radiation-induced transient behavior
                using numerical modeling.
              </li>

              <li>
                Developing machine learning-based
                inverse modeling approaches for
                semiconductor device parameter
                extraction and design optimization.
              </li>

              <li>
                Analyzing simulation data, preparing
                technical manuscripts, and presenting
                research findings at international
                conferences and scientific meetings.
              </li>

            </ul>
          </div>

          <div class="exp-tags">
            <span class="exp-tag">TCAD</span>
            <span class="exp-tag">GaN HEMT</span>
            <span class="exp-tag">Ga₂O₃ MOSFET</span>
            <span class="exp-tag">Radiation Effects</span>
            <span class="exp-tag">Machine Learning</span>
            <span class="exp-tag">Python</span>
            <span class="exp-tag">MATLAB</span>
          </div>

        </article>

      </div>

    </section>


    <!-- ================================== -->
    <!-- TEACHING EXPERIENCE -->
    <!-- ================================== -->

    <section class="exp-section">

      <h2 class="exp-section-title">
        <i class="fas fa-chalkboard-teacher"></i>
        Teaching Experience
      </h2>

      <div class="exp-timeline">

        <!-- Graduate Teaching Assistant -->
        <article class="exp-card">

          <div class="exp-card-header">

            <h3 class="exp-role">
              Graduate Teaching Assistant
            </h3>

            <span class="exp-date">
              Jan 2024 – Present
            </span>

          </div>

          <div class="exp-organization">
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
                Supporting undergraduate instruction
                through laboratory supervision,
                office hours, review sessions,
                assignment grading, and individualized
                academic assistance.
              </li>

              <li>
                Guiding students in circuit analysis,
                digital logic design, electrical
                engineering fundamentals, and
                practical laboratory experiments.
              </li>

              <li>
                Improved existing laboratory manuals
                for Circuit Theory I and II to enhance
                clarity, instructional consistency,
                and student learning outcomes.
              </li>

              <li>
                Developed Cadence-based assignment
                manuals for Introduction to Logic
                System Design to support hands-on
                digital circuit design and simulation.
              </li>

              <li>
                Collaborating with course instructors
                to evaluate student performance,
                improve instructional materials,
                and support effective laboratory
                instruction.
              </li>

            </ul>
          </div>

          <div class="exp-tags">
            <span class="exp-tag">Circuit Theory</span>
            <span class="exp-tag">Digital Logic</span>
            <span class="exp-tag">Cadence</span>
            <span class="exp-tag">Lab Instruction</span>
            <span class="exp-tag">Curriculum Development</span>
            <span class="exp-tag">Student Mentorship</span>
          </div>

        </article>


        <!-- Faculty Member SUST -->
        <article class="exp-card">

          <div class="exp-card-header">

            <h3 class="exp-role">
              Faculty Member
            </h3>

            <span class="exp-date">
              Sep 2018 – Aug 2022
            </span>

          </div>

          <div class="exp-organization">
            Department of Electrical and
            Electronic Engineering<br>
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
                Delivered undergraduate engineering
                instruction through lectures,
                tutorials, laboratory sessions,
                and academic assessments.
              </li>

              <li>
                Developed course materials,
                assignments, examinations,
                and laboratory activities to
                strengthen theoretical understanding
                and practical engineering skills.
              </li>

              <li>
                Guided undergraduate students
                in technical problem-solving,
                engineering projects, and
                academic development.
              </li>

              <li>
                Participated in departmental
                academic activities, course
                coordination, and continuous
                improvement of engineering education.
              </li>

              <li>
                Contributed to a collaborative
                learning environment by mentoring
                students and supporting their
                academic and professional growth.
              </li>

            </ul>
          </div>

          <div class="exp-tags">
            <span class="exp-tag">University Teaching</span>
            <span class="exp-tag">Electrical Engineering</span>
            <span class="exp-tag">Laboratory Instruction</span>
            <span class="exp-tag">Academic Mentoring</span>
            <span class="exp-tag">Course Development</span>
          </div>

        </article>

      </div>

    </section>


    <!-- ================================== -->
    <!-- RESEARCH MENTORSHIP -->
    <!-- ================================== -->

    <section class="exp-section">

      <h2 class="exp-section-title">
        <i class="fas fa-user-graduate"></i>
        Research Mentorship
      </h2>

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

          <div class="exp-organization">
            University of Missouri–Columbia
          </div>

          <div class="exp-location">
            <i class="fas fa-map-marker-alt"></i>
            Columbia, Missouri, USA
          </div>

          <div class="exp-description">
            <ul>

              <li>
                Mentored four undergraduate students
                in engineering research, providing
                guidance on research methodology,
                technical analysis, and scientific
                communication.
              </li>

              <li>
                Supported students in developing
                research skills, interpreting
                technical findings, preparing
                conference abstracts, and
                presenting their work.
              </li>

              <li>
                Mentorship activities contributed
                to five conference presentations
                and one additional manuscript
                recently accepted for presentation.
              </li>

              <li>
                Encouraged independent
                problem-solving, collaborative
                research, and professional
                development through technical
                discussions and constructive feedback.
              </li>

            </ul>
          </div>

          <div class="exp-tags">
            <span class="exp-tag">4 Undergraduate Students</span>
            <span class="exp-tag">5 Conference Presentations</span>
            <span class="exp-tag">1 Additional Accepted Manuscript</span>
            <span class="exp-tag">Research Mentorship</span>
          </div>

        </article>

      </div>

    </section>


    <!-- ================================== -->
    <!-- PROFESSIONAL SERVICE -->
    <!-- ================================== -->

    <section class="exp-section">

      <h2 class="exp-section-title">
        <i class="fas fa-clipboard-check"></i>
        Professional Service
      </h2>

      <div class="exp-timeline">

        <!-- 2025 BATS -->
        <article class="exp-card">

          <div class="exp-card-header">

            <h3 class="exp-role">
              Conference Reviewer
            </h3>

            <span class="exp-date">
              2025
            </span>

          </div>

          <div class="exp-organization">
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
                and Sensors (BATS).
              </li>

              <li>
                Evaluated submitted research
                and provided constructive
                feedback to support the
                scientific review process.
              </li>

            </ul>
          </div>

          <div class="exp-tags">
            <span class="exp-tag">Peer Review</span>
            <span class="exp-tag">1 Completed Review</span>
            <span class="exp-tag">Conference Service</span>
          </div>

        </article>


        <!-- 2024 Q-BATS -->
        <article class="exp-card">

          <div class="exp-card-header">

            <h3 class="exp-role">
              Conference Reviewer
            </h3>

            <span class="exp-date">
              2024
            </span>

          </div>

          <div class="exp-organization">
            International Workshop on Quantum
            &amp; Biomedical Applications,
            Technologies, and Sensors (Q-BATS)
          </div>

          <div class="exp-description">
            <ul>

              <li>
                Completed two peer reviews
                for the 2024 International
                Workshop on Quantum &amp;
                Biomedical Applications,
                Technologies, and Sensors
                (Q-BATS).
              </li>

              <li>
                Contributed to the technical
                evaluation of conference
                submissions through independent
                peer review and constructive feedback.
              </li>

            </ul>
          </div>

          <div class="exp-tags">
            <span class="exp-tag">Peer Review</span>
            <span class="exp-tag">2 Completed Reviews</span>
            <span class="exp-tag">Conference Service</span>
          </div>

        </article>

      </div>

    </section>

  </main>

</div>

</div>
