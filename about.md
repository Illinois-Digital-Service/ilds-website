---
layout: default
title: About | Illinois Digital Service
permalink: /about/
---

<div class="page-about">
  {% include page-heading.html
    title="About"
    show_logo=true
    bg_image="/assets/images/background_images/jadon-johnson-6C-qwLRNHHE-unsplash.jpg"
    overlay=true
  %}

  <section class="about-section">
    <div class="container">
      <h2 class="label">ABOUT</h2>
      <p class="lead">We are a network of Illinois-based civic technologists with deep experience working across federal, state, and local government.</p>
      <p>We help government leaders wrestle with the hard work of reimagining public services, bringing skills and expertise in:</p>

      <ul class="asterisk-list">
        {% include asterisk-bullet.html bg="var(--lake-1)" fg="var(--cream)" text="Product management" %}
        {% include asterisk-bullet.html bg="var(--yellow-1)" fg="var(--violet-2)" text="User experience research" %}
        {% include asterisk-bullet.html bg="var(--corn-1)" fg="var(--yellow-1)" text="Visual and content design" %}
        {% include asterisk-bullet.html bg="var(--monarch-1)" fg="var(--cardinal-1)" text="Software engineering" %}
        {% include asterisk-bullet.html bg="var(--cardinal-2)" fg="var(--corn-1)" text="Data analysis and storytelling" %}
      </ul>

      <p>As a nonprofit technology partner, we offer pro bono services to state and local Illinois government agencies.</p>
      <p>If you're a government leader looking to improve your service delivery technology, <a href="{{ '/connect/' | relative_url }}" class="link-underline"><span>let's start a conversation</span></a>.</p>
    </div>
  </section>

  <section class="how-we-work-about">
    <div class="container">
      <h2 class="label">HOW WE WORK</h2>

      <div class="steps">
        <div class="step step-1">
          {% include number-1.html %}
          <div class="step-content">
            <h3>Start small to build momentum</h3>
            <p>We break complex problems into small, testable chunks.</p>
          </div>
        </div>
        <div class="step step-2">
          {% include number-2.html %}
          <div class="step-content">
            <h3>Work with those close to the problem</h3>
            <p>We collaborate deeply with government staff and nonprofit partners.</p>
          </div>
        </div>
        <div class="step step-3">
          {% include number-3.html %}
          <div class="step-content">
            <h3>Test ideas with real people</h3>
            <p>We take ideas out of the theoretical and test them in the real world as quickly as possible.</p>
          </div>
        </div>
        <div class="step step-4">
          {% include number-4.html %}
          <div class="step-content">
            <h3>Deliver early and often</h3>
            <p>We don't wait for the perfect version of "done" before we start delivering.</p>
          </div>
        </div>
        <div class="step step-5">
          {% include number-5.html %}
          <div class="step-content">
            <h3>Share what we learn</h3>
            <p>We work in the open and publish as we go.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="results-section">
    <div class="container">
      <p class="lead">This results in technology that:</p>

      <ul class="asterisk-list">
        {% include asterisk-bullet.html bg="var(--yellow-1)" fg="var(--violet-2)" text="Gets people what they need with less friction" %}
        {% include asterisk-bullet.html bg="var(--corn-1)" fg="var(--yellow-1)" text="Creates simple experiences that do not overwhelm" %}
        {% include asterisk-bullet.html bg="var(--cardinal-2)" fg="var(--corn-1)" text="Delivers accessible services available in many languages" %}
        {% include asterisk-bullet.html bg="var(--monarch-1)" fg="var(--cardinal-1)" text="Makes life easier for government delivery staff" %}
      </ul>
    </div>
  </section>

  <section class="team-section">
    <div class="container">
      <h2 class="label">LEADERSHIP</h2>
      <div class="team-grid">
        {% include team-card.html name="Emily Herrick" role="Director of Projects" %}
        {% include team-card.html name="Alex Soble" role="Executive Director" %}
      </div>
      <br/>
      <br/>
      <h2 class="label">CONTRIBUTORS</h2>
      <div class="team-grid">
        {% include team-card.html name="Omar Gonzalez" role="Talent Advisor" %}
        {% include team-card.html name="Nathalie Rayter" role="Product Manager" %}
        {% include team-card.html name="Kaleigh Simmons" role="Co-Founder and Content Designer" %}
        {% include team-card.html name="Savannah Million" role="UX Designer" %}
        {% include team-card.html name="Andrew McCaskill" role="Civic Tech Apprentice" %}
        {% include team-card.html name="Paige Wilson-Coleman" role="Civic Tech Apprentice" %}
      </div>
      <br/>
      <br/>
      <h2 class="label">ADVISORY COMMITTEE</h2>
      <div class="team-grid">
        {% include team-card.html name="Andrew Coy" role="Advisor" %}
        {% include team-card.html name="Frank Zhu" role="Advisor" %}
        {% include team-card.html name="Jennifer Phillips" role="Advisor" %}
      </div>
    </div>
  </section>

  <section class="structure-section">
    <div class="container">
      <img src="{{ '/assets/logos/partner_digitalharbor_square.svg' | relative_url }}" alt="Digital Harbor Foundation" class="structure-logo">
      <div class="structure-content">
        <h2 class="label">OUR STRUCTURE</h2>
        <p class="lead">Illinois Digital Service is a fiscally-sponsored project of the <a href="https://digitalharbor.org/" target="_blank" rel="noopener">Digital Harbor Foundation<span class="visually-hidden"> (opens in new tab)</span></a>.</p>
      </div>
    </div>
  </section>

  <section class="funders-section">
    <div class="container">
      <h2 class="label">FUNDERS</h2>
      <div class="funders-grid">
        <a href="https://familiesandworkers.org/" target="_blank" rel="noopener" aria-label="The Families & Workers Fund (opens in new tab)">
          <img src="{{ '/assets/logos/partner_FWF_logo.svg' | relative_url }}" alt="The Families & Workers Fund - visit The Families & Workers Fund website">
        </a>
        <a href="https://p33chicago.com/" target="_blank" rel="noopener" aria-label="P33 (opens in new tab)">
          <img src="{{ '/assets/logos/partner_P33_logo.svg' | relative_url }}" alt="P33 - visit the P33 website">
        </a>
        <a href="https://www.origamiworks.org/" target="_blank" rel="noopener" aria-label="Origami Works Foundation (opens in new tab)">
          <img src="{{ '/assets/logos/partner_owf_logo.avif' | relative_url }}" alt="Origami Works Foundation - visit the Origami Works Foundation website">
        </a>
      </div>
    </div>
  </section>
</div>
