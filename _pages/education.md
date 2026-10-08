---
title: "Education"
permalink: /education/
layout: default
author_profile: false
classes: wide
---

<div class="wrap" markdown="1">

<style>
  /* Page-only layout */
  .edu-layout{
    display: grid;
    grid-template-columns: 260px 1fr;
    gap: 28px;
    align-items: start;
  }
  @media (max-width: 900px){
    .edu-layout{ grid-template-columns: 1fr; }
  }

  /* Author card */
  .author-card{
    position: sticky;
    top: 90px;                /* keeps it visible while scrolling */
    border: 1px solid #e5e7eb;
    border-radius: 14px;
    padding: 16px;
    background: #fff;
  }
  @media (max-width: 900px){
    .author-card{ position: static; }
  }

  .author-avatar{
    width: 110px;
    height: 110px;
    border-radius: 999px;
    object-fit: cover;
    display: block;
    margin: 0 auto 10px auto;
  }
  .author-name{
    text-align: center;
    font-weight: 800;
    margin: 0;
  }
  .author-bio{
    text-align: center;
    color: #6b7280;
    margin: 6px 0 12px 0;
    font-size: 0.95rem;
  }
  .author-links{
    list-style: none;
    padding: 0;
    margin: 0;
  }
  .author-links li{
    margin: 8px 0;
  }
  .author-links a{
    text-decoration: none;
    display: inline-flex;
    gap: 8px;
    align-items: center;
  }
</style>

<div class="edu-layout">

  <!-- LEFT: manual author profile -->
  <aside class="author-card">
    <img class="author-avatar" src="/assets/images/profile.JPG" alt="Showmik Singha">
    <p class="author-name">Showmik Singha</p>
    <p class="author-bio">PhD Candidate, University of Missouri</p>

    <ul class="author-links">
      <li>
        <a href="mailto:ssqk4@umsystem.edu">
          <i class="fas fa-fw fa-envelope"></i>
          <span>Email</span>
        </a>
      </li>
      <li>
        <a href="https://github.com/showmiksingha" target="_blank" rel="noopener">
          <i class="fab fa-fw fa-github"></i>
          <span>GitHub</span>
        </a>
      </li>
      <li>
        <a href="https://www.linkedin.com/in/showmik-singha-293967147" target="_blank" rel="noopener">
          <i class="fab fa-fw fa-linkedin"></i>
          <span>LinkedIn</span>
        </a>
      </li>
    </ul>
  </aside>

  <!-- RIGHT: your existing content -->
  <main>
<div class="wrap" markdown="1">

## <i class="fas fa-graduation-cap"></i> Education

<div class="edu-timeline">

  <!-- Missouri -->
  <div class="edu-item">
    <div class="edu-logo">
      <img src="/assets/images/mizzou-logo.png" alt="University of Missouri - Columbia">
    </div>

    <div class="edu-content">
      <h3>Doctor of Philosophy (Ph.D.), Electrical and Computer Engineering</h3>
      <div class="edu-meta">
        <span>Jan 2024 – Present</span>
        <span>Department of Electrical Engineering and Computer Science</span>
      </div>
      <p class="edu-inst">University of Missouri–Columbia, USA</p>
      <p class="edu-extra"><strong>GPA:</strong> 4.00 / 4.00</p>
    </div>
  </div>

  <div class="edu-divider"></div>

  <!-- Boston University -->
  <div class="edu-item">
    <div class="edu-logo">
      <img src="/assets/images/bu-logo.png" alt="Boston University">
    </div>

    <div class="edu-content">
      <h3>Master of Science (M.S.), Electrical and Computer Engineering</h3>
      <div class="edu-meta">
        <span>Jan 2024</span>
        <span>Department of Electrical and Computer Engineering</span>
      </div>
      <p class="edu-inst">Boston University, Boston, Massachusetts, USA</p>
      <p class="edu-extra"><strong>GPA:</strong> 3.43 / 4.00</p>
    </div>
  </div>

  <div class="edu-divider"></div>

  <!-- SUST -->
  <div class="edu-item">
    <div class="edu-logo">
      <img src="/assets/images/sust-logo.png" alt="Shahjalal University of Science and Technology">
    </div>

    <div class="edu-content">
      <h3>B.Sc. in Electrical and Electronic Engineering (EEE)</h3>
      <div class="edu-meta">
      <span>February 2018</span>
        <span>Department of Electrical and Electronic Engineering</span>
        <span>Rank: 1st</span>
      </div>
      <p class="edu-inst">
        Shahjalal University of Science and Technology (SUST), Sylhet, Bangladesh
      </p>
      <p class="edu-extra"><strong>GPA:</strong> 3.93 / 4.00</p>
    </div>
  </div>

</div>

---

<!-- =========================
     MAJOR COURSES
========================== -->
<h2>
  <i class="fas fa-book"></i> Major Courses
</h2>
<hr class="section-rule"/>

<style>
/* ===== Major Courses Pills ===== */
.edu-course-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin: 20px 0 30px;
}

.edu-course-pill {
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
    box-shadow 0.25s ease,
    transform 0.25s ease;
}

.edu-course-pill:hover {
  background: #2563eb;
  color: #ffffff;
  border-color: #2563eb;
  transform: translateY(-3px);
  box-shadow: 0 5px 14px rgba(37, 99, 235, 0.22);
}

@media (max-width: 600px) {
  .edu-course-grid {
    gap: 8px;
  }

  .edu-course-pill {
    padding: 8px 12px;
    font-size: 0.82rem;
  }
}
</style>

<div class="edu-course-grid">
  <span class="edu-course-pill">Solid State Devices</span>
  <span class="edu-course-pill">Optoelectronics</span>
  <span class="edu-course-pill">VLSI</span>
  <span class="edu-course-pill">Power Electronics</span>
  <span class="edu-course-pill">Analog and Digital Electronics</span>
  <span class="edu-course-pill">Signals and Linear Systems</span>
  <span class="edu-course-pill">Digital Signal Processing</span>
  <span class="edu-course-pill">Control Systems</span>
  <span class="edu-course-pill">Power Systems</span>
  <span class="edu-course-pill">Microprocessors and Interfacing</span>
  <span class="edu-course-pill">Electrical Properties of Materials</span>
  <span class="edu-course-pill">Digital Electronics</span>
  <span class="edu-course-pill">Electromagnetic Fields and Waves</span>
  <span class="edu-course-pill">Electrical Machines</span>
  <span class="edu-course-pill">Electrical Circuits</span>
  <span class="edu-course-pill">C Programming</span>
</div>








</div> <!-- /.wrap -->
