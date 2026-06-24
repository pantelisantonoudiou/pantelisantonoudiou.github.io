---
title: "SeizyML"
excerpt: "An interpretable machine learning framework for semi-automated seizure detection and validation."
layout: single
author_profile: true
date: 2025-01-15
header:
  teaser: /assets/images/seizyml_logo.png
author_profile: true
---

[![GitHub Repo](https://img.shields.io/badge/GitHub-neurosimata%2Fseizy_ml-blue?logo=github)](https://github.com/neurosimata/seizy_ml)

## 🧠 What is SeizyML?

**SeizyML** is an open-source Python toolkit for semi-automated detection of electrographic seizures. It combines simple, interpretable machine learning models with manual validation resulting in high accuracy and sensitivity, reducing bias, saving time, and improving reproducibility.

---

## ⚙️ Key Features

- Fully open-source and built in Python.
- GUI for manual curation of detected seizures.
- Requires minimal training data to get started.
- Lightweight (Just a standard CPU and enough memory).

---

## 💡 Why I Built It

Despite many seizure-related studies, there was no accessible tool to help researchers automate seizure detection from raw LFP/EEG data. SeizyML fills that gap by offering a validated, easy-to-use pipeline designed to **augment** human expertise.

---

## 📊 Validation

We tested SeizyML on extensive EEG data from chronically epileptic mice. The **Gaussian Naive Bayes** model detected **all seizures**, had the **lowest false detection rate**, and required only a small training set.

---

## 🔧 Tech Stack

- Python 3.
- scikit-learn, NumPy, matplotlib.

---

## 📎 Links

- 👉 [GitHub Repo](https://github.com/neurosimata/seizy_ml)
- 📄 [Related Publication](https://link.springer.com/article/10.1007/s12021-025-09719-4)
