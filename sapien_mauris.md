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
    justify-content: space-between;
    align-items: center;
    width: 100%; 
    gap: 0; 
  }

  .accordion:hover {opacity: 0.7;}

  .accordion-arrow {transition: transform 0.3s ease; font-size: 18px;}

  .accordion.active .accordion-arrow {transform: rotate(90deg);}

  .accordion span.accordion-arrow {margin-left: 200px;}


  .panel {display: none; margin-bottom: 5px;}

  .panel p{line-height: 2.5;}
</style>

<h2 class="accordion">
  Project Management
  <span class="accordion-arrow">▶</span>
</h2>

<div class="panel">
<p>
  Atlassian Agile Project Management Professional Certificate —
  <a href="LINK" target="_blank"><em>Check the certificate here.</em></a><br>

  Agile Foundations —
  <a href="LINK" target="_blank"><em>Check the certificate here.</em></a><br>

  Agile Project Management with Jira Cloud: 1 Projects, Boards, and Issues —
  <a href="LINK" target="_blank"><em>Check the certificate here.</em></a><br>

  Agile Project Management with Jira Cloud: 2 Lean and Agile Processes —
  <a href="LINK" target="_blank"><em>Check the certificate here.</em></a><br>

  Agile Project Management with Jira Cloud: 3 Advanced Topics —
  <a href="LINK" target="_blank"><em>Check the certificate here.</em></a><br>

  Mistakes to Avoid in Agile Project Management —
  <a href="LINK" target="_blank"><em>Check the certificate here.</em></a><br>

  Scrum: The Basics —
  <a href="LINK" target="_blank"><em>Check the certificate here.</em></a>
</p>
</div>


<h2 class="accordion">
  Data Visualization
  <span class="accordion-arrow">▶</span>
</h2>

<div class="panel">
<p>
  Fundamentals of Visualization with Tableau —
  <a href="LINK" target="_blank"><em>Check the certificate here.</em></a>
</p>
</div>


<h2 class="accordion">
  MarTech & CRM
  <span class="accordion-arrow">▶</span>
</h2>

<div class="panel">
 <p>
  Introduction to CRM with HubSpot —
  <a href="LINK" target="_blank"><em>Check the certificate here.</em></a>
</p>
</div>

<script>
const accordions = document.querySelectorAll(".accordion");

accordions.forEach((accordion) => {
  accordion.addEventListener("click", function () {

    // Close all other accordions
    accordions.forEach((item) => {
      if (item !== this) {
        item.classList.remove("active");
        item.nextElementSibling.style.display = "none";
      }
    });

    // Toggle the clicked one
    this.classList.toggle("active");

    const panel = this.nextElementSibling;
    panel.style.display =
      panel.style.display === "block" ? "none" : "block";
  });
});
</script>







