---
layout: about
title: about
permalink: /
subtitle: Undergraduate Researcher in Machine Learning and Scientific Computing Lab @ Seoul National University

profile:
  align: right
  image: profile_dh_video.mp4
  image_circular: false
  more_info: >
    <p><a href="https://snu-mlsc.github.io/" target="_blank" rel="noopener noreferrer">SNU MLSC Lab</a></p>
    <p>Seoul, South Korea</p>

selected_papers: false
social: false

announcements:
  enabled: false
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

<style>
  :root {
    --dh-ink: #1c1917;
    --dh-muted: #78716c;
    --dh-accent: #b45309;
    --dh-line: #e7e5e4;
    --dh-panel: #f5f5f4;
    --global-theme-color: #b45309;
  }

  html[data-theme="dark"] {
    --dh-ink: #f5f5f4;
    --dh-muted: #a8a29e;
    --dh-accent: #f59e0b;
    --dh-line: #44403c;
    --dh-panel: #292524;
    --global-theme-color: #f59e0b;
  }

  body.fixed-top-nav {
    padding-top: 0 !important;
  }

  body > header,
  body > footer {
    display: none !important;
  }

  .post {
    color: var(--dh-ink);
    font-family: "Iowan Old Style", "Palatino Linotype", Palatino, Georgia, "Times New Roman", serif;
  }

  .post a {
    color: var(--dh-accent);
    text-decoration-thickness: 1px;
    text-underline-offset: 0.18em;
  }

  .post-header {
    margin-bottom: 1.1rem;
    padding-bottom: 0.85rem;
    border-bottom: 1px solid var(--dh-line);
  }

  .post-title {
    font-size: 2.15rem;
    font-weight: 600;
    letter-spacing: -0.02em;
    line-height: 1.15;
  }

  .post-header .desc {
    margin-top: 0.45rem;
    color: var(--dh-muted);
    font-family: "Segoe UI", "Helvetica Neue", Arial, sans-serif;
    font-size: 0.95rem;
    letter-spacing: 0.01em;
  }

  article > .profile {
    width: 200px !important;
    max-width: 32%;
    margin-top: 0.15rem;
    margin-bottom: 0.4rem;
  }

  article > .profile video {
    display: block;
    width: 100%;
    height: auto;
    border: 1px solid var(--dh-ink);
    border-radius: 2px;
    object-fit: cover;
  }

  article > .profile .more-info {
    margin-top: 0.55rem;
    color: var(--dh-muted);
    font-family: "Segoe UI", "Helvetica Neue", Arial, sans-serif;
    font-size: 0.82rem;
    line-height: 1.45;
  }

  article > .profile .more-info p {
    margin: 0;
  }

  .home-sections {
    clear: both;
    margin-top: 1.6rem;
    padding-top: 0;
  }

  .home-sections h2 {
    margin-top: 2.5rem;
    margin-bottom: 0.95rem;
    color: var(--dh-muted);
    font-family: "Segoe UI", "Helvetica Neue", Arial, sans-serif;
    font-size: 0.74rem;
    font-weight: 600;
    letter-spacing: 0.16em;
    text-transform: uppercase;
  }

  .home-sections h2::after {
    content: "";
    display: block;
    width: 1.7rem;
    height: 2px;
    margin-top: 0.45rem;
    background: var(--dh-accent);
  }

  .home-sections h2:first-child {
    margin-top: 0;
  }

  .home-sections .news table {
    margin: 0;
  }

  .home-sections .news th {
    width: 22%;
    padding: 0.35rem 0.9rem 0.35rem 0;
    border: 0;
    color: var(--dh-muted);
    font-family: "Segoe UI", "Helvetica Neue", Arial, sans-serif;
    font-size: 0.86rem;
    font-variant-numeric: tabular-nums;
    font-weight: 500;
  }

  .home-sections .news td {
    padding: 0.35rem 0;
    border: 0;
    border-left: 1px solid var(--dh-line);
    padding-left: 0.95rem;
  }

  .profile-links {
    margin-top: 1rem;
    font-family: "Segoe UI", "Helvetica Neue", Arial, sans-serif;
    font-size: 0.92rem;
  }

  .profile-links a {
    margin-right: 0;
    color: var(--dh-ink);
    text-decoration: none;
  }

  .profile-links a + a::before {
    content: "/";
    margin: 0 0.55rem;
    color: var(--dh-muted);
  }

  .profile-links a:hover {
    color: var(--dh-accent);
  }

  .publication-toolbar {
    display: flex;
    align-items: baseline;
    justify-content: space-between;
    gap: 1rem;
    margin: 0 0 1.25rem;
  }

  .publication-note {
    margin: 0;
    color: var(--dh-muted);
    font-family: "Segoe UI", "Helvetica Neue", Arial, sans-serif;
    font-size: 0.86rem;
  }

  .publication-toggle {
    display: inline-flex;
    gap: 1rem;
    margin: 0;
    padding: 0;
    border: 0;
    background: transparent;
  }

  .publication-toggle button {
    border: 0;
    border-bottom: 1px solid transparent;
    border-radius: 0;
    background: transparent;
    color: var(--dh-muted);
    padding: 0.15rem 0;
    cursor: pointer;
    font-family: "Segoe UI", "Helvetica Neue", Arial, sans-serif;
    font-size: 0.86rem;
    font-weight: 500;
    letter-spacing: 0.04em;
    text-transform: uppercase;
  }

  .publication-toggle button[aria-selected="true"] {
    background: transparent;
    border-bottom-color: var(--dh-accent);
    color: var(--dh-ink);
  }

  .publication-panel[hidden] {
    display: none;
  }

  .publication-panel.publications {
    margin-top: 0;
  }

  .publication-panel ol.bibliography {
    margin: 0;
  }

  .publication-panel ol.bibliography > li {
    margin-bottom: 0;
    padding: 1.5rem 0;
    border-top: 1px solid var(--dh-line);
  }

  .publication-panel ol.bibliography > li:first-child {
    padding-top: 0;
    border-top: 0;
  }

  .publication-panel ol.bibliography > li:last-child {
    padding-bottom: 0;
  }

  .publication-panel ol.bibliography > li > .row {
    display: grid;
    grid-template-columns: 220px minmax(0, 1fr);
    gap: 1.5rem;
    align-items: start;
    margin: 0;
  }

  .publication-panel ol.bibliography > li > .row > .abbr,
  .publication-panel ol.bibliography > li > .row > [id] {
    flex: none;
    width: auto;
    max-width: none;
    padding: 0;
  }

  .publication-panel ol.bibliography .abbr {
    margin: 0;
  }

  .publication-panel ol.bibliography .abbr figure {
    margin: 0;
  }

  .publication-panel ol.bibliography .preview {
    display: block;
    width: 220px;
    max-width: 100%;
    height: auto;
    background: #111;
    border: 1px solid var(--dh-ink);
    border-radius: 0 !important;
    box-shadow: none;
  }

  .publication-panel ol.bibliography video.preview {
    object-fit: cover;
  }

  .publication-panel ol.bibliography .title {
    margin-bottom: 0.45rem;
    color: var(--dh-ink);
    font-size: 1.2rem;
    font-weight: 600;
    letter-spacing: -0.015em;
    line-height: 1.3;
  }

  .publication-panel ol.bibliography .title a {
    color: inherit;
    text-decoration: none;
  }

  .publication-panel ol.bibliography .title a:hover {
    color: var(--dh-accent);
  }

  .publication-panel ol.bibliography .author {
    margin-bottom: 0.45rem;
    color: var(--dh-muted);
    font-family: "Segoe UI", "Helvetica Neue", Arial, sans-serif;
    font-size: 0.92rem;
    line-height: 1.5;
  }

  .publication-panel ol.bibliography .author > em {
    color: var(--dh-ink);
    font-style: normal;
    font-weight: 600;
    border-bottom: 0;
  }

  .publication-panel ol.bibliography .periodical {
    margin-bottom: 0.65rem;
    color: var(--dh-ink);
    font-family: "Segoe UI", "Helvetica Neue", Arial, sans-serif;
    font-size: 0.92rem;
  }

  .publication-panel ol.bibliography .periodical em {
    font-style: italic;
    font-weight: 500;
  }

  .publication-panel ol.bibliography .pub-demo {
    margin-left: 0.35rem;
    color: var(--dh-accent);
    font-style: italic;
    font-weight: 500;
  }

  .publication-panel ol.bibliography .links {
    display: flex;
    flex-wrap: wrap;
    gap: 0.85rem;
    margin-top: 0.75rem;
  }

  .publication-panel ol.bibliography .links:empty {
    display: none;
  }

  .publication-panel ol.bibliography .links a.btn {
    margin: 0;
    padding: 0;
    border: 0;
    border-radius: 0;
    background: transparent;
    color: var(--dh-ink);
    font-family: "Segoe UI", "Helvetica Neue", Arial, sans-serif;
    font-size: 0.84rem;
    font-weight: 500;
    letter-spacing: 0.04em;
    text-transform: uppercase;
    text-decoration: underline;
    text-underline-offset: 0.22em;
  }

  .publication-panel ol.bibliography .links a.btn:hover {
    background: transparent;
    color: var(--dh-accent);
  }

  .publication-panel ol.bibliography .links a[href*="arxiv.org"] {
    order: 1;
  }

  .publication-panel ol.bibliography .links a.abstract {
    display: none;
  }

  .publication-panel ol.bibliography .links a[href*="diffbmp.com"] {
    order: 2;
  }

  .publication-panel ol.bibliography .links a.bibtex {
    order: 3;
  }

  .publication-tldr {
    margin-top: 0.85rem;
    padding: 0.7rem 0.85rem;
    border: 0;
    background: var(--dh-panel);
    color: var(--dh-muted);
    font-family: "Segoe UI", "Helvetica Neue", Arial, sans-serif;
    font-size: 0.9rem;
    line-height: 1.55;
  }

  .publication-tldr p {
    margin: 0;
  }

  .publication-tldr-label {
    color: var(--dh-ink);
    font-weight: 600;
  }

  .publication-tldr-more[hidden] {
    display: none;
  }

  .publication-tldr-toggle {
    margin-left: 0.35rem;
    padding: 0;
    border: 0;
    background: transparent;
    color: var(--dh-accent);
    cursor: pointer;
    font: inherit;
    font-weight: 600;
  }

  .home-sections ul {
    padding-left: 0;
    list-style: none;
  }

  .home-sections li {
    margin-bottom: 0.55rem;
    font-family: "Segoe UI", "Helvetica Neue", Arial, sans-serif;
    line-height: 1.55;
  }

  .experience-list {
    margin: 0;
    padding: 0;
    list-style: none;
  }

  .experience-list li {
    margin: 0 0 1.2rem;
  }

  .experience-list li:last-child {
    margin-bottom: 0;
  }

  .experience-role {
    display: flex;
    flex-wrap: wrap;
    align-items: baseline;
    gap: 0.4rem 0.55rem;
    margin: 0;
    line-height: 1.45;
  }

  .experience-role img {
    position: relative;
    top: 0.12em;
    height: 18px;
    width: auto;
  }

  .experience-role strong {
    font-weight: 600;
  }

  .experience-meta {
    color: var(--dh-muted);
  }

  .experience-meta::before {
    content: "—";
    margin-right: 0.45rem;
    color: var(--dh-line);
  }

  .experience-note {
    margin: 0.3rem 0 0 1.7rem;
    color: var(--dh-muted);
    font-size: 0.9rem;
    font-style: italic;
    line-height: 1.45;
  }

  @media (max-width: 575.98px) {
    .post-title {
      font-size: 1.7rem;
    }

    article > .profile {
      width: 150px !important;
      max-width: 46%;
      margin-top: 0;
    }

    .home-sections {
      margin-top: 1.2rem;
    }

    .publication-toolbar {
      align-items: stretch;
      flex-direction: column;
    }

    .publication-panel ol.bibliography > li > .row {
      grid-template-columns: 1fr;
      gap: 0.9rem;
    }
  }
