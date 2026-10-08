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
         FEATURED RECOGNITIONS
    ====================================== -->

    <h2 class="awards-heading">
      <i class="fas fa-star"></i>
      Featured Recognitions
    </h2>

    <div class="featured-grid">

      <!-- Featured 1 -->
      <div class="featured-card">

        <div class="featured-header">
          <div class="featured-icon">
            <i class="fas fa-trophy"></i>
          </div>
          <span class="featured-date">April 2026</span>
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

      <!-- Featured 2 -->
      <div class="featured-card">

        <div class="featured-header">
          <div class="featured-icon">
            <i class="fas fa-medal"></i>
          </div>
          <span class="featured-date">May 2026</span>
        </div>

        <div class="featured-title">
          Outstanding Ph.D. Student and Teaching Assistant Award
        </div>

        <div class="featured-org">
          Department of Electrical Engineering and Computer Science<br>
          University of Missouri
        </div>

        <div class="featured-description">
          Recognition for achievements in doctoral
          studies and undergraduate teaching.
        </div>

      </div>

      <!-- Featured 3 -->
      <div class="featured-card">

        <div class="featured-header">
          <div class="featured-icon">
            <i class="fas fa-graduation-cap"></i>
          </div>
          <span class="featured-date">May 2026</span>
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

      <!-- May 2026: Dean's Fellowship -->
      <div class="award-card">
        <div class="award-icon green">
          <i class="fas fa-graduation-cap"></i>
        </div>

        <div class="award-details">
          <div class="award-title">
            Dean's Summer Retention Fellowship
          </div>

          <div class="award-organization">
            College of Engineering, University of Missouri
          </div>

          <div class="award-description">
            Received fellowship support for continued
            doctoral research during Summer 2026.
          </div>

          <div class="award-labels">
            <span class="award-tag green">Graduate Fellowship</span>
            <span class="award-tag date">May 2026</span>
          </div>
        </div>
      </div>

      <!-- May 2026: Outstanding Student and TA -->
      <div class="award-card">
        <div class="award-icon gold">
          <i class="fas fa-medal"></i>
        </div>

        <div class="award-details">
          <div class="award-title">
            Outstanding Ph.D. Student and Teaching Assistant Award
          </div>

          <div class="award-organization">
            Department of Electrical Engineering and Computer Science,
            University of Missouri
          </div>

          <div class="award-labels">
            <span class="award-tag gold">Research & Teaching</span>
            <span class="award-tag date">May 2026</span>
          </div>
        </div>
      </div>

      <!-- April 2026: Outstanding PhD -->
      <div class="award-card">
        <div class="award-icon gold">
          <i class="fas fa-trophy"></i>
        </div>

        <div class="award-details">
          <div class="award-title">
            Outstanding Ph.D. Student Award
          </div>

          <div class="award-organization">
            College of Engineering, University of Missouri
          </div>

          <div class="award-labels">
            <span class="award-tag gold">Academic Excellence</span>
            <span class="award-tag date">April 2026</span>
          </div>
        </div>
      </div>

      <!-- April 2026: Mentor Nomination -->
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
            <span class="award-tag purple">Mentorship Nomination</span>
            <span class="award-tag date">April 2026</span>
          </div>
        </div>
      </div>

      <!-- ============== 2025 ============== -->
      <div class="timeline-year">
        <h3>2025</h3>
      </div>

      <!-- August 2025: Travel -->
      <div class="award-card">
        <div class="award-icon green">
          <i class="fas fa-plane"></i>
        </div>

        <div class="award-details">
          <div class="award-title">
            Travel Fellowship Award
          </div>

          <div class="award-organization">
            Department of Electrical Engineering and Computer Science,
            University of Missouri
          </div>

          <div class="award-labels">
            <span class="award-tag green">Travel Fellowship</span>
            <span class="award-tag date">August 2025</span>
          </div>
        </div>
      </div>

      <!-- April 2025: RCAF -->
      <div class="award-card">
        <div class="award-icon gold">
          <i class="fas fa-award"></i>
        </div>

        <div class="award-details">
          <div class="award-title">
            2nd Place & People's Choice Award
          </div>

          <div class="award-organization">
            41st Research and Creative Activities Forum (RCAF)
            Poster Competition, University of Missouri
          </div>

          <div class="label">
          </div>

          <div class="award-labels">
            <span class="award-tag gold">Research Presentation</span>
            <span class="award-tag date">April 2025</span>
          </div>
        </div>
      </div>

      <!-- March 2025: CMOC -->
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
            <span class="award-tag gold">Research Excellence</span>
            <span class="award-tag date">March 2025</span>
          </div>
        </div>
      </div>

      <!-- ============== 2024 ============== -->
      <div class="timeline-year">
        <h3>2024</h3>
      </div>

      <!-- August 2024: Travel -->
      <div class="award-card">
        <div class="award-icon green">
          <i class="fas fa-plane"></i>
        </div>

        <div class="award-details">
          <div class="award-title">
            Travel Fellowship Award
          </div>

          <div class="award-organization">
            Department of Electrical Engineering and Computer Science,
            University of Missouri
          </div>

          <div class="award-labels">
            <span class="award-tag green">Travel Fellowship</span>
            <span class="award-tag date">August 2024</span>
          </div>
        </div>
      </div>

      <!-- March 2024: CMOC -->
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
            <span class="award-tag gold">Research Presentation</span>
            <span class="award-tag date">March 2024</span>
          </div>
        </div>
      </div>

      <!-- ============== 2019 ============== -->
      <div class="timeline-year">
        <h3>2019</h3>
      </div>

      <!-- October 2019: ICE4CT -->
      <div class="award-card">
        <div class="award-icon gold">
          <i class="fas fa-trophy"></i>
        </div>

        <div class="award-details">
          <div class="award-title">
            Best Paper Award
          </div>

          <div class="award-organization">
            First International Conference on Emerging Electrical
            Energy, Electronics and Computing Technologies (ICE4CT)
          </div>

          <div class="award-labels">
            <span class="award-tag gold">Best Paper</span>
            <span class="award-tag date">October 2019</span>
          </div>
        </div>
      </div>

      <!-- ============== 2018 ============== -->
      <div class="timeline-year">
        <h3>2018</h3>
      </div>

      <!-- February 2018: BSc Honours -->
      <div class="award-card">
        <div class="award-icon purple">
          <i class="fas fa-graduation-cap"></i>
        </div>

        <div class="award-details">
          <div class="award-title">
            B.Sc. (Engg.) Degree with Honours
          </div>

          <div class="award-organization">
            Department of Electrical and Electronic Engineering,
            Shahjalal University of Science and Technology
          </div>

          <div class="award-description">
            Graduated with Honours, achieving a CGPA
            of 3.93/4.00 and securing first position
            in the class.
          </div>

          <div class="award-labels">
            <span class="award-tag purple">Academic Distinction</span>
            <span class="award-tag date">February 2018</span>
          </div>
        </div>
      </div>

    </div>

  </main>

</div>
</div>
