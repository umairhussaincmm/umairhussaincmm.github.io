---
layout: home
title: Umair Hussain
description: Data Scientist & Computational Mechanics PhD — blending physics-based modeling with AI for real-world engineering.
---

<!-- ═══════════════════════════════════════════
     HERO
══════════════════════════════════════════════ -->
<section class="hero" id="hero">
  <div class="hero__text">
    <span class="hero__eyebrow">Data Scientist · PhD in Computational Mechanics</span>
    <h1 class="hero__name">Umair<br>Hussain</h1>
    <p class="hero__tagline">
      Bridging the gap between physics-based simulation and data-driven AI — building intelligent solutions for complex engineering problems.
    </p>
    <div class="hero__cta">
      <a href="#research" class="btn btn--gold">Explore Research</a>
      <a href="#contact" class="btn btn--outline">Get in Touch</a>
    </div>
  </div>
  <div class="hero__image-wrap">
    <img src="/images/dp2.jpg" alt="Umair Hussain" class="hero__photo">
  </div>
</section>

<!-- ═══════════════════════════════════════════
     ABOUT
══════════════════════════════════════════════ -->
<section class="section" id="about">
  <div class="section__header anim-fadein">
    <span class="section__label">Who I Am</span>
    <h2 class="section__title">About</h2>
    <div class="section__divider"></div>
  </div>

  <div class="about__grid">
    <div class="about__bio anim-fadein anim-delay-1">
      <p>
        I am a Data Scientist at <strong>ChampionX (now part of SLB)</strong>, developing AI and machine learning solutions for the oil &amp; gas industry. My work sits at the intersection of data science and physics — building models that don't just fit data but respect the underlying physics of the systems they describe.
      </p>
      <p>
        My technical foundation comes from a <strong>PhD at IIT Madras</strong>, where I specialized in computational mechanics, phase field modeling, and finite element methods. My doctoral research focused on modeling the electrochemical responses of Li-ion battery anodes using a coupled multiphysics framework — solving chemical diffusion under stress, coupled with electrochemical reactions.
      </p>
      <p>
        I am proficient in the open-source C++ FEM library <a href="https://www.dealii.org/" target="_blank"><strong>deal.II</strong></a>, and have contributed a standalone phase field solver to its <a href="https://www.dealii.org/current/doxygen/deal.II/code_gallery_Crystal_Growth_Phase_Field_Model.html" target="_blank">code gallery</a>. I also enhanced simulation performance by 60% through MPI parallelization using PETSc.
      </p>

      <div class="skills-grid" style="margin-top:1.5rem;">
        <span class="skill-tag">Phase Field Modeling</span>
        <span class="skill-tag">Finite Element Method</span>
        <span class="skill-tag">Machine Learning</span>
        <span class="skill-tag">C++</span>
        <span class="skill-tag">Python</span>
        <span class="skill-tag">MATLAB</span>
        <span class="skill-tag">deal.II</span>
        <span class="skill-tag">PETSc</span>
        <span class="skill-tag">TensorFlow</span>
        <span class="skill-tag">Parallel Computing</span>
        <span class="skill-tag">Gaussian Process Regression</span>
        <span class="skill-tag">Multiphysics Modeling</span>
        <span class="skill-tag">Abaqus</span>
        <span class="skill-tag">ParaView</span>
        <span class="skill-tag">Linux</span>
      </div>
    </div>

    <div class="about__sidebar anim-fadein anim-delay-2">
      <div class="info-card">
        <div class="info-card__title">Education</div>
        <div class="edu-item">
          <div class="edu-item__degree">M.S. + Ph.D. in Mechanical Engineering</div>
          <div class="edu-item__inst"><a href="https://mech.iitm.ac.in/meiitm/" target="_blank">IIT Madras, Chennai</a></div>
          <div class="edu-item__year">2019 – 2025 &nbsp</div>
        </div>
        <div class="edu-item">
          <div class="edu-item__degree">B.Tech in Mechanical Engineering</div>
          <div class="edu-item__inst"><a href="https://www.jmi.ac.in/mechanical" target="_blank">Jamia Millia Islamia, New Delhi</a></div>
          <div class="edu-item__year">2015 – 2019 &nbsp</div>
        </div>
      </div>

      <div class="info-card">
        <div class="info-card__title">Awards & Fellowships</div>
        <div class="edu-item">
          <div class="edu-item__degree">Prime Minister Research Fellowship (PMRF)</div>
          <div class="edu-item__year">2019 – 2024 &nbsp</div>
        </div>
        <div class="edu-item">
          <div class="edu-item__degree">Half-time Research Assistantship (HTRA)</div>
          <div class="edu-item__year">2019 – 2020</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ═══════════════════════════════════════════
     RESEARCH
