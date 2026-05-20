# ATCV Self-Test Quiz

Interactive self-test quiz for **EEEM071 — Advanced Topics in Computer Vision** at the University of Surrey. Covers the full lecture series (L1–L25) with multiple-choice questions, instant feedback, and explanations.

## Live URLs

| Quiz | URL |
|------|-----|
| ATCV Full Course (L1–L25) | https://lampofsocrates.github.io/aiquiz/ |
| ATCV + CNN Interpretability (Combined) | https://lampofsocrates.github.io/aiquiz/combined_quiz.html |

## Features

- **Multiple-choice questions** with instant answer feedback and explanations
- **Flag questions** (☆) to mark for review
- **Back-to-top navigation** on every question
- **Progress tracking** per section, saved to `localStorage`
- **Wrong-only mode** — filter to questions answered incorrectly
- **HTML export** — download a printable answer key
- **Left nav** with section-by-section progress counters

## Structure

```
index.html          # Main quiz (L1–L25)
combined_quiz.html  # Combined quiz (ATCV + CNN Interpretability)
data_l1_l11.js      # Question data: Lectures 1–11
data_l12_l18.js     # Question data: Lectures 12–18
data_l19_l25.js     # Question data: Lectures 19–25
```

## Topics Covered

| Lectures | Topics |
|----------|--------|
| L1–L4 | Image formation, filtering, edge detection |
| L5–L7 | Feature detection, descriptors, matching |
| L8–L11 | Stereo, optical flow, segmentation |
| L12–L18 | CNNs, training, architectures, detection |
| L19–L20 | Optical flow (deep) |
| L21 | GANs, VAE, SimCLR, Deep Image Prior |
| L22–L25 | Vision-language, detection (R-CNN→DETR), 3D, sketch |

## Deployment

Served via **GitHub Pages** from the `main` branch root. Changes pushed to `main` deploy automatically.
