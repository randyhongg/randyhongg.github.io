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
.research-unit {
  margin: 56px 0;
}
.research-unit:first-of-type {
  margin-top: 0;
}
.research-eyebrow {
  font-size: 12px;
  font-weight: 700;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: #666;
  margin: 0 0 14px;
  padding-bottom: 10px;
  border-bottom: 1px solid #ececec;
  text-align: center;
}
.research-body {
  text-align: justify;
  text-align-last: justify;
  margin-bottom: 24px;
}
.research-images {
  display: flex;
  gap: 12px;
}
.research-images img {
  width: 49%;
  border-radius: 6px;
  display: block;
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
.section-title {
  text-align: center;
  margin-bottom: 1.5rem;
}
@media (max-width: 700px) {
  .photo-slider figure {
    width: 260px;
  }
}
</style>

<div class="research-unit" style="margin-top: 24px;">

<p class="research-eyebrow">Neural interfaces</p>

<div class="research-body">

Artificial neural networks have provided us with an approach towards translating noisy neural signals into motor function control, evident through the successes of prostheses and brain computer interfaces on the market. However, biological heterogeneity and model architectures that demand high quantities of training data have introduced challenges in making this technology accessible and generalizable. I am interested in using neuroscience and mathematical theory to forge approaches that are more cost efficient and accurate than contemporary data analysis methods. Particular interest in engineering non-invasive closed-loop neural interfaces.

</div>

<div class="research-images">
  <img src="../images/neural_network_visual.png">
  <img src="../images/data_plot_visual.png">
</div>

</div>

<div class="research-unit">

<p class="research-eyebrow">Network dynamics</p>

<div class="research-body">

Despite our efforts, we understand very little about how the brain communicates information across its connectome from first principles due to limitations in our measurement tools. Whatever strategy is imposed is clearly very effective and efficient, being able to foster consciousness while consuming the same number of watts as a lightbulb, while only using neurons that are constrained to biophysical restrictions. This is in stark contrast to contemporary artifical intelligence models, which consume high quantities of energy and fail to recreate feats of the brain despite their nodes not being subject to biophysical restrictions. I am interested in studying network dynamics, connectome structure, and information passing strategies to develop biologically-inspired computational algorithms that are cost efficient and effective.  

</div>

<div class="research-images">
  <img src="../images/sphere_visual.png">
  <img src="../images/graph_visual.png">
</div>

</div>

<a class="cta-button" href="/projects/">View my projects →</a>

## Conference Presentations
{: .section-title}

<div class="photo-slider-wrap">
  <div class="photo-slider" id="conferenceSlider">
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
  <div class="photo-slider-nav">
    <button id="conferenceSliderPrev" aria-label="Previous photo">←</button>
    <button id="conferenceSliderNext" aria-label="Next photo">→</button>
  </div>
</div>

<div class="photo-lightbox" id="conferenceLightbox">
  <button class="photo-lightbox-close" id="conferenceLightboxClose" aria-label="Close">&times;</button>
  <div class="photo-lightbox-content">
    <img id="conferenceLightboxImg" src="" alt="">
    <p class="photo-lightbox-caption" id="conferenceLightboxCaption"></p>
  </div>
</div>

<script>
(function() {
  const slider = document.getElementById('conferenceSlider');
  const prevBtn = document.getElementById('conferenceSliderPrev');
  const nextBtn = document.getElementById('conferenceSliderNext');
  const lightbox = document.getElementById('conferenceLightbox');
  const lightboxImg = document.getElementById('conferenceLightboxImg');
  const lightboxCaption = document.getElementById('conferenceLightboxCaption');
  const lightboxClose = document.getElementById('conferenceLightboxClose');
  if (!slider) return;

  const card = slider.querySelector('figure');
  if (!card) return;
  const gap = 20;
  let autoTimer;
  let suppressClick = false;

  function cardStep() {
    return card.getBoundingClientRect().width + gap;
  }

  function scrollByCard(direction) {
    slider.scrollBy({ left: direction * cardStep(), behavior: 'smooth' });
  }

  function advance() {
    const atEnd = slider.scrollLeft + slider.clientWidth >= slider.scrollWidth - 5;
    if (atEnd) {
      slider.scrollTo({ left: 0, behavior: 'smooth' });
    } else {
      scrollByCard(1);
    }
  }

  function startAuto() {
    stopAuto();
    autoTimer = setInterval(advance, 3000);
  }
  function stopAuto() {
    clearInterval(autoTimer);
  }

  prevBtn.addEventListener('click', () => { scrollByCard(-1); stopAuto(); startAuto(); });
  nextBtn.addEventListener('click', () => { scrollByCard(1); stopAuto(); startAuto(); });

  slider.addEventListener('mouseenter', stopAuto);
  slider.addEventListener('mouseleave', startAuto);
  slider.addEventListener('touchstart', stopAuto, { passive: true });
  slider.addEventListener('touchend', startAuto);

  slider.querySelectorAll('figure').forEach((figure) => {
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

  startAuto();
})();
</script>
