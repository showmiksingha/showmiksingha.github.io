---
title: "ECA"
permalink: /eca/
layout: default
author_profile: false
classes: wide
---

<div class="wrap" markdown="1">

<style>
  /* ====== Layout (same as Education/Skills) ====== */
  .page-grid{
    display:grid;
    grid-template-columns:260px 1fr;
    gap:28px;
    align-items:start;
  }

  @media(max-width:900px){
    .page-grid{
      grid-template-columns:1fr;
    }
  }

  /* ====== Author card ====== */
  .author-card{
    position:sticky;
    top:90px;
    border:1px solid #e5e7eb;
    border-radius:14px;
    padding:16px;
    background:#fff;
  }

  @media(max-width:900px){
    .author-card{
      position:static;
    }
  }

  .author-avatar{
    width:110px;
    height:110px;
    border-radius:999px;
    object-fit:cover;
    display:block;
    margin:0 auto 10px;
  }

  .author-name{
    text-align:center;
    font-weight:800;
    margin:0;
  }

  .author-bio{
    text-align:center;
    color:#6b7280;
    margin:6px 0 12px;
    font-size:.95rem;
  }

  .author-links{
    list-style:none;
    padding:0;
    margin:0;
  }

  .author-links li{
    margin:8px 0;
  }

  .author-links a{
    display:inline-flex;
    gap:8px;
    align-items:center;
    text-decoration:none;
  }

  /* ====== Page header card ====== */
  .eca-hero{
    border:1px solid #e5e7eb;
    border-radius:16px;
    padding:18px 18px;
    background:linear-gradient(
      180deg,
      rgba(243,244,246,.7),
      rgba(255,255,255,1)
    );
    margin-bottom:18px;
    position:relative;
    overflow:hidden;
  }

  .eca-hero:before{
    content:"";
    position:absolute;
    inset:-80px -120px auto auto;
    width:260px;
    height:260px;
    background:radial-gradient(
      circle,
      rgba(59,130,246,.18),
      rgba(59,130,246,0)
    );
    filter:blur(2px);
    transform:rotate(18deg);
  }

  .eca-hero h2{
    margin:0 0 6px 0;
    position:relative;
  }

  .eca-hero p{
    margin:0;
    color:#6b7280;
    position:relative;
  }

  /* ====== Section card ====== */
  .eca-card{
    border:1px solid #e5e7eb;
    border-radius:16px;
    padding:16px 16px;
    background:#fff;
    margin:16px 0;
  }

  .eca-title{
    display:flex;
    align-items:center;
    gap:10px;
    margin:0 0 10px 0;
  }

  .eca-title i{
    opacity:.9;
  }

  .muted{
    color:#6b7280;
  }

  /* ====== Badges ====== */
  .badges{
    display:flex;
    flex-wrap:wrap;
    gap:10px;
    margin:12px 0 0 0;
  }

  .badge{
    display:inline-flex;
    align-items:center;
    gap:8px;
    padding:8px 10px;
    border:1px solid #e5e7eb;
    border-radius:999px;
    background:#fff;
    color:#111827;
    font-size:.92rem;
  }

  /* ====== Placeholder area for future images ====== */
  .image-placeholder{
    margin-top:16px;
    border:1px dashed #d1d5db;
    border-radius:14px;
    padding:24px;
    text-align:center;
    color:#9ca3af;
    background:#f9fafb;
    font-size:.92rem;
  }

  /* ====== Subtle scroll reveal ====== */
  .reveal{
    opacity:0;
    transform:translateY(10px);
    transition:opacity .55s ease, transform .55s ease;
  }

  .reveal.is-in{
    opacity:1;
    transform:none;
  }
</style>

<div class="page-grid">

<!-- =========================================================
     LEFT: AUTHOR PROFILE
========================================================= -->

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
        <i class="fas fa-envelope"></i>
        Email
      </a>
    </li>

    <li>
      <a
        href="https://github.com/showmiksingha"
        target="_blank"
        rel="noopener"
      >
        <i class="fab fa-github"></i>
        GitHub
      </a>
    </li>

    <li>
      <a
        href="https://www.linkedin.com/in/showmiksingha/"
        target="_blank"
        rel="noopener"
      >
        <i class="fab fa-linkedin"></i>
        LinkedIn
      </a>
    </li>

  </ul>

</aside>


<!-- =========================================================
     RIGHT: PAGE CONTENT
========================================================= -->

<main markdown="1">


<!-- =========================================================
     HEADER
========================================================= -->

