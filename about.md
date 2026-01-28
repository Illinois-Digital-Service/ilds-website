---
layout: default
title: About Us | Illinois Digital Service
permalink: /about/
---

<main class="page-about">
  {% include page-heading.html
    title="About Us"
    show_logo=true
    bg_image="/assets/images/background_images/jonnelle-yankovich-eHfntsBAgqk-unsplash.jpg"
  %}

  <section class="about-section">
    <div class="container">
      <span class="label">ABOUT US</span>
      <p class="lead">Illinois Digital Service is a network of Illinois-based civic technologists with deep experience working across federal, state, and local government.</p>
      <p>We help government leaders wrestle with the hard work of reimagining public services. We bring skills and expertise in:</p>

      <ul class="asterisk-list">
        {% include asterisk-bullet.html bg="var(--lake-1)" fg="var(--violet-2)" text="Product management" %}
        {% include asterisk-bullet.html bg="var(--yellow-1)" fg="var(--purple)" text="User experience research" %}
        {% include asterisk-bullet.html bg="var(--corn-1)" fg="var(--yellow-1)" text="Visual and content design" %}
        {% include asterisk-bullet.html bg="var(--cardinal-1)" fg="var(--red)" text="Software engineering" %}
        {% include asterisk-bullet.html bg="var(--monarch-1)" fg="var(--orange)" text="Data analysis and storytelling" %}
      </ul>

      <p>As a nonprofit technology partner, we offer pro bono services to state and local Illinois government agencies.</p>
      <p>If you're a government leader looking to improve your service delivery technology, <a href="/connect/" class="link-underline"><span>drop us a line</span></a>.</p>
    </div>
  </section>

  <section class="how-we-work-about">
    <div class="container">
      <span class="label">HOW WE WORK</span>

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
        {% include asterisk-bullet.html bg="var(--yellow-1)" fg="var(--purple)" text="Gets people what they need with less friction" %}
        {% include asterisk-bullet.html bg="var(--corn-1)" fg="var(--yellow-1)" text="Creates simple experiences that do not overwhelm" %}
        {% include asterisk-bullet.html bg="var(--cardinal-2)" fg="var(--corn-1)" text="Delivers accessible services available in many languages" %}
        {% include asterisk-bullet.html bg="var(--monarch-1)" fg="var(--red)" text="Makes life easier for government delivery staff" %}
      </ul>
    </div>
  </section>

  <section class="team-section">
    <div class="container">
      <span class="label">OUR TEAM</span>

      <div class="team-grid">
        <div class="team-card">
          <h4>Andrew Coy</h4>
          <p>Advisor</p>
        </div>
        <div class="team-card">
          <h4>Bryan Boyer</h4>
          <p>Project Management</p>
        </div>
        <div class="team-card">
          <h4>Omar Gonzalez</h4>
          <p>Talent Advisor</p>
        </div>
        <div class="team-card">
          <h4>Pam Hastings</h4>
          <p>UX Design</p>
        </div>
        <div class="team-card">
          <h4>Emily Herrick</h4>
          <p>Director of Projects</p>
        </div>
        <div class="team-card">
          <h4>Jen Philips</h4>
          <p>Workforce Advisor</p>
        </div>
        <div class="team-card">
          <h4>Nathalie Rayter</h4>
          <p>Product Manager</p>
        </div>
        <div class="team-card">
          <h4>Tyler Richardett</h4>
          <p>Data</p>
        </div>
        <div class="team-card">
          <h4>Kaleigh Simmons</h4>
          <p>Co-Founder and Content Designer</p>
        </div>
        <div class="team-card">
          <h4>Savannah Million</h4>
          <p>UX Designer</p>
        </div>
        <div class="team-card">
          <h4>Daniel Onibokun</h4>
          <p>Civic Tech Apprentice</p>
        </div>
        <div class="team-card">
          <h4>Andrew McCaskill</h4>
          <p>Civic Tech Apprentice</p>
        </div>
        <div class="team-card">
          <h4>Alex Soble</h4>
          <p>Executive Director</p>
        </div>
        <div class="team-card">
          <h4>Paige Wilson-Coleman</h4>
          <p>Civic Tech Apprentice</p>
        </div>
        <div class="team-card">
          <h4>Frank Zhu</h4>
          <p>Advisor</p>
        </div>
      </div>
    </div>
  </section>

  <section class="structure-section">
    <div class="container">
      <img src="{{ '/assets/logos/partner_digitalharbor_square.svg' | relative_url }}" alt="Digital Harbor Foundation" class="structure-logo">
      <div class="structure-content">
        <span class="label">OUR STRUCTURE</span>
        <p class="lead">Illinois Digital Service is a fiscally-sponsored project of the <a href="https://digitalharbor.org/" target="_blank" rel="noopener">Digital Harbor Foundation</a>.</p>
        <p>We are deeply grateful for their support!</p>
      </div>
    </div>
  </section>

  <section class="funders-section">
    <div class="container">
      <span class="label">FUNDERS</span>
      <div class="funders-grid">
        <a href="https://familiesandworkers.org/" target="_blank" rel="noopener"><img src="{{ '/assets/logos/partner_FWF_logo.svg' | relative_url }}" alt="The Families & Workers Fund"></a>
        <a href="https://p33chicago.com/" target="_blank" rel="noopener"><img src="{{ '/assets/logos/partner_P33_logo.svg' | relative_url }}" alt="P33"></a>
        <a href="https://www.origamiworks.org/" target="_blank" rel="noopener"><img src="{{ '/assets/logos/partner_owf_logo.avif' | relative_url }}" alt="Origami Works Foundation"></a>
      </div>
    </div>
  </section>
</main>
