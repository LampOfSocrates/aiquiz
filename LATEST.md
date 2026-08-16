## What this is
Interactive self-test quiz site for EEEM071 "Advanced Topics in Computer Vision" (University of Surrey), covering lectures L1-L25 as multiple-choice questions with instant feedback and explanations.

## Where it runs
Static site served via GitHub Pages from the `main` branch: https://lampofsocrates.github.io/aiquiz/ (combined quiz at /combined_quiz.html). Pushes to `main` deploy automatically.

## Features
- Multiple-choice questions with instant feedback and explanations (index.html, data_l1_l11.js / data_l12_l18.js / data_l19_l25.js)
- Combined quiz (ATCV + CNN Interpretability) at combined_quiz.html
- Flag questions for review, wrong-only filter mode
- Progress tracking per section via localStorage, left nav with progress counters
- Back-to-top navigation per question, HTML export of a printable answer key
- Focus Topics: standalone interactive visual guides under focus/ (SIFT pipeline, Sobel & Canny edge detection, backprop-by-hand with bias toggle and value randomiser)

## Recently tried
- 2026-05-24: Added Backprop-by-Hand Focus Topic (bias toggle + "new numbers" randomiser)
- 2026-05-24: Added Sobel & Canny edge detection Focus Topic
- 2026-05-24: Vendored SIFT Pipeline artifact locally under focus/ (replaced external claude.ai link so it works on static GH Pages)
- 2026-05-24: Added Focus Topics section to index.html linking to the SIFT Pipeline guide
- 2026-05-20: Added README with project overview and deployment URLs

## Next
- Add more Focus Topics for other lecture blocks (inference: L1-L25 coverage is uneven, only 3 focus topics exist so far)
- Root has several leftover working files (artifact_*.html, artifact_encoded.txt) not referenced in README structure — consider cleanup (inference)
- No package.json/build tooling — purely static HTML/JS, so no test or lint pipeline exists to expand (inference)
