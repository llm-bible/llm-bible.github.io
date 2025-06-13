---
layout: publication
title: 'Little Data, Big Impact: Privacy-aware Visual Language Models Via Minimal Tuning'
authors: Laurens Samson, Nimrod Barazani, Sennay Ghebreab, Yuki M. Asano
conference: "Arxiv"
year: 2024
bibkey: samson2024little
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.17423"}
tags: ['Fine-Tuning', 'GPT', 'Applications', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
As Visual Language Models (VLMs) become increasingly embedded in everyday applications, ensuring they can recognize and appropriately handle privacy-sensitive content is essential. We conduct a comprehensive evaluation of ten state-of-the-art VLMs and identify limitations in their understanding of visual privacy. Existing datasets suffer from label inconsistencies, limiting their reliability. To address this, we introduce two compact, high-quality benchmarks, PrivBench and PrivBench-H, that focus on commonly recognized privacy categories aligned with the General Data Protection Regulation (GDPR). Additionally, we present PrivTune, an instruction-tuning dataset specifically curated to improve privacy sensitivity. We obtain a Privacy VLM by fine-tuning an off-the-shelf VLM on only 100 samples from PrivTune, which leads to substantial gains on all benchmarks, surpassing GPT-4, while maintaining strong performance on other tasks. Our findings show that privacy-awareness in VLMs can be substantially improved with minimal data and careful dataset design, setting the stage for safer, more privacy-aligned AI systems.
