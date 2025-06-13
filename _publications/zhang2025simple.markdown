---
layout: publication
title: 'Silvr: A Simple Language-based Video Reasoning Framework'
authors: Ce Zhang, Yan-bo Lin, Ziyang Wang, Mohit Bansal, Gedas Bertasius
conference: "Arxiv"
year: 2025
bibkey: zhang2025simple
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.24869'}
  - {name: "Code", url: 'https://github.com/CeeZh/SILVR'}
tags: ['Has Code', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Multimodal Models']
---
Recent advances in test-time optimization have led to remarkable reasoning capabilities in Large Language Models (LLMs), enabling them to solve highly complex problems in math and coding. However, the reasoning capabilities of multimodal LLMs (MLLMs) still significantly lag, especially for complex video-language tasks. To address this issue, we present SiLVR, a Simple Language-based Video Reasoning framework that decomposes complex video understanding into two stages. In the first stage, SiLVR transforms raw video into language-based representations using multisensory inputs, such as short clip captions and audio/speech subtitles. In the second stage, language descriptions are fed into a powerful reasoning LLM to solve complex video-language understanding tasks. To handle long-context multisensory inputs, we use an adaptive token reduction scheme, which dynamically determines the temporal granularity with which to sample the tokens. Our simple, modular, and training-free video reasoning framework achieves the best-reported results on Video-MME (long), Video-MMMU (comprehension), Video-MMLU, CGBench, and EgoLife. Furthermore, our empirical study focused on video reasoning capabilities shows that, despite not being explicitly trained on video, strong reasoning LLMs can effectively aggregate multisensory input information from video, speech, and audio for complex temporal, causal, long-context, and knowledge acquisition reasoning tasks in video. Code is available at https://github.com/CeeZh/SILVR.
