---
title: "ECA"
permalink: /eca/
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

/* ===== Author Card: Same as Other Pages ===== */
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

/* ===== ECA Main Content ===== */
.eca-content {
  min-width: 0;
  color: #334155;
  line-height: 1.75;
}

.eca-content * {
  box-sizing: border-box;
}

.eca-header {
  margin-bottom: 30px;
}

.eca-header h1 {
  margin: 0 0 10px;
  font-size: clamp(1.8rem, 3vw, 2.35rem);
  font-weight: 800;
  letter-spacing: -.04em;
  color: #0f172a;
}

.eca-header p {
  margin: 0;
  max-width: 750px;
  color: #64748b;
  font-size: .98rem;
}

/* ===== Section Heading ===== */
.eca-section {
  margin-bottom: 38px;
}

.eca-section-heading {
  display: flex;
  align-items: center;
  gap: 12px;
  margin: 0 0 18px;
}

.eca-section-icon {
  width: 39px;
  height: 39px;
  border-radius: 11px;
  background: #eff6ff;
  color: #2563eb;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-shrink: 0;
  font-size: 1rem;
}

.eca-section-heading h2 {
  margin: 0;
  font-size: 1.3rem;
  font-weight: 750;
  color: #0f172a;
  letter-spacing: -.02em;
}

/* ===== Activity Card ===== */
.eca-card {
  background: #fff;
  border: 1px solid #e2e8f0;
  border-radius: 15px;
  padding: 23px;
  margin-bottom: 16px;
  transition:
    box-shadow .22s ease,
    border-color .22s ease,
    transform .22s ease;
}

.eca-card:hover {
  border-color: #bfdbfe;
  box-shadow: 0 8px 26px rgba(15,23,42,.06);
  transform: translateY(-2px);
}

.eca-card-top {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  flex-wrap: wrap;
  gap: 12px;
  margin-bottom: 13px;
}

.eca-org {
  display: flex;
  align-items: flex-start;
  gap: 13px;
  min-width: 0;
  flex: 1;
}

.eca-org-icon {
  width: 44px;
  height: 44px;
  border: 1px solid #dbeafe;
  background: #f0f7ff;
  color: #2563eb;
  border-radius: 12px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 1.2rem;
  flex-shrink: 0;
}

.eca-org-title {
  margin: 0 0 3px;
  color: #0f172a;
  font-size: 1.1rem;
  font-weight: 750;
  line-height: 1.4;
}

.eca-org-subtitle {
  color: #64748b;
  font-size: .88rem;
  margin: 0;
}

.eca-card p {
  margin: 12px 0 0;
  font-size: .94rem;
  line-height: 1.8;
}

.eca-card strong {
  color: #1e293b;
}

/* ===== Role Badges ===== */
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
  border-radius: 7px;
  padding: 6px 10px;
  font-size: .8rem;
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

/* ===== Highlights ===== */
.eca-highlights {
  display: flex;
  gap: 8px;
  flex-wrap: wrap;
  margin-top: 16px;
}

.eca-highlight {
  font-size: .76rem;
  font-weight: 550;
  color: #475569;
  padding: 5px 10px;
  background: #f8fafc;
  border: 1px solid #edf2f7;
  border-radius: 999px;
}

/* ===== Sports Grid ===== */
.eca-sports-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 12px;
  margin: 19px 0;
}

.eca-sport {
  border: 1px solid #e2e8f0;
  background: #fafcff;
  border-radius: 12px;
  text-align: center;
  padding: 20px 10px;
  transition: background .2s, border-color .2s;
}

.eca-sport:hover {
  background: #eff6ff;
  border-color: #bfdbfe;
}

.eca-sport-icon {
  font-size: 1.45rem;
  color: #2563eb;
  margin-bottom: 10px;
}

.eca-sport-name {
  font-size: .94rem;
  font-weight: 700;
  color: #1e293b;
}

.eca-sport-desc {
  color: #64748b;
  font-size: .76rem;
  margin-top: 4px;
}

/* ===== Small Screens ===== */
@media (max-width: 650px) {
  .eca-card {
    padding: 17px;
  }

  .eca-sports-grid {
    grid-template-columns: 1fr;
  }

  .eca-sport {
    padding: 14px;
  }

  .eca-header h1 {
    font-size: 1.7rem;
  }

  .eca-section-heading h2 {
    font-size: 1.16rem;
  }
}
</style>

