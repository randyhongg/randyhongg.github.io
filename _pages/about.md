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
.profile-banner {
  display: flex;
  align-items: center;
  gap: 22px;
  background: #f7f6f4;
  border-radius: 12px;
  padding: 16px;
  margin-bottom: 4px;
}
.profile-photo {
  width: 190px;
  aspect-ratio: 4 / 5;
  object-fit: cover;
  border-radius: 10px;
  display: block;
  flex-shrink: 0;
}
.profile-text {
  border-left: 3px solid #ddd;
  padding-left: 18px;
}
.profile-statement {
  font-size: 19px;
  font-weight: 600;
  margin: 0 0 4px;
  color: #1a1a1a;
}
.profile-subtitle {
  font-size: 14px;
  color: #666;
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
@media (max-width: 480px) {
  .profile-banner {
    flex-direction: column;
    align-items: flex-start;
  }
  .profile-text {
    border-left: none;
    padding-left: 0;
    border-top: 3px solid #ddd;
    padding-top: 12px;
    margin-top: 4px;
  }
}
</style>
## About Me

<div class="profile-banner" markdown="1">

<img class="profile-photo" src="../images/website_pfp.jpg" alt="Randy Hong">

<div class="profile-text" markdown="1">

<p class="profile-statement">Ph.D. Student at the University of California, Davis.</p>
<p class="profile-subtitle">Neuroscience Graduate Group.</p>

</div>

</div>

<div class="reveal" style="text-align: justify; text-align-last: justify; margin-bottom: 2rem; margin-top: 1.5rem;" markdown="1">

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
