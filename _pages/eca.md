---
title: "ECA"
permalink: /eca/
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
   LEFT AUTHOR PROFILE
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
  margin: 0 auto 10px;
}

.author-name {
  text-align: center;
  font-weight: 800;
  margin: 0;
}

.author-bio {
  text-align: center;
  color: #6b7280;
  margin: 6px 0 12px;
  font-size: .95rem;
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
  display: inline-flex;
  gap: 8px;
  align-items: center;
  text-decoration: none;
}

/* ==========================================
   MAIN CONTENT
========================================== */

.eca-content {
  min-width: 0;
  color: #334155;
  line-height: 1.75;
}

.eca-content * {
  box-sizing: border-box;
}

.eca-header {
  margin-bottom: 27px;
}

.eca-header h1 {
  margin: 0 0 10px;
  font-size: clamp(1.8rem, 3vw, 2.35rem);
  font-weight: 800;
  letter-spacing: -.035em;
  color: #0f172a;
}

.eca-intro {
  color: #64748b;
  font-size: .96rem;
  line-height: 1.75;
  margin: 0;
  max-width: 800px;
}

/* ==========================================
   SECTION HEADINGS
========================================== */

.eca-section {
  margin-bottom: 35px;
}

.eca-section-heading {
  display: flex;
  align-items: center;
  gap: 12px;
  margin-bottom: 18px;
}

.eca-section-icon {
  width: 40px;
  height: 40px;
  border-radius: 11px;
  background: #eff6ff;
  color: #2563eb;

  display: flex;
  justify-content: center;
  align-items: center;
  flex-shrink: 0;
}

.eca-section-heading h2 {
  margin: 0;
  color: #0f172a;
  font-size: 1.3rem;
  font-weight: 750;
  letter-spacing: -.02em;
}

/* ==========================================
   BENTO CARD GRID
========================================== */

.eca-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 16px;
}

.eca-card {
  min-width: 0;
  padding: 23px;
  background: #fff;
  border: 1px solid #e2e8f0;
  border-radius: 15px;

  transition:
    transform .25s ease,
    box-shadow .25s ease,
    border-color .25s ease;
}

.eca-card:hover {
  transform: translateY(-3px);
  border-color: #bfdbfe;
  box-shadow: 0 10px 28px rgba(15,23,42,.065);
}

.eca-card.featured {
  grid-column: 1 / -1;
  background:
    linear-gradient(
      135deg,
      #ffffff 0%,
      #ffffff 65%,
      #f4f8ff 100%
    );
}

.eca-card-top {
  display: flex;
  align-items: flex-start;
  gap: 13px;
  margin-bottom: 14px;
}

.eca-org-icon {
  width: 46px;
  height: 46px;
  border-radius: 12px;
  background: #eff6ff;
  border: 1px solid #dbeafe;
  color: #2563eb;

  display: flex;
  justify-content: center;
  align-items: center;

  font-size: 1.15rem;
  flex-shrink: 0;
}

.eca-org-title {
  margin: 0 0 4px;
  color: #0f172a;
  font-weight: 750;
  font-size: 1.07rem;
  line-height: 1.45;
}

.eca-org-subtitle {
  margin: 0;
  color: #64748b;
  font-size: .84rem;
  line-height: 1.5;
}

.eca-card p {
  color: #475569;
  font-size: .91rem;
  line-height: 1.75;
  margin: 12px 0 0;
}

.eca-card strong {
  color: #1e293b;
}

/* ==========================================
   ROLE BADGES
========================================== */

.eca-role-list {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin: 14px 0 16px;
}

.eca-role {
  display: inline-flex;
  align-items: center;
  gap: 7px;
  padding: 7px 12px;

  border-radius: 999px;
  font-size: .78rem;
  line-height: 1.4;
  font-weight: 650;
}

.eca-role.current {
  color: #166534;
  background: #f0fdf4;
  border: 1px solid #bbf7d0;
}

.eca-role.previous {
  color: #475569;
  background: #f8fafc;
  border: 1px solid #e2e8f0;
}

.eca-role.member {
  color: #1d4ed8;
  background: #eff6ff;
  border: 1px solid #dbeafe;
}

/* ==========================================
   PROJECT-STYLE BLUE HOVER PILLS
========================================== */

.eca-highlights {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 19px;
}

.eca-highlight {
  display: inline-flex;
  align-items: center;

  padding: 9px 15px;
  background: #f8fafc;
  color: #334155;

  border: 1px solid #e2e8f0;
  border-radius: 999px;

  font-size: .88rem;
  font-weight: 500;
  line-height: 1.4;
  cursor: default;

  transition:
    background-color .25s ease,
    color .25s ease,
    border-color .25s ease,
    transform .25s ease,
    box-shadow .25s ease;
}

.eca-highlight:hover {
  background: #2563eb;
  color: #fff;
  border-color: #2563eb;

  transform: translateY(-2px);
  box-shadow: 0 4px 12px rgba(37,99,235,.18);
}

/* ==========================================
   SPORTS GRID
========================================== */

.eca-sports-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 15px;
  margin-top: 18px;
}

.eca-sport {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;

  text-align: center;
  padding: 27px 14px;

  min-height: 160px;
  background: #fff;
  border: 1px solid #e2e8f0;
  border-radius: 15px;

  transition:
    transform .25s ease,
    background-color .25s ease,
    border-color .25s ease,
    box-shadow .25s ease;
}

.eca-sport:hover {
  transform: translateY(-3px);
  background: #f8fbff;
  border-color: #bfdbfe;
  box-shadow: 0 8px 24px rgba(15,23,42,.055);
}

.eca-sport-icon {
  height: 48px;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 13px;
  color: #2563eb;
  font-size: 2rem;
}

.eca-sport-icon svg {
  width: 46px;
  height: 46px;
  display: block;
}

.eca-sport-name {
  font-size: 1rem;
  font-weight: 750;
  color: #0f172a;
}

.eca-sport-desc {
  margin-top: 5px;
  font-size: .79rem;
  line-height: 1.5;
  color: #64748b;
}

.eca-sports-text {
  padding: 19px 23px;
  background: #f8fafc;
  border: 1px solid #e2e8f0;
  border-radius: 13px;
  margin-top: 16px;
}

.eca-sports-text p {
  color: #475569;
  font-size: .91rem;
  line-height: 1.8;
  margin: 0;
}

.eca-sports-text p + p {
  margin-top: 10px;
}

/* ==========================================
   RESPONSIVE
========================================== */

@media (max-width: 700px) {
  .eca-grid {
    grid-template-columns: 1fr;
  }

  .eca-card.featured {
    grid-column: auto;
  }

  .eca-sports-grid {
    grid-template-columns: 1fr;
  }

  .eca-card {
    padding: 18px;
  }

  .eca-sport {
    min-height: 120px;
    padding: 20px 14px;
  }

  .eca-header h1 {
    font-size: 1.75rem;
  }

  .eca-section-heading h2 {
    font-size: 1.15rem;
  }

  .eca-highlight {
    font-size: .82rem;
    padding: 8px 13px;
  }
}

@media (prefers-reduced-motion: reduce) {
  .eca-card,
  .eca-highlight,
  .eca-sport {
    transition: none;
  }
}
</style>


<div class="edu-layout">

<!-- ==========================================
     LEFT AUTHOR PROFILE
========================================== -->

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
        Email
      </a>
    </li>

    <li>
      <a
        href="https://github.com/showmiksingha"
        target="_blank"
        rel="noopener noreferrer"
      >
        <i class="fab fa-fw fa-github"></i>
        GitHub
      </a>
    </li>

    <li>
      <a
        href="https://www.linkedin.com/in/showmik-singha-293967147"
        target="_blank"
        rel="noopener noreferrer"
      >
        <i class="fab fa-fw fa-linkedin"></i>
        LinkedIn
      </a>
    </li>

  </ul>

</aside>


<!-- ==========================================
     RIGHT MAIN CONTENT
