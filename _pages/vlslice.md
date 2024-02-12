---
layout: page
permalink: /vlslice/
title: "VLSlice: Interactive Vision-and-Language Slice Discovery"
description: Accepted as a conference paper at ICCV 2023
nav: false
horizontal: false
---

<div style="display: flex; flex-direction: column; align-items: center; margin-bottom: 1rem">

<img src="/assets/img/vlslice_interface.png" alt="VLSlice" width="100%" style="margin-bottom: 1rem;"/>
<div style="width: 100%; display: flex; justify-content: center; font-size: 25px; margin-bottom: 1rem; flex-direction: row; flex-wrap: wrap;">
<a style="margin: 5px;" href="https://arxiv.org/abs/2309.06703">[ pdf ]</a>
<a style="margin: 5px;" href="{{ '/assets/pdf/vlslice_poster.pdf' | relative_url }}">[ poster ]</a>
<a style="margin: 5px;" href="https://drive.google.com/file/d/1mOuvjphNb2xNDC7shoGbPwyjbfArwud4/view?usp=drive_link">[ iccv talk ]</a>
<a style="margin: 5px;" href="https://www.youtube.com/watch?v=2CMDcGGsMjo&list=PLUxOP3kBxs2JYA5KT0YEmNJEyjqAqLOf3&index=1">[ showcase talk ]</a>
<a style="margin: 5px;" href="https://drive.google.com/file/d/1JkbVXnCds6rOErUx-YWZmp3mQ3IDJuhi/view?usp=drive_link">[ video demo ]</a>
<a style="margin: 5px;" href="https://github.com/slymane/vlslice">[ code ]</a>
</div>

<div style="width: 100%; display: flex; justify-content: center; font-size: 16px; margin-bottom: 0.5rem;">
<a style="margin: 5px;" href="https://ericslyman.com/">Eric Slyman <sup>1</sup></a>
<a style="margin: 5px;" href="https://minsuk.com/">Minsuk Kahng <sup>2</sup></a>
<a style="margin: 5px;" href="https://web.engr.oregonstate.edu/~leestef/">Stefan Lee <sup>1</sup></a>
</div>

<div style="width: 100%; display: flex; justify-content: center; font-size: 12px;">
<div style="margin: 5px;"><sup>1</sup>Oregon State University</div>
<div style="margin: 5px;"><sup>2</sup>Google Research</div>
</div>

</div>

<p style="text-align: justify; text-justify: inter-word; padding-right: 5px">
    Recent work in vision-and-language demonstrates that large-scale pretraining can learn generalizable models that are efficiently transferable to downstream tasks. While this may improve dataset-scale aggregate metrics, analyzing performance around hand-crafted subgroups targeting specific bias dimensions reveals systemic undesirable behaviors. However, this subgroup analysis is frequently stalled by annotation efforts, which require extensive time and resources to collect the necessary data. Prior art attempts to automatically discover subgroups to circumvent these constraints but typically leverages model behavior on existing task-specific annotations and rapidly degrades on more complex inputs beyond "tabular" data, none of which study vision-and-language models. This paper presents VLSlice, an interactive system enabling user-guided discovery of coherent representation-level subgroups with consistent visiolinguistic behavior, denoted as vision-and-language slices, from unlabeled image sets. We show that VLSlice enables users to quickly generate diverse high-coherency slices in a user study (n=22) and release the tool publicly.
</p>