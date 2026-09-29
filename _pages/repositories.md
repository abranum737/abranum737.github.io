---
layout: page
permalink: /repositories/
title: repositories
description: Code behind my data projects
nav: true
nav_order: 2

repos:
  - name: ClinVar → dbSNP → PubMed Pipeline
    repo: abranum737/Clinvar_data_organization
    description: >
      Multi-step Python pipeline that converts ClinVar exports into a combined dataset,
      groups variants by gene, scrapes dbSNP for linked publications across ~130k SNPs
      (with caching), and pulls GWAS p-values. Feeds my GWAS research dashboard.
    tags: [Python, ETL, Web scraping, Genomics]
  - name: Clinical Trial Change Tracker
    repo: abranum737/clinicaltrialsearch
    description: >
      Automated script that downloads COVID-19 trials from ClinicalTrials.gov, compares
      today's snapshot against a previous day, and generates a PDF report of what changed.
    tags: [Python, pandas, ReportLab, Automation]
  - name: NEJM Article Length Analysis
    repo: abranum737/paper_length
    description: >
      Scraper that pulls New England Journal of Medicine articles from PubMed, follows
      each to its full text, and computes word counts for analysis.
    tags: [Python, BeautifulSoup, Web scraping]
---

<style>
  .repo-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));
    gap: 1.25rem;
    margin-top: 1rem;
  }
  .repo-card {
    display: flex;
    flex-direction: column;
    padding: 1.25rem;
    border: 1px solid var(--global-divider-color);
    border-radius: 10px;
    background: var(--global-card-bg-color);
    color: var(--global-text-color);
    text-decoration: none;
    transition: transform 0.15s ease, border-color 0.15s ease, box-shadow 0.15s ease;
  }
  .repo-card:hover {
    transform: translateY(-3px);
    border-color: var(--global-theme-color);
    box-shadow: 0 6px 18px rgba(0, 0, 0, 0.08);
    color: var(--global-text-color);
    text-decoration: none;
  }
  .repo-card h3 {
    font-size: 1.1rem;
    margin: 0 0 0.25rem;
    color: var(--global-theme-color);
  }
  .repo-card .repo-path {
    font-family: monospace;
    font-size: 0.8rem;
    opacity: 0.65;
    margin-bottom: 0.75rem;
    word-break: break-all;
  }
  .repo-card p {
    font-size: 0.92rem;
    line-height: 1.5;
    flex-grow: 1;
    margin-bottom: 1rem;
  }
  .repo-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 0.4rem;
  }
  .repo-tags span {
    font-size: 0.75rem;
    padding: 0.15rem 0.6rem;
    border-radius: 999px;
    border: 1px solid var(--global-theme-color);
    color: var(--global-theme-color);
  }
</style>

<div class="repo-grid">
  {% for r in page.repos %}
  <a class="repo-card" href="https://github.com/{{ r.repo }}" target="_blank" rel="noopener">
    <h3><i class="fa-brands fa-github"></i> {{ r.name }}</h3>
    <div class="repo-path">{{ r.repo }}</div>
    <p>{{ r.description }}</p>
    <div class="repo-tags">
      {% for t in r.tags %}<span>{{ t }}</span>{% endfor %}
    </div>
  </a>
  {% endfor %}
</div>

<p style="margin-top: 1.5rem;">
  See everything on <a href="https://github.com/abranum737" target="_blank" rel="noopener">my GitHub profile</a>.
</p>