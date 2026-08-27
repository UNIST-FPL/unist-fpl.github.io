---
layout: splash
permalink: /
hidden: true
classes:
  - fpl-landing-page
title: "Fusion and Plasma Application Research Laboratory"
excerpt: "FPL develops simulation tools and conducts research for fusion energy and plasma applications."
---

<main class="fpl-landing" aria-labelledby="fpl-landing-title">
  <section class="fpl-landing__hero">
    <img
      class="fpl-landing__logo"
      src="{{ '/assets/images/FPL_Logo.png' | relative_url }}"
      alt="FPL — Fusion and Plasma Application Research Laboratory"
    />

    <h1 id="fpl-landing-title">Fusion and Plasma Application Research Laboratory</h1>
    <p class="fpl-landing__intro">
      We develop simulation tools and conduct research to address key challenges
      in fusion energy and plasma applications.
    </p>

    <div class="fpl-landing__actions" aria-label="Website links">
      <a
        class="fpl-landing__button fpl-landing__button--primary"
        href="https://pond-steel-3de.notion.site/Fusion-and-Plasma-application-research-Laboratory-36dbea4215f28075b141e972ef659a9f?source=copy_link"
        target="_blank"
        rel="noopener noreferrer"
      >
        Visit the FPL Website
        <span aria-hidden="true">&#8599;</span>
      </a>
      <a class="fpl-landing__button fpl-landing__button--secondary" href="{{ '/legacy/' | relative_url }}">
        Previous Website
      </a>
    </div>
  </section>

  <section class="fpl-landing__research" aria-labelledby="fpl-research-title">
    <p class="fpl-landing__eyebrow">Research at FPL</p>
    <h2 id="fpl-research-title">Simulation, physics, and computation</h2>

    <div class="fpl-landing__gallery">
      <figure class="fpl-landing__research-card">
        <div class="fpl-landing__image-wrap">
          <img src="{{ '/assets/images/FPL-MIResearch.png' | relative_url }}" alt="Plasma transport and magnetic-island simulation results" loading="lazy" />
        </div>
        <figcaption>Plasma Transport &amp; Magnetic Islands</figcaption>
      </figure>

      <figure class="fpl-landing__research-card">
        <div class="fpl-landing__image-wrap">
          <img src="{{ '/assets/images/FPL-GkCodDev.png' | relative_url }}" alt="Parallel meshing and plasma simulation code workflow" loading="lazy" />
        </div>
        <figcaption>Plasma Simulation Code Development</figcaption>
      </figure>
    </div>
  </section>
</main>