══════════════════════════════════════════════ -->
<section class="section section--alt" id="research">
  <div class="section__header anim-fadein">
    <span class="section__label">PhD & Collaborative Work</span>
    <h2 class="section__title">Research</h2>
    <div class="section__divider"></div>
  </div>

  <!-- PhD Thesis — Centerpiece -->
  <div class="research-hero anim-fadein anim-delay-1">
    <div class="research-hero__label">Ph.D. Thesis</div>
    <div class="research-hero__title">Electrochemical Responses During Lithiation of High Capacity Anode in Li-Ion Battery</div>
    <div class="research-hero__supervisors">
      Supervisors: Dr. Narasimhan Swaminathan &amp; Dr. Gandham Phanikumar · IIT Madras
    </div>
    <div class="research-hero__body">
      <p>Developed a coupled multiphysics framework using phase field modeling to simulate the electrochemical behavior of Li-ion battery anodes during (dis)charging. The model captures chemical diffusion under mechanical stress, coupled with electrochemical boundary conditions via Butler-Volmer kinetics.</p>
      <ul class="research-points">
        <li>Demonstrated the impact of phase transformation, electrode size, and mechanical stresses on electrochemical responses using voltammograms — covering both elastic and elasto-plastic deformation regimes.</li>
        <li>Developed a generalized multi-phase field solver capable of handling multiple coexisting phases, including in-depth analysis of model parameters and their mapping to physical factors.</li>
        <li>Applied the multi-phase field framework to the peritectic solidification problem, demonstrating its versatility beyond battery systems.</li>
        <li>Implemented all solvers in <strong>deal.II</strong> (C++ FEM library) and contributed a standalone crystal growth solver to its public code gallery.</li>
        <li>Achieved <strong>60% performance improvement</strong> via MPI parallelization using PETSc-based wrappers in deal.II.</li>
      </ul>
    </div>
  </div>

  <!-- Collaborative Project -->
  <div class="research-card anim-fadein anim-delay-2" style="margin-top:2rem;">
    <div class="research-card__title">Data-Driven Modeling for Predicting Microstructural Properties of Li-Ion Battery Electrodes</div>
    <div class="research-card__collab">Collaborators: Dr. Anand Agrawal &amp; Dr. Narasimhan Swaminathan · IIT Madras</div>
    <div class="research-card__body">
      Developed a Gaussian process regression model to predict Li-ion battery electrode performance from microstructural features like grain size — eliminating the need for expensive full simulations. Generated voltammogram datasets using FEM solvers (deal.II) with Butler-Volmer boundary conditions, and created microstructure meshes using Microgen and GMSH. The probabilistic model provides interpretable, uncertainty-aware predictions for electrode design optimization.
    </div>
  </div>
</section>

<!-- ═══════════════════════════════════════════
     PUBLICATIONS
