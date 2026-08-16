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
    <p class="hero-background">I received my Ph.D. from <a href="https://www.cmu.edu/">Carnegie Mellon University</a>, advised by <a href="https://www.andrew.cmu.edu/user/kunz1/">Kun Zhang</a> and <a href="https://www.cmu.edu/dietrich/philosophy/people/faculty/spirtes.html">Peter Spirtes</a>. Previously, I interned at Adobe Research and Google.</p>

    <div class="hero-socials">
      <a href="https://scholar.google.com/citations?user=mChB-hQAAAAJ&amp;hl=en&amp;oi=ao"><i class="ai ai-google-scholar" aria-hidden="true"></i><span>Google Scholar</span></a>
      <a href="https://github.com/Mid-Push"><i class="fab fa-github" aria-hidden="true"></i><span>GitHub</span></a>
      <a href="https://www.linkedin.com/in/shaoan-xie-9b24201a7/"><i class="fab fa-linkedin" aria-hidden="true"></i><span>LinkedIn</span></a>
      <a href="mailto:shaoan@cmu.edu"><i class="far fa-envelope" aria-hidden="true"></i><span>Email</span></a>
    </div>
  </div>

  <div class="multimodal-visual">
    <svg class="multimodal-map" viewBox="0 0 700 330" role="img" aria-labelledby="multimodal-map-title multimodal-map-desc">
      <title id="multimodal-map-title">Multimodal learning research map</title>
      <desc id="multimodal-map-desc">We learn from image, video, and text collected from the world to study alignment, understanding, reasoning, and generation.</desc>
      <defs>
        <linearGradient id="model-surface" x1="0" y1="0" x2="1" y2="1">
          <stop offset="0" stop-color="#6967df" stop-opacity=".17" />
          <stop offset="1" stop-color="#38a187" stop-opacity=".12" />
        </linearGradient>
        <linearGradient id="model-core" x1="0" y1="0" x2="1" y2="1">
          <stop offset="0" stop-color="#665dd2" />
          <stop offset="1" stop-color="#319875" />
        </linearGradient>
        <marker id="map-arrow" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
          <path d="M 0 0 L 10 5 L 0 10 z" class="map-arrowhead" />
        </marker>
        <filter id="map-shadow" x="-20%" y="-20%" width="140%" height="150%">
          <feDropShadow dx="0" dy="5" stdDeviation="7" flood-color="#182542" flood-opacity=".09" />
        </filter>
      </defs>

      <g class="map-ambient" aria-hidden="true">
        <circle cx="325" cy="42" r="3" /><circle cx="425" cy="286" r="3" />
        <circle cx="196" cy="252" r="2.5" /><circle cx="620" cy="165" r="2.5" />
        <path d="M195 252 253 225M425 286l-34-44M620 165l-48-2M325 42l8 43" />
      </g>

      <g class="map-connectors" aria-hidden="true">
        <path d="M136 69 C184 69 195 112 244 132" marker-end="url(#map-arrow)" />
        <path d="M136 165 H235" marker-end="url(#map-arrow)" />
        <path d="M136 261 C184 261 195 218 244 198" marker-end="url(#map-arrow)" />
        <path d="M446 132 C488 112 493 72 525 69" marker-end="url(#map-arrow)" />
        <path d="M454 151 C487 145 495 137 525 137" marker-end="url(#map-arrow)" />
        <path d="M454 179 C487 185 495 193 525 193" marker-end="url(#map-arrow)" />
        <path d="M446 198 C488 218 493 258 525 261" marker-end="url(#map-arrow)" />
      </g>

      <g class="input-card" transform="translate(18 35)" filter="url(#map-shadow)">
        <rect width="118" height="68" rx="14" />
        <g class="input-icon image-icon" aria-hidden="true">
          <rect x="15" y="14" width="36" height="31" rx="5" />
          <circle cx="42" cy="22" r="3.5" />
          <path d="m19 40 10-10 7 7 5-5 7 8" />
        </g>
        <text x="65" y="32">Image</text><text class="input-detail" x="65" y="47">pixels</text>
      </g>

      <g class="input-card" transform="translate(18 131)" filter="url(#map-shadow)">
        <rect width="118" height="68" rx="14" />
        <g class="input-icon video-icon" aria-hidden="true">
          <rect x="14" y="16" width="31" height="25" rx="4" />
          <rect x="20" y="22" width="31" height="25" rx="4" />
          <path d="m34 28 8 6-8 6z" />
        </g>
        <text x="65" y="32">Video</text><text class="input-detail" x="65" y="47">frames</text>
      </g>

      <g class="input-card" transform="translate(18 227)" filter="url(#map-shadow)">
        <rect width="118" height="68" rx="14" />
        <g class="input-icon text-icon" aria-hidden="true">
          <rect x="15" y="15" width="38" height="35" rx="6" />
          <path d="M22 25h24M22 32h18M22 39h22" />
        </g>
        <text x="65" y="32">Text</text><text class="input-detail" x="65" y="47">tokens</text>
      </g>

      <g class="model-card" transform="translate(235 84)" filter="url(#map-shadow)">
        <rect width="220" height="162" rx="24" />
        <g class="world-network" aria-hidden="true">
          <circle class="world-sphere" cx="110" cy="64" r="42" />
          <path d="M68 64h84M110 22c-14 12-22 26-22 42s8 30 22 42M110 22c14 12 22 26 22 42s-8 30-22 42M76 40c10 7 21 10 34 10s24-3 34-10M76 88c10-7 21-10 34-10s24 3 34 10" />
          <circle cx="79" cy="47" r="5" /><circle cx="133" cy="37" r="5" />
          <circle cx="119" cy="83" r="6" /><circle cx="145" cy="72" r="4.5" />
        </g>
        <text class="model-title" x="110" y="135" text-anchor="middle">Learning from the World</text>
        <text class="model-detail" x="110" y="150" text-anchor="middle">multimodal observations</text>
      </g>

      <g class="capability-card align-card" transform="translate(525 36)" filter="url(#map-shadow)">
        <rect width="157" height="66" rx="15" />
        <g class="capability-icon" aria-hidden="true">
          <circle cx="27" cy="27" r="8" /><circle cx="41" cy="39" r="8" />
          <path d="m33 32 4 3" />
        </g>
        <text x="63" y="36">Align</text>
      </g>

      <g class="capability-card understand-card" transform="translate(525 108)" filter="url(#map-shadow)">
        <rect width="157" height="58" rx="15" />
        <g class="capability-icon" aria-hidden="true">
          <circle cx="34" cy="18" r="5" /><circle cx="23" cy="39" r="5" /><circle cx="45" cy="39" r="5" />
          <path d="m31 23-6 11m12-11 6 11" />
        </g>
        <text x="63" y="35">Understand</text>
      </g>

      <g class="capability-card reason-card" transform="translate(525 172)" filter="url(#map-shadow)">
        <rect width="157" height="58" rx="15" />
        <g class="capability-icon" aria-hidden="true">
          <circle cx="21" cy="35" r="4" /><circle cx="34" cy="22" r="4" /><circle cx="47" cy="35" r="4" />
          <path d="m24 32 7-7m6 0 7 7m-3 3h6" />
        </g>
        <text x="63" y="35">Reason</text>
      </g>

      <g class="capability-card generate-card" transform="translate(525 236)" filter="url(#map-shadow)">
        <rect width="157" height="66" rx="15" />
        <g class="capability-icon" aria-hidden="true">
          <rect x="17" y="20" width="28" height="24" rx="4" />
          <path d="m20 40 7-8 5 5 4-4 6 7M48 17v9M44 21h8" />
        </g>
        <text x="63" y="36">Generate</text>
      </g>
    </svg>
  </div>
