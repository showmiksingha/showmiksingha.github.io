---
title: "Awards"
permalink: /awards/
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

/* ============================================
   APPLE-STYLE FEATURED RECOGNITIONS BENTO GRID
============================================ */

.featured-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  grid-template-areas:
    "hero hero"
    "teaching fellowship";
  gap: 16px;
  margin-top: 20px;
}

/* General Bento Card */
.featured-card {
  position: relative;
  isolation: isolate;
  display: flex;
  flex-direction: column;
  min-width: 0;
  min-height: 248px;
  padding: clamp(22px, 3vw, 32px);
  border: 1px solid #e5e7eb;
  border-radius: 22px;
  overflow: hidden;
  background: #f8fafc;

  transition:
    transform 0.28s ease,
    box-shadow 0.28s ease,
    border-color 0.28s ease;
}

/* Hover Effect */
.featured-card:hover {
  transform: translateY(-5px);
  border-color: #bfdbfe;
  box-shadow: 0 16px 34px rgba(30, 64, 175, 0.10);
}

/* Large Featured Card */
.featured-card--hero {
  grid-area: hero;
  min-height: 270px;

  background: linear-gradient(
    125deg,
    #eaf3ff 0%,
    #f5f9ff 60%,
    #ffffff 100%
  );

  border-color: #dbeafe;
}

/* Teaching Card */
.featured-card--teaching {
  grid-area: teaching;

  background: linear-gradient(
    145deg,
    #f8fafc,
    #eef2ff
  );
}

/* Fellowship Card */
.featured-card--fellowship {
  grid-area: fellowship;

  background: linear-gradient(
    145deg,
    #f8fafc,
    #edf9f4
  );
}

/* Decorative Background Icons */
.featured-watermark {
  position: absolute;
  right: -12px;
  bottom: -16px;
  color: #2563eb;
  opacity: 0.075;
  font-size: clamp(105px, 15vw, 190px);
  line-height: 1;
  pointer-events: none;
  z-index: -1;
}

.featured-card--fellowship .featured-watermark {
  color: #059669;
}

/* Card Header */
.featured-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 12px;
  margin-bottom: 22px;
}

/* Icons */
.featured-icon {
  width: 48px;
  height: 48px;

  display: inline-flex;
  align-items: center;
  justify-content: center;
  flex-shrink: 0;

  border-radius: 15px;
  color: #2563eb;
  background: #dbeafe;
  font-size: 1.25rem;
}

.featured-card--fellowship .featured-icon {
  background: #d1fae5;
  color: #047857;
}

/* Date Badge */
.featured-date {
  display: inline-flex;
  align-items: center;

  border: 1px solid #dbeafe;
  border-radius: 999px;
  padding: 6px 12px;

  background: rgba(255, 255, 255, 0.8);
  color: #334155;

  font-weight: 650;
  font-size: 0.75rem;
  white-space: nowrap;
}

/* Category */
.featured-eyebrow {
  color: #2563eb;
  font-size: 0.76rem;
  font-weight: 800;
  letter-spacing: 0.09em;
  text-transform: uppercase;
  margin-bottom: 10px;
}

.featured-card--fellowship .featured-eyebrow {
  color: #047857;
}

/* Award Title */
.featured-title {
  max-width: 580px;
  margin: 0 0 11px;

  color: #0f172a;
  font-size: clamp(1.12rem, 1.6vw, 1.4rem);
  line-height: 1.35;
  font-weight: 800;
  overflow-wrap: anywhere;
}

.featured-card--hero .featured-title {
  font-size: clamp(1.45rem, 2.5vw, 2rem);
  max-width: 640px;
}

/* Organization */
.featured-org {
  color: #475569;
  font-size: 0.88rem;
  line-height: 1.65;
}

/* Description */
.featured-description {
  color: #64748b;
  font-size: 0.86rem;
  line-height: 1.65;

  margin-top: auto;
  padding-top: 18px;
  max-width: 570px;
}

/* Responsive Bento */
@media (max-width: 700px) {
  .featured-grid {
    grid-template-columns: minmax(0, 1fr);
    grid-template-areas:
      "hero"
      "teaching"
      "fellowship";
  }

  .featured-card {
    min-height: 235px;
  }
}

@media (prefers-reduced-motion: reduce) {
  .featured-card {
    transition: none;
  }

  .featured-card:hover {
    transform: none;
  }
}

/* ============================================
   AWARDS TIMELINE
============================================ */

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

  transition:
    transform 0.2s,
    border-color 0.2s,
    box-shadow 0.2s;
}

