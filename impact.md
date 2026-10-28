---
layout: default
title: DRAFT 2026 Impact | Illinois Digital Service
permalink: /preview-impact/
noindex: true
---

<section class="impact-gate" id="impact-gate">
  <div class="container">
    <p class="label">DRAFT PREVIEW</p>
    <h1>2026 Impact</h1>
    <p>This page is a draft. Enter the password to view it.</p>
    <form id="impact-gate-form">
      <label for="impact-gate-password">Password</label>
      <div class="impact-gate-row">
        <input type="password" id="impact-gate-password" autocomplete="current-password" required>
        <button type="submit">View draft</button>
      </div>
      <p class="impact-gate-error" id="impact-gate-error" role="alert"></p>
    </form>
  </div>
</section>

<div id="impact-content" hidden>
<div class="page-impact">
  {% include page-heading.html
    title="DRAFT: 2026 Impact"
    show_logo=true
    bg_image="/assets/images/background_images/prairie.jpg"
    bg_position="center"
    overlay=true
  %}

  <section class="impact-intro">
    <div class="container">
      <h2 class="label">2026</h2>
      <p class="lead">Here's what we've worked on with Illinois public agencies this year, and what's changed for the people they serve.</p>
    </div>
  </section>

  <section class="impact-project">
    <div class="container">
      <p class="label impact-partner">IN PARTNERSHIP WITH: ILLINOIS DEPARTMENT OF LABOR</p>
      <h2>Website redesign</h2>

      <ul class="asterisk-list">
        {% capture idol_1 %}<strong>Redesigned and simplified content based on user needs.</strong> Brought grade reading level on key website pages from 12th and 9th grade levels down to 6th.{% endcapture %}
        {% include asterisk-bullet.html bg="var(--lake-1)" fg="var(--cream)" text=idol_1 %}
        {% capture idol_2 %}<strong>Ran user testing sessions with Illinois workers</strong>, testing prototypes with Spanish-speaking and Chinese-speaking workers.{% endcapture %}
        {% include asterisk-bullet.html bg="var(--yellow-1)" fg="var(--violet-2)" text=idol_2 %}
        {% capture idol_3 %}<strong>Improved automated translations</strong> by working with a Spanish-speaking UX expert to customize AI-generated Spanish translations.{% endcapture %}
        {% include asterisk-bullet.html bg="var(--corn-1)" fg="var(--yellow-1)" text=idol_3 %}
      </ul>

      <div class="impact-figures">
        <figure class="impact-figure">
          <img src="{{ '/assets/images/impact-2026/idol-homepage-before.jpg' | relative_url }}" alt="The old Department of Labor homepage: a large agency seal above a dense paragraph describing the department's responsibilities and office locations." loading="lazy">
          <figcaption>Before</figcaption>
        </figure>
        <figure class="impact-figure">
          <img src="{{ '/assets/images/impact-2026/idol-homepage-after.jpg' | relative_url }}" alt="The new Department of Labor homepage: a photo of two workers in hard hats, a one-sentence summary of what the department does, and a &quot;How can we help you?&quot; section with separate links for workers and employers." loading="lazy">
          <figcaption>Now</figcaption>
        </figure>
      </div>
    </div>
  </section>

  <section class="impact-project impact-project-alt">
    <div class="container">
      <p class="label impact-partner">IN PARTNERSHIP WITH: CITY OF CHICAGO - CUT THE TAPE INITIATIVE, DEPARTMENT OF TECHNOLOGY &amp; INNOVATION, DEPARTMENT OF HOUSING</p>
      <h2>Speeding affordable housing development</h2>

      <ul class="asterisk-list">
        {% capture chi_1 %}Sketched a first-draft <strong>service journey map</strong> of reviews.{% endcapture %}
        {% capture chi_2 %}Ran <strong>11 user research interviews</strong> with affordable housing developers, permitting expeditors, and city staff to understand the service journey of reviewing city-funded affordable housing.{% endcapture %}
        {% include asterisk-bullet.html bg="var(--cardinal-2)" fg="var(--corn-1)" text=chi_2 %}
        {% include asterisk-bullet.html bg="var(--monarch-1)" fg="var(--cardinal-1)" text=chi_1 %}
        {% capture chi_3 %}Worked with the Department of Technology &amp; Innovation, Department of Housing, and Cut the Tape Initiative to <strong>prototype a unified data tracker</strong> for affordable housing developments.{% endcapture %}
        {% include asterisk-bullet.html bg="var(--violet-1)" fg="var(--lake-4)" text=chi_3 %}
      </ul>

      <div class="impact-figures">
        <figure class="impact-figure is-portrait">
          <img src="{{ '/assets/images/impact-2026/housing-journey-stickies.jpg' | relative_url }}" alt="Sticky notes on a large sheet of paper, mapping the City departments and reviews involved in building affordable housing." loading="lazy">
          <figcaption>Lots of sticky notes as we mapped the cross-departmental service journey of affordable housing reviews</figcaption>
        </figure>
        <figure class="impact-figure">
          <img src="{{ '/assets/images/impact-2026/housing-tracker-wireframe.jpg' | relative_url }}" alt="A low-fidelity wireframe of the housing tracker: a map of Chicago with affordable housing properties marked, and a status panel showing how many days a sample project has spent in each review stage." loading="lazy">
          <figcaption>Using lo-fi wireframes to get feedback on ideas and designs</figcaption>
        </figure>
      </div>
    </div>
  </section>

  <section class="impact-project impact-more">
    <div class="container">
      <p class="label">AND MORE</p>
      <h2>Building the field</h2>

      <div class="impact-more-cards">
        <div class="impact-more-card">
          <img src="{{ '/assets/images/illustrations/violet.png' | relative_url }}" alt="" class="impact-more-illustration">
          <div class="impact-more-content">
            <h3>Shared best practices</h3>
            <p>with government staff and leaders at the state, county, and city levels on technology and design topics like:</p>
            <ul class="plain-list">
              <li>mobile-first development</li>
              <li>user-centered data strategy</li>
              <li>setting up innovation teams</li>
            </ul>
          </div>
        </div>
        <div class="impact-more-card">
          <img src="{{ '/assets/images/illustrations/monarch.png' | relative_url }}" alt="" class="impact-more-illustration">
          <div class="impact-more-content">
            <h3>Published six posts on our Illinotes blog</h3>
            <p>on topics ranging from <a href="https://illinoisdigitalservice.substack.com/p/three-things-to-know-about-hiring" target="_blank" rel="noopener">government technology hiring</a>,
              <span class="impact-more-line">to how we <a href="https://illinoisdigitalservice.substack.com/p/building-and-announcing-the-illinois" target="_blank" rel="noopener">built and launched our own website</a>.</span></p>
          </div>
        </div>
        <div class="impact-more-card">
          <img src="{{ '/assets/images/illustrations/corn.png' | relative_url }}" alt="" class="impact-more-illustration">
          <div class="impact-more-content">
            <h3>Piloted a civic tech apprenticeship program</h3>
            <p>to build pipelines that connect Illinois talent with state and local government technology.</p>
            <p>Read one apprentice's <a href="https://illinoisdigitalservice.substack.com/p/what-i-learned-as-a-civic-technology" target="_blank" rel="noopener">capstone reflection</a>.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="impact-stats-section">
    <div class="container">
      <h2 class="impact-stats-heading"><span class="label">2026</span> By the numbers</h2>
      <ul class="impact-stats" aria-label="2026 highlights">
        <li class="impact-stat impact-stat-1">
          <span class="impact-stat-number impact-stat-number-pair">
            <span>12th <span aria-hidden="true">→</span><span class="visually-hidden">to</span> 6th<span class="visually-hidden">,</span></span>
            <span>9th <span aria-hidden="true">→</span><span class="visually-hidden">to</span> 6th</span>
          </span>
          <span class="impact-stat-text">Grade reading level on key Department of Labor web pages</span>
        </li>
        <li class="impact-stat impact-stat-2">
          <span class="impact-stat-number">11</span>
          <span class="impact-stat-text">User research interviews with people who build and review affordable housing developments in Chicago</span>
        </li>
        <li class="impact-stat impact-stat-3">
          <span class="impact-stat-number">6</span>
          <span class="impact-stat-text">Posts on civic technology published on our Illinotes blog</span>
        </li>
        <li class="impact-stat impact-stat-4">
          <span class="impact-stat-number">10</span>
          <span class="impact-stat-text">Usability tests with workers for Department of Labor web redesign</span>
        </li>
      </ul>
    </div>
  </section>
