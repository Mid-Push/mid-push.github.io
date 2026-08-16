---
layout: homepage
---

<section class="hero-section" id="about">
  <div class="hero-copy">
    <h1>Shaoan Xie</h1>
    <p class="hero-role">Generative AI Researcher</p>

    <div class="hero-topics" aria-label="Research areas">
      <span>Multimodal Generation</span>
      <span>Image &amp; Video</span>
      <span>Diffusion Models</span>
      <span>Post-training &amp; RL</span>
    </div>

    <p class="hero-summary">My research focuses on building multimodal generative models that can generate, reason, and learn from feedback while remaining controllable and generalizable.</p>

    <div class="hero-socials">
      <a href="https://scholar.google.com/citations?user=mChB-hQAAAAJ&amp;hl=en&amp;oi=ao"><i class="ai ai-google-scholar" aria-hidden="true"></i><span>Google Scholar</span></a>
      <a href="https://github.com/Mid-Push"><i class="fab fa-github" aria-hidden="true"></i><span>GitHub</span></a>
      <a href="https://www.linkedin.com/in/shaoan-xie-9b24201a7/"><i class="fab fa-linkedin" aria-hidden="true"></i><span>LinkedIn</span></a>
      <a href="mailto:shaoan@cmu.edu"><i class="far fa-envelope" aria-hidden="true"></i><span>Email</span></a>
    </div>
  </div>

  <div class="generation-visual" aria-label="Illustration of diffusion-based image generation and editing">
    <div class="generation-pipeline">
      <figure class="noise-stage">
        <div class="noise-field"></div>
        <figcaption>Gaussian Noise</figcaption>
      </figure>

      <svg class="pipeline-arrow" viewBox="0 0 38 24" aria-hidden="true"><path d="M2 12h29M23 4l8 8-8 8"></path></svg>

      <figure class="diffusion-stage">
        <div class="diffusion-stack" aria-hidden="true">
          <span style="--step:0"></span>
          <span style="--step:1"></span>
          <span style="--step:2"></span>
          <span style="--step:3"></span>
          <span style="--step:4"></span>
        </div>
        <figcaption>Diffusion Process</figcaption>
      </figure>

      <svg class="pipeline-arrow" viewBox="0 0 38 24" aria-hidden="true"><path d="M2 12h29M23 4l8 8-8 8"></path></svg>

      <div class="generation-outputs">
        <figure class="output-card">
          <img src="assets/img/arxiv_dream.png" alt="Text-guided image generation examples">
          <figcaption>Image Generation</figcaption>
        </figure>
        <figure class="output-card output-motion">
          <img src="assets/img/smartbrush_demo.gif" alt="SmartBrush generative editing demonstration">
          <span class="play-icon" aria-hidden="true"><i class="fas fa-play"></i></span>
          <figcaption>Generative Editing</figcaption>
        </figure>
      </div>
    </div>
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
    <li><time>Sep. 2025</time><span>My work was featured by <a href="https://www.cmu.edu/news/stories/archives/2025/september/peacocks-eating-ice-cream-cmu-philosophers-teaching-ai-to-ask-why">CMU News</a> and <a href="https://mbzuai.ac.ae/news/create-and-edit-images-like-a-smart-artist/">MBZUAI News</a>.</span></li>
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
