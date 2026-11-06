---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

## Education

- **Ph.D. in Data Science**, University of Chicago, Data Science Institute, September 2024 – May 2028. Advisor: Shuangning Li (UChicago Booth School of Business).
- **B.A. in Computer Science and Mathematics**, New York University, Courant Institute of Mathematical Sciences, September 2020 – May 2024.

## Research Projects

### Machine Learning-Assisted Causal Inference · January 2023 – May 2025

Developed imputation-and-re-imputation tests for missing outcomes, refitting imputers under each treatment assignment to use covariates while preserving randomization inference. Proved finite-population-exact Type-I error control under the proposed missingness mechanism despite imputation-model misspecification, and established Monte Carlo convergence and exponential error bounds. ML-based covariate adjustment improved power; test inversion produced confidence regions under stronger assumptions.

### LLM Post-Training · January 2025 – October 2026

Generated 66,603 causal training examples with exact-inference labels. Used full-parameter supervised fine-tuning on four H100 GPUs and DAPO-based reinforcement learning across code, natural language, and symbolic representations. Supervised fine-tuning improved causal accuracy by 22.9 percentage points versus base models and out-of-distribution accuracy by 8.1 points versus CauGym/CDCR across seven benchmarks. Reasoning faithfulness improved by 20.2 points across medical, legal, and tabular tasks versus base models. Published at *NeurIPS 2026* as a Spotlight paper (top 3% of accepted papers).

## Research Engineering Experience

- **scikit-learn**, Open-Source Contributor, March 2023 – Present. Delivered 22 merged pull requests across five modules, including standardized parameter validation and a `GaussianMixture` efficiency improvement shipped in scikit-learn 1.3 (PR #26021).
- **Tencent**, Research Scientist Intern, Speech AI, May – November 2021. Developed C++ ASR alignment and timestamping components, plus HiFi-GAN vocoder components for text-to-speech inference.
- **pandas**, Open-Source Developer, March – April 2023. Fixed a metadata propagation bug (PR #52924).

## Selected Publications

- Heng*, **Zhang***, Feng. [Design-based Causal Inference with Missing Outcomes](https://www.tandfonline.com/doi/full/10.1080/01621459.2025.2516204). *Journal of the American Statistical Association*, 2025.
- Dai*, Liu*, **Zhang***, D. Zhang, Peng, Tan. Towards a Universal Causal Reasoner. *NeurIPS 2026*, Spotlight.
- Bao*, **Zhang***, Cao*, Evans. [From Division to Unity: A Large-Scale Study](https://dl.acm.org/doi/10.1145/3701716.3715502). *WWW 2025*.
- **Zhang***, Bao, Wang, Yan, Liu, Evans. Building an Atlas of Social Experiments to Link Studies and Bridge Gaps. Under review by ARR, 2026.
- Wang, **Zhang**, Shen, Dong. Broad Misalignment Is Concentrated in Weight Changes Supporting Narrow Harmful Learning. Under review by ARR, 2026.

*Equal contribution where marked.*

## Technical Skills

- **Statistical methods:** Causal inference, randomization tests, hypothesis testing, missing-data methods, covariate adjustment, confidence regions, Monte Carlo methods, probabilistic modeling.
- **LLM post-training:** Synthetic data generation, rejection sampling, full-parameter supervised fine-tuning, reinforcement learning, DeepSpeed ZeRO-3, FlashAttention-2, vLLM.

## Award

National Olympiad in Informatics, First Prize, 2018.