========================================== -->

<main class="eca-content">

<header class="eca-header">
  <h1>Extracurricular Activities</h1>


</header>


<!-- ==========================================
     LEADERSHIP AND STUDENT ORGANIZATIONS
========================================== -->

<section class="eca-section">

  <div class="eca-section-heading">
    <div class="eca-section-icon">
      <i class="fas fa-users"></i>
    </div>
    <h2>Leadership &amp; Student Organizations</h2>
  </div>


  <div class="eca-grid">

    <!-- EECS GSA FEATURED CARD -->

    <article class="eca-card featured">

      <div class="eca-card-top">

        <div class="eca-org-icon">
          <i class="fas fa-user-tie"></i>
        </div>

        <div>
          <h3 class="eca-org-title">
            Electrical Engineering and Computer Science
            Graduate Student Association (EECS GSA)
          </h3>

          <p class="eca-org-subtitle">
            University of Missouri–Columbia, USA
          </p>
        </div>

      </div>

      <div class="eca-role-list">

        <span class="eca-role current">
          <i class="fas fa-check-circle"></i>
          President · 2026–2027
        </span>

        <span class="eca-role previous">
          <i class="fas fa-bullhorn"></i>
          Director of Communications · 2025–2026
        </span>

      </div>

      <p>
        I currently serve as the
        <strong>President of the EECS GSA</strong>
        for the 2026–2027 academic year, following my
        previous role as
        <strong>Director of Communications</strong>
        during 2025–2026.
      </p>

      <p>
        Through these leadership roles, I support graduate
        student engagement, communication between students
        and the department, and academic, professional, and
        social initiatives within the EECS community.
      </p>

      <div class="eca-highlights">

        <span class="eca-highlight">
          Student Leadership
        </span>

        <span class="eca-highlight">
          Community Engagement
        </span>

        <span class="eca-highlight">
          Communication
        </span>

        <span class="eca-highlight">
          Event Coordination
        </span>

      </div>

    </article>


    <!-- IEEE SUST -->

    <article class="eca-card">

      <div class="eca-card-top">

        <div class="eca-org-icon">
          <i class="fas fa-bolt"></i>
        </div>

        <div>

          <h3 class="eca-org-title">
            IEEE SUST Student Branch
          </h3>

          <p class="eca-org-subtitle">
            Shahjalal University of Science and Technology,
            Bangladesh
          </p>

        </div>

      </div>

      <div class="eca-role-list">

        <span class="eca-role previous">
          <i class="fas fa-wallet"></i>
          Former Treasurer
        </span>

      </div>

      <p>
        I previously served as the
        <strong>Treasurer of the IEEE SUST Student Branch</strong>
        during my undergraduate studies. This role provided
        experience in financial management, organizational
        planning, and collaboration on student-led technical
        and professional activities.
      </p>

      <div class="eca-highlights">

        <span class="eca-highlight">
          Financial Management
        </span>

        <span class="eca-highlight">
          Organizational Planning
        </span>

        <span class="eca-highlight">
          Professional Networking
        </span>

      </div>

    </article>


    <!-- ROBOSUST -->

    <article class="eca-card">

      <div class="eca-card-top">

        <div class="eca-org-icon">
          <i class="fas fa-robot"></i>
        </div>

        <div>

          <h3 class="eca-org-title">
            RoboSUST – Robotics Club
          </h3>

          <p class="eca-org-subtitle">
            Shahjalal University of Science and Technology,
            Bangladesh
          </p>

        </div>

      </div>

      <div class="eca-role-list">

        <span class="eca-role member">
          <i class="fas fa-user"></i>
          Former Member
        </span>

      </div>

      <p>
        I was a member of <strong>RoboSUST</strong>,
        a student robotics club at SUST. My involvement
        reflected my interest in engineering innovation,
        hands-on technical learning, and collaboration
        with students passionate about robotics and
        emerging technologies.
      </p>

      <div class="eca-highlights">

        <span class="eca-highlight">
          Robotics
        </span>

        <span class="eca-highlight">
          Engineering Innovation
        </span>

        <span class="eca-highlight">
          Collaborative Learning
        </span>

      </div>

    </article>

  </div>

