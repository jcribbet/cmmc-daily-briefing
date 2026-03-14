---
layout: home
title: CMMC Daily Intelligence Briefing
---

## About This Briefing

A curated daily digest of the most significant CMMC 2.0, DIB cybersecurity, and defense contractor compliance developments. Published every weekday morning at 6:30 AM CT.

Each briefing covers:
- **Regulatory & DoD Updates** — Rulemaking, DFARS, CyberAB, assessment timelines
- **Implementation Guidance** — SSP/POA&M, scoping, assessment preparation
- **Tools & Vendors** — GRC platforms, MSP/MSSP offerings, product news
- **Thought Leadership** — Expert commentary, industry analysis, community discussions

---

## Briefings Archive

{% assign sorted = site.briefings | sort: 'date' | reverse %}
{% for briefing in sorted %}
- [{{ briefing.title }}]({{ briefing.url | relative_url }}) — {{ briefing.date | date: "%B %d, %Y" }}
{% endfor %}