<div class="edu-layout">

  <!-- ================================= -->
  <!-- LEFT: AUTHOR PROFILE              -->
  <!-- ================================= -->

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
          href="https://www.linkedin.com/in/showmiksingha/"
          target="_blank"
          rel="noopener noreferrer"
        >
          <i class="fab fa-fw fa-linkedin"></i>
          LinkedIn
        </a>
      </li>

    </ul>

  </aside>


  <!-- ================================= -->
  <!-- RIGHT: ECA CONTENT                -->
  <!-- ================================= -->

  <main class="eca-content">

    <header class="eca-header">

      <h1>Extracurricular Activities</h1>

    

    </header>


    <!-- ================================= -->
    <!-- LEADERSHIP AND STUDENT ORGANIZATIONS -->
    <!-- ================================= -->

    <section class="eca-section">

      <div class="eca-section-heading">

        <div class="eca-section-icon">
          <i class="fas fa-users"></i>
        </div>

        <h2>Leadership &amp; Student Organizations</h2>

      </div>


      <!-- EECS GSA -->

      <article class="eca-card">

        <div class="eca-card-top">

          <div class="eca-org">

            <div class="eca-org-icon">
              <i class="fas fa-user-tie"></i>
            </div>

            <div>

              <h3 class="eca-org-title">
                Electrical Engineering and Computer Science Graduate Student Association
                (EECS GSA)
              </h3>

              <p class="eca-org-subtitle">
                University of Missouri–Columbia
              </p>

            </div>

          </div>

        </div>

        <div class="eca-role-list">

          <span class="eca-role current">
            <i class="fas fa-circle-check"></i>
            President · 2026–2027
          </span>

          <span class="eca-role previous">
            <i class="fas fa-bullhorn"></i>
            Director of Communications · 2025–2026
          </span>

        </div>

        <p>
          I currently serve as the
          <strong>President of the EECS GSA</strong> at the University of
          Missouri–Columbia for the 2026–2027 academic year.
          Previously, I served as the
          <strong>Director of Communications</strong>
          during the 2025–2026 academic year.
        </p>

        <p>
          Through these leadership roles, I have been
          involved in fostering graduate student engagement,
          facilitating communication between students and
          the department, supporting student initiatives,
          and promoting academic, professional, and social
          activities within the EECS community.
        </p>

        <div class="eca-highlights">

          <span class="eca-highlight">
            Graduate Student Leadership
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

          <div class="eca-org">

            <div class="eca-org-icon">
              <i class="fas fa-bolt"></i>
            </div>

            <div>

              <h3 class="eca-org-title">
                IEEE SUST Student Branch
              </h3>

              <p class="eca-org-subtitle">
                Shahjalal University of Science
                and Technology, Bangladesh
              </p>

            </div>

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
          <strong>Treasurer of the IEEE SUST Student
          Branch</strong>during my undergraduate studies.
        </p>

        <p>
          My involvement provided opportunities to engage
          in financial management, organizational planning,
          technical activities, and collaboration with
          fellow students. It also helped me develop an
          appreciation for professional networking and
          student-led engineering initiatives.
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

    </section>


    <!-- ================================= -->
    <!-- TECHNICAL CLUBS                  -->
    <!-- ================================= -->

    <section class="eca-section">

      <div class="eca-section-heading">

        <div class="eca-section-icon">
          <i class="fas fa-robot"></i>
        </div>

        <h2>Technical Clubs &amp; Communities</h2>

      </div>


      <!-- ROBOSUST -->

      <article class="eca-card">

        <div class="eca-card-top">

          <div class="eca-org">

            <div class="eca-org-icon">
              <i class="fas fa-microchip"></i>
            </div>

            <div>

              <h3 class="eca-org-title">
                RoboSUST – Robotics Club
              </h3>

              <p class="eca-org-subtitle">
                Shahjalal University of Science
                and Technology, Bangladesh
              </p>

            </div>

          </div>

        </div>

        <div class="eca-role-list">

          <span class="eca-role member">
            <i class="fas fa-user-gear"></i>
            Former Member
          </span>

        </div>

        <p>
          I was a member of
          <strong>RoboSUST</strong>, a student robotics
          club at Shahjalal University of Science and
          Technology.
        </p>

        <p>
          My involvement reflected my interest in robotics,
          engineering innovation, and hands-on technical
          learning. The club offered an environment for
          exchanging ideas, exploring practical engineering
          applications, and collaborating with students
          passionate about technology.
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

    </section>


    <!-- ================================= -->
    <!-- SPORTS                           -->
    <!-- ================================= -->

    <section class="eca-section">

      <div class="eca-section-heading">

        <div class="eca-section-icon">
          <i class="fas fa-futbol"></i>
        </div>

        <h2>Sports &amp; Recreation</h2>

      </div>

      <article class="eca-card">

        <p>
          Sports have always been an important part of my
          extracurricular activities. During my undergraduate
          studies at SUST, I was involved in
          <strong>handball</strong> and participated in
          interdepartmental sports tournaments.
        </p>

        <p>
          Currently, I enjoy playing
          <strong>pickleball and soccer at Mizzou</strong>,
          which helps me stay physically active, maintain
          a healthy work-life balance, and connect with
          the university community.
        </p>


        <div class="eca-sports-grid">

          <!-- HANDBALL -->

          <div class="eca-sport">

            <div class="eca-sport-icon">
              <i class="fas fa-hand-fist"></i>
            </div>

            <div class="eca-sport-name">
              Handball
            </div>

            <div class="eca-sport-desc">
              SUST · Interdepartmental
              Tournaments
            </div>

          </div>


          <!-- PICKLEBALL -->

          <div class="eca-sport">

            <div class="eca-sport-icon">
              <i class="fas fa-table-tennis-paddle-ball"></i>
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

        <p>
          I value team sports as a way to maintain balance
          outside academic and research activities while
          developing
          <strong>
            teamwork, discipline, communication,
            and camaraderie.
          </strong>
        </p>

      </article>

    </section>

  </main>

</div>

</div>
