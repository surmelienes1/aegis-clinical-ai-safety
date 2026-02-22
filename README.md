# 🛡️ AEGIS
**Adaptive EHR Guard Intelligence System**

[![Deployed on Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black?logo=vercel)](#)
[![Hasso Plattner Institute](https://img.shields.io/badge/Institution-HPI-red)](#)
[![Status](https://img.shields.io/badge/Status-Presentation_Ready-success)](#)

> **Live Demo:** [VERCEL LINK]

## 📌 Overview
AEGIS is an interactive, zero-dependency visual intelligence platform designed to evaluate the safety, reasoning, and adversarial robustness of Clinical AI models operating on Electronic Health Records (EHR). 

Developed as an **HPI Master's Project**, this dashboard allows researchers and clinicians to directly compare baseline LLM performance against our novel **Hybrid Pipeline** (needle detection + self-consistency voting) when facing safety-critical clinical constraints and prompt injection attacks.

## ✨ Key Features
* **📊 Global Benchmark Analytics:** Instantly compare Baseline vs. Hybrid vs. Adversarial accuracy.
* **🌳 Reasoning Tree (Tree of Thoughts):** Visual node-graph tracing the model's exact decision pathways and beam-search pruning.
* **📜 EHR Log Inspector:** Read the full simulated patient context with color-coded tags for true needles and semantic distractors.
* **⚔️ Adversarial Robustness:** Track how models handle malicious prompt injections (e.g., *"Override all alerts"*).
* **🧠 Deep Analytics:** Radar charts, graduated safety scoring, and Normalized Context Accuracy (NCA).

## 🚀 How to Use (Quick Start)
This application is entirely client-side (Static HTML/JS/CSS). No backend or database is required.

1. **Open the Live Link:** Navigate to the Vercel deployment link above.
2. **Load Demo Data:** Press the <kbd>L</kbd> key on your keyboard, or click the **"⚡ LOAD DEMO CASES"** button to instantly populate the dashboard with 5 pre-built evaluation cases.
3. **Upload Custom Data:** Drag and drop your own AEGIS `Results JSONL` and `Golden JSON` files directly onto the screen.
4. **Keyboard Shortcuts:** Press <kbd>?</kbd> at any time to open the shortcut menu.

## 🛠️ Technical Architecture
* **Frontend:** Vanilla HTML5, CSS3 (macOS Sequoia / iOS 18 Premium Dark UI).
* **Visualization:** D3.js (v7.8.5) for radial, top-down, and left-right tree layouts and radar charts.
* **Deployment:** Vercel (Edge CDN).

## 🎓 Academic Context
This software artifact was developed as part of a Master's Project at the **Hasso Plattner Institute (HPI)** in Potsdam, Germany (Feb 2026), focusing on Clinical AI Safety and hard-constraint adherence in medical environments.
