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
  max-width: 900px;
  position: relative;
  left: 50%;
  transform: translateX(-50%);
}
.resume-download {
  text-align: center;
  margin-bottom: 32px;
}
.resume-download a {
  display: inline-block;
  padding: 10px 20px;
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
  font-size: 13px;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: #999;
  margin: 40px 0 14px;
  border-bottom: 1px solid #eee;
  padding-bottom: 8px;
}
.resume-card {
  border: 1px solid #e5e5e5;
  border-radius: 12px;
  padding: 18px 22px;
  margin-bottom: 14px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.06);
  background-color: #fff;
  transition: box-shadow 0.2s ease, transform 0.2s ease;
}
.resume-card:hover {
  box-shadow: 0 6px 16px rgba(0, 0, 0, 0.1);
  transform: translateY(-2px);
}
.resume-card summary {
  cursor: pointer;
  list-style: none;
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  gap: 12px;
}
.resume-card summary::-webkit-details-marker {
  display: none;
}
.resume-card .rc-title {
  font-size: 16px;
  font-weight: 600;
  color: #222;
}
.resume-card .rc-org {
  font-size: 14px;
  font-weight: 400;
  color: #555;
}
.resume-card .rc-dates {
  font-size: 13px;
  color: #999;
  white-space: nowrap;
}
.resume-card .rc-chevron {
  display: inline-block;
  margin-left: 8px;
  transition: transform 0.2s ease;
  color: #999;
}
.resume-card[open] .rc-chevron {
  transform: rotate(180deg);
}
.resume-card .rc-body {
  margin-top: 12px;
  font-size: 14px;
  color: #444;
}
.resume-card .rc-body ul {
  margin: 0;
  padding-left: 20px;
}
.resume-card .rc-body li {
  margin-bottom: 6px;
}
.resume-simple-list {
  font-size: 14px;
  color: #444;
  line-height: 1.9;
}
.skills-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-top: 8px;
}
.skills-tags span {
  font-size: 13px;
  padding: 6px 12px;
  border: 1px solid #ddd;
  border-radius: 20px;
  color: #444;
  background-color: #fafafa;
}
</style>

<div class="resume-wide">

<div class="resume-download">
  <a href="/files/randy-hong-cv.pdf" target="_blank">Download CV (PDF) ↗</a>
</div>

<div class="resume-section-title">Education</div>

<div class="resume-card" markdown="0">
  <div style="display: flex; justify-content: space-between; align-items: baseline; gap: 12px;">
    <div><span class="rc-title">Ph.D., Neuroscience (Neuroengineering)</span><br><span class="rc-org">University of California, Davis</span></div>
    <span class="rc-dates">Expected Dec 2031</span>
  </div>
</div>

<div class="resume-card" markdown="0">
  <div style="display: flex; justify-content: space-between; align-items: baseline; gap: 12px;">
    <div><span class="rc-title">B.S. Computational Neuroscience · B.A. Public Health Studies</span><br><span class="rc-org">Hobart and William Smith Colleges — Minor in Physics · GPA 4.07/4.00</span></div>
    <span class="rc-dates">Expected May 2026</span>
  </div>
</div>

<div class="resume-card" markdown="0">
  <div style="display: flex; justify-content: space-between; align-items: baseline; gap: 12px;">
    <div><span class="rc-title">Biotechnology Concentration</span><br><span class="rc-org">Yonsei University, Seoul, South Korea</span></div>
    <span class="rc-dates">Spring 2025</span>
  </div>
</div>

<div class="resume-section-title">Research Experience</div>

<details class="resume-card">
  <summary>
    <div><span class="rc-title">Independent Project Researcher</span> <span class="rc-org">— Hobart and William Smith Colleges</span></div>
    <span class="rc-dates">Jan 2026 – May 2026 <span class="rc-chevron">⌄</span></span>
  </summary>
  <div class="rc-body" markdown="1">