.award-card:hover {
  transform: translateX(4px);
  border-color: #bfdbfe;
  box-shadow: 0 5px 18px rgba(0, 0, 0, 0.055);
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
       RIGHT: AWARDS & HONORS
  ====================================== -->

  <main class="awards-content">

    <h1>Awards & Honors</h1>

    <!-- ===== STATISTICS ===== -->
    <div class="awards-stats">

      <div class="awards-stat">
        <strong>11</strong>
        <span>Honors & Recognitions</span>
      </div>

      <div class="awards-stat">
        <strong>3</strong>
        <span>Fellowships</span>
      </div>

      <div class="awards-stat">
        <strong>2018–26</strong>
        <span>Recognition Timeline</span>
      </div>

    </div>

    <!-- =====================================
         APPLE-STYLE FEATURED BENTO GRID
    ====================================== -->

    <h2 class="awards-heading">
      <i class="fas fa-star"></i>
      Featured Recognitions
    </h2>

    <div class="featured-grid">

      <!-- Large Hero Card -->
      <div class="featured-card featured-card--hero">

        <i class="fas fa-trophy featured-watermark"
           aria-hidden="true"></i>

        <div class="featured-header">

          <div class="featured-icon">
            <i class="fas fa-trophy"></i>
          </div>

          <span class="featured-date">
            April 2026
          </span>

        </div>

        <div class="featured-eyebrow">
          Academic Excellence
        </div>

        <div class="featured-title">
          Outstanding Ph.D. Student Award
        </div>

        <div class="featured-org">
          College of Engineering<br>
          University of Missouri
        </div>

        <div class="featured-description">
          Recognized for academic excellence and
          contributions to doctoral research.
        </div>

      </div>

      <!-- Teaching and Research Card -->
      <div class="featured-card featured-card--teaching">

        <i class="fas fa-medal featured-watermark"
           aria-hidden="true"></i>

        <div class="featured-header">

          <div class="featured-icon">
            <i class="fas fa-medal"></i>
          </div>

          <span class="featured-date">
            May 2026
          </span>

        </div>

        <div class="featured-eyebrow">
          Research & Teaching
        </div>

        <div class="featured-title">
          Outstanding Ph.D. Student and Teaching
          Assistant Award
        </div>

        <div class="featured-org">
          Department of Electrical Engineering and
          Computer Science<br>
          University of Missouri
        </div>

        <div class="featured-description">
          Recognition for achievements in doctoral
          studies and undergraduate teaching.
        </div>

      </div>

      <!-- Fellowship Card -->
      <div class="featured-card featured-card--fellowship">

        <i class="fas fa-graduation-cap featured-watermark"
           aria-hidden="true"></i>

        <div class="featured-header">

          <div class="featured-icon">
            <i class="fas fa-graduation-cap"></i>
          </div>

          <span class="featured-date">
            May 2026
          </span>

        </div>

        <div class="featured-eyebrow">
          Graduate Fellowship
        </div>

        <div class="featured-title">
          Dean's Summer Retention Fellowship
        </div>

        <div class="featured-org">
          College of Engineering<br>
          University of Missouri
        </div>

        <div class="featured-description">
          Fellowship supporting continued doctoral
          research during Summer 2026.
        </div>

      </div>

    </div>

    <!-- =====================================
         RECOGNITION TIMELINE
    ====================================== -->

    <h2 class="awards-heading">
      <i class="fas fa-award"></i>
      Recognition Timeline
    </h2>

    <div class="awards-timeline">

      <!-- ============== 2026 ============== -->

      <div class="timeline-year">
        <h3>2026</h3>
      </div>

      <!-- Dean's Summer Retention Fellowship -->
      <div class="award-card">
        <div class="award-icon green">
          <i class="fas fa-graduation-cap"></i>
        </div>

        <div class="award-details">
          <div class="award-title">
            Dean's Summer Retention Fellowship
          </div>

          <div class="award-organization">
            College of Engineering,
            University of Missouri
          </div>

          <div class="award-description">
            Received fellowship support for continued
            doctoral research during Summer 2026.
          </div>

          <div class="award-labels">
            <span class="award-tag green">
              Graduate Fellowship
            </span>
            <span class="award-tag date">
              May 2026
            </span>
          </div>
        </div>
      </div>

      <!-- Outstanding Student and TA -->
      <div class="award-card">
        <div class="award-icon gold">
          <i class="fas fa-medal"></i>
        </div>

        <div class="award-details">
          <div class="award-title">
            Outstanding Ph.D. Student and
            Teaching Assistant Award
          </div>

          <div class="award-organization">
            Department of Electrical Engineering
            and Computer Science,
            University of Missouri
          </div>

          <div class="award-labels">
            <span class="award-tag gold">
              Research & Teaching
            </span>
            <span class="award-tag date">
              May 2026
            </span>
          </div>
        </div>
      </div>

      <!-- Outstanding PhD -->
      <div class="award-card">
        <div class="award-icon gold">
          <i class="fas fa-trophy"></i>
        </div>

        <div class="award-details">
          <div class="award-title">
            Outstanding Ph.D. Student Award
          </div>

          <div class="award-organization">
            College of Engineering,
            University of Missouri
          </div>

          <div class="award-labels">
            <span class="award-tag gold">
              Academic Excellence
            </span>
            <span class="award-tag date">
              April 2026
            </span>
          </div>
        </div>
      </div>

      <!-- Undergraduate Mentor Nomination -->
      <div class="award-card">
        <div class="award-icon purple">
          <i class="fas fa-chalkboard-teacher"></i>
        </div>

        <div class="award-details">
          <div class="award-title">
            Undergraduate Mentor of the Year Nomination
          </div>

          <div class="award-organization">
            University of Missouri
          </div>

          <div class="award-description">
            Nominated for recognition of contributions
            to undergraduate student mentorship,
            guidance, and academic development.
          </div>

          <div class="award-labels">
            <span class="award-tag purple">
              Mentorship Nomination
            </span>
            <span class="award-tag date">
              April 2026
            </span>
          </div>
        </div>
      </div>

      <!-- ============== 2025 ============== -->

      <div class="timeline-year">
        <h3>2025</h3>
      </div>

      <!-- Travel Fellowship 2025 -->
      <div class="award-card">
        <div class="award-icon green">
          <i class="fas fa-plane"></i>
        </div>

        <div class="award-details">
          <div class="award-title">
            Travel Fellowship Award
          </div>

          <div class="award-organization">
            Department of Electrical Engineering
            and Computer Science,
            University of Missouri
          </div>

          <div class="award-labels">
            <span class="award-tag green">
              Travel Fellowship
            </span>
            <span class="award-tag date">
              August 2025
            </span>
          </div>
        </div>
      </div>

      <!-- RCAF 2025 -->
      <div class="award-card">
        <div class="award-icon gold">
          <i class="fas fa-award"></i>
        </div>

        <div class="award-details">
          <div class="award-title">
            2nd Place & People's Choice Award
          </div>

          <div class="award-organization">
            41st Research and Creative Activities
            Forum (RCAF) Poster Competition,
            University of Missouri
          </div>

          <div class="award-labels">
            <span class="award-tag gold">
              Research Presentation
            </span>
            <span class="award-tag date">
              April 2025
            </span>
          </div>
        </div>
      </div>

      <!-- Connecticut Symposium 2025 -->
      <div class="award-card">
        <div class="award-icon gold">
          <i class="fas fa-trophy"></i>
        </div>

        <div class="award-details">
          <div class="award-title">
            Best Oral Paper & Graduate Poster Award
          </div>

          <div class="award-organization">
            33rd Annual Connecticut Symposium on
            Microelectronics & Optoelectronics
          </div>

          <div class="award-labels">
            <span class="award-tag gold">
              Research Excellence
            </span>
            <span class="award-tag date">
              March 2025
            </span>
          </div>
        </div>
      </div>

      <!-- ============== 2024 ============== -->

      <div class="timeline-year">
        <h3>2024</h3>
      </div>

      <!-- Travel Fellowship 2024 -->
      <div class="award-card">
        <div class="award-icon green">
          <i class="fas fa-plane"></i>
        </div>

        <div class="award-details">
          <div class="award-title">
            Travel Fellowship Award
          </div>

          <div class="award-organization">
            Department of Electrical Engineering
            and Computer Science,
            University of Missouri
          </div>

          <div class="award-labels">
            <span class="award-tag green">
              Travel Fellowship
            </span>
            <span class="award-tag date">
              August 2024
            </span>
          </div>
        </div>
      </div>

      <!-- Connecticut Symposium 2024 -->
      <div class="award-card">
        <div class="award-icon gold">
          <i class="fas fa-medal"></i>
        </div>

        <div class="award-details">
          <div class="award-title">
            Best Graduate Poster Award
          </div>

          <div class="award-organization">
            32nd Annual Connecticut Symposium on
            Microelectronics & Optoelectronics
          </div>

          <div class="award-labels">
            <span class="award-tag gold">
              Research Presentation
            </span>
            <span class="award-tag date">
              March 2024
            </span>
          </div>
        </div>
      </div>

      <!-- ============== 2019 ============== -->

      <div class="timeline-year">
        <h3>2019</h3>
      </div>

      <!-- Best Paper ICE4CT -->
      <div class="award-card">
        <div class="award-icon gold">
          <i class="fas fa-trophy"></i>
        </div>

        <div class="award-details">
          <div class="award-title">
            Best Paper Award
          </div>

          <div class="award-organization">
            First International Conference on Emerging
            Electrical Energy, Electronics and Computing
            Technologies (ICE4CT)
          </div>

          <div class="award-labels">
            <span class="award-tag gold">
              Best Paper
            </span>
            <span class="award-tag date">
              October 2019
            </span>
          </div>
        </div>
      </div>

      <!-- ============== 2018 ============== -->

      <div class="timeline-year">
        <h3>2018</h3>
      </div>

      <!-- BSc Degree with Honours -->
      <div class="award-card">
        <div class="award-icon purple">
          <i class="fas fa-graduation-cap"></i>
        </div>

        <div class="award-details">
          <div class="award-title">
            B.Sc. (Engg.) Degree with Honours
          </div>

          <div class="award-organization">
            Department of Electrical and Electronic
            Engineering,
            Shahjalal University of Science and Technology
          </div>

          <div class="award-description">
            Graduated with Honours, achieving a CGPA
            of 3.93/4.00 and securing first position
            in the class.
          </div>

          <div class="award-labels">
            <span class="award-tag purple">
              Academic Distinction
            </span>
            <span class="award-tag date">
              February 2018
            </span>
          </div>
        </div>
      </div>

    </div>

  </main>

</div>
</div>
