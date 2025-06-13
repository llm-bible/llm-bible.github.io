---
layout: publication
title: 'Fast Prompt Alignment For Text-to-image Generation'
authors: Khalil Mrini, Hanlin Lu, Linjie Yang, Weilin Huang, Heng Wang
conference: "Arxiv"
year: 2024
bibkey: mrini2024fast
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.08639'}
  - {name: "Code", url: 'https://github.com/tiktok/fast_prompt_alignment'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Security', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Prompting', 'In-Context Learning', 'Pretraining Methods']
---
Text-to-image generation has advanced rapidly, yet aligning complex textual
prompts with generated visuals remains challenging, especially with intricate
object relationships and fine-grained details. This paper introduces Fast
Prompt Alignment (FPA), a prompt optimization framework that leverages a
one-pass approach, enhancing text-to-image alignment efficiency without the
iterative overhead typical of current methods like OPT2I. FPA uses large
language models (LLMs) for single-iteration prompt paraphrasing, followed by
fine-tuning or in-context learning with optimized prompts to enable real-time
inference, reducing computational demands while preserving alignment fidelity.
Extensive evaluations on the COCO Captions and PartiPrompts datasets
demonstrate that FPA achieves competitive text-image alignment scores at a
fraction of the processing time, as validated through both automated metrics
(TIFA, VQA) and human evaluation. A human study with expert annotators further
reveals a strong correlation between human alignment judgments and automated
scores, underscoring the robustness of FPA's improvements. The proposed method
showcases a scalable, efficient alternative to iterative prompt optimization,
enabling broader applicability in real-time, high-demand settings. The codebase
is provided to facilitate further research:
https://github.com/tiktok/fast_prompt_alignment
