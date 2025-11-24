---
layout: default
title: "Mansour Shahhosseini"
description: "PhD Student in Quantitative Marketing at UTD"
---

<script>
document.addEventListener("DOMContentLoaded", function() {
    let footer = document.querySelector("footer");
    if (footer) {
        footer.innerHTML = "Life is not fair, nor is it unfair. It is what it is.";
    }
});
</script>

<style>
:root {
  --accent: #2563eb;
  --accent-soft: rgba(37, 99, 235, 0.08);
  --text-main: #111827;
  --text-muted: #6b7280;
  --border-subtle: #e5e7eb;
}

/* Global overrides */
body {
  background-color: #ffffff;
  color: var(--text-main);
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "SF Pro Text",
    "Segoe UI", sans-serif;
}

hr {
  display: none; /* Hide theme hr if present */
}

/* Page container */
.profile-page {
  max-width: 960px;
  margin: 2.5rem auto 4rem auto;
  padding: 0 1.5rem;
}

.profile-shell {
  background: #ffffff;
  border-radius: 1.5rem;
  border: 1px solid var(--border-subtle);
  box-shadow: 0 18px 40px rgba(15, 23, 42, 0.06);
  padding: 2.5rem 2.25rem 2.75rem;
}

/* Top hero section */
.profile-hero {
  display: flex;
  flex-wrap: wrap;
  gap: 1.75rem;
  align-items: center;
  margin-bottom: 2.5rem;
}

.profile-hero-info {
  flex: 1 1 260px;
  min-width: 230px;
}

.profile-name {
  font-size: clamp(1.9rem, 2.4vw, 2.25rem);
  font-weight: 700;
  letter-spacing: -0.03em;
  margin: 0 0 0.35rem;
}

.profile-title {
  font-size: 1rem;
  font-weight: 500;
  color: var(--text-muted);
  margin-bottom: 0.35rem;
}

.profile-subtitle {
  font-size: 0.95rem;
  color: var(--text-muted);
}

.profile-meta {
  margin-top: 0.8rem;
  font-size: 0.9rem;
  color: var(--text-muted);
}

.profile-meta span {
  padding: 0.2rem 0.6rem;
  border-radius: 999px;
  background: var(--accent-soft);
  color: #1d4ed8;
}

/* Profile photo */
.profile-photo-wrap {
  flex: 0 0 auto;
  margin-left: auto;
}

.my-profile-pic {
  display: block;
  width: 210px;
  height: 210px;
  border-radius: 999px;
  object-fit: cover;
  border: 3px solid #f3f4f6;
  box-shadow: 0 12px 30px rgba(15, 23, 42, 0.25);
}

/* Content layout */
.profile-content {
  display: grid;
  grid-template-columns: minmax(0, 2fr);
  gap: 1.75rem;
}

/* Reusable section card */
.section-card {
  border-radius: 1.1rem;
  border: 1px solid #f3f4f6;
  background: #ffffff;
  padding: 1.4rem 1.35rem 1.25rem;
  transition: box-shadow 150ms ease, transform 150ms ease,
              border-color 150ms ease, background-color 150ms ease;
}

.section-card:hover {
  box-shadow: 0 14px 30px rgba(15, 23, 42, 0.08);
  transform: translateY(-1px);
  border-color: var(--accent-soft);
}

/* Section headings */
.section-card h2 {
  font-size: 1.05rem;
  font-weight: 600;
  margin: 0 0 0.9rem;
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
}

.section-card h2::before {
  content: "";
  width: 9px;
  height: 9px;
  border-radius: 999px;
  background: var(--accent);
}

/* Links */
a {
  color: var(--accent);
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

/* Lists */
.section-card ul {
  margin: 0.4rem 0 0;
  padding-left: 1.1rem;
}

.section-card li {
  margin-bottom: 0.35rem;
}

/* Research interests pills */
.interests-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 0.4rem;
}

.interest-pill {
  font-size: 0.85rem;
  padding: 0.25rem 0.65rem;
  border-radius: 999px;
  background: var(--accent-soft);
  color: #1d4ed8;
}

/* Education timeline */
.timeline {
  position: relative;
  margin: 0.25rem 0 0;
  padding: 0;
  list-style: none;
}

