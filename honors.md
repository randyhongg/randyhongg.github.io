---
layout: single
title: "Resume"
permalink: /resume/
author_profile: false
---
## Resume
{: style="text-align: center;"}
<style>
.page__title {
  display: none;
}
.resume-wide {
  width: 90vw;
  max-width: 780px;
  position: relative;
  left: 50%;
  transform: translateX(-50%);
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
}
.resume-download {
  text-align: center;
  margin-bottom: 36px;
}
.resume-download a {
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
.resume-download a:hover {
  box-shadow: 0 6px 16px rgba(0, 0, 0, 0.1);
  transform: translateY(-2px);
}
.resume-section-title {
  font-size: 12px;
  font-weight: 700;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: #b0b0b0;
  margin: 44px 0 16px;
  padding-bottom: 10px;
  border-bottom: 1px solid #ececec;
}
.resume-section-title:first-of-type {
  margin-top: 0;
}
.resume-card {
  border: 1px solid #e8e8e8;
  border-radius: 14px;
  padding: 20px 24px;
  margin-bottom: 12px;
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.04);
  background-color: #fff;
  transition: box-shadow 0.2s ease, transform 0.2s ease, border-color 0.2s ease;
}
.resume-card:hover {
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.08);
  transform: translateY(-2px);
  border-color: #ddd;
}
.resume-card summary {
  cursor: pointer;
  list-style: none;
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 16px;
}
.resume-card summary::-webkit-details-marker {
  display: none;
}
.rc-heading {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 16px;
}
.rc-heading-left {
  display: flex;
  align-items: center;
  gap: 14px;
  min-width: 0;
}
.rc-logo {
  width: 36px;
  height: 36px;
  border-radius: 8px;
  object-fit: contain;
  background-color: #fafafa;
  border: 1px solid #eee;
  padding: 4px;
  flex-shrink: 0;
}
.rc-title {
  font-size: 15.5px;
  font-weight: 600;
  color: #1a1a1a;
  line-height: 1.4;
}
.rc-org {
  font-size: 14px;
  font-weight: 400;
  color: #777;
  line-height: 1.4;
}
.rc-dates {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  font-size: 12px;
  font-weight: 500;
  color: #888;
  white-space: nowrap;
  background-color: #f6f6f7;
  padding: 5px 11px;
  border-radius: 20px;
  flex-shrink: 0;
}
.rc-chevron {
  display: inline-block;
  font-size: 13px;
  transition: transform 0.2s ease;
  color: #aaa;
}
.resume-card[open] .rc-chevron {
  transform: rotate(180deg);
}
.resume-card[open] {
  border-color: #ddd;
}
.rc-body {
  margin-top: 14px;
  padding-top: 14px;
  border-top: 1px solid #f0f0f0;
  font-size: 14px;
  color: #4a4a4a;
  line-height: 1.55;
}
.rc-body ul {
  margin: 0;
  padding-left: 18px;
}
.rc-body li {
  margin-bottom: 8px;
}
.rc-body li:last-child {
  margin-bottom: 0;
}
.honors-list {
  padding: 6px 24px;
}
.honor-item {
  border-bottom: 1px solid #f2f2f2;
}
.honor-item:last-child {
  border-bottom: none;
}
.honor-item summary {
  cursor: pointer;
  list-style: none;
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 16px;
  padding: 13px 0;
  font-size: 14.5px;
  color: #333;
}
.honor-item summary::-webkit-details-marker {
  display: none;
}
.honor-title-wrap {
  display: flex;
  align-items: center;
  gap: 10px;
  min-width: 0;
}
.honor-logo {
  width: 22px;
  height: 22px;
  border-radius: 5px;
  object-fit: contain;
  background-color: #fafafa;
  border: 1px solid #eee;
  padding: 2px;
  flex-shrink: 0;
}
.honor-item .honor-date {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  font-size: 12.5px;
  color: #999;
  white-space: nowrap;
  font-style: normal;
}
.honor-item .honor-chevron {
  font-size: 11px;
  color: #bbb;
  transition: transform 0.2s ease;
}
.honor-item[open] .honor-chevron {
  transform: rotate(180deg);
}
.honor-item .honor-body {
  padding: 0 0 16px;
  font-size: 13.5px;
  color: #666;
  line-height: 1.55;
}
.skills-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
}
.skills-tags span {
  font-size: 13px;
  font-weight: 500;
  padding: 7px 14px;
  border: 1px solid #e5e5e5;
  border-radius: 20px;
  color: #444;
  background-color: #fafafa;
  transition: background-color 0.15s ease, border-color 0.15s ease;
}
.skills-tags span:hover {
  background-color: #f0f0f0;
  border-color: #ddd;
}
@media (max-width: 600px) {
  .rc-heading, .resume-card summary {
    flex-direction: column;
    align-items: flex-start;
    gap: 8px;
  }
  .honors-list li {
    flex-direction: column;
    gap: 2px;
  }
}
</style>

