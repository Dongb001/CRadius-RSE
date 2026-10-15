# Monaural Continuous-Radius Regional Speech Extraction

This is a static demonstration page for the paper **“Monaural Continuous-Radius Regional Speech Extraction with Cross-Radius Consistency Learning.”** It introduces the task, presents the reported experimental results, and provides precomputed listening examples.

## Page contents

### 1. Overview

Explains monaural regional speech extraction. Given a query radius, the model outputs the cumulative speech from all speakers inside that region. This section introduces continuous radius control, cross-radius consistency learning, and the full-target, partial-target, and empty-target cases.

### 2. Results

Reproduces the three tables reported in the manuscript:

- baseline comparison;
- ablation study of discrete/continuous radius encoding and cross-radius consistency;
- evaluation with additional speakers and additive noise.

### 3. Listening examples

Provides precomputed mixtures with the original input and model outputs queried at 1, 2, 3, and 4 m. The examples illustrate how the selected target region changes with the query radius.

### 4. Paper

Provides a link to the paper on [arXiv](https://arxiv.org/abs/2610.11507).

The page supports Chinese / English switching. All audio and result displays are static, precomputed examples; the model is not run in the browser.