</div>

{% include cta-section.html
  heading="Read more on Illinotes"
  heading_url="https://illinoisdigitalservice.substack.com/"
  bg_color="var(--orange)"
  text_color="var(--cream)"
  link_color="var(--cream)"
  new_tab=true
%}

{% include cta-section.html
  heading="Work with IL*DS"
  heading_url="/connect/"
  bg_image="/assets/images/background_images/wonderhunt-VnPmEZ95Y1U-unsplash.jpg"
  text_color="var(--cream)"
  link_color="var(--cream)"
  overlay=true
%}
</div>

<script>
  // Lightweight client-side gate for the draft. Not real security: the content is still in the page source.
  (function () {
    const PASSWORD_HASH = 'e95666cc1c3310e3e200e1f55330453e7640973237a181cc9ca330bfcd259585';
    const STORAGE_KEY = 'impact-draft-unlocked';
    const gate = document.getElementById('impact-gate');
    const content = document.getElementById('impact-content');
    const form = document.getElementById('impact-gate-form');
    const input = document.getElementById('impact-gate-password');
    const error = document.getElementById('impact-gate-error');

    function unlock() {
      gate.hidden = true;
      content.hidden = false;
    }

    async function sha256(text) {
      const buffer = await crypto.subtle.digest('SHA-256', new TextEncoder().encode(text));
      return Array.from(new Uint8Array(buffer)).map(b => b.toString(16).padStart(2, '0')).join('');
    }

    try {
      if (sessionStorage.getItem(STORAGE_KEY) === 'true') unlock();
    } catch (e) {}

    form.addEventListener('submit', async (event) => {
      event.preventDefault();
      if (await sha256(input.value.trim()) === PASSWORD_HASH) {
        try { sessionStorage.setItem(STORAGE_KEY, 'true'); } catch (e) {}
        unlock();
        window.scrollTo(0, 0);
      } else {
        error.textContent = 'That password is not right. Try again.';
        input.select();
      }
    });
  })();
</script>
