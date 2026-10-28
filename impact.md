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
    <p>This page is a draft for review and feedback. Enter the password to view it.</p>
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
      <h2>Improving an Illinois Department’s Digital Front Door</h2>

      <div class="impact-body">
        <h3 class="label">BACKGROUND</h3>
        <p>The Department of Labor supports workers whose labor rights have been violated because their employer did not follow workplace laws — for example, by stealing wages, not paying minimum wage, or denying meal breaks.</p>
        <p>To better serve workers in crisis, we have been partnering to reimagine <a href="https://labor.illinois.gov" target="_blank" rel="noopener">labor.illinois.gov</a>, the Department’s digital front door.</p>
      </div>

      <div class="impact-context">
        <div class="impact-goal">
          <p class="label">OUR SHARED GOAL</p>
          <p>Transform a website that holds dense legal content about Illinois labor law into a plain-language resource easier to access and understand.</p>
        </div>
      </div>

      <h3 class="label impact-done-label">WHAT WE’VE DONE</h3>
      <ul class="asterisk-list">
        {% capture idol_2 %}<strong>Learned from workers through user research and usability testing.</strong> Gathered feedback and tested prototypes with Spanish-speaking and Chinese-speaking workers.{% endcapture %}
        {% include asterisk-bullet.html bg="var(--yellow-1)" fg="var(--violet-2)" text=idol_2 %}
        {% capture idol_1 %}<strong>Redesigned and simplified content based on user needs.</strong> Lowered grade reading level on key website pages from 12th and 9th grade levels to 6th.{% endcapture %}
        {% include asterisk-bullet.html bg="var(--lake-1)" fg="var(--cream)" text=idol_1 %}
        {% capture idol_3 %}<strong>Discovered and corrected AI hallucinations in translated content.</strong> Brought humans into the loop to customize and correct AI-generated translations.{% endcapture %}
        {% include asterisk-bullet.html bg="var(--corn-1)" fg="var(--yellow-1)" text=idol_3 %}
      </ul>

      <div class="impact-figures">
        <figure class="impact-figure">
          <picture>
            <source media="(max-width: 767px)" srcset="{{ '/assets/images/impact-2026/idol-homepage-before-mobile.jpg' | relative_url }}">
            <img src="{{ '/assets/images/impact-2026/idol-homepage-before.jpg' | relative_url }}" alt="The old Department of Labor homepage: a large agency seal, the heading &quot;Welcome to the Illinois Department of Labor,&quot; and a paragraph describing the department's size, responsibilities, and office locations." loading="lazy">
          </picture>
          <figcaption>Before</figcaption>
        </figure>
        <figure class="impact-figure">
          <picture>
            <source media="(max-width: 767px)" srcset="{{ '/assets/images/impact-2026/idol-homepage-after-mobile.jpg' | relative_url }}">
            <img src="{{ '/assets/images/impact-2026/idol-homepage-after.jpg' | relative_url }}" alt="The new Department of Labor homepage: a one-sentence summary, &quot;We protect workers' wages, help employers follow the law, and ensure everyone understands their rights at work,&quot; followed by a &quot;How can we help you?&quot; section with separate lists of links for workers and for employers." loading="lazy">
          </picture>
          <figcaption>Now</figcaption>
        </figure>
      </div>
    </div>
  </section>

  <section class="impact-project impact-project-alt">
    <div class="container">
      <p class="label impact-partner">IN PARTNERSHIP WITH: CITY OF CHICAGO – CUT THE TAPE INITIATIVE, DEPARTMENT OF TECHNOLOGY &amp; INNOVATION, DEPARTMENT OF HOUSING</p>
      <h2>Speeding Affordable Housing Development</h2>

      <div class="impact-body">
        <h3 class="label">BACKGROUND</h3>
        <p>Chicago funds affordable housing development through its Low-Income Housing Tax Credit program. Before construction can begin, these projects go through processes to review designs, secure permits, and secure financing, working with multiple departments and with City Council. This can take more than 30 months to complete.</p>
        <p>Through its Cut the Tape Initiative, the city has invested in bringing that timeline down to 18 months.</p>
      </div>

      <div class="impact-context">
        <div class="impact-goal">
          <p class="label">OUR SHARED GOAL</p>
          <p>Use cross-department technology, service design, and convening to improve handoffs, break down siloed processes, and unify data tracking in order to speed affordable housing development.</p>
        </div>
      </div>

      <h3 class="label impact-done-label">WHAT WE’VE DONE</h3>
      <ul class="asterisk-list">
        {% capture chi_1 %}Sketched a first-draft <strong>service journey map</strong> of reviews.{% endcapture %}
        {% capture chi_2 %}Organized <strong>11 user research interviews</strong> with affordable housing developers, permitting expeditors, and city staff to understand the service journey.{% endcapture %}
        {% include asterisk-bullet.html bg="var(--cardinal-2)" fg="var(--corn-1)" text=chi_2 %}
        {% include asterisk-bullet.html bg="var(--monarch-1)" fg="var(--cardinal-1)" text=chi_1 %}
        {% capture chi_3 %}Worked with the Department of Technology &amp; Innovation, the Department of Housing, and the Cut the Tape Initiative to <strong>prototype a unified data tracker</strong> for affordable housing developments.{% endcapture %}
        {% include asterisk-bullet.html bg="var(--violet-1)" fg="var(--lake-4)" text=chi_3 %}
        {% capture chi_4 %}<strong>Piloted a cross-team status meeting</strong> using the prototype to guide project updates.{% endcapture %}
        {% include asterisk-bullet.html bg="var(--lake-1)" fg="var(--cream)" text=chi_4 %}
      </ul>

      <div class="impact-figures">
        <figure class="impact-figure is-portrait">
          <img src="{{ '/assets/images/impact-2026/housing-journey-stickies.jpg' | relative_url }}" alt="Sticky notes on a large sheet of paper, mapping the City departments and reviews involved in building affordable housing." loading="lazy">
          <figcaption>Lots of sticky notes as we mapped the cross-departmental service journey</figcaption>
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
      <h2>Building the Field</h2>

      <div class="impact-body">
        <p>We help build the field of civic technology in Illinois.</p>
      </div>

      <div class="impact-context">
        <div class="impact-goal">
          <p class="label">OUR SHARED GOAL</p>
          <p>Spread new ways of working, share ideas, and invest in the next generation of civic tech talent.</p>
        </div>
      </div>

      <div class="impact-more-cards">
        <div class="impact-more-card">
          <img src="{{ '/assets/images/illustrations/corn.png' | relative_url }}" alt="" class="impact-more-illustration">
          <div class="impact-more-content">
            <h3>Piloted a civic tech apprenticeship program</h3>
            <p>to build pipelines that connect Illinois talent with state and local government technology.</p>
            <p>Read one apprentice's <a href="https://illinoisdigitalservice.substack.com/p/what-i-learned-as-a-civic-technology" target="_blank" rel="noopener">capstone reflection</a>.</p>
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
          <span class="impact-stat-text">Simplified, easier-to-read content on key Department of Labor web pages, lowering grade reading levels</span>
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
          <span class="impact-stat-number">12</span>
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
