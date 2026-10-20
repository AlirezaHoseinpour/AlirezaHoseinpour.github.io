---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 25

title: Research Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Graduate Research Assistant
    company: University of Illinois Chicago
    company_url: 'https://www.uic.edu/'
    location: Chicago, IL
    date_start: '2026-08-15'
    date_end: ''
    description: |2-
        **Advisor:** [Dr. Austin Mordahl](https://austinmordahl.com/)
        * Conducting research at the intersection of agentic AI and software engineering.

  - title: Graduate Research Assistant
    company: Bowling Green State University
    company_url: 'https://www.bgsu.edu/'
    company_logo: bgsu
    location: Bowling Green, OH
    date_start: '2025-01-01'
    date_end: '2026-08-01'
    description: |2-
        **Advisor:** [Dr. Abbas Heydarnoori](https://heydarnoori.github.io/)
        * Co-developed **LinkAnchor**, an autonomous LLM-based agent for software traceability (**FSE 2026**).
        * Led an empirical study of 500 AI-generated pull requests across 5 coding agents, building a taxonomy of test failures (**MSR 2026**).
        * Fine-tuned open-source LLMs for automatic issue assignment (**LIA**, arXiv 2026).
        * Investigated retrieval-augmented LLM reasoning for automated issue report classification.

  - title: Undergraduate Thesis Research
    company: Sharif University of Technology
    company_url: 'https://www.sharif.edu/'
    company_logo: sharif
    location: Tehran
    date_start: '2023-02-01'
    date_end: '2023-12-01'
    description: |2-
        **Thesis Advisor:** [Dr. Mahdieh Soleymani](https://scholar.google.com/citations?user=S1U0KlgAAAAJ&hl=en)
        * Investigated the robustness of CNNs and Vision Transformers under distribution shifts from spurious correlations, conducting large-scale experiments with varied training strategies.
        * Designed and implemented novel datasets with synthetic spurious signals to test generalization.

design:
  columns: '2'
---
