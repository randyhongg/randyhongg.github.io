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
.research-hero {
  position: relative;
  padding: 24px 0 8px;
  overflow: hidden;
}
.research-hero svg {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  opacity: 0.18;
  z-index: 0;
}
.research-hero h2 {
  position: relative;
  z-index: 1;
  margin: 0;
}
.research-section {
  border-left: 3px solid #cfc9bb;
  padding: 2px 0 2px 18px;
  margin: 28px 0 10px;
}
.research-section-title {
  font-size: 17px;
  font-weight: 600;
  margin: 0 0 4px;
  color: #1a1a1a;
}
.research-section-subtitle {
  font-size: 13px;
  color: #888;
  margin: 0;
}
.cta-button-wrap {
  text-align: center;
  margin: 8px 0 40px;
}
.cta-button {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  padding: 11px 22px;
  border: 1px solid #ddd;
  border-radius: 8px;
  text-decoration: none;
  font-size: 14px;
  font-weight: 600;
  color: #222;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.06);
  transition: box-shadow 0.2s ease, transform 0.2s ease;
}
.cta-button:hover {
  box-shadow: 0 6px 16px rgba(0, 0, 0, 0.1);
  transform: translateY(-2px);
}
</style>

<div class="research-hero">
  <svg viewBox="0 0 800 90" preserveAspectRatio="none">
    <line x1="40" y1="20" x2="160" y2="65" stroke="#999" stroke-width="1"></line>
    <line x1="160" y1="65" x2="290" y2="15" stroke="#999" stroke-width="1"></line>
    <line x1="290" y1="15" x2="430" y2="60" stroke="#999" stroke-width="1"></line>
    <line x1="160" y1="65" x2="290" y2="78" stroke="#999" stroke-width="1"></line>
    <line x1="430" y1="60" x2="560" y2="22" stroke="#999" stroke-width="1"></line>
    <line x1="560" y1="22" x2="690" y2="68" stroke="#999" stroke-width="1"></line>
    <line x1="290" y1="78" x2="430" y2="60" stroke="#999" stroke-width="1"></line>
    <circle cx="40" cy="20" r="4" fill="#888"></circle>
    <circle cx="160" cy="65" r="4" fill="#888"></circle>
    <circle cx="290" cy="15" r="4" fill="#888"></circle>
    <circle cx="290" cy="78" r="4" fill="#888"></circle>
    <circle cx="430" cy="60" r="4" fill="#888"></circle>
    <circle cx="560" cy="22" r="4" fill="#888"></circle>
    <circle cx="690" cy="68" r="4" fill="#888"></circle>
  </svg>
  <h2 style="text-align: center;">Research Interests</h2>
</div>

<div class="research-section">
  <p class="research-section-title">Engineering deep learning algorithms to build more efficient neural interfaces</p>
  <p class="research-section-subtitle">Cost-efficient, generalizable approaches to decoding neural signals</p>
</div>

<div style="text-align: justify; text-align-last: justify; margin-bottom: 2rem;">  

Artificial neural networks have provided us with an approach towards translating noisy neural signals into motor function control, evident through the successes of prostheses and brain computer interfaces on the market. However, biological heterogeneity and model architectures that demand high quantities of training data have introduced challenges in making this technology accessible and generalizable. I am interested in using neuroscience and mathematical theory to forge approaches that are more cost efficient and accurate than contemporary data analysis methods. Particular interest in engineering non-invasive closed-loop neural interfaces.

</div>  

<div style="display: flex; gap: 12px; margin: 16px 0;">
  <img src="../images/neural_network_visual.png" style="width: 49%; border-radius: 6px;">
  <img src="../images/data_plot_visual.png" style="width: 49%; border-radius: 6px;">
</div>

<div class="research-section">
  <p class="research-section-title">Understanding network dynamics and routing strategies of neural computation</p>
  <p class="research-section-subtitle">Biologically-inspired algorithms grounded in connectome structure</p>
</div>

<div style="text-align: justify; text-align-last: justify; margin-bottom: 2rem;">  

Despite our efforts, we understand very little about how the brain communicates information across its connectome from first principles due to limitations in our measurement tools. Whatever strategy is imposed is clearly very effective and efficient, being able to foster consciousness while consuming the same number of watts as a lightbulb, while only using neurons that are constrained to biophysical restrictions. This is in stark contrast to contemporary artifical intelligence models, which consume high quantities of energy and fail to recreate feats of the brain despite their nodes not being subject to biophysical restrictions. I am interested in studying network dynamics, connectome structure, and information passing strategies to develop biologically-inspired computational algorithms that are cost efficient and effective.  

</div>

<div style="display: flex; gap: 12px; margin: 16px 0;">
  <img src="../images/sphere_visual.png" style="width: 49%; border-radius: 6px;">
  <img src="../images/graph_visual.png" style="width: 49%; border-radius: 6px;">
</div>

<div class="cta-button-wrap">
  <a class="cta-button" href="/projects/">View My Projects <span>→</span></a>
</div>

## Conference Presentations
{: style="text-align: center;"}

<style>
.conference-photos-wide {
  width: 90vw;
  max-width: 900px;
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
