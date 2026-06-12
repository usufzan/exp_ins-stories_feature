# Expatrio Stories Feature Vendor Recommendation

This repository contains a static HTML site summarizing the vendor evaluation for an in-dashboard short-form content experience for Expatrio.

The goal of the site is to help decision-makers quickly understand the recommendation, compare the shortlisted vendors, and access deeper evaluation details when needed.

## Purpose

Expatrio is exploring whether story-like short-form content inside the dashboard can help users better understand insurance-related decisions.

This site presents:

* The recommended pilot vendor
* The backup vendor
* Vendors to deprioritize
* Evaluation criteria
* Pilot plan
* Demo pages for StorifyMe and StorySDK

## Recommendation Summary

The current recommendation is to run a short proof sprint with **StorifyMe** as the primary pilot vendor.

**Storyly** should be kept as the backup and capability benchmark.

**StorySDK** and open-source options such as `react-instastories` should be used only to understand the future internal-build path, not as the main pilot vendor.

## Site Structure

```text
.
├── index.html
├── evaluation-criteria.html
├── vendor-details.html
├── pilot-plan.html
├── demo-storifyme-dashboard.html
├── demo-storysdk-dashboard.html
└── assets/
```

## Pages

* `index.html` — executive summary and recommendation
* `evaluation-criteria.html` — criteria used to compare vendors
* `vendor-details.html` — vendor-by-vendor findings
* `pilot-plan.html` — suggested proof-sprint plan and vendor questions
* `demo-storifyme-dashboard.html` — StorifyMe dashboard demo
* `demo-storysdk-dashboard.html` — StorySDK dashboard demo

## Local Preview

You can open `index.html` directly in a browser.

For a cleaner local preview, run a simple local server:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## GitHub Pages

This site can be hosted with GitHub Pages.

Recommended settings:

```text
Settings → Pages → Deploy from branch → main → /root
```

The public URL should look like:

```text
https://usufzan.github.io/exp_ins-stories_feature/
```

## Important Note

This site is a pilot recommendation, not a final procurement decision.

The recommended next step is to validate the vendor through a short proof sprint before making any long-term commitment.