══════════════════════════════════════════════ -->
<section class="section" id="publications">
  <div class="section__header anim-fadein">
    <span class="section__label">Peer-Reviewed Work</span>
    <h2 class="section__title">Publications</h2>
    <div class="section__divider"></div>
  </div>

  <div class="pub-list">

    <!-- Journal 1 -->
    <div class="pub-item anim-fadein">
      <div class="pub-item__num">01</div>
      <div class="pub-item__content">
        <span class="pub-item__badge">Journal Article</span>
        <div class="pub-item__title">Probabilistic Modelling of the Nonlinear Mapping Between Voltammograms and the Grain Size of the Electrode Material in Li-Ion Batteries Using Optimally Tuned Gaussian Process Regression Models</div>
        <div class="pub-item__authors">A. K. Agrawal, N. Swaminathan, and <strong>U. Hussain</strong></div>
        <div class="pub-item__journal">Journal of The Electrochemical Society, vol. 172, no. 1, p. 013501, 2025</div>
        <a href="https://doi.org/10.1149/1945-7111/ada0b6" target="_blank" class="pub-item__link">
          <svg width="12" height="12" viewBox="0 0 24 24" fill="currentColor"><path d="M19 19H5V5h7V3H5a2 2 0 00-2 2v14a2 2 0 002 2h14a2 2 0 002-2v-7h-2v7zM14 3v2h3.59l-9.83 9.83 1.41 1.41L19 6.41V10h2V3h-7z"/></svg>
          DOI: 10.1149/1945-7111/ada0b6
        </a>
      </div>
    </div>

    <!-- Journal 2 -->
    <div class="pub-item anim-fadein anim-delay-1">
      <div class="pub-item__num">02</div>
      <div class="pub-item__content">
        <span class="pub-item__badge">Journal Article</span>
        <div class="pub-item__title">Numerical Voltammetry of Phase Separating Materials Using Phase Field Modeling</div>
        <div class="pub-item__authors"><strong>U. Hussain</strong>, N. Swaminathan, and G. Phanikumar</div>
        <div class="pub-item__journal">Journal of The Electrochemical Society, vol. 171, no. 7, p. 070502, Jul. 2024</div>
        <a href="https://doi.org/10.1149/1945-7111/ad59cc" target="_blank" class="pub-item__link">
          <svg width="12" height="12" viewBox="0 0 24 24" fill="currentColor"><path d="M19 19H5V5h7V3H5a2 2 0 00-2 2v14a2 2 0 002 2h14a2 2 0 002-2v-7h-2v7zM14 3v2h3.59l-9.83 9.83 1.41 1.41L19 6.41V10h2V3h-7z"/></svg>
          DOI: 10.1149/1945-7111/ad59cc
        </a>
      </div>
    </div>

    <!-- Journal 3 -->
    <div class="pub-item anim-fadein anim-delay-2">
      <div class="pub-item__num">03</div>
      <div class="pub-item__content">
        <span class="pub-item__badge">Journal Article</span>
        <div class="pub-item__title">Mapping of Multiphase Field Model Parameters to Physical Factors in Order to Simulate Desired Phase Transformations</div>
        <div class="pub-item__authors"><strong>U. Hussain</strong>, G. Phanikumar, and N. Swaminathan</div>
        <div class="pub-item__journal">Computational Materials Science, vol. 226, p. 112227, Jun. 2023</div>
        <a href="https://doi.org/10.1016/J.COMMATSCI.2023.112227" target="_blank" class="pub-item__link">
          <svg width="12" height="12" viewBox="0 0 24 24" fill="currentColor"><path d="M19 19H5V5h7V3H5a2 2 0 00-2 2v14a2 2 0 002 2h14a2 2 0 002-2v-7h-2v7zM14 3v2h3.59l-9.83 9.83 1.41 1.41L19 6.41V10h2V3h-7z"/></svg>
          DOI: 10.1016/J.COMMATSCI.2023.112227
        </a>
      </div>
    </div>

    <!-- Conference Paper -->
    <div class="pub-item anim-fadein anim-delay-3">
      <div class="pub-item__num">04</div>
      <div class="pub-item__content">
        <span class="pub-item__badge pub-item__badge--conf">Conference Proceedings</span>
        <div class="pub-item__title">A Multi-Phase Field Framework Application to the Study of the Peritectic Reaction for an Arbitrary Material System</div>
        <div class="pub-item__authors"><strong>U. Hussain</strong>, N. Swaminathan, and G. Phanikumar</div>
        <div class="pub-item__journal">Recent Advances in Mechanics of Functional Materials and Structures · Springer Nature Singapore, 2024, pp. 231–240</div>
        <a href="https://doi.org/10.1007/978-981-99-5919-8_20" target="_blank" class="pub-item__link">
          <svg width="12" height="12" viewBox="0 0 24 24" fill="currentColor"><path d="M19 19H5V5h7V3H5a2 2 0 00-2 2v14a2 2 0 002 2h14a2 2 0 002-2v-7h-2v7zM14 3v2h3.59l-9.83 9.83 1.41 1.41L19 6.41V10h2V3h-7z"/></svg>
          DOI: 10.1007/978-981-99-5919-8_20
        </a>
      </div>
    </div>

    <!-- Open Source -->
    <div class="pub-item anim-fadein">
      <div class="pub-item__num">OS</div>
      <div class="pub-item__content">
        <span class="pub-item__badge" style="background:#2e6b3e;">Open Source</span>
        <div class="pub-item__title">Crystal Growth Using Phase Field Modeling</div>
        <div class="pub-item__authors"><strong>U. Hussain</strong></div>
        <div class="pub-item__journal">deal.II Code Gallery · Contributed standalone FEM solver</div>
        <a href="https://dealii.org/developer/doxygen/deal.II/code_gallery_Crystal_Growth_Phase_Field_Model.html" target="_blank" class="pub-item__link">
          <svg width="12" height="12" viewBox="0 0 24 24" fill="currentColor"><path d="M19 19H5V5h7V3H5a2 2 0 00-2 2v14a2 2 0 002 2h14a2 2 0 002-2v-7h-2v7zM14 3v2h3.59l-9.83 9.83 1.41 1.41L19 6.41V10h2V3h-7z"/></svg>
          View in deal.II Gallery
        </a>
      </div>
    </div>

  </div>