<div class="resume-wide">

<div class="resume-download">
<a href="/files/randy-hong-cv.pdf" target="_blank">Download CV (PDF) &#8599;</a>
</div>

<div class="resume-section-title">Education</div>

<div class="resume-card">
<div class="rc-heading">
<div class="rc-heading-left">
<img class="rc-logo" src="../images/davis_logo.png" alt="UC Davis logo">
<div><span class="rc-title">Ph.D., Neuroscience</span><br><span class="rc-org">University of California, Davis</span></div>
</div>
<span class="rc-dates">Expected Dec 2031</span>
</div>
</div>

<div class="resume-card">
<div class="rc-heading">
<div class="rc-heading-left">
<img class="rc-logo" src="../images/hws_logo.png" alt="HWS logo">
<div><span class="rc-title">B.S., Computational Neuroscience</span><br><span class="rc-org">Hobart and William Smith Colleges</span></div>
</div>
<span class="rc-dates">May 2026</span>
</div>
</div>

<div class="resume-section-title">Research Experience</div>

<details class="resume-card">
<summary>
<div class="rc-heading-left">
<img class="rc-logo" src="../images/hws_logo.png" alt="HWS logo">
<div><span class="rc-title">Undergraduate Student Researcher</span> <span class="rc-org">&mdash; Hobart and William Smith Colleges</span></div>
</div>
<span class="rc-dates">Jan 2026 &ndash; May 2026 <span class="rc-chevron">&#8964;</span></span>
</summary>
<div class="rc-body">
<ul>
<li>Project advised by Professor Ileana Dumitriu (Dept. of Physics)&mdash;aimed at translating motor function intention into a neural prosthetic limb controllable using sEMG sensors and deep learning algorithms</li>
<li>Collected sEMG data wirelessly transmitting serial data from a Myoware 2.0 sEMG sensor to a Sparkfun ESP32 Thing Plus, processed using Jupyter notebook scripts to produce gesture classifications</li>
<li>Reproduced motor function within a neural prosthetic by sending gesture classifications from a Jupyter notebook script to an Arduino Uno and PCA9685 servo motor driver to produce contractions in the fingers of the prosthetic</li>
</ul>
</div>
</details>

<details class="resume-card">
<summary>
<div class="rc-heading-left">
<img class="rc-logo" src="../images/hws_logo.png" alt="HWS logo">
<div><span class="rc-title">Honors Thesis Candidate</span> <span class="rc-org">&mdash; Hobart and William Smith Colleges</span></div>
</div>
<span class="rc-dates">Jun 2025 &ndash; May 2026 <span class="rc-chevron">&#8964;</span></span>
</summary>
<div class="rc-body">
<ul>
<li>Thesis coadvised by Professors Daniel Graham (Psychological Science) and Yan Hao (Mathematics)&mdash;predicting edge weight asymmetries within a mouse brain connectome using a one-parameter generative colliding-spreading model</li>
<li>Assessed methodologies for predicting edge asymmetries&mdash;edge weight symmetrization, edge traffic difference measures, message load injection variance&mdash;to identify parameters maximizing predictive capability</li>
<li>Utilized MATLAB for adjacency matrix manipulation, live scripts for parameter optimization, and data visualization</li>
<li>Performed extensive literature review on colliding-spreading model consistency with real mammalian neural computation and edge asymmetries' role in information-spreading optimization</li>
</ul>
</div>
</details>

