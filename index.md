---
layout: page
title: ClipTrigger
---

<!-- ───── Hero Section ───── -->
<section class="hero-video">
  <video autoplay loop muted playsinline>
    <source src="{{ '/assets/img/hero_loop.mp4' | relative_url }}" type="video/mp4">
  </video>

  <div class="hero-overlay">
    <img
      class="hero-logo"
      src="{{ '/assets/img/ClipTrigger-Icon_farbig.png' | relative_url }}"
      alt="ClipTrigger App Icon">
    <h1>Relive your <span class="accent">greatest plays</span> instantly</h1>
    <p>
      ClipTrigger fires your favourite reaction clips the second something epic
      happens in-game – from local MP4s to YouTube memes.
    </p>
    <a class="cta" href="https://www.overwolf.com/app/ClipTrigger" target="_blank" rel="noopener">
      Get it on Overwolf
    </a>
  </div>
</section>

<!-- ───── Trigger Settings Section ───── -->
<section class="hero-trigger">
  <img class="hero-trigger-bg"
       src="{{ '/assets/img/Trigger-Settings.png' | relative_url }}"
       alt=""
       aria-hidden="true">

  <div class="hero-trigger-overlay">
    <div class="media">
      <img
        src="{{ '/assets/img/Trigger-Settings(2).png' | relative_url }}"
        alt="Trigger settings detail view">
    </div>

    <div class="content">
      <h2>Fine-tune every trigger</h2>
      <p>
        Define exactly when each clip should play, set hotkeys or combine effects – no coding needed.
      </p>
      <a class="cta"
         href="https://www.overwolf.com/app/ClipTrigger#screenshots"
         target="_blank"
         rel="noopener">
        Explore all options
      </a>
    </div>
  </div>
</section>

<!-- ───── Features Grid ───── -->
<section class="feature-grid">
  {% for f in site.data.features %}
  <article class="feature-card">
    <span class="feature-icon">{{ f.icon }}</span>
    <h3>{{ f.title }}</h3>
    <p>{{ f.desc }}</p>
  </article>
  {% endfor %}
</section>