</style>

<p>
  I am an undergraduate student at <a href="https://en.snu.ac.kr/" target="_blank" rel="noopener noreferrer">Seoul National University</a> (College of Liberal Studies),<br>
  majoring in both <a href="https://cse.snu.ac.kr/" target="_blank" rel="noopener noreferrer">Computer Science and Engineering</a> and <a href="https://www.math.snu.ac.kr/" target="_blank" rel="noopener noreferrer">Mathematical Sciences</a>.
</p>

<p>
  My research interests lie in Scientific Machine Learning for modeling, forecasting, and state estimation of fluid flows across kinetic and continuum regimes.
  I am particularly interested in treating physical fields as visual data and using techniques from computer vision and image processing to capture their structure and dynamics.
</p>

<p class="profile-links">
  <a href="mailto:2012abcd@snu.ac.kr">Email</a>
  <a href="https://www.linkedin.com/in/daehyeop-kim-41536530a/" target="_blank" rel="noopener noreferrer">LinkedIn</a>
  <a href="https://github.com/DaehyeopKim" target="_blank" rel="noopener noreferrer">GitHub</a>
</p>

<div class="home-sections">

<h2 id="news">News</h2>

<div class="news">
  {% if site.news != blank %}
    {% assign news_size = site.news | size %}
    <div
      class="table-responsive"
      {% if page.announcements.scrollable and news_size > 3 %}
        style="max-height: 60vw"
      {% endif %}
    >
      <table class="table table-sm table-borderless">
        {% assign news = site.news | reverse %}
        {% assign news_limit = page.announcements.limit | default: news_size %}
        {% for item in news limit: news_limit %}
          <tr>
            <th scope="row" style="width: 20%">{{ item.date | date: '%b %Y' }}</th>
            <td>
              {% if item.inline %}
                {{ item.content | remove: '<p>' | remove: '</p>' | emojify }}
              {% else %}
                <a class="news-title" href="{{ item.url | relative_url }}">{{ item.title }}</a>
              {% endif %}
            </td>
          </tr>
        {% endfor %}
      </table>
    </div>
  {% else %}
    <p>No news so far...</p>
  {% endif %}
