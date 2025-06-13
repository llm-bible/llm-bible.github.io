---
layout: publication
title: 'ETVA: Evaluation Of Text-to-video Alignment Via Fine-grained Question Generation And Answering'
authors: Kaisi Guan, Zhengfeng Lai, Yuchong Sun, Peng Zhang, Wei Liu, Kieran Liu, Meng Cao, Ruihua Song
conference: "Arxiv"
year: 2025
bibkey: guan2025evaluation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.16867"}
tags: ['Prompting', 'Agentic', 'Applications', 'Tools']
---
Precisely evaluating semantic alignment between text prompts and generated
videos remains a challenge in Text-to-Video (T2V) Generation. Existing
text-to-video alignment metrics like CLIPScore only generate coarse-grained
scores without fine-grained alignment details, failing to align with human
preference. To address this limitation, we propose ETVA, a novel Evaluation
method of Text-to-Video Alignment via fine-grained question generation and
answering. First, a multi-agent system parses prompts into semantic scene
graphs to generate atomic questions. Then we design a knowledge-augmented
multi-stage reasoning framework for question answering, where an auxiliary LLM
first retrieves relevant common-sense knowledge (e.g., physical laws), and then
video LLM answers the generated questions through a multi-stage reasoning
mechanism. Extensive experiments demonstrate that ETVA achieves a Spearman's
correlation coefficient of 58.47, showing a much higher correlation with human
judgment than existing metrics which attain only 31.0. We also construct a
comprehensive benchmark specifically designed for text-to-video alignment
evaluation, featuring 2k diverse prompts and 12k atomic questions spanning 10
categories. Through a systematic evaluation of 15 existing text-to-video
models, we identify their key capabilities and limitations, paving the way for
next-generation T2V generation.