</section>

<!-- ═══════════════════════════════════════════
     EXPERIENCE
══════════════════════════════════════════════ -->
<section class="section section--alt" id="experience">
  <div class="section__header anim-fadein">
    <span class="section__label">Industry</span>
    <h2 class="section__title">Work Experience</h2>
    <div class="section__divider"></div>
  </div>

  <div class="timeline">

    <div class="timeline-item anim-fadein">
      <div class="timeline-item__period">May 2025 – Present</div>
      <div class="timeline-item__role">Data Scientist</div>
      <div class="timeline-item__company">ChampionX (now part of SLB)</div>
      <ul class="timeline-item__bullets">
        <li>Developing AI and physics-based models for artificial lift systems including sucker rod pumps and ESPs.</li>
        <li>Working on corrosion prediction using machine learning for oil &amp; gas applications.</li>
      </ul>
    </div>

    <div class="timeline-item anim-fadein anim-delay-1">
      <div class="timeline-item__period">Nov 2024 – April 2025</div>
      <div class="timeline-item__role">Research Analyst — Intern</div>
      <div class="timeline-item__company">ChampionX (now part of SLB)</div>
      <ul class="timeline-item__bullets">
        <li>Developed a FEM model for the sucker rod pump to predict the dynamometer (pump) card.</li>
        <li>Built a machine learning pipeline to predict broken shaft events from sensor data.</li>
      </ul>
    </div>

  </div>
</section>

<!-- ═══════════════════════════════════════════
     TEACHING
══════════════════════════════════════════════ -->
<section class="section" id="teaching">
  <div class="section__header anim-fadein">
    <span class="section__label">Education & Outreach</span>
    <h2 class="section__title">Teaching Experience</h2>
    <div class="section__divider"></div>
  </div>

  <div class="teaching-grid">

    <div class="teaching-card anim-fadein">
      <div class="teaching-card__period">Jul 2022 – Nov 2023</div>
      <div class="teaching-card__role">Teaching Assistant — Basics of Finite Element Analysis I &amp; II &nbsp;·&nbsp; FEM: Variational Methods to Programming</div>
      <div class="teaching-card__inst">NPTEL</div>
    </div>

    <div class="teaching-card anim-fadein anim-delay-1">
      <div class="teaching-card__period">Feb 2022 – May 2022</div>
      <div class="teaching-card__role">Instructor — Short Course on Computational Tools</div>
      <div class="teaching-card__inst">PSG Institute of Technology and Applied Research</div>
    </div>

  </div>

  <!-- Conferences -->
  <div style="margin-top:3rem;">
    <h3 style="font-family:'Playfair Display',serif;color:var(--navy);font-size:1.2rem;margin-bottom:1.5rem;" class="anim-fadein">Conference Presentations</h3>
    <div class="teaching-grid">
      <div class="teaching-card anim-fadein">
        <div class="teaching-card__period">Jul 2024 · Vancouver, Canada</div>
        <div class="teaching-card__role">16th World Congress on Computational Mechanics (WCCM 2024)</div>
      </div>
      <div class="teaching-card anim-fadein anim-delay-1">
        <div class="teaching-card__period">Sept 2023 · Barcelona, Spain</div>
        <div class="teaching-card__role">XVII International Conference on Computational Plasticity (Complas)</div>
        <div class="teaching-card__inst">Universitat Politècnica de Catalunya (UPC)</div>
      </div>
      <div class="teaching-card anim-fadein anim-delay-2">
        <div class="teaching-card__period">Dec 2022 · Guwahati, India</div>
        <div class="teaching-card__role">8th Asian Conference on Mechanics of Functional Materials &amp; Structures</div>
        <div class="teaching-card__inst">IIT Guwahati</div>
      </div>
      <div class="teaching-card anim-fadein anim-delay-3">
        <div class="teaching-card__period">Jun 2022 · Bengaluru, India</div>
        <div class="teaching-card__role">ME@75: Research Frontiers</div>
        <div class="teaching-card__inst">IISc Bangalore</div>
      </div>
    </div>
  </div>
