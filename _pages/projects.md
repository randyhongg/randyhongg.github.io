---
layout: single
title: ""
permalink: /projects/
author_profile: false
---
## Selected Projects
{: style="text-align: center;"}
<style>
.page__title {
  display: none;
}
.projects-wide {
  width: 90vw;
  max-width: 900px;
  position: relative;
  left: 50%;
  transform: translateX(-50%);
}
.project-card {
  display: flex;
  gap: 20px;
  align-items: flex-start;
  margin-bottom: 30px;
  padding: 24px;
  border: 1px solid #e5e5e5;
  border-radius: 12px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.06);
  background-color: #fff;
  transition: box-shadow 0.2s ease, transform 0.2s ease;
}
.project-card:hover {
  box-shadow: 0 6px 16px rgba(0, 0, 0, 0.1);
  transform: translateY(-2px);
}
.project-card img {
  width: 240px;
  border-radius: 8px;
  flex-shrink: 0;
}
.project-card .project-content {
  max-width: 600px;
}
</style>
<div class="projects-wide">

<div class="project-card">
  <img src="../images/arm_pose.jpg" alt="Project 1">
  <div class="project-content">
    <h3 style="margin: 0 0 4px;">sEMG-Based Motor Function Translation of a Prosthesis</h3>
    <p style="margin: 0 0 4px; font-size: 13px; color: #888;">Randy Hong, Ileana Dumitriu Ph.D.</p>
    <p style="margin: 0 0 8px; text-align: justify; text-align-last: justify;">Using Myoware 2.0 sEMG sensors and an ESP32, we recorded and transmitted neural signals from the forearm to a gesture classification model. An Arduino Uno and PCA9685 rotated motors of the fingers of a 3D-printed prosthesis to specific degrees to recreate the hand pose.</p>
    <a href="https://github.com/randyhongg/project-repo" target="_blank" style="font-size: 14px;">View project →</a>
  </div>
</div>

<div class="project-card">
  <img src="../images/Scheme (1).jpg" alt="Project 2">
  <div class="project-content">
    <h3 style="margin: 0 0 8px;">Message Flux Imbalance Under Copy-Spread-Annihilate Dynamics Predict Edge Weight Asymmetries on Mammalian Connectomes</h3>
    <p style="margin: 0 0 4px; font-size: 13px; color: #888;">Randy Hong, Yan Hao Ph.D., Daniel Graham Ph.D.</p>
    <p style="margin: 0 0 8px; text-align: justify; text-align-last: justify;">Using a Markovian-agent message-passing model, we simulated polysynaptic messaging on both a mouse and marmoset brain connectome to demonstrate that message flux imbalance can accurately predict bidirectional edge weight asymmetries on mammalian brain networks.</p>
    <a href="https://github.com/randyhongg/project-repo-2" target="_blank" style="font-size: 14px;">View project →</a>
  </div>
</div>

<div class="project-card">
  <img src="../images/log_regress.jpg" alt="Project 3">
  <div class="project-content">
    <h3 style="margin: 0 0 8px;">Movement Intention Classification Using Electrocorticography Beta Frequency Bands and Logistic Regression Model</h3>
    <p style="margin: 0 0 4px; font-size: 13px; color: #888;">Randy Hong, Mahmood Ashoory, Julia Suzuki, Hannah Ellis, Niels Pacheco-Barrios M.D.</p>
    <p style="margin: 0 0 8px; text-align: justify; text-align-last: justify;">Previous studies demonstrated that recordings of beta frequency bands of the prefrontal cortex provide us with the greatest predictive capabilities of movement types before its onset. Using the AJILE12 dataset, we extracted beta frequency bands and processed it using a logistic regression model to predict the correct timesteps where motor function initiation occurs.</p>
    <a href="https://github.com/randyhongg/project-repo-2" target="_blank" style="font-size: 14px;">View project →</a>
  </div>
</div>

</div>
