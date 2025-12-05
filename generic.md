---
layout: page
title: Work Experience
---

<style>
  .accordion {
    cursor: pointer;
    padding: 5px 0;
    border: none;
    background: none;
    font-size: 24px;
    font-weight: bold;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .accordion:hover { opacity: 0.7; }

  .accordion-arrow {
    transition: transform 0.3s ease;
    font-size: 18px;
    margin-left: 10px;
  }

  .accordion.active .accordion-arrow {
    transform: rotate(90deg);
  }

  /* All panels open by default */
  .panel {
    display: block;
    margin-bottom: 20px;
  }

  /* Closed state */
  .panel.collapsed {
    display: none;
  }

  /* Nice line spacing for content */
  .panel p, .panel ul {
    line-height: 1.7;
  }
</style>

<h2 class="accordion">
  Charge Incubator
  <span class="accordion-arrow">▶</span>
</h2>
<div class="panel">
  <p><strong>Program Assistant</strong> <em>(Contract)</em> — Oslo, Norway | Aug 2025 - Current</p>
  <ul>
    <li>Supported the LEAP Program through <strong>end-to-end coordination</strong> …</li>
    <li>Redesigned and managed the Charge <strong>website using Squarespace CMS</strong> …</li>
  </ul>
</div>

<h2 class="accordion">
  H&M
  <span class="accordion-arrow">▶</span>
</h2>
<div class="panel">
  <p><strong>Sales Advisor</strong> <em>(Contract)</em> — Oslo, Norway | May 2025 - Aug 2025</p>
  <ul>
    <li>Delivered <strong>exceptional B2C sales</strong> …</li>
    <li>Maintained a well-organized, fully stocked sales floor …</li>
  </ul>
</div>

<h2 class="accordion">
  Chaskka
  <span class="accordion-arrow">▶</span>
</h2>
<div class="panel">
  <p><strong>Social Media Marketing Strategist</strong> <em>(Contract)</em> — Oslo, Norway | Mar 2025 - Aug 2025</p>
  <ul>
    <li>Executed <strong>two successful influencer partnerships</strong> …</li>
    <li>Designed and created <strong>20+ physical collaterals</strong> …</li>
  </ul>
</div>

<h2 class="accordion">
  ITC
  <span class="accordion-arrow">▶</span>
</h2>
<div class="panel">
  <p><strong>Assistant Manager</strong> — Delhi, India | Jul 2024 - Nov 2024</p>
  <ul>
    <li>Analyzed <strong>demand–supply data for 10+ SKUs</strong> …</li>
  </ul>

  <p><strong>Management Intern</strong> — Bangalore, India | Jul 2024 - Nov 2024</p>
  <ul>
    <li>Analyzed <strong>3 years of data across 20 SKUs</strong> …</li>
  </ul>
</div>

<h2 class="accordion">
  Reminiscent Interior
  <span class="accordion-arrow">▶</span>
</h2>
<div class="panel">
  <p><strong>Marketing Strategist</strong> — Bangalore, India | Sep 2021 - Feb 2022</p>
  <ul>
    <li>Created and optimized content across <strong>10+ platforms</strong> …</li>
  </ul>
</div>

<h2 class="accordion">
  Godrej & Boyce
  <span class="accordion-arrow">▶</span>
</h2>
<div class="panel">
  <p><strong>Consultant</strong> <em>(Contract)</em> — Mumbai, India | Dec 2020 - Feb 2021</p>
  <ul>
    <li>Conducted <strong>6+ weeks of training</strong> …</li>
  </ul>

  <p><strong>Assistant Manager in Marketing</strong> — Mumbai, India | Jun 2019 - Nov 2020</p>
  <ul>
    <li>Acted as a liaison between <strong>design, execution, sales…</strong></li>
  </ul>
</div>

<script>
  document.addEventListener("DOMContentLoaded", function () {
    const accordions = document.querySelectorAll(".accordion");

    // Make all arrows appear 'active' because all panels are open
    accordions.forEach(acc => acc.classList.add("active"));

    accordions.forEach(acc => {
      acc.addEventListener("click", function () {
        const panel = this.nextElementSibling;

        // Toggle this panel only
        panel.classList.toggle("collapsed");
        this.classList.toggle("active");
      });
    });
  });
</script>

