---
layout: page
permalink: /publications/
title: publications
description: Peer-reviewed research in optical MEMS sensing and sustainable nanomaterials.
nav: true
nav_order: 2
---

<style>
  .publications-intro {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 1.5rem;
    margin-bottom: 2rem;
    padding-bottom: 1.25rem;
    border-bottom: 1px solid var(--global-divider-color);
  }

  .publications-intro p {
    max-width: 680px;
    margin: 0;
    line-height: 1.65;
  }

  .publications-intro .btn {
    display: inline-flex;
    flex: 0 0 auto;
    align-items: center;
    gap: 0.45rem;
    white-space: nowrap;
  }

  @media (max-width: 767px) {
    .publications-intro {
      display: block;
    }

    .publications-intro .btn {
      margin-top: 1rem;
    }
  }
</style>

<div class="publications-intro">
  <p>Peer-reviewed work spanning optical MEMS sensing, multiphysics modelling, and sustainable nanomaterials for energy applications.</p>
  <a
    class="btn btn-sm btn-outline-primary"
    href="https://scholar.google.com/citations?user=seTJ_c8AAAAJ&amp;hl=en"
    target="_blank"
    rel="external nofollow noopener"
  >
    <i class="ai ai-google-scholar" aria-hidden="true"></i>
    Google Scholar
  </a>
</div>

<div class="publications">
  {% bibliography %}
</div>