- Project advised by Professor Ileana Dumitriu (Dept. of Physics)—aimed at translating motor function intention into a neural prosthetic limb controllable using sEMG sensors and deep learning algorithms
- Collected sEMG data wirelessly transmitting serial data from a Myoware 2.0 sEMG sensor to a Sparkfun ESP32 Thing Plus, processed using Jupyter notebook scripts to produce gesture classifications
- Reproduced motor function within a neural prosthetic by sending gesture classifications from a Jupyter notebook script to an Arduino Uno and PCA9685 servo motor driver to produce contractions in the fingers of the prosthetic
  </div>
</details>

<details class="resume-card">
  <summary>
    <div><span class="rc-title">Honors Thesis Candidate</span> <span class="rc-org">— Hobart and William Smith Colleges</span></div>
    <span class="rc-dates">Jun 2025 – May 2026 <span class="rc-chevron">⌄</span></span>
  </summary>
  <div class="rc-body" markdown="1">
- Thesis coadvised by Professors Daniel Graham (Psychological Science) and Yan Hao (Mathematics)—predicting edge weight asymmetries within a mouse brain connectome using a one-parameter generative colliding-spreading model
- Assessed methodologies for predicting edge asymmetries—edge weight symmetrization, edge traffic difference measures, message load injection variance—to identify parameters maximizing predictive capability
- Utilized MATLAB for adjacency matrix manipulation, live scripts for parameter optimization, and data visualization
- Performed extensive literature review on colliding-spreading model consistency with real mammalian neural computation and edge asymmetries' role in information-spreading optimization
  </div>
</details>

<details class="resume-card">
  <summary>
    <div><span class="rc-title">Summer Research Student</span> <span class="rc-org">— Neuromatch Academy</span></div>
    <span class="rc-dates">Jul 2025 <span class="rc-chevron">⌄</span></span>
  </summary>
  <div class="rc-body" markdown="1">
- Admitted to a rigorous computational neuroscience summer program equipping students with modeling, data analysis, and coding experience in Python (Matplotlib, NumPy, scikit-learn)
- Developed a descriptive logistic regression model predicting the onset of naturalistic upper-limb motor function activation in epilepsy patients, using ECoG and movement data from the AJILE12 dataset to achieve ~70% accuracy
- Manipulated and visualized ~800GB of ECoG data—performing PCA, extracting beta frequency bands via bandpass filters, and constructing movement information vectors
  </div>
</details>

<details class="resume-card">
  <summary>
    <div><span class="rc-title">Research Assistant</span> <span class="rc-org">— Hobart and William Smith Colleges</span></div>
    <span class="rc-dates">Sep 2024 – Dec 2024 <span class="rc-chevron">⌄</span></span>
  </summary>
  <div class="rc-body" markdown="1">
- Advised by Professor Thomas Jensen and Lab Manager Justine Simms (Biology)—used controlled anesthesia injections into chicken embryo eggs to evaluate cerebral brain function in early-mid incubation (stage 33 HH) via embryonic movement
- Experimentally assessed cerebral brain function onset by varying anesthesia dose timing across developmental periods, measuring movement via candling and heart rate using an Eggbuddy device
  </div>
</details>

<details class="resume-card">
  <summary>
    <div><span class="rc-title">Research Assistant</span> <span class="rc-org">— Hobart and William Smith Colleges</span></div>
    <span class="rc-dates">Aug 2023 – Aug 2024 <span class="rc-chevron">⌄</span></span>
  </summary>
  <div class="rc-body" markdown="1">
- Advised by Professor Stephanie Anglin (Psychological Science)—correlational study on public epistemological perception of science's truth-assessment capabilities vs. understanding of scientific principles
- Developed coding criteria to categorize qualitative responses into quantitative data; manually categorized hundreds of responses; performed statistical analysis in SPSS
- Facilitated lab efforts via pilot testing, literature review, and writing portions of abstracts and conference proposals
  </div>
</details>

<div class="resume-section-title">Teaching Experience</div>

<details class="resume-card">
  <summary>
    <div><span class="rc-title">Teaching Assistant, PSY230 Biopsychology</span> <span class="rc-org">— Hobart and William Smith Colleges</span></div>
    <span class="rc-dates">Aug 2024 – May 2026 <span class="rc-chevron">⌄</span></span>
  </summary>
  <div class="rc-body" markdown="1">