<div class="resume-section-title">Academic Service</div>

<details class="resume-card">
<summary>
<div class="rc-heading-left">
<img class="rc-logo" src="../images/hws_logo.png" alt="HWS logo">
<div><span class="rc-title">President</span> <span class="rc-org">&mdash; Asian Student Union</span></div>
</div>
<span class="rc-dates">Apr 2023 &ndash; Dec 2024 <span class="rc-chevron">&#8964;</span></span>
</summary>
<div class="rc-body">
<ul>
<li>Led the only Asian-diaspora focused cultural club on campus, boosting DEI incentives through cross-collaboration with other cultural clubs and the institution</li>
<li>Organized events of 100+ attendees, managing budgets of several thousand dollars and external company communication (Lunar New Year Celebration, Mid-Autumn Festival, Diwali)</li>
<li>Acted as liaison between Student Engagement, the Adams Intercultural Center, student government, and the Asian Student Union</li>
</ul>
</div>
</details>

<div class="resume-section-title">Honor Societies</div>

<div class="resume-card honors-list">
<details class="honor-item">
<summary><span class="honor-title-wrap"><img class="honor-logo" src="../images/phi_beta_kappa_logo.png" alt="Phi Beta Kappa logo"><span>Phi Beta Kappa</span></span><span class="honor-date">March 2026 <span class="honor-chevron">&#8964;</span></span></summary>
<div class="honor-body">Phi Beta Kappa is the oldest and most prestigious academic honor society in the United States, recognizing students who have demonstrated intellectual curiosity and achieved distinction in the liberal arts and sciences. Highly selective, merit and character based.</div>
</details>
<details class="honor-item">
<summary><span class="honor-title-wrap"><img class="honor-logo" src="../images/tri_alpha_logo.png" alt="Tri-Alpha logo"><span>Tri-Alpha Honor Society</span></span><span class="honor-date">March 2024 <span class="honor-chevron">&#8964;</span></span></summary>
<div class="honor-body">Tri Alpha recognizes first generation college students who meet the rigorous criteria established for membership.</div>
</details>
<details class="honor-item">
<summary><span class="honor-title-wrap"><img class="honor-logo" src="../images/psi_chi_logo.png" alt="Psi Chi logo"><span>Psi Chi Honor Society</span></span><span class="honor-date">February 2024 <span class="honor-chevron">&#8964;</span></span></summary>
<div class="honor-body">Psi Chi is the international honor society in psychology, recognizing students who meet the rigorous criteria established for membership.</div>
</details>
</div>

<div class="resume-section-title">Awards &amp; Honors</div>

<div class="resume-card honors-list">
<details class="honor-item">
<summary><span class="honor-title-wrap"><img class="honor-logo" src="../images/hws_logo.png" alt="HWS logo"><span>25th Annual Physics Holland Prize Winner</span></span><span class="honor-date">April 2026 <span class="honor-chevron">&#8964;</span></span></summary>
<div class="honor-body">Awarded to the student who conducts the best lecture on a physics derivation of their choice. Winner is awarded monetary compensation. I demonstrated how fixing the mathematical inconsistencies of Ampere's law led to the Maxwell equations and conclusion that light is a propagating electromagnetic wave.</div>
</details>
<details class="honor-item">
<summary><span class="honor-title-wrap"><img class="honor-logo" src="../images/hws_logo.png" alt="HWS logo"><span>Professor Jeffrey M. Greenspon Memorial Award</span></span><span class="honor-date">April 2026 <span class="honor-chevron">&#8964;</span></span></summary>
<div class="honor-body">Awarded to one graduating senior who has shown high achievement and a strong interest in neuroscience.</div>
</details>
<details class="honor-item">
<summary><span class="honor-title-wrap"><img class="honor-logo" src="../images/ib_logo.png" alt="International Baccalaureate logo"><span>International Baccalaureate Diploma</span></span><span class="honor-date">May 2022 <span class="honor-chevron">&#8964;</span></span></summary>
<div class="honor-body">Demonstrates completion of the International Baccalaureate Diploma Program. Internationally recognized for its rigor and preparation of students for higher-level education. Obtainment of the diploma indicates the completion of IB examinations, an independent research paper, and an original community service project.</div>
</details>
</div>