.timeline::before {
  content: '';
  position: absolute;
  left: 10px;
  top: 4px;
  bottom: 0;
  width: 2px;
  background: #e5e7eb;
}

.timeline-item {
  position: relative;
  margin: 1.4rem 0;
  padding-left: 2.4rem;
}

.timeline-item::before {
  content: '';
  position: absolute;
  left: 1px;
  top: 3px;
  width: 14px;
  height: 14px;
  border-radius: 999px;
  background: #ffffff;
  border: 2px solid var(--accent);
  box-shadow: 0 0 0 3px var(--accent-soft);
}

.timeline-year {
  font-size: 0.85rem;
  font-weight: 600;
  color: var(--text-muted);
}

.timeline-content h4 {
  margin: 0.15rem 0 0.1rem;
  font-size: 0.98rem;
  font-weight: 600;
}

.timeline-content p {
  margin: 0.05rem 0;
  font-size: 0.9rem;
  color: var(--text-muted);
}

.timeline li {
  list-style: none !important;
}

/* Contact icons row */
.contact-row {
  display: flex;
  flex-wrap: wrap;
  gap: 0.6rem 1rem;
  align-items: center;
}

.contact-row a {
  display: inline-flex;
  align-items: center;
  gap: 0.35rem;
  font-size: 0.9rem;
  font-weight: 500;
  padding: 0.35rem 0.7rem;
  border-radius: 999px;
  border: 1px solid #e5e7eb;
  background: #f9fafb;
  text-decoration: none;
}

.contact-row a:hover {
  background: #eef2ff;
  border-color: var(--accent-soft);
}

.contact-row img {
  display: inline-block;
}

/* Small text tweaks */
.small-text {
  font-size: 0.9rem;
  color: var(--text-muted);
}

/* Responsive */
@media (max-width: 720px) {
  .profile-shell {
    padding: 1.8rem 1.4rem 2.2rem;
  }

  .profile-hero {
    text-align: left;
  }

  .profile-photo-wrap {
    margin-left: 0;
  }

  .profile-photo-wrap,
  .my-profile-pic {
    margin-inline: 0;
  }
}
</style>

