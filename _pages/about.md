---
layout: page
title: GreenSys
permalink: /
description: All workshop editions
nav_order: 1
---

<style>
  .edition-index {
    min-height: calc(100vh - 14rem);
    display: flex;
    align-items: flex-start;
    justify-content: center;
    padding: 2rem 0 4rem;
  }

  .edition-card {
    width: min(100%, 44rem);
    background: #fff;
    border: 1px solid #cfcfcf;
    padding: 2.5rem 2rem;
    box-shadow: 0 8px 24px rgba(0, 0, 0, 0.06);
  }

  .edition-logo {
    width: min(100%, 18rem);
    display: block;
    margin: 0 auto 2rem;
  }

  .edition-title {
    margin-bottom: 1.5rem;
  }

  .edition-list {
    margin: 0;
    padding: 0;
    list-style: none;
  }

  .edition-item + .edition-item {
    margin-top: 1rem;
  }

  .edition-link {
    font-size: 1.2rem;
    font-weight: 600;
  }

  .edition-meta {
    color: #3f3f3f;
  }

  @media (max-width: 767.98px) {
    .edition-card {
      padding: 2rem 1.25rem;
    }
  }
</style>

<div class="edition-index">
  <div class="edition-card">
    <img class="edition-logo" src="{{ '/assets/img/logo-no-background.svg' | relative_url }}" alt="GreenSys logo">
    <h2 class="edition-title">GreenSys Workshop</h2>
    <ul class="edition-list">
      <li class="edition-item">
        <a class="edition-link" href="{{ '/2026/' | relative_url }}">GreenSys 2026</a>,
        <span class="edition-meta">Edinburgh, Scotland</span>
      </li>
      <li class="edition-item">
        <a class="edition-link" href="{{ '/2025/' | relative_url }}">GreenSys 2025</a>,
        <span class="edition-meta">Rotterdam, The Netherlands</span>
      </li>
    </ul>
  </div>
</div>
