---
layout: default
title: Illinois Digital Service
---

<section class="hero">
  <div class="container">
    {% include hero-logo.html %}
  </div>
</section>

<section class="mission">
  <div class="container">
    <h1>Making Illinois public services easier to use for everybody who lives here.</h1>
    <p>Illinois Digital Service works shoulder-to-shoulder with Illinois government agencies to deliver better technology, faster.</p>
  </div>
</section>

<section class="how-we-work">
  <div class="container">
    <h2 class="label">HOW WE WORK</h2>

    <div class="steps">
      <div class="step step-1">
        <img src="{{ '/assets/images/illustrations/1-monarch.png' | relative_url }}" alt="" class="step-number">
        <h3 class="h4">Start small to build momentum</h3>
      </div>
      <div class="step step-2">
        <img src="{{ '/assets/images/illustrations/2-violet.png' | relative_url }}" alt="" class="step-number">
        <h3 class="h4">Work with those close to the problem</h3>
      </div>
      <div class="step step-3">
        <img src="{{ '/assets/images/illustrations/3-boat.png' | relative_url }}" alt="" class="step-number">
        <h3 class="h4">Test ideas with real people</h3>
      </div>
      <div class="step step-4">
        <img src="{{ '/assets/images/illustrations/4-cardinal.png' | relative_url }}" alt="" class="step-number">
        <h3 class="h4">Deliver early and often</h3>
      </div>
      <div class="step step-5">
        <img src="{{ '/assets/images/illustrations/5-corn.png' | relative_url }}" alt="" class="step-number">
        <h3 class="h4">Share what we learn</h3>
      </div>
    </div>

    <a href="{{ '/about/' | relative_url }}" class="link-underline"><span>Learn more about us</span></a>
  </div>
</section>

{% include cta-section.html
  heading="Our projects"
  heading_url="/projects/"
  bg_color="var(--orange)"
  text_color="var(--cream)"
  link_color="var(--cream)"
%}

{% include cta-section.html
  heading="Work with IL*DS"
  heading_url="/connect/"
  bg_image="/assets/images/background_images/wonderhunt-VnPmEZ95Y1U-unsplash.jpg"
  text_color="var(--cream)"
  link_color="var(--cream)"
  overlay=true
%}