<div class="resume-section-title">Grants &amp; Funding</div>

<div class="resume-card honors-list">
<details class="honor-item">
<summary><span class="honor-title-wrap"><img class="honor-logo" src="../images/nih_logo.png" alt="NIH logo"><span>NIH T32 Training Program in Basic Neuroscience Fellowship</span></span><span class="honor-date">May 2026 <span class="honor-chevron">&#8964;</span></span></summary>
<div class="honor-body">Selectively issued to incoming graduate students to support their neuroscience training. Provides trainees with one year of tuition, stipend, and travel funding to scientific conferences. Appointment is competitive and in recognition of outstanding undergraduate academic records and research experience.</div>
</details>
<details class="honor-item">
<summary><span class="honor-title-wrap"><img class="honor-logo" src="../images/hws_logo.png" alt="HWS logo"><span>Department of Physics Research Funding Grant</span></span><span class="honor-date">January 2026 <span class="honor-chevron">&#8964;</span></span></summary>
<div class="honor-body">Issued in support of an sEMG prosthesis project.</div>
</details>
<details class="honor-item">
<summary><span class="honor-title-wrap"><img class="honor-logo" src="../images/hws_logo.png" alt="HWS logo"><span>Summer Mentored Research Grant</span></span><span class="honor-date">June 2025 <span class="honor-chevron">&#8964;</span></span></summary>
<div class="honor-body">Stipend issued to students in support of summer research efforts during the summer of 2025.</div>
</details>
<details class="honor-item">
<summary><span class="honor-title-wrap"><img class="honor-logo" src="../images/hws_logo.png" alt="HWS logo"><span>McGuire Study Abroad Fund</span></span><span class="honor-date">December 2024 <span class="honor-chevron">&#8964;</span></span></summary>
<div class="honor-body">Issued to one student based on academic merit to financially support a study abroad experience, used in Seoul, South Korea.</div>
</details>
<details class="honor-item">
<summary><span class="honor-title-wrap"><img class="honor-logo" src="../images/hws_logo.png" alt="HWS logo"><span>Dept. of Psychological Science Dr. Stephen L. Cohen '67 Grant</span></span><span class="honor-date">February 2024 <span class="honor-chevron">&#8964;</span></span></summary>
<div class="honor-body">Issued to sponsor travel funds for the Eastern Psychological Association Conference in Philadelphia, Pennsylvania.</div>
</details>
<details class="honor-item">
<summary><span class="honor-title-wrap"><img class="honor-logo" src="../images/posse_logo.png" alt="Posse Foundation logo"><span>Posse Foundation Full-Tuition Leadership Scholarship</span></span><span class="honor-date">January 2021 <span class="honor-chevron">&#8964;</span></span></summary>
<div class="honor-body">Awarded by the Posse Foundation, a nonprofit organization that partners with select colleges and universities in the United States to provide scholarships through a cohort-based model. Students receive four-year, full-tuition scholarships. Highly selective, merit and leadership based.</div>
</details>
</div>

<div class="resume-section-title">Skills &amp; Tools</div>

<div class="resume-card">
<div class="skills-tags">
<span>Python</span><span>PyTorch</span><span>scikit-learn</span><span>NumPy</span><span>Pandas</span><span>Matplotlib</span><span>MATLAB</span><span>R</span><span>Arduino IDE</span><span>Signal Processing</span><span>Circuit Analysis</span><span>PCB Soldering</span><span>ESP32</span><span>PCA9685</span>
</div>
</div>

</div>
