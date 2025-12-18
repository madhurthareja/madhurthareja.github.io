---
layout: about
title: About
permalink: /
subtitle: Multimodal AI × Embedded Systems Researcher

profile:
  align: right
  image: prof_pic.png
  image_circular: false
  more_info: >
    <p style="font-size: 12px">madhurthareja1105@gmail.com</p>
    <p style="font-size: 12px"><a href="https://github.com/madhurthareja" target="_blank">github.com/madhurthareja</a></p>
    <p style="font-size: 12px"><a href="https://www.linkedin.com/in/madhurthareja/" target="_blank">linkedin.com/in/madhurthareja</a></p>

news: false
selected_papers: false
social: false
---
{% assign cv_path = "/assets/pdf/Madhur_Thareja_Resume.pdf" %}

<style>
  .home-hero {
    display: flex;
    flex-wrap: wrap;
    gap: 2rem;
    padding: 2rem;
    border-radius: 24px;
    background: linear-gradient(135deg, rgba(79, 70, 229, 0.1), rgba(16, 185, 129, 0.12));
    box-shadow: 0 30px 80px rgba(15, 23, 42, 0.18);
    margin-bottom: 2.5rem;
  }

  .home-hero h1 {
    margin: 0.25rem 0 1rem;
    font-size: clamp(2rem, 4vw, 2.75rem);
  }

  .hero-eyebrow {
    text-transform: uppercase;
    letter-spacing: 0.2em;
    font-size: 0.75rem;
    color: var(--global-theme-color);
  }

  .hero-lead {
    font-size: 1.1rem;
    line-height: 1.7;
    max-width: 48ch;
  }

  .cta-group {
    display: flex;
    flex-wrap: wrap;
    gap: 0.85rem;
    margin-top: 1.5rem;
  }

  .cta-group a {
    display: inline-flex;
    align-items: center;
    gap: 0.35rem;
    padding: 0.75rem 1.65rem;
    border-radius: 999px;
    font-weight: 600;
    text-decoration: none;
    box-shadow: 0 15px 40px rgba(15, 23, 42, 0.18);
  }

  .cta-primary {
    background: var(--global-theme-color);
    color: #fff;
  }

  .cta-ghost {
    border: 1px solid rgba(15, 23, 42, 0.15);
    color: inherit;
    background: #fff;
  }

  .hero-pills {
    display: flex;
    flex-direction: column;
    gap: 0.75rem;
    margin: 0;
    padding: 0;
    list-style: none;
    min-width: 240px;
  }

  .hero-pill {
    padding: 0.85rem 1.1rem;
    border-radius: 16px;
    background: rgba(255, 255, 255, 0.75);
    border: 1px solid rgba(15, 23, 42, 0.08);
    box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.4);
  }

  .focus-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
    gap: 1.5rem;
    margin-bottom: 2.5rem;
  }

  .focus-card {
    padding: 1.5rem;
    border-radius: 18px;
    border: 1px solid rgba(15, 23, 42, 0.08);
    background: #fff;
    box-shadow: 0 20px 40px rgba(15, 23, 42, 0.08);
  }

  .focus-card h3 {
    margin-top: 0;
  }

  .focus-card ul {
    margin: 0;
    padding-left: 1.2rem;
    color: var(--global-text-color-light, #6b7280);
  }

  .impact-section {
    padding: 2rem;
    border-radius: 24px;
    background: rgba(15, 23, 42, 0.04);
    border: 1px solid rgba(15, 23, 42, 0.08);
  }

  .impact-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 1.5rem;
    margin-top: 1.5rem;
  }

  .impact-card {
    padding: 1.25rem;
    border-radius: 18px;
    background: #fff;
    border: 1px solid rgba(15, 23, 42, 0.08);
  }

  .internship-section {
    margin-bottom: 2.5rem;
  }

  .internship-cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 1.25rem;
  }

  .internship-card {
    padding: 1.25rem;
    border-radius: 18px;
    border: 1px solid rgba(15, 23, 42, 0.08);
    background: rgba(255, 255, 255, 0.95);
    box-shadow: 0 18px 40px rgba(15, 23, 42, 0.08);
  }

  .internship-card h3 {
    margin: 0 0 0.35rem;
  }

  .internship-meta {
    font-size: 0.85rem;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: var(--global-text-color-light, #6b7280);
    margin-bottom: 0.6rem;
  }

  .internship-card ul {
    margin: 0;
    padding-left: 1.1rem;
    color: var(--global-text-color-light, #6b7280);
  }

  @media (max-width: 640px) {
    .home-hero {
      padding: 1.5rem;
    }

    .hero-pills {
      flex-direction: row;
      flex-wrap: wrap;
    }

    .hero-pill {
      flex: 1 1 calc(50% - 0.5rem);
    }
  }
</style>

<section class="home-hero">
  <div>
    <p class="hero-eyebrow">Multimodal AI × Embedded Intelligence</p>
    <h1>Systems that reason, sense, and move.</h1>
    <p class="hero-lead">
      I'm Madhur Thareja, a dual-major undergrad (IIT Madras Electronic Systems + BITS Pilani Computer Science)
      building agents that fuse visual, language, and sensor streams with hardware-aware execution. My work spans
      generative perception, embodied planning, and reliable autonomy for assistive healthcare and mobility.
    </p>
    <div class="cta-group">
      <a class="cta-primary" href="{{ cv_path }}" target="_blank" rel="noopener">Download CV</a>
      <a class="cta-ghost" href="mailto:madhurthareja1105@gmail.com">Email me</a>
    </div>
  </div>
  <ul class="hero-pills">
    <li class="hero-pill"><strong>Current labs:</strong> XuLab @CMU</li>
    <li class="hero-pill"><strong>Specialty:</strong> Multimodal grounding + uncertainty-aware control</li>
    <li class="hero-pill"><strong>Systems wins:</strong> Samsung CDS podium · Intel OpenVINO RVV</li>
  </ul>
</section>

<section class="focus-grid">
  <article class="focus-card">
    <h3>Clinical & scientific reasoning</h3>
    <p>Designing multimodal pipelines that pair microscopy, language, and EHR context for diagnostic copilots.</p>
    <ul>
      <li>MediLLM + MMedRAG agents</li>
      <li>Data-efficient supervision</li>
    </ul>
  </article>
  <article class="focus-card">
    <h3>Agents that teach & assist</h3>
    <p>PAL tutors blend VLM grounding with uncertainty-aware reinforcement learning for personalized instruction.</p>
    <ul>
      <li>Multi-agent orchestration</li>
      <li>Human-in-the-loop calibration</li>
      <li>Trustworthy explanations</li>
    </ul>
  </article>
  <article class="focus-card">
    <h3>Edge autonomy</h3>
    <p>From RISC-V pipelines to smart wheelchairs, I align ML models with the limits of silicon, sensors, and power.</p>
    <ul>
      <li>RTL → GDSII tapeouts</li>
      <li>LiDAR/stereo sensor fusion</li>
      <li>OpenVINO RVV enablement</li>
    </ul>
  </article>
</section>

<section class="internship-section">
  <h2>Recent internships</h2>
  <p>Hands-on stints where I owned production-grade research pipelines and silicon-to-software stacks.</p>
  <div class="internship-cards">
    <article class="internship-card">
      <!-- <div class="internship-meta">Nov 2025 – Present · University of Pittsburgh</div>
      <h3>LivecellX — Research Intern</h3>
      <ul>
        <li>Scaling single-cell tracking with Ultrack and diffusion-based refinements for noisy microscopy.</li>
        <li>Building evaluation dashboards to stress-test segmentation ambiguity and class imbalance.</li>
        <li>Shipping Python tooling that bridges lab notebooks with reproducible pipelines.</li>
      </ul> -->
    </article>
    <article class="internship-card">
      <div class="internship-meta">Aug 2025 – Present · Carnegie Mellon University</div>
      <h3>Researcher</h3>
      <!-- <ul>
        <li>Marrying MedGemma VLM perception with structured reasoning for clinical copilots.</li>
        <li>Added symbolic filtering + retrieval control to cut hallucinations in multi-speciality agents.</li>
        <li>Designed an easy-to-hard triage trainer to surface uncertainty along complex cases.</li>
      </ul> -->
    </article>
    <article class="internship-card">
      <div class="internship-meta">Jan 2025 – Feb 2025 · Samsung Semiconductor</div>
      <h3>Chip Design Studio Fellow</h3>
      <!-- <ul>
        <li>Closed RTL → GDSII for single-cycle and 5-stage RISC-V cores across FPGA targets.</li>
        <li>Integrated UART, PWM, and sensing IP for robotics control demos under tight power budgets.</li>
        <li>Ranked #2 nationally while mentoring junior cohorts on verification and tapeout hygiene.</li>
      </ul> -->
    </article>
  </div>
</section>

<section class="impact-section">
  <h2>What I'm chasing</h2>
  <p>
    Shrinking the gap between high-level reasoning and low-level actuation so that healthcare, mobility, and assistive
    devices become more reliable, adaptive, and humane.
  </p>
  <div class="impact-grid">
    <div class="impact-card">
      <h4>Multimodal sensing ➜ action</h4>
      <p>Linking perception, language, and control policies so agents can explain why they move.</p>
    </div>
    <div class="impact-card">
      <h4>Uncertainty-aware decisions</h4>
      <p>Calibrated risk estimates that let humans stay in the loop when it matters most.</p>
    </div>
    <div class="impact-card">
      <h4>Deployable stacks</h4>
      <p>Toolchains that go from research notebooks to embedded deployments without drama.</p>
    </div>
  </div>
</section>