- TA for Professor Elizabeth Belcher—dedicated three hours weekly to lecturing, facilitating exam review sessions, and writing exam-styled homework questions
- Lectured on neuroanatomy, neurophysiology, neurodevelopment, and sensorimotor function, prioritizing student engagement and pacing
- Served as liaison between students and professor to address confusion and refine teaching clarity
  </div>
</details>

<div class="resume-section-title">Professional Experience</div>

<details class="resume-card">
  <summary>
    <div><span class="rc-title">Career Assistant Intern</span> <span class="rc-org">— Salisbury Center for Career Services</span></div>
    <span class="rc-dates">Jan 2024 – Dec 2024 <span class="rc-chevron">⌄</span></span>
  </summary>
  <div class="rc-body" markdown="1">
- Assisted students one-on-one with career development, internship applications, resumes, cover letters, and LinkedIn profiles
- Managed privacy of sensitive student information while developing resumes efficiently
- Attended meetings with Associate Director to review and streamline the resume development process
  </div>
</details>

<details class="resume-card">
  <summary>
    <div><span class="rc-title">Medical Intern</span> <span class="rc-org">— Chapters Family Treatment Center</span></div>
    <span class="rc-dates">Jun 2023 – Dec 2023 <span class="rc-chevron">⌄</span></span>
  </summary>
  <div class="rc-body" markdown="1">
- Assisted the Medical Director in diagnosis screening—researching and administering neuropsychological exams (KBIT-2, aimswebPlus, General Cognitive Assessment, MINI, PID-5, Conners 4th Edition)
- Developed a medical report template with exam descriptions, result charts, and interpretive summaries
- Facilitated non-clinical groups with teen/adolescent patients, documenting behavior and mental status exams via BestNotes
  </div>
</details>

<div class="resume-section-title">Academic Service</div>

<details class="resume-card">
  <summary>
    <div><span class="rc-title">President</span> <span class="rc-org">— Asian Student Union</span></div>
    <span class="rc-dates">Apr 2023 – Dec 2024 <span class="rc-chevron">⌄</span></span>
  </summary>
  <div class="rc-body" markdown="1">
- Led the only Asian-diaspora focused cultural club on campus, boosting DEI incentives through cross-collaboration with other cultural clubs and the institution
- Organized events of 100+ attendees, managing budgets of several thousand dollars and external company communication (Lunar New Year Celebration, Mid-Autumn Festival, Diwali)
- Acted as liaison between Student Engagement, the Adams Intercultural Center, student government, and the Asian Student Union
  </div>
</details>

<div class="resume-section-title">Honors & Grants</div>

<div class="resume-card resume-simple-list" markdown="1">
- NIH T32 Training Program in Basic Neuroscience Fellowship — *May 2026*
- 25th Annual Physics Holland Prize Winner — *April 2026*
- Professor Jeffrey M. Greenspon Memorial Award — *April 2026*
- Elected to Phi Beta Kappa — *March 2026*
- Department of Physics Research Funding Grant — *January 2026*
- Summer Mentored Research Grant — *June 2025*
- McGuire Study Abroad Fund — *December 2024*
- Elected to Tri-Alpha Honor Society — *March 2024*
- Elected to Psi Chi Honor Society — *February 2024*
- Dept. of Psychological Science Dr. Stephen L. Cohen '67 Grant — *February 2024*
- Salisbury Center Guaranteed Internship Funding — *January 2024*
- First Year Academic Achievement Award — *April 2023*
- Charles '01 & Charles '32 Allison Endowed Scholarship Fund — *September 2022*
- Mara '66 and Frank O'Laughlin Endowed Scholarship Fund — *September 2022*
- International Baccalaureate Diploma — *May 2022*
- Posse Foundation Full-Tuition Leadership Scholarship — *January 2021*
</div>

<div class="resume-section-title">Skills & Tools</div>

<div class="resume-card" markdown="0">
  <div class="skills-tags">
    <span>Python</span><span>PyTorch</span><span>scikit-learn</span><span>NumPy</span><span>Pandas</span><span>Matplotlib</span><span>MATLAB</span><span>R</span><span>Arduino IDE</span><span>Signal Processing</span><span>Circuit Analysis</span><span>PCB Soldering</span><span>ESP32</span><span>PCA9685</span>
  </div>
</div>

</div>
