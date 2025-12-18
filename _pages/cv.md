---
layout: none
permalink: /cv/
title: CV
nav: true
nav_order: 5
description: Download the latest resume.
---

{% assign cv_path = "/assets/pdf/Madhur_Thareja_Resume.pdf" %}

<meta http-equiv="refresh" content="0; url={{ cv_path }}" />

<section class="cv-redirect">
  <h2>Opening your CV…</h2>
  <p>If the PDF doesn't open automatically, you can download it directly below.</p>
  <a class="btn" href="{{ cv_path }}" target="_blank" rel="noopener">Download CV</a>
</section>

<style>
  .cv-redirect {
    min-height: 50vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    gap: 1rem;
  }

  .cv-redirect .btn {
    display: inline-flex;
    gap: 0.4rem;
    align-items: center;
    padding: 0.65rem 1.5rem;
    border-radius: 999px;
    background: var(--global-theme-color); 
    color: #fff;
    text-decoration: none;
    font-weight: 600;
    box-shadow: 0 12px 30px rgba(15, 23, 42, 0.18);
  }

  .cv-redirect .btn:hover {
    filter: brightness(1.05);
  }
</style>
