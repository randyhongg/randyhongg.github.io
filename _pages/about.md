---
permalink: /
title: "About Me"
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---
<style>
.page__title {
  display: none;
}
.story-card {
  display: flex;
  align-items: center;
  gap: 20px;
  border: 1px solid #ddd;
  border-radius: 10px;
  padding: 18px;
  margin-top: 14px;
  max-width: 800px;
  cursor: pointer;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.06);
  transition: box-shadow 0.2s ease, transform 0.2s ease;
}
.story-card:hover {
  box-shadow: 0 6px 16px rgba(0, 0, 0, 0.1);
  transform: translateY(-2px);
}
.profile-intro {
  overflow: hidden;
  margin-bottom: 4px;
}
.profile-photo-wrap {
  float: left;
  width: 220px;
  margin: 0 24px 12px 0;
}
.profile-photo {
  width: 100%;
  aspect-ratio: 4 / 5;
  object-fit: cover;
  border-radius: 12px;
  display: block;
}
.profile-name {
  font-size: 20px;
  font-weight: 600;
  margin: 4px 0 2px;
}
.profile-title {
  font-size: 14px;
  color: #666;
  margin: 0 0 14px;
}
.profile-lead {
  font-size: 16px;
  line-height: 1.6;
  color: #333;
  margin: 0;
}
.contact-links {
  display: flex;
  gap: 16px;
  flex-wrap: wrap;
  margin-top: 14px;
}
.contact-card {
  flex: 1 1 220px;
  max-width: 260px;
  border: 1px solid #ddd;
  border-radius: 10px;
  padding: 18px;
  text-decoration: none !important;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.06);
  transition: box-shadow 0.2s ease, transform 0.2s ease, border-color 0.2s ease;
  display: block;
}
.contact-card:hover {
  box-shadow: 0 6px 16px rgba(0, 0, 0, 0.1);
  transform: translateY(-2px);
  border-color: #999;
}
.contact-card .contact-label {
  font-size: 11px;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  color: #999;
  margin: 0 0 6px;
}
.contact-card .contact-title {
  font-size: 17px;
  font-weight: 600;
  color: #222;
  margin: 0 0 6px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.contact-card .contact-arrow {
  transition: transform 0.2s ease;
}
.contact-card:hover .contact-arrow {
  transform: translateX(4px);
}
.contact-card .contact-desc {
  font-size: 13px;
  color: #666;
  margin: 0;
}
@media (max-width: 560px) {
  .profile-photo-wrap {
    float: none;
    width: 100%;
    max-width: 260px;
    margin: 0 auto 16px;
  }
}
</style>
## About Me

<div class="profile-intro" markdown="1">

<div class="profile-photo-wrap">
  <img class="profile-photo" src="../images/website_pfp.jpg" alt="Randy Hong">
</div>

<p class="profile-name">Randy Hong</p>
<p class="profile-title">Ph.D. Student, Neuroscience Graduate Group &mdash; UC Davis</p>
<p class="profile-lead">First-generation Vietnamese-American from Los Angeles, working at the intersection of neuroscience and engineering to build technology for people who've lost function.</p>

</div>

<div class="reveal" style="text-align: justify; text-align-last: justify; margin-bottom: 2rem; margin-top: 1.5rem;" markdown="1">

Ph.D. student in the Neuroscience Graduate Group at the University of California, Davis. Graduated Phi Beta Kappa & Summa Cum Laude with Joint Honors from Hobart and William Smith Colleges with a Bachelor of Science in Computational Neuroscience and minor in Physics. I am a first-generation Vietnamese-American from Los Angeles, California. Witnessing the tribulations of the Vietnamese refugee diaspora instilled a deep passion to uplift demographics suffering from loss. I aspire to contribute to neuroengineering efforts to assist impaired demographics and am interested in problems concerning human rights and systemic violence.

I am interested in decoding neural signals and interfacing with the brain. My catalyst into mathematics stemmed from a need to interpret neural signals and blossomed into a deep appreciation of its application towards understanding phenomena of the physical world. My coursework in theoretical physics (electromagnetism, quantum mechanics) reaffirmed this admiration; behind abstraction laid truths that become tangible through mathematical rigor.

</div>

## Featured Stories

<div class="story-card reveal" onclick="window.open('https://www.hws.edu/news/2026/randy-hong-uc-davis.aspx', '_blank')">
  <img src="images/arm_pose.jpg" alt="Article thumbnail" style="width: 140px; height: 140px; object-fit: cover; border-radius: 8px; flex-shrink: 0;">
  <div>
    <strong style="font-size: 17px;">Randy Hong '26 Built a Mind-Controlled Prosthetic Arm. Next Stop: UC Davis.</strong>
    <p style="margin: 6px 0 0; font-size: 15px; color: #666;">HWS Office of Communications</p>
  </div>
</div>

<div class="story-card" onclick="window.open('https://www.possefoundation.org/news-and-events/hws-commencement-speaker-begins-next-chapter-in-neuroscience', '_blank')">
  <img src="images/commencement_speaker.jpg" alt="Article thumbnail" style="width: 140px; height: 140px; object-fit: cover; border-radius: 8px; flex-shrink: 0;">
  <div>
    <strong style="font-size: 17px;">HWS Commencement Speaker Begins Next Chapter in Neuroscience</strong>
    <p style="margin: 6px 0 0; font-size: 15px; color: #666;">The Posse Foundation</p>
  </div>
</div>

## Contact Me
<div class="contact-links">
  <a class="contact-card reveal" href="https://www.linkedin.com/in/randy-hong/" target="_blank">
    <p class="contact-label">Network</p>
    <p class="contact-title">LinkedIn <span class="contact-arrow">→</span></p>
    <p class="contact-desc">Connect with me for professional inquiries.</p>
  </a>
  <a class="contact-card reveal" href="https://github.com/randyhongg" target="_blank">
    <p class="contact-label">Repository</p>
    <p class="contact-title">GitHub <span class="contact-arrow">→</span></p>
    <p class="contact-desc">Browse the source code behind my projects and research.</p>
  </a>
  <a class="contact-card reveal" href="mailto:randytranhong@gmail.com">
    <p class="contact-label">Direct</p>
    <p class="contact-title">Email <span class="contact-arrow">→</span></p>
    <p class="contact-desc">Reach out directly to chat about research or collaboration.</p>
  </a>
</div>
