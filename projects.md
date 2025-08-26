---
layout: single
title: "Projects"
permalink: /projects/
toc: true
author_profile: true
---

Below are three focused case studies that reflect how I approach data work:
clear problem framing, tidy data, transparent code, and decision-first visuals.

---

## Valorant Match Outcome Predictor
**Goal.** Predict match outcome from pre-match and early-round features.  
**Data.** Public match statistics aggregated into tidy tables (features such as map, agent comp, econ, first-blood rate).  
**Approach.** Baseline logistic regression → tuned tree-based models; careful split to avoid data leakage; feature importance and calibration.  
**Output.** Notebook with evaluation plots; concise README explaining features, modeling choices, and limitations.

**Skills demonstrated:** supervised ML workflow, feature engineering, model validation, reproducible notebooks.  
**Repository:** https://github.com/caitlincheekirkpatrick/valorant-outcome-predictor

---

## Volleyball Analytics: Serve-Receive & Attack Efficiency
**Goal.** Transform match sheets into a dashboard that surfaces rotation-level weaknesses and serve-receive patterns.  
**Data.** Parsed CSVs from match logs; Python for cleaning and reshaping to star schema.  
**Approach.** Pandas for ETL; Power BI model with DAX KPIs (SR%, attack eff., sideout %, rotation on/off analysis); bookmarks for coaches’ views.  
**Output.** Interactive Power BI report; screenshots and a written walkthrough in the repo.

**Skills demonstrated:** data modeling, DAX KPIs, performance visualization, analytics storytelling.  
**Repository:** https://github.com/caitlincheekirkpatrick/volleyball-analytics

---

## Cocktail Recommender (Content-Based)
**Goal.** Recommend cocktails based on flavor profile and available ingredients.  
**Data.** Open recipe corpus normalized to ingredients and descriptors.  
**Approach.** Text/ingredient featurization (TF-IDF / embeddings) and cosine similarity; simple API endpoint for queries; front-end snippet to demo usage.  
**Output.** Readable project structure with dataset doc, API usage examples, and a small demo page.

**Skills demonstrated:** data cleaning, vectorization, similarity search, lightweight API design.  
**Repository:** https://github.com/caitlincheekirkpatrick/cocktail-recommender