</section>

<!-- ═══════════════════════════════════════════
     CONTACT
══════════════════════════════════════════════ -->
<section class="section section--alt" id="contact">
  <div class="section__header anim-fadein">
    <span class="section__label">Let's Connect</span>
    <h2 class="section__title">Contact</h2>
    <div class="section__divider"></div>
  </div>

  <div class="contact__grid">
    <div class="anim-fadein">
      <p class="contact__intro">
        Whether you're interested in research collaboration, discussing physics-informed AI, or exploring how computational mechanics meets data science — I'd love to hear from you.
      </p>

      <div class="contact-links">
        <a href="mailto:husain.umair2010@gmail.com" class="contact-link">
          <div class="contact-link__icon">
            <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor" style="color:var(--navy)"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/></svg>
          </div>
          husain.umair2010@gmail.com
        </a>
        <a href="https://github.com/umairhussaincmm" target="_blank" class="contact-link">
          <div class="contact-link__icon">
            <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor" style="color:var(--navy)"><path d="M12 0C5.374 0 0 5.373 0 12c0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0 1 12 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.3 24 12c0-6.627-5.373-12-12-12z"/></svg>
          </div>
          github.com/umairhussaincmm
        </a>
        <a href="https://www.linkedin.com/in/umair-h-204191b4" target="_blank" class="contact-link">
          <div class="contact-link__icon">
            <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor" style="color:var(--navy)"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 0 1-2.063-2.065 2.064 2.064 0 1 1 2.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
          </div>
          linkedin.com/in/umair-h-204191b4
        </a>
        <a href="https://umairhussaincmm.github.io/" target="_blank" class="contact-link">
          <div class="contact-link__icon">
            <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor" style="color:var(--navy)"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 17.93c-3.95-.49-7-3.85-7-7.93 0-.62.08-1.21.21-1.79L9 15v1c0 1.1.9 2 2 2v1.93zm6.9-2.54c-.26-.81-1-1.39-1.9-1.39h-1v-3c0-.55-.45-1-1-1H8v-2h2c.55 0 1-.45 1-1V7h2c1.1 0 2-.9 2-2v-.41c2.93 1.19 5 4.06 5 7.41 0 2.08-.8 3.97-2.1 5.39z"/></svg>
          </div>
          umairhussaincmm.github.io
        </a>
      </div>
    </div>

    <div class="cv-download-card anim-fadein anim-delay-1">
      <h3>Curriculum Vitae</h3>
      <p>Download my full CV for a detailed overview of my research, publications, and professional experience.</p>
      <a href="/docs/CV_Umair.pdf" class="btn btn--gold" download>
        <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor"><path d="M19 9h-4V3H9v6H5l7 7 7-7zM5 18v2h14v-2H5z"/></svg>
        Download CV (PDF)
      </a>
      <p style="margin-top:1rem;font-size:0.8rem;color:rgba(255,255,255,0.4);">
        Also reachable at me19d704@smail.iitm.ac.in
      </p>
    </div>
  </div>
</section>

<!-- Footer -->
<footer class="site-footer">
  © {{ 'now' | date: "%Y" }} Umair Hussain &nbsp;·&nbsp; Built with Jekyll &nbsp;·&nbsp; Hosted on GitHub Pages
</footer>
