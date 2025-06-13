---
layout: publication
title: 'VASCAR: Content-aware Layout Generation Via Visual-aware Self-correction'
authors: Jiahao Zhang, Ryota Yoshihashi, Shunsuke Kitada, Atsuki Osanai, Yuta Nakashima
conference: "Arxiv"
year: 2024
bibkey: zhang2024content
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.04237"}
tags: ['GPT', 'Training Techniques', 'Multimodal Models', 'Model Architecture']
---
Large language models (LLMs) have proven effective for layout generation due
to their ability to produce structure-description languages, such as HTML or
JSON. In this paper, we argue that while LLMs can perform reasonably well in
certain cases, their intrinsic limitation of not being able to perceive images
restricts their effectiveness in tasks requiring visual content, e.g.,
content-aware layout generation. Therefore, we explore whether large
vision-language models (LVLMs) can be applied to content-aware layout
generation. To this end, inspired by the iterative revision and heuristic
evaluation workflow of designers, we propose the training-free Visual-Aware
Self-Correction LAyout GeneRation (VASCAR). VASCAR enables LVLMs (e.g., GPT-4o
and Gemini) iteratively refine their outputs with reference to rendered layout
images, which are visualized as colored bounding boxes on poster background
(i.e., canvas). Extensive experiments and user study demonstrate VASCAR's
effectiveness, achieving state-of-the-art (SOTA) layout generation quality.
Furthermore, the generalizability of VASCAR across GPT-4o and Gemini
demonstrates its versatility.
