---
layout: page
permalink: /mmb-judge/
title: "MMB: Calibrating MLLM-as-a-judge via Multimodal Bayesian Prompt Ensembles"
description: Accepted as a conference paper at ICCV 2025
nav: false
horizontal: false
---

<div style="display: flex; flex-direction: column; align-items: center; margin-bottom: 1rem">

<div style="background-color: white; width: 100%;">
<img src="/assets/img/mmb.png" alt="MMB" width="100%" style="margin-bottom: 1rem;"/>
</div>
<div style="width: 100%; display: flex; justify-content: center; font-size: 25px; margin-bottom: 1rem; flex-direction: row; flex-wrap: wrap;">
<a style="margin: 5px;" href="https://arxiv.org/abs/2509.08777">[ pdf ]</a>
<a style="margin: 5px;" href="{{ '/assets/img/mmb_poster.png' | relative_url }}">[ poster ]</a>
</div>

<div style="width: 100%; display: flex; justify-content: center; font-size: 16px;">
<a style="margin: 5px;" href="https://ericslyman.com/">Eric Slyman <sup>1,2</sup></a>
<a style="margin: 5px;" href="https://mehrab-tanjim.github.io/">Mehrab Tanjim <sup>1</sup></a>
<a style="margin: 5px;" href="https://kushalkafle.com/">Kushal Kafle <sup>1</sup></a>
<a style="margin: 5px;" href="https://web.engr.oregonstate.edu/~leestef/">Stefan Lee <sup>2</sup></a>
</div>

<div style="width: 100%; display: flex; justify-content: center; font-size: 12px;">
<div style="margin: 5px;"><sup>1</sup>Adobe</div>
<div style="margin: 5px;"><sup>2</sup>Oregon State University</div>
</div>
</div>

## Abstract

<p style="text-align: justify; text-justify: inter-word; padding-right: 5px">
Multimodal large language models (MLLMs) are increasingly used to evaluate text-to-image (TTI) generation systems, providing automated judgments based on visual and textual context. However, these "judge" models often suffer from biases, overconfidence, and inconsistent performance across diverse image domains. While prompt ensembling has shown promise for mitigating these issues in unimodal, text-only settings, our experiments reveal that standard ensembling methods fail to generalize effectively for TTI tasks. To address these limitations, we propose a new multimodal-aware method called Multimodal Mixture-of-Bayesian Prompt Ensembles (MMB). Our method uses a Bayesian prompt ensemble approach augmented by image clustering, allowing the judge to dynamically assign prompt weights based on the visual characteristics of each sample. We show that MMB improves accuracy in pairwise preference judgments and greatly enhances calibration, making it easier to gauge the judge's true uncertainty. In evaluations on two TTI benchmarks, HPSv2 and MJBench, MMB outperforms existing baselines in alignment with human annotations and calibration across varied image content. Our findings highlight the importance of multimodal-specific strategies for judge calibration and suggest a promising path forward for reliable large-scale TTI evaluation.
</p>