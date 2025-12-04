---
layout: page
title: Certifications
---
<style>
  a {
    color: inherit;           /* same color as surrounding text */
    text-decoration: none;    /* removes underline */
  }
</style>

<style>
  .accordion {
    cursor: pointer;
    padding: 5px 0;
    border: none;
    background: none;
    font-size: 24px;
    font-weight: bold;
    display: flex;
    justify-content: flex-start;
    align-items: center;
    gap: 6px;
  }

  .accordion:hover {opacity: 0.7;}

  .accordion-arrow {transition: transform 0.3s ease; font-size: 18px;}

  .accordion.active .accordion-arrow {transform: rotate(90deg);}

  .panel {display: none; margin: 5px 0 15px 0;}
</style>

<h2 class="accordion">
  Project Management
  <span class="accordion-arrow">▶</span>
</h2>

<div class="panel">
  <p>
    Atlassian Agile Project Management Professional Certificate —
    <a href="https://www.linkedin.com/learning/certificates/9b78b038e6a58a7eb913a65f79c8866f62861ef0ef1e1b97dc6045de8ce1e126?trk=share_certificate" target="_blank">
      Check the certificate here.
    </a>
    Agile Foundations —
    <a href="https://www.linkedin.com/learning/certificates/9b78b038e6a58a7eb913a65f79c8866f62861ef0ef1e1b97dc6045de8ce1e126?trk=share_certificate" target="_blank">
      Check the certificate here.
    </a>
    Agile Project Management with Jira Cloud: 1 Projects, Boards, and Issues —
    <a href="https://www.linkedin.com/learning/certificates/9b78b038e6a58a7eb913a65f79c8866f62861ef0ef1e1b97dc6045de8ce1e126?trk=share_certificate" target="_blank">
      Check the certificate here.
    </a>
    Agile Project Management with Jira Cloud: 2 Lean and Agile Processes —
    <a href="https://www.linkedin.com/learning/certificates/9b78b038e6a58a7eb913a65f79c8866f62861ef0ef1e1b97dc6045de8ce1e126?trk=share_certificate" target="_blank">
      Check the certificate here.
    </a>
    Agile Project Management with Jira Cloud: 3 Advanced Topics —
    <a href="https://www.linkedin.com/learning/certificates/9b78b038e6a58a7eb913a65f79c8866f62861ef0ef1e1b97dc6045de8ce1e126?trk=share_certificate" target="_blank">
      Check the certificate here.
    </a>
    Mistakes to Avoid in Agile Project Management —
    <a href="https://www.linkedin.com/learning/certificates/9b78b038e6a58a7eb913a65f79c8866f62861ef0ef1e1b97dc6045de8ce1e126?trk=share_certificate" target="_blank">
      Check the certificate here.
    </a>
    Scrum: The Basics —
    <a href="https://www.linkedin.com/learning/certificates/9b78b038e6a58a7eb913a65f79c8866f62861ef0ef1e1b97dc6045de8ce1e126?trk=share_certificate" target="_blank">
      Check the certificate here.
    </a>
  </p>
</div>

<script>
  const acc = document.querySelector(".accordion");
  const panel = document.querySelector(".panel");

  acc.addEventListener("click", function () {
    this.classList.toggle("active");
    panel.style.display = panel.style.display === "block" ? "none" : "block";
  });
</script>