</section>


<!-- ==========================================
     SPORTS AND RECREATION
========================================== -->

<section class="eca-section">

  <div class="eca-section-heading">

    <div class="eca-section-icon">
      <i class="fas fa-futbol"></i>
    </div>

    <h2>Sports &amp; Recreation</h2>

  </div>


  <div class="eca-sports-grid">

    <!-- HANDBALL -->

    <div class="eca-sport">

      <div class="eca-sport-icon">
        <i class="fas fa-volleyball-ball"></i>
      </div>

      <div class="eca-sport-name">
        Handball
      </div>

      <div class="eca-sport-desc">
        SUST · Interdepartmental Tournaments
      </div>

    </div>


    <!-- PICKLEBALL WITH CUSTOM CROSSED PADDLES SVG -->

    <div class="eca-sport">

      <div class="eca-sport-icon">

        <svg
          viewBox="0 0 64 64"
          xmlns="http://www.w3.org/2000/svg"
          role="img"
          aria-label="Two crossed pickleball paddles and a pickleball"
        >

          <!-- Left paddle handle -->
          <path
            d="M36 41 L47 56"
            fill="none"
            stroke="currentColor"
            stroke-width="5"
            stroke-linecap="round"
          />

          <!-- Right paddle handle -->
          <path
            d="M28 41 L17 56"
            fill="none"
            stroke="currentColor"
            stroke-width="5"
            stroke-linecap="round"
          />

          <!-- Left paddle face -->
          <g transform="rotate(-32 24 25)">
            <rect
              x="14"
              y="10"
              width="20"
              height="30"
              rx="9"
              fill="#dbeafe"
              stroke="currentColor"
              stroke-width="2.5"
            />
            <path
              d="M19 20 H29 M19 27 H29"
              stroke="currentColor"
              stroke-width="1.3"
              opacity=".45"
            />
          </g>

          <!-- Right paddle face -->
          <g transform="rotate(32 40 25)">
            <rect
              x="30"
              y="10"
              width="20"
              height="30"
              rx="9"
              fill="#bfdbfe"
              stroke="currentColor"
              stroke-width="2.5"
            />
            <path
              d="M35 20 H45 M35 27 H45"
              stroke="currentColor"
              stroke-width="1.3"
              opacity=".45"
            />
          </g>

          <!-- Pickleball -->
          <circle
            cx="32"
            cy="11"
            r="8"
            fill="#facc15"
            stroke="#ca8a04"
            stroke-width="1.3"
          />

          <!-- Pickleball holes -->
          <g fill="#a16207">
            <circle cx="29" cy="8" r="1.2"/>
            <circle cx="35" cy="9" r="1.2"/>
            <circle cx="31" cy="14" r="1.2"/>
            <circle cx="36" cy="15" r="1"/>
          </g>

        </svg>

      </div>

      <div class="eca-sport-name">
        Pickleball
      </div>

      <div class="eca-sport-desc">
        Mizzou · Recreational
      </div>

    </div>


    <!-- SOCCER -->

    <div class="eca-sport">

      <div class="eca-sport-icon">
        <i class="fas fa-futbol"></i>
      </div>

      <div class="eca-sport-name">
        Soccer
      </div>

      <div class="eca-sport-desc">
        Mizzou · Recreational
      </div>

    </div>

  </div>


  <div class="eca-sports-text">

    <p>
      Sports have always been an important part of
      my extracurricular activities. During my
      undergraduate studies at SUST, I played
      <strong>handball</strong> and participated in
      interdepartmental tournaments. Currently, I enjoy
      playing <strong>pickleball and soccer at Mizzou</strong>.
    </p>

    <p>
      I value team sports as a way to maintain balance
      outside academic and research activities while
      developing teamwork, discipline, communication,
      and camaraderie.
    </p>

  </div>

</section>


</main>

</div>

</div>
