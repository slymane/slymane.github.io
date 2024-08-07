---
layout: page
permalink: /fairdedup/
title: "FairDeDup: Detecting and Mitigating Vision-Language Fairness Disparities in Semantic Dataset Deduplication"
description: Accepted as a conference paper at CVPR 2024
nav: false
horizontal: false
---

<div style="display: flex; flex-direction: column; align-items: center; margin-bottom: 1rem">

<div style="background-color: white; width: 100%;">
<img src="/assets/img/fairdedup.svg" alt="FairDeDup" width="100%" style="margin-bottom: 1rem;"/>
</div>
<div style="width: 100%; display: flex; justify-content: center; font-size: 25px; margin-bottom: 1rem; flex-direction: row; flex-wrap: wrap;">
<a style="margin: 5px;" href="https://arxiv.org/abs/2404.16123">[ pdf ]</a>
<a style="margin: 5px;" href="https://www.youtube.com/watch?v=6EfEM-hgIn8">[ talk ]</a>
<a style="margin: 5px;" href="{{ '/assets/pdf/fairdedup_poster.pdf' | relative_url }}">[ cvpr poster ]</a>
<a style="margin: 5px;" href="{{ '/assets/pdf/fairdedup.pdf' | relative_url }}">[ ai week poster ]</a>
</div>

<div style="width: 100%; display: flex; justify-content: center; font-size: 16px;">
<a style="margin: 5px;" href="https://ericslyman.com/">Eric Slyman <sup>1,2*</sup></a>
<a style="margin: 5px;" href="https://web.engr.oregonstate.edu/~leestef/">Stefan Lee <sup>1</sup></a>
<a style="margin: 5px;" href="https://research.adobe.com/person/scott-cohen/">Scott Cohen <sup>2</sup></a>
<a style="margin: 5px;" href="https://kushalkafle.com/">Kushal Kafle <sup>2</sup></a>
</div>

<div style="width: 100%; display: flex; justify-content: center; font-size: 12px;">
<div style="margin: 5px;"><sup>1</sup>Oregon State University</div>
<div style="margin: 5px;"><sup>2</sup>Adobe</div>
</div>

<div style="width: 100%; display: flex; justify-content: center; font-size: 12px; margin-bottom: 1.0rem;">
*Work conducted during Slyman’s 2023 summer internship at Adobe
</div>

<div style="width: 100%; display: flex; justify-content: left; font-size: 12px;">
    <div style="width: 15%; margin-right: 5px;">
        <b>Media Coverage:</b>
    </div>
    <div style="width: 85%; display: flex; flex-direction: column;">
        <div>
            <em>"Bias & Representation in AI,"</em> &nbsp; State of Diversity @ OSU
            <a style="margin: 5px;" href="https://youtu.be/dSyHzdRnaXc?t=2092"> [ featured talk ] </a>
        </div>
        <div>
            <em>"Researchers develop new training technique to make AI systems less socially biased,"</em> &nbsp; OSU Newsroom
            <a style="margin: 5px;" href="https://today.oregonstate.edu/news/researchers-develop-new-training-technique-aims-make-ai-systems-less-socially-biased">[ article ]</a>
        </div>
        <div> 
            Radio interviews with KLCC (NPR), JPB (NPR), and KEX Radio (iHeartRadio) coming soon!
        </div>
    </div>
</div>


</div>

## Abstract

<p style="text-align: justify; text-justify: inter-word; padding-right: 5px">
    Recent dataset deduplication techniques have demonstrated that content-aware dataset pruning can dramatically reduce the cost of training Vision-Language Pretrained (VLP) models without significant performance losses compared to training on the original dataset. These results have been based on pruning commonly used image-caption datasets collected from the web -- datasets that are known to harbor harmful social biases that may then be codified in trained models. In this work, we evaluate how deduplication affects the prevalence of these biases in the resulting trained models and introduce an easy-to-implement modification to the recent SemDeDup algorithm that can reduce the negative effects that we observe. When examining CLIP-style models trained on deduplicated variants of LAION-400M, we find our proposed FairDeDup algorithm consistently leads to improved fairness metrics over SemDeDup on the FairFace and FACET datasets while maintaining zero-shot performance on CLIP benchmarks.
</p>