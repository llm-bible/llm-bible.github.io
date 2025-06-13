---
layout: publication
title: 'Understand, Solve And Translate: Bridging The Multilingual Mathematical Reasoning Gap'
authors: Hyunwoo Ko, Guijin Son, Dasol Choi
conference: "Arxiv"
year: 2025
bibkey: ko2025solve
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.02448"}
tags: ['Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
Large language models (LLMs) demonstrate exceptional performance on complex
reasoning tasks. However, despite their strong reasoning capabilities in
high-resource languages (e.g., English and Chinese), a significant performance
gap persists in other languages. To investigate this gap in Korean, we
introduce HRM8K, a benchmark comprising 8,011 English-Korean parallel bilingual
math problems. Through systematic analysis of model behaviors, we identify a
key finding: these performance disparities stem primarily from difficulties in
comprehending non-English inputs, rather than limitations in reasoning
capabilities. Based on these findings, we propose UST (Understand, Solve, and
Translate), a method that strategically uses English as an anchor for reasoning
and solution generation. By fine-tuning the model on 130k synthetically
generated data points, UST achieves a 10.91% improvement on the HRM8K benchmark
and reduces the multilingual performance gap from 11.6% to 0.7%. Additionally,
we show that improvements from UST generalize effectively to different Korean
domains, demonstrating that capabilities acquired from machine-verifiable
content can be generalized to other areas. We publicly release the benchmark,
training dataset, and models.