<div class="profile-page">
  <div class="profile-shell">
    <!-- Hero / Header -->
    <section class="profile-hero">
      <div class="profile-hero-info">
        <h1 class="profile-name">Mansour Shahhosseini</h1>
        <p class="profile-title">PhD Student in Quantitative Marketing</p>
        <p class="profile-subtitle">The University of Texas at Dallas</p>
        <div class="profile-meta">
          <span>Customer Analytics · Social Media · Unstructured Data</span>
        </div>
      </div>
      <div class="profile-photo-wrap">
        <img src="assets/profile.jpg" alt="Profile Photo" class="my-profile-pic" />
      </div>
    </section>

    <!-- Main content -->
    <div class="profile-content">

      <!-- CV -->
      <section id="cv" class="section-card">
        <h2>CV</h2>
        <p class="small-text">
          Please see my full CV
          <a href="https://www.dropbox.com/scl/fi/xesa5zyqnbydtcvs8wkty/MansourShahhosseini_CV.docx?rlkey=qdrngb2cws7po5t5f38hnsdi9&amp;st=gp67fcdc&amp;dl=0" target="_blank" rel="noopener noreferrer">
            here
          </a>.
        </p>
      </section>

      <!-- Research Interests -->
      <section id="research-interests" class="section-card">
        <h2>Research Interests</h2>
        <p><strong>Areas</strong></p>
        <div class="interests-grid">
          <span class="interest-pill">Customer Analytics</span>
          <span class="interest-pill">Social Media</span>
          <span class="interest-pill">Unstructured Data in Marketing</span>
        </div>
        <p style="margin-top:0.9rem;"><strong>Methods</strong></p>
        <div class="interests-grid">
          <span class="interest-pill">Econometrics</span>
          <span class="interest-pill">Causal Inference</span>
          <span class="interest-pill">Deep Learning</span>
        </div>
      </section>

      <!-- Education -->
      <section id="education" class="section-card">
        <h2>Education</h2>
        <ul class="timeline">
          <li class="timeline-item">
            <span class="timeline-year">2025–2029 (Expected)</span>
            <div class="timeline-content">
              <h4>PhD Student</h4>
              <p>Quantitative Marketing<br>The University of Texas at Dallas</p>
            </div>
          </li>
          <li class="timeline-item">
            <span class="timeline-year">2023–2025</span>
            <div class="timeline-content">
              <h4>Master of Business Research</h4>
              <p>Quantitative Marketing<br>Temple University</p>
            </div>
          </li>
          <li class="timeline-item">
            <span class="timeline-year">2020–2023</span>
            <div class="timeline-content">
              <h4>Master of Business Administration</h4>
              <p>Marketing<br>Sharif University of Technology</p>
            </div>
          </li>
          <li class="timeline-item">
            <span class="timeline-year">2016–2020</span>
            <div class="timeline-content">
              <h4>Bachelor of Science</h4>
              <p>Materials Engineering<br>Iran University of Science and Technology</p>
            </div>
          </li>
        </ul>
      </section>

      <!-- Publications -->
      <section id="publications" class="section-card">
        <h2>Publications</h2>
        <ul>
          <li>
            Shahhosseini, M., &amp; Khalili Nasr, A. (2024).
            <a href="https://www.tandfonline.com/doi/abs/10.1080/10548408.2024.2306358" target="_blank" rel="noopener noreferrer">
              <em>What attributes affect customer satisfaction in green restaurants? An aspect-based sentiment analysis approach.</em>
            </a>
            <br />
            <span class="small-text">Journal of Travel &amp; Tourism Marketing, 41(4), 472–490.</span>
          </li>
        </ul>
      </section>

      <!-- Working Papers -->
      <section id="working-papers" class="section-card">
        <h2>Working Papers</h2>
        <ul>
          <li>“How to Sell in the Secondhand Market”</li>
          <li>“What Makes a Movie Trailer Great?”</li>
        </ul>
      </section>

      <!-- Work in Progress -->
      <section id="work-in-progress" class="section-card">
        <h2>Work in Progress</h2>
        <ul>
          <li>“Customer Guided GenAI”</li>
          <li>“Livestreamers' Hidden Value”</li>
        </ul>
      </section>

      <!-- Codes -->
      <section id="codes" class="section-card">
        <h2>Codes</h2>
        <ul>
          <li><a href="https://github.com/MansourShahhosseini/LLM-Tutorial" target="_blank" rel="noopener noreferrer">LLMs Tutorial</a></li>
          <li><a href="https://github.com/MansourShahhosseini/Quantitative-Economics" target="_blank" rel="noopener noreferrer">Quantitative Economics</a></li>
          <li><a href="https://github.com/MansourShahhosseini/Face-Photograph-Memorability-Score" target="_blank" rel="noopener noreferrer">Face Memorability Prediction</a></li>
        </ul>
      </section>

      <!-- Contact -->
      <section id="contact" class="section-card">
        <h2>Contact</h2>
        <div class="contact-row">
          <a href="mailto:mansour.shahhosseini@utdallas.edu">
            <img src="https://img.icons8.com/ios-filled/20/000000/new-post.png" alt="Email Icon">
            <span>Email</span>
          </a>
          <a href="https://github.com/MansourShahhosseini" target="_blank" rel="noopener noreferrer">
            <img src="https://img.icons8.com/ios-glyphs/20/000000/github.png" alt="GitHub Icon">
            <span>GitHub</span>
          </a>
          <a href="https://scholar.google.com/citations?user=8iK7T7EAAAAJ&amp;hl=en" target="_blank" rel="noopener noreferrer">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c7/Google_Scholar_logo.svg/768px-Google_Scholar_logo.svg.png" width="20" height="20" alt="Google Scholar Icon">
            <span>Google Scholar</span>
          </a>
          <a href="https://www.linkedin.com/in/mansourshahhosseini/" target="_blank" rel="noopener noreferrer">
            <img src="https://pbs.twimg.com/profile_images/1478307374506995713/6RA1Ax4__400x400.jpg" width="20" height="20" alt="LinkedIn Icon">
            <span>LinkedIn</span>
          </a>
        </div>
      </section>

    </div>
  </div>
</div>