<div class="eca-hero reveal">

  <h2 class="eca-title">
    <i class="fas fa-people-group"></i>
    Extracurricular Activities
  </h2>

  <p>
    Leadership, community service, volunteering, student engagement,
    and activities beyond my academic and research work.
  </p>

  <div class="badges">

    <span class="badge">
      <i class="fas fa-users"></i>
      Student Leadership
    </span>

    <span class="badge">
      <i class="fas fa-hand-holding-heart"></i>
      Volunteering
    </span>

    <span class="badge">
      <i class="fas fa-people-group"></i>
      Community Engagement
    </span>

    <span class="badge">
      <i class="fas fa-futbol"></i>
      Sports
    </span>

  </div>

</div>


<!-- =========================================================
     EECS GSA
========================================================= -->

<div class="eca-card reveal" markdown="1">

  <h3 class="eca-title">
    <i class="fas fa-users"></i>
    Electrical Engineering and Computer Science Graduate Student Association
    (EECS GSA)
  </h3>

  <p class="muted" style="margin-top:0;">
    <strong>University of Missouri–Columbia</strong>
  </p>

  <p>
    I am actively involved with the Electrical Engineering and Computer Science
    Graduate Student Association (EECS GSA) at the University of Missouri.
    Through the organization, I contribute to initiatives that strengthen the
    graduate student community and encourage interaction among students,
    faculty, and staff within the department.
  </p>

  <p>
    My involvement includes planning and coordinating graduate student events,
    professional-development activities, networking opportunities, and
    community-building programs. I have worked with fellow student leaders on
    event organization, funding and logistics, venue coordination, food
    arrangements, publicity, and student engagement.
  </p>

  <p>
    Activities have included departmental social events, graduate student
    meet-and-greets, internship-experience sessions, and community events such
    as the EECS departmental potluck. These experiences have helped me further
    develop leadership, teamwork, communication, and organizational skills
    outside my research responsibilities.
  </p>

  <div class="image-placeholder">
    Images will be added here later.
  </div>

  <!--
  FUTURE IMAGE FOLDER:
  /assets/images/eca/eecs-gsa/
  -->

</div>




<!-- =========================================================
     STUDENT & COMMUNITY ENGAGEMENT
========================================================= -->

<div class="eca-card reveal" markdown="1">

  <h3 class="eca-title">
    <i class="fas fa-people-group"></i>
    Student & Community Engagement
  </h3>

  <p>
    Throughout my academic career, I have enjoyed contributing to activities
    that bring students together and help create a supportive academic
    community. My experience as a university faculty member, graduate student,
    and participant in student organizations has provided opportunities to work
    with students from diverse academic and professional backgrounds.
  </p>

  <p>
    I particularly enjoy mentoring and supporting students, sharing academic
    and professional experiences, and contributing to activities that encourage
    collaboration beyond the classroom and research laboratory.
  </p>

  <div class="image-placeholder">
    Images will be added here later.
  </div>

  <!--
  FUTURE IMAGE FOLDER:
  /assets/images/eca/community/
  -->

</div>


<!-- =========================================================
     FOOTBALL & SPORTS
========================================================= -->

<div class="eca-card reveal" markdown="1">

  <h3 class="eca-title">
    <i class="fas fa-futbol"></i>
    Football & Team Sports
  </h3>

  <p>
    Sports have also been an important part of my extracurricular activities.
    I have participated in football and inter-hall sporting activities,
    providing opportunities to work as part of a team and engage with fellow
    students outside the academic environment.
  </p>

  <p>
    I value team sports as a way to maintain balance outside academic work
    while developing teamwork, discipline, communication, and camaraderie.
  </p>

  <div class="image-placeholder">
    Images will be added here later.
  </div>

  <!--
  FUTURE IMAGE FOLDER:
  /assets/images/eca/football/
  -->

</div>


<!-- =========================================================
     OTHER ACTIVITIES
========================================================= -->

<div class="eca-card reveal" markdown="1">

  <h3 class="eca-title">
    <i class="fas fa-star"></i>
    Other Activities
  </h3>

  <p>
    In addition to research, teaching, volunteering, student leadership, and
    sports, I enjoy participating in departmental and community activities that
    provide opportunities to connect with people, learn from different
    experiences, and contribute to the broader university community.
  </p>

  <div class="image-placeholder">
    Additional activities and images will be added here later.
  </div>

  <!--
  FUTURE IMAGE FOLDER:
  /assets/images/eca/others/
  -->

</div>


</main>

</div>


<!-- =========================================================
     SCROLL REVEAL SCRIPT
========================================================= -->

<script>
(function(){

  const obs = new IntersectionObserver((entries) => {

    entries.forEach(en => {

      if(en.isIntersecting){
        en.target.classList.add('is-in');
      }

    });

  }, {
    threshold:0.08
  });

  document
    .querySelectorAll('.reveal')
    .forEach(el => obs.observe(el));

})();
</script>


</div>
