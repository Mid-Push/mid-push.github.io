---
layout: homepage
---

<section class="hero-section" id="about">
  <div class="hero-copy">
    <h1>Shaoan Xie</h1>
    <p class="hero-role">Generative AI Researcher</p>

    <div class="hero-topics" aria-label="Research areas">
      <span>Multimodal Learning</span>
      <span>Alignment &amp; Understanding</span>
      <span>Reasoning</span>
      <span>Generation</span>
    </div>

    <p class="hero-summary">My research focuses on building multimodal models that align, understand, reason, and generate while remaining controllable and generalizable.</p>
    <p class="hero-background">My Ph.D. research was advised by <a href="https://www.andrew.cmu.edu/user/kunz1/">Kun Zhang</a> and <a href="https://www.cmu.edu/dietrich/philosophy/people/faculty/spirtes.html">Peter Spirtes</a>.</p>

    <div class="hero-socials">
      <a href="https://scholar.google.com/citations?user=mChB-hQAAAAJ&amp;hl=en&amp;oi=ao"><i class="ai ai-google-scholar" aria-hidden="true"></i><span>Google Scholar</span></a>
      <a href="https://github.com/Mid-Push"><i class="fab fa-github" aria-hidden="true"></i><span>GitHub</span></a>
      <a href="https://www.linkedin.com/in/shaoan-xie-9b24201a7/"><i class="fab fa-linkedin" aria-hidden="true"></i><span>LinkedIn</span></a>
      <a href="mailto:shaoan@cmu.edu"><i class="far fa-envelope" aria-hidden="true"></i><span>Email</span></a>
    </div>

    <div class="hero-experience" aria-label="Education and research experience">
      <span class="experience-label">Experience</span>
      <div class="experience-list">
        <a class="experience-item" href="https://www.cmu.edu/">
          <span class="experience-logo cmu-logo"><img src="assets/img/cmu_logo.jpeg" alt=""></span>
          <span class="experience-copy"><strong>Carnegie Mellon</strong><small>Ph.D.</small></span>
        </a>
        <a class="experience-item" href="https://research.adobe.com/">
          <span class="experience-logo"><i class="fab fa-adobe" aria-hidden="true"></i></span>
          <span class="experience-copy"><strong>Adobe Research</strong><small>Research Intern</small></span>
        </a>
        <a class="experience-item" href="https://research.google/">
          <span class="experience-logo"><i class="fab fa-google" aria-hidden="true"></i></span>
          <span class="experience-copy"><strong>Google</strong><small>Research Intern</small></span>
        </a>
      </div>
    </div>
  </div>

  <div class="hero-featured" id="featured-research">
    <div class="section-heading-row">
      <h2>Featured Research</h2>
      <a href="#publications">View all publications <span aria-hidden="true">→</span></a>
    </div>
    {% include selected-research.html %}
  </div>

  <div class="multimodal-visual" hidden aria-hidden="true">
    <svg class="multimodal-map" viewBox="0 0 720 400" role="img" aria-labelledby="multimodal-map-title multimodal-map-desc">
      <title id="multimodal-map-title">Multimodal learning research map</title>
      <desc id="multimodal-map-desc">We learn from image, video, text, and action collected from the world to study alignment, understanding, reasoning, and generation.</desc>
      <defs>
        <radialGradient id="world-surface" cx="50%" cy="44%" r="62%">
          <stop offset="0" stop-color="#7774e8" stop-opacity=".14" />
          <stop offset=".7" stop-color="#7774e8" stop-opacity=".06" />
          <stop offset="1" stop-color="#7774e8" stop-opacity="0" />
        </radialGradient>
        <linearGradient id="model-core" x1="0" y1="0" x2="1" y2="1">
          <stop offset="0" stop-color="#5654e8" />
          <stop offset="1" stop-color="#8582ef" />
        </linearGradient>
        <filter id="map-shadow" x="-20%" y="-20%" width="140%" height="150%">
          <feDropShadow dx="0" dy="5" stdDeviation="7" flood-color="#182542" flood-opacity=".09" />
        </filter>
      </defs>

      <g class="world-rings" aria-hidden="true">
        <circle class="world-glow" cx="340" cy="200" r="128" />
        <circle class="world-orbit orbit-outer" cx="340" cy="200" r="148" />
        <circle class="world-orbit orbit-dashed" cx="340" cy="200" r="126" />
        <circle class="world-orbit orbit-inner" cx="340" cy="200" r="110" />
        <circle class="orbit-dot" cx="250" cy="78" r="4" />
        <circle class="orbit-dot" cx="412" cy="63" r="3.5" />
        <circle class="orbit-dot" cx="478" cy="147" r="4" />
        <circle class="orbit-dot" cx="440" cy="319" r="3.5" />
        <circle class="orbit-dot" cx="274" cy="335" r="4" />
        <circle class="orbit-dot" cx="199" cy="253" r="3.5" />
      </g>

      <g class="map-connectors" aria-hidden="true">
        <path class="input-connector" d="M136 57 C181 57 174 111 216 122" />
        <path class="input-connector" d="M136 148 C174 148 180 159 205 159" />
        <path class="input-connector" d="M136 239 C174 239 180 241 205 241" />
        <path class="input-connector" d="M136 330 C181 330 174 289 216 278" />
        <path class="output-connector align-line" d="M468 122 C510 111 500 57 538 57" />
        <path class="output-connector understand-line" d="M475 159 C511 159 509 148 538 148" />
        <path class="output-connector reason-line" d="M475 241 C511 241 509 239 538 239" />
        <path class="output-connector generate-line" d="M468 278 C510 289 500 330 538 330" />
        <path class="arrow-tip align-tip" d="M532 49 548 57 532 65Z" />
        <path class="arrow-tip understand-tip" d="M532 140 548 148 532 156Z" />
        <path class="arrow-tip reason-tip" d="M532 231 548 239 532 247Z" />
        <path class="arrow-tip generate-tip" d="M532 322 548 330 532 338Z" />
        <g class="input-dots">
          <circle cx="136" cy="57" r="4" /><circle cx="216" cy="122" r="4" />
          <circle cx="136" cy="148" r="4" /><circle cx="205" cy="159" r="4" />
          <circle cx="136" cy="239" r="4" /><circle cx="205" cy="241" r="4" />
          <circle cx="136" cy="330" r="4" /><circle cx="216" cy="278" r="4" />
        </g>
      </g>

      <g class="input-card" transform="translate(8 21)" filter="url(#map-shadow)">
        <rect width="128" height="72" rx="15" />
        <g class="input-icon image-icon" aria-hidden="true">
          <rect x="15" y="15" width="38" height="34" rx="5" />
          <circle cx="43" cy="23" r="3.5" />
          <path d="m19 44 11-11 7 7 5-5 8 9" />
        </g>
        <text x="70" y="33">Image</text><text class="input-detail" x="70" y="49">pixels</text>
      </g>

      <g class="input-card" transform="translate(8 112)" filter="url(#map-shadow)">
        <rect width="128" height="72" rx="15" />
        <g class="input-icon video-icon" aria-hidden="true">
          <rect x="15" y="18" width="38" height="32" rx="5" />
          <path d="M15 26h38M20 18v8m9-8v8m10-8v8m9-8v8M20 42h28" />
          <path d="m31 30 9 6-9 6z" />
        </g>
        <text x="70" y="33">Video</text><text class="input-detail" x="70" y="49">frames</text>
      </g>

      <g class="input-card" transform="translate(8 203)" filter="url(#map-shadow)">
        <rect width="128" height="72" rx="15" />
        <g class="input-icon text-icon" aria-hidden="true">
          <rect x="18" y="14" width="34" height="42" rx="4" />
          <path d="M24 27h22M24 35h22M24 43h16" />
        </g>
        <text x="70" y="33">Text</text><text class="input-detail" x="70" y="49">tokens</text>
      </g>

      <g class="input-card" transform="translate(8 294)" filter="url(#map-shadow)">
        <rect width="128" height="72" rx="15" />
        <g class="input-icon action-icon" aria-hidden="true">
          <circle cx="34" cy="36" r="5" />
          <path d="M34 31V17m0 0-5 5m5-5 5 5M39 36h14m0 0-5-5m5 5-5 5M34 41v14m0 0-5-5m5 5 5-5M29 36H15m0 0 5-5m-5 5 5 5" />
        </g>
        <text x="70" y="33">Action</text><text class="input-detail" x="70" y="49">controls</text>
      </g>

      <g class="world-network" transform="translate(340 145)" aria-hidden="true">
        <path d="M-44-12-25-33 2-40 27-29 45-8 43 18 24 35-3 39-29 28-45 7ZM-25-33-13-9 2-40 12-13 27-29M-44-12-13-9-45 7-24 10-29 28M-13-9 12-13 28 4 43 18 24 35 5 18-3 39M-24 10 5 18 28 4M-13-9 5 18M12-13 28 4" />
        <circle cx="-44" cy="-12" r="5" /><circle cx="-25" cy="-33" r="5" />
        <circle cx="2" cy="-40" r="5" /><circle cx="27" cy="-29" r="5" />
        <circle cx="45" cy="-8" r="5" /><circle cx="43" cy="18" r="5" />
        <circle cx="24" cy="35" r="5" /><circle cx="-3" cy="39" r="5" />
        <circle cx="-29" cy="28" r="5" /><circle cx="-45" cy="7" r="5" />
        <circle cx="-13" cy="-9" r="6" /><circle cx="12" cy="-13" r="5" />
        <circle cx="28" cy="4" r="5" /><circle cx="5" cy="18" r="6" /><circle cx="-24" cy="10" r="5" />
      </g>
      <text class="model-title" x="340" y="234" text-anchor="middle">Learning from</text>
      <text class="model-title" x="340" y="255" text-anchor="middle">the World</text>
      <text class="model-detail" x="340" y="276" text-anchor="middle">multimodal observations</text>

      <g class="capability-card align-card" transform="translate(550 21)" filter="url(#map-shadow)">
        <rect width="162" height="72" rx="16" />
        <g class="capability-icon" aria-hidden="true">
          <circle cx="28" cy="28" r="9" /><circle cx="43" cy="42" r="9" />
          <path d="m35 34 3 3" />
        </g>
        <text x="72" y="42">Align</text>
      </g>

      <g class="capability-card understand-card" transform="translate(550 112)" filter="url(#map-shadow)">
        <rect width="162" height="72" rx="16" />
        <g class="capability-icon" aria-hidden="true">
          <circle cx="36" cy="23" r="6" /><circle cx="24" cy="48" r="6" /><circle cx="48" cy="48" r="6" />
          <path d="m33 29-7 13m13-13 7 13" />
        </g>
        <text x="72" y="42">Understand</text>
      </g>

      <g class="capability-card reason-card" transform="translate(550 203)" filter="url(#map-shadow)">
        <rect width="162" height="72" rx="16" />
        <g class="capability-icon" aria-hidden="true">
          <circle cx="36" cy="23" r="6" /><circle cx="24" cy="48" r="6" /><circle cx="48" cy="48" r="6" />
          <path d="m33 29-7 13m13-13 7 13" />
        </g>
        <text x="72" y="42">Reason</text>
      </g>

      <g class="capability-card generate-card" transform="translate(550 294)" filter="url(#map-shadow)">
        <rect width="162" height="72" rx="16" />
        <g class="capability-icon" aria-hidden="true">
          <rect x="17" y="22" width="34" height="29" rx="4" />
          <path d="m21 47 8-9 6 6 5-5 8 8M53 18v12M47 24h12" />
        </g>
        <text x="72" y="42">Generate</text>
      </g>
    </svg>
  </div>
