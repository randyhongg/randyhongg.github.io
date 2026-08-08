---
layout: single
title: "Research"
permalink: /research/
author_profile: false
---
<style>
.page__title {
  display: none;
}
</style>
## Research Interests
{: style="text-align: center;"}

**Engineering deep learning algorithms to build more efficient neural interfaces**

<div style="text-align: justify; text-align-last: justify; margin-bottom: 2rem;">  

Artificial neural networks have provided us with an approach towards translating noisy neural signals into motor function control, evident through the successes of prostheses and brain computer interfaces on the market. However, biological heterogeneity and model architectures that demand high quantities of training data have introduced challenges in making this technology accessible and generalizable. I am interested in using neuroscience and mathematical theory to forge approaches that are more cost efficient and accurate than contemporary data analysis methods. Particular interest in engineering non-invasive closed-loop neural interfaces.

</div>  

<div style="display: flex; gap: 12px; margin: 16px 0;">
  <img src="../images/neural_network_visual.png" style="width: 49%; border-radius: 6px;">
  <img src="../images/data_plot_visual.png" style="width: 49%; border-radius: 6px;">
</div>

**Understanding network dynamics and routing strategies of neural computation**

<div style="text-align: justify; text-align-last: justify; margin-bottom: 2rem;">  

Despite our efforts, we understand very little about how the brain communicates information across its connectome from first principles due to limitations in our measurement tools. Whatever strategy is imposed is clearly very effective and efficient, being able to foster consciousness while consuming the same number of watts as a lightbulb, while only using neurons that are constrained to biophysical restrictions. This is in stark contrast to contemporary artifical intelligence models, which consume high quantities of energy and fail to recreate feats of the brain despite their nodes not being subject to biophysical restrictions. I am interested in studying network dynamics, connectome structure, and information passing strategies to develop biologically-inspired computational algorithms that are cost efficient and effective.  

</div>

<div style="display: flex; gap: 12px; margin: 16px 0;">
  <img src="../images/sphere_visual.png" style="width: 49%; border-radius: 6px;">
  <img src="../images/graph_visual.png" style="width: 49%; border-radius: 6px;">
</div>

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

## Conference Presentations
{: style="text-align: center;"}

<style>
.conference-photos-wide {
  width: 90vw;
  max-width: 1500px;
  position: relative;
  left: 50%;
  transform: translateX(-50%);
  margin: 32px 0;
}
.conference-photos-wide .photo-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 20px;
}
.conference-photos-wide figure {
  margin: 0;
  border: 1px solid #e5e5e5;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.06);
  background-color: #fff;
}
.conference-photos-wide img {
  width: 100%;
  aspect-ratio: 4 / 3;
  object-fit: cover;
  display: block;
}
.conference-photos-wide figcaption {
  padding: 10px 14px;
  font-size: 13px;
  color: #666;
  text-align: center;
}
@media (max-width: 700px) {
  .conference-photos-wide .photo-grid {
    grid-template-columns: repeat(4, 1fr);
  }
}
</style>

<div class="conference-photos-wide">
  <div class="photo-grid">
    <figure>
      <img src="../images/netsci2026.jpg" alt="NetSci 2026">
      <figcaption>NetSci 2026, Boston, MA</figcaption>
    </figure>
    <figure>
      <img src="../images/rochsym2026.jpg" alt="Rochester Symposium 2026">
      <figcaption>Rochester Symposium for Physics Students 2026, Rochester, NY</figcaption>
    </figure>
    <figure>
      <img src="../images/ras_lina.jpg" alt="RAS 2024">
      <figcaption>Rochester Academy of Science 2024, Rochester, NY</figcaption>
    </figure>
    <figure>
      <img src="../images/epa.jpg" alt="Eastern Psychological Association 2024">
      <figcaption>Eastern Psychological Association 2024, Philadelphia, PA</figcaption>
    </figure>
  </div>
</div>