</div>

<h2 id="publications">Publications</h2>

<div class="publication-toolbar">
  <p class="publication-note">(* denotes equal contribution)</p>
  <div class="publication-toggle" role="tablist" aria-label="Publication filter">
    <button id="pub-tab-selected" type="button" role="tab" aria-controls="pub-panel-selected" aria-selected="true">Selected</button>
    <button id="pub-tab-all" type="button" role="tab" aria-controls="pub-panel-all" aria-selected="false">All Publications</button>
  </div>
</div>

<div id="pub-panel-selected" class="publication-panel publications" role="tabpanel" aria-labelledby="pub-tab-selected">
  {% bibliography --group_by none --query @*[selected=true && hidden!=true]* --prefix selected-pubs %}
</div>

<div id="pub-panel-all" class="publication-panel publications" role="tabpanel" aria-labelledby="pub-tab-all" hidden>
  {% bibliography --group_by none --query @*[hidden!=true]* --prefix all-pubs %}
</div>

<script>
  (() => {
    const tabs = document.querySelectorAll(".publication-toggle [role='tab']");
    const panels = document.querySelectorAll(".publication-panel");
    const titleLinks = {
      hong2026diffbmp: "https://diffbmp.com/",
    };

    tabs.forEach((tab) => {
      tab.addEventListener("click", () => {
        tabs.forEach((item) => item.setAttribute("aria-selected", String(item === tab)));
        panels.forEach((panel) => {
          panel.hidden = panel.id !== tab.getAttribute("aria-controls");
        });
      });
    });

    document.querySelectorAll(".publication-panel video.preview").forEach((video) => {
      video.autoplay = true;
      video.loop = true;
      video.muted = true;
      video.playsInline = true;
      video.removeAttribute("controls");
      video.play().catch(() => {});
    });

    Object.entries(titleLinks).forEach(([paperId, url]) => {
      document.querySelectorAll(`.publication-panel #${paperId} .title`).forEach((title) => {
        if (title.querySelector("a")) return;
        const link = document.createElement("a");
        link.href = url;
        link.target = "_blank";
        link.rel = "noopener noreferrer";
        link.textContent = title.textContent;
        title.textContent = "";
        title.appendChild(link);
      });
    });

    document.querySelectorAll(".publication-panel #hong2026diffbmp .title").forEach((title) => {
      if (title.querySelector(".pub-demo")) return;
      const demo = document.createElement("em");
      demo.className = "pub-demo";
      demo.textContent = "[Selected for Demonstration]";
      title.append(" ", demo);
    });

    const splitTldr = (text) => {
      const cleanText = text
        .replace(/\s+/g, " ")
        .trim()
        .replace(/^TL;DR:\s*/i, "")
        .trim();
      const sentences = cleanText.match(/[^.!?]+[.!?]+(?:\s|$)|[^.!?]+$/g) || [cleanText];
      const preview = sentences[0].trim();
      return {
        preview,
        rest: cleanText.slice(preview.length).trim(),
      };
    };

    document.querySelectorAll(".publication-panel .links").forEach((links) => {
      const entry = links.closest("[id]");
      const abstractBlock = entry?.querySelector("div.abstract");
      const abstractButton = links.querySelector("a.abstract");

      abstractButton?.remove();

      if (entry && abstractBlock && !entry.querySelector(".publication-tldr")) {
        const { preview, rest } = splitTldr(abstractBlock.textContent);
        const tldr = document.createElement("div");
        const paragraph = document.createElement("p");
        const label = document.createElement("span");

        tldr.className = "publication-tldr";
        label.className = "publication-tldr-label";
        label.textContent = "TL;DR: ";

        paragraph.append(label, document.createTextNode(preview));

        if (rest) {
          const more = document.createElement("span");
          const toggle = document.createElement("button");

          more.className = "publication-tldr-more";
          more.hidden = true;
          more.textContent = ` ${rest}`;

          toggle.className = "publication-tldr-toggle";
          toggle.type = "button";
          toggle.setAttribute("aria-expanded", "false");
          toggle.textContent = "show more";
          toggle.addEventListener("click", () => {
            const expanded = toggle.getAttribute("aria-expanded") === "true";
            more.hidden = expanded;
            toggle.setAttribute("aria-expanded", String(!expanded));
            toggle.textContent = expanded ? "show more" : "show less";
          });

          paragraph.append(more, toggle);
        }

        tldr.appendChild(paragraph);
        links.after(tldr);
      }

      const preferredOrder = ["arXiv", "Website", "Bib"];
      preferredOrder.forEach((label) => {
        Array.from(links.querySelectorAll("a")).forEach((link) => {
          if (link.textContent.trim() === label) links.appendChild(link);
        });
      });
    });
  })();
</script>

<h2 id="research-experience">Research Experience</h2>

{% assign research_experience_page = site.pages | where: "permalink", "/research-experience/" | first %}
{{ research_experience_page.content | markdownify }}

<h2 id="projects">Projects</h2>

{% assign selected_projects_page = site.pages | where: "permalink", "/selected-projects/" | first %}
{{ selected_projects_page.content | markdownify }}

<h2 id="education">Education</h2>

{% assign education_page = site.pages | where: "permalink", "/education/" | first %}
{{ education_page.content | markdownify }}

</div>
