---
title: "Interpretable Machine Learning for Seizure Detection"
excerpt: "An open-source ML tool for automated, bias-reduced seizure detection in electrographic recordings."
header:
    teaser: /assets/images/seizyml.png
layout: single
external_url: https://link.springer.com/article/10.1007/s12021-025-09719-4
author_profile: true
date: 2025-03-03
---

<a href="https://link.springer.com/article/10.1007/s12021-025-09719-4">
  <img src="/assets/images/seizyml.png" alt="SeizyML" style="max-width: 600px; margin-bottom: 1rem; border-radius: 6px;">
</a>

**Summary**
Here we describe the research behind the development of **SeizyML**, an open-source tool designed to automate the detection of electrographic seizures using interpretable machine learning models. It supports manual validation to reduce bias and was tested across a large dataset of chronically epileptic mice.

**Key findings:**
- Interpretable machine learning models can achieve 100% seizure detection accuracy in mice, suggesting their potential for automating seizure detection in research.
- Per-file normalization and model type were the biggest contributors to seizure detection performance.
- We compared four models and found Gaussian Naïve Bayes to be the most accurate and resilient, requiring minimal training data.

**Authors:**  
Pantelis Antonoudiou, Trina Basu & Jamie L. Maguire

[View the paper](https://link.springer.com/article/10.1007/s12021-025-09719-4)  
[View the code on GitHub](https://github.com/neurosimata/seizy_ml)
