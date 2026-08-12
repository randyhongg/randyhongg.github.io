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
}
.photo-slider {
  display: flex;
  overflow-x: auto;
  scroll-snap-type: x mandatory;
  gap: 20px;
  padding: 4px 4px 16px;
  scrollbar-width: none;
}
.photo-slider::-webkit-scrollbar {
  display: none;
}
.photo-slider figure {
  flex: 0 0 auto;
  width: 320px;
  scroll-snap-align: start;
  margin: 0;
  border: 1px solid #e5e5e5;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.06);
  background-color: #fff;
  cursor: pointer;
  transition: box-shadow 0.2s ease, transform 0.2s ease;
}
.photo-slider figure:hover {
  box-shadow: 0 6px 16px rgba(0, 0, 0, 0.12);
  transform: translateY(-2px);
}
.photo-slider img {
  width: 100%;
  aspect-ratio: 4 / 3;
  object-fit: cover;
  display: block;
  transition: transform 0.3s ease;
}
.photo-slider figure:hover img {
  transform: scale(1.04);
}
.photo-slider figcaption {
  padding: 10px 14px;
  font-size: 13px;
  color: #666;
  text-align: center;
}
.photo-slider-nav {
  display: flex;
  justify-content: center;
  gap: 12px;
  margin-top: 8px;
}
.photo-slider-nav button {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  border: 1px solid #ddd;
  background: #fff;
  color: #333;
  font-size: 16px;
  cursor: pointer;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.06);
  transition: box-shadow 0.2s ease, transform 0.2s ease;
}
.photo-slider-nav button:hover {
  box-shadow: 0 6px 16px rgba(0, 0, 0, 0.1);
  transform: translateY(-2px);
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
  .photo-slider figure {
    width: 260px;
  }
}
</style>
## About Me
{: style="text-align: center;"}

<img class="profile-banner-img" src="../images/banner.jpg" alt="Randy Hong, Ph.D. Student, University of California Davis, Neuroscience Graduate Group">

<div class="reveal" style="text-align: justify; text-align-last: justify; margin-bottom: 2rem;" markdown="1">

I am interested in decoding neural signals and interfacing with the brain. My catalyst into mathematics stemmed from a need to interpret neural signals and blossomed into a deep appreciation of its application towards understanding phenomena of the physical world. My coursework in theoretical physics (electromagnetism, quantum mechanics) reaffirmed this admiration; behind abstraction laid truths that become tangible through mathematical rigor.

</div>

## Photos
{: style="text-align: center;"}

<div class="photo-slider-wrap">
  <div class="photo-slider" id="photoSlider">
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
  <div class="photo-slider-nav">
    <button id="photoSliderPrev" aria-label="Previous photo">←</button>
    <button id="photoSliderNext" aria-label="Next photo">→</button>
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
  const slider = document.getElementById('photoSlider');
  const prevBtn = document.getElementById('photoSliderPrev');
  const nextBtn = document.getElementById('photoSliderNext');
  const lightbox = document.getElementById('photoLightbox');
  const lightboxImg = document.getElementById('photoLightboxImg');
  const lightboxCaption = document.getElementById('photoLightboxCaption');
  const lightboxClose = document.getElementById('photoLightboxClose');
  if (!slider) return;

  const figures = slider.querySelectorAll('figure');
  const totalFigures = figures.length;
  const gap = 20;
  let currentIndex = 0;
  let autoTimer;

  function cardStep() {
    return figures[0].getBoundingClientRect().width + gap;
  }

  function scrollToIndex(index, smooth) {
    slider.scrollTo({ left: index * cardStep(), behavior: smooth ? 'smooth' : 'auto' });
  }

  function goToNext() {
    currentIndex++;
    
    // If we've reached the last photo, go back to the beginning
    if (currentIndex >= totalFigures) {
      currentIndex = 0;
      scrollToIndex(currentIndex, false);
      return;
    }
    
    scrollToIndex(currentIndex, true);
  }

  function goToPrev() {
    currentIndex--;
    
    // If we've gone before the first photo, go to the last
    if (currentIndex < 0) {
      currentIndex = totalFigures - 1;
      scrollToIndex(currentIndex, false);
      return;
    }
    
    scrollToIndex(currentIndex, true);
  }

  function startAuto() {
    stopAuto();
    autoTimer = setInterval(goToNext, 2500);
  }
  
  function stopAuto() {
    clearInterval(autoTimer);
  }

  prevBtn.addEventListener('click', () => { 
    goToPrev(); 
    stopAuto(); 
    startAuto(); 
  });
  
  nextBtn.addEventListener('click', () => { 
    goToNext(); 
    stopAuto(); 
    startAuto(); 
  });

  slider.addEventListener('mouseenter', stopAuto);
  slider.addEventListener('mouseleave', startAuto);
  slider.addEventListener('touchstart', stopAuto, { passive: true });
  slider.addEventListener('touchend', startAuto);

  figures.forEach((figure) => {
    figure.addEventListener('click', () => {
      const img = figure.querySelector('img');
      const caption = figure.querySelector('figcaption');
      lightboxImg.src = img.src;
      lightboxImg.alt = img.alt;
      lightboxCaption.textContent = caption ? caption.textContent : '';
      lightbox.classList.add('open');
    });
  });

  function closeLightbox() {
    lightbox.classList.remove('open');
  }

  lightboxClose.addEventListener('click', closeLightbox);
  lightbox.addEventListener('click', (e) => {
    if (e.target === lightbox) closeLightbox();
  });
  document.addEventListener('keydown', (e) => {
    if (e.key === 'Escape') closeLightbox();
  });

  // Start autoscrolling
  startAuto();
})();
</script>

## Featured Stories
{: style="text-align: center;"}

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
{: style="text-align: center;"}

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
