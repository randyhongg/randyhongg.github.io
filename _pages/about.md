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
.profile-banner-img {
  width: 100%;
  border-radius: 12px;
  display: block;
  margin-bottom: 1.5rem;
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
.cta-button {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
  width: 100%;
  max-width: 800px;
  margin: 56px auto 0;
  padding: 18px 24px;
  background: #ececea;
  border-radius: 10px;
  text-decoration: none;
  font-size: 15px;
  font-weight: 600;
  color: #333;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.06);
  transition: background 0.2s ease, box-shadow 0.2s ease, transform 0.2s ease;
}
.cta-button:hover {
  background: #e2e0dc;
  box-shadow: 0 6px 16px rgba(0, 0, 0, 0.08);
  transform: translateY(-2px);
}
.photo-slider-wrap {
  width: 90vw;
  max-width: 1200px;
  position: relative;
  left: 50%;
  transform: translateX(-50%);
  margin: 32px 0;
  overflow: hidden;
}
.photo-slider-track {
  display: flex;
  gap: 20px;
  width: max-content;
  animation: photoMarquee 45s linear infinite;
}
.photo-slider-wrap:hover .photo-slider-track {
  animation-play-state: paused;
}
@keyframes photoMarquee {
  from {
    transform: translateX(0);
  }
  to {
    transform: translateX(-50%);
  }
}
.photo-slider-track figure {
  flex: 0 0 auto;
  width: 320px;
  margin: 0;
  border: 1px solid #e5e5e5;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.06);
  background-color: #fff;
  cursor: pointer;
}
.photo-slider-track img {
  width: 100%;
  aspect-ratio: 4 / 3;
  object-fit: cover;
  display: block;
}
.photo-slider-track figcaption {
  padding: 10px 14px;
  font-size: 13px;
  color: #666;
  text-align: center;
}
.photo-lightbox {
  display: none;
  position: fixed;
  inset: 0;
  background: rgba(0, 0, 0, 0.82);
  z-index: 1000;
  align-items: center;
  justify-content: center;
  padding: 32px;
  cursor: zoom-out;
}
.photo-lightbox.open {
  display: flex;
}
.photo-lightbox-content {
  max-width: 90vw;
  max-height: 90vh;
  text-align: center;
  cursor: default;
}
.photo-lightbox-content img {
  max-width: 100%;
  max-height: 80vh;
  border-radius: 8px;
  display: block;
  margin: 0 auto;
}
.photo-lightbox-caption {
  color: #eee;
  font-size: 14px;
  margin-top: 14px;
}
.photo-lightbox-close {
  position: absolute;
  top: 20px;
  right: 28px;
  color: #fff;
  font-size: 28px;
  background: none;
  border: none;
  cursor: pointer;
  line-height: 1;
}
@media (max-width: 700px) {
  .photo-slider-track figure {
    width: 260px;
  }
}
</style>
## About Me

<img class="profile-banner-img" src="../images/banner.jpg" alt="Randy Hong, Ph.D. Student, University of California Davis, Neuroscience Graduate Group">

<div class="reveal" style="text-align: justify; text-align-last: justify; margin-bottom: 2rem;" markdown="1">

I am interested in decoding neural signals and interfacing with the brain. My catalyst into mathematics stemmed from a need to interpret neural signals and blossomed into a deep appreciation of its application towards understanding phenomena of the physical world. My coursework in theoretical physics (electromagnetism, quantum mechanics) reaffirmed this admiration; behind abstraction laid truths that become tangible through mathematical rigor.

</div>

## Photos

<div class="photo-slider-wrap">
  <div class="photo-slider-track" id="photoSliderTrack">
    <figure>
      <img src="../images/speaker.jpg" alt="Commencement">
      <figcaption>Delivering my Speech as the Selected Student Speaker at Commencement, May 2026</figcaption>
    </figure>
    <figure>
      <img src="../images/holland_win.jpg" alt="Holland Teach">
      <figcaption>Presentation of "Deriving the E&M Wave Equation using Maxwell's Equation", April 2026</figcaption>
    </figure>
    <figure>
      <img src="../images/holland_judge.jpg" alt="Holland Judge">
      <figcaption>Victory Following the 25th Annual Physics Prize Competition, April 2026</figcaption>
    </figure>
    <figure>
      <img src="../images/pbk_pose.jpg" alt="Phi Beta Kappa induction">
      <figcaption>Induction into Phi Beta Kappa, April 2026</figcaption>
    </figure>
    <figure>
      <img src="../images/chicago.jpg" alt="Chicago River">
      <figcaption>Chicago River, March 2026</figcaption>
    </figure>
    <figure>
      <img src="../images/vietnam.jpg" alt="Saigon">
      <figcaption>Saigon 2026</figcaption>
    </figure>
    <figure>
      <img src="../images/netsci2026.jpg" alt="NetSci 2026">
      <figcaption>NetSci 2026, Boston, MA</figcaption>
    </figure>
    <figure>
      <img src="../images/netsci2026.jpg" alt="NetSci 2026">
      <figcaption>NetSci 2026, Boston, MA</figcaption>
    </figure>
    <!-- duplicated set below, required for a seamless continuous loop -->
    <figure>
      <img src="../images/speaker.jpg" alt="Commencement">
      <figcaption>Delivering my Speech as the Selected Student Speaker at Commencement, May 2026</figcaption>
    </figure>
    <figure>
      <img src="../images/holland_win.jpg" alt="Holland Teach">
      <figcaption>Presentation of "Deriving the E&M Wave Equation using Maxwell's Equation", April 2026</figcaption>
    </figure>
    <figure>
      <img src="../images/holland_judge.jpg" alt="Holland Judge">
      <figcaption>Victory Following the 25th Annual Physics Prize Competition, April 2026</figcaption>
    </figure>
    <figure>
      <img src="../images/pbk_pose.jpg" alt="Phi Beta Kappa induction">
      <figcaption>Induction into Phi Beta Kappa, April 2026</figcaption>
    </figure>
    <figure>
      <img src="../images/chicago.jpg" alt="Chicago River">
      <figcaption>Chicago River, March 2026</figcaption>
    </figure>
    <figure>
      <img src="../images/vietnam.jpg" alt="Saigon">
      <figcaption>Saigon 2026</figcaption>
    </figure>
    <figure>
      <img src="../images/netsci2026.jpg" alt="NetSci 2026">
      <figcaption>NetSci 2026, Boston, MA</figcaption>
    </figure>
    <figure>
      <img src="../images/netsci2026.jpg" alt="NetSci 2026">
      <figcaption>NetSci 2026, Boston, MA</figcaption>
    </figure>
  </div>
</div>

<div class="photo-lightbox" id="photoLightbox">
  <button class="photo-lightbox-close" id="photoLightboxClose" aria-label="Close">&times;</button>
  <div class="photo-lightbox-content">
    <img id="photoLightboxImg" src="" alt="">
    <p class="photo-lightbox-caption" id="photoLightboxCaption"></p>
  </div>
</div>

<script>
(function() {
  const track = document.getElementById('photoSliderTrack');
  const lightbox = document.getElementById('photoLightbox');
  const lightboxImg = document.getElementById('photoLightboxImg');
  const lightboxCaption = document.getElementById('photoLightboxCaption');
  const lightboxClose = document.getElementById('photoLightboxCl