</section>

<section class="credibility-strip" id="research-impact" aria-label="Research highlights">
  <article class="credibility-item">
    <div class="credibility-icon green"><i class="fas fa-chart-line" aria-hidden="true"></i></div>
    <div><strong>Product Impact</strong><span>SmartBrush integrated into Adobe Photoshop and Firefly</span></div>
  </article>
  <article class="credibility-item">
    <div class="credibility-icon purple"><i class="fas fa-trophy" aria-hidden="true"></i></div>
    <div><strong>Research Recognition</strong><span>CVPR 2023/2025 Highlights &nbsp;•&nbsp; ICLR 2023 Spotlight</span></div>
  </article>
  <article class="credibility-item">
    <div class="credibility-icon blue"><i class="fas fa-users" aria-hidden="true"></i></div>
    <div><strong>Research Leadership</strong><span>ICLR ’26 &amp; ’27 Area Chair &nbsp;•&nbsp; NeurIPS ’26 Area Chair</span></div>
  </article>
</section>

<section class="content-section news-section" id="news">
  <div class="section-heading-row">
    <h2>News</h2>
  </div>
  <ul class="news-list">
    <li><time>Jul. 2026</time><span>New work on <a href="https://openreview.net/pdf?id=0T1Pd65fyD">counterfactual prediction</a> was accepted by <em>TMLR</em>. Two papers on <a href="https://arxiv.org/pdf/2512.10720">identifiable interpretation and control in generative models</a> and <a href="https://arxiv.org/pdf/2607.00858">long video–text alignment</a> were accepted to <em>ECCV 2026</em>.</span></li>
    <li><time>Apr. 2026</time><span>New work on <a href="https://arxiv.org/pdf/2502.02690">controllable video generation</a> and <a href="https://arxiv.org/pdf/2512.10669">compositional generalization</a> was accepted to <em>ICLR 2026</em> and <em>CVPR 2026</em>, respectively. Our <a href="assets/files/shaoan_dllm.pdf">denoising-process rewards for diffusion language models</a> paper was accepted to <em>ACL 2026 Main</em>.</span></li>
    <li><time>Aug. 2025</time><span>Selected to serve as an Area Chair for <a href="https://iclr.cc/">ICLR 2026</a>.</span></li>
    <li><time>May 2025</time><span>Two papers on <a href="assets/files/shaoan_concept.pdf">controllable image generation through vision–language concepts</a> and <a href="https://openreview.net/pdf?id=cW9Ttnm1aC">nonparametric identification of latent concepts</a> were accepted to <a href="https://icml.cc/">ICML 2025</a>.</span></li>
    <li><time>Apr. 2025</time><span><a href="https://openaccess.thecvf.com/content/CVPR2025/papers/Xie_SmartCLIP_Modular_Vision-language_Alignment_with_Identification_Guarantees_CVPR_2025_paper.pdf">SmartCLIP</a> received a <em>CVPR 2025 Highlight</em> distinction.</span></li>
  </ul>
</section>

<section class="content-section publications-section" id="publications">
  <div class="section-heading-row">
    <h2>Publications</h2>
    <a href="https://scholar.google.com/citations?user=mChB-hQAAAAJ&amp;hl=en&amp;oi=ao">Google Scholar <span aria-hidden="true">↗</span></a>
  </div>
  {% include_relative _includes/publications.html %}
</section>

<section class="content-section services-section" id="services">
  <div class="section-heading-row">
    <h2>Academic Service</h2>
  </div>
  {% include_relative _includes/services.md %}
</section>