</section>

<section class="featured-section" id="featured-research">
  <div class="section-heading-row">
    <h2>Featured Research</h2>
    <a href="#publications">View all publications <span aria-hidden="true">→</span></a>
  </div>
  {% include selected-research.html %}
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
    <li><time>Jul. 2026</time><span>A paper on <a href="https://openreview.net/pdf?id=0T1Pd65fyD">counterfactual prediction</a> was accepted to <em>TMLR</em>. Two papers were accepted to <em>ECCV 2026</em>: <a href="https://arxiv.org/pdf/2512.10720">interpreting and controlling text-to-image models</a> and <a href="https://arxiv.org/pdf/2607.00858">long video-text alignment</a>.</span></li>
    <li><time>Apr. 2026</time><span>Papers were accepted to <em>ICLR 2026</em> and <em>CVPR 2026</em>, and our work on <a href="assets/files/shaoan_dllm.pdf">post-training diffusion language models with denoising-process rewards</a> was accepted to <em>ACL 2026 Main</em>.</span></li>
    <li><time>Aug. 2025</time><span>I will serve as an Area Chair for <a href="https://iclr.cc/">ICLR 2026</a>.</span></li>
    <li><time>May 2025</time><span>Two papers were accepted to <a href="https://icml.cc/">ICML 2025</a>.</span></li>
    <li><time>Apr. 2025</time><span>SmartCLIP was selected as a <a href="https://cvpr.thecvf.com/">CVPR 2025 Highlight</a>.</span></li>
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
