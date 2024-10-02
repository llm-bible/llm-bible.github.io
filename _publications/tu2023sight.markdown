---
layout: publication
title: 'Sight Beyond Text: Multi-modal Training Enhances Llms In Truthfulness And Ethics'
authors: Tu Haoqin, Zhao Bingchen, Wei Chen, Xie Cihang
conference: "Arxiv"
year: 2023
bibkey: tu2023sight
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.07120"}
tags: ['Ethics And Bias', 'Fine Tuning', 'Responsible AI', 'Training Techniques']
---
Multi-modal large language models (MLLMs) are trained based on large language models (LLM), with an enhanced capability to comprehend multi-modal inputs and generate textual responses. While they excel in multi-modal tasks, the pure NLP abilities of MLLMs are often underestimated and left untested. In this study, we get out of the box and unveil an intriguing characteristic of MLLMs -- our preliminary results suggest that visual instruction tuning, a prevailing strategy for transitioning LLMs into MLLMs, unexpectedly and interestingly helps models attain both improved truthfulness and ethical alignment in the pure NLP context. For example, a visual-instruction-tuned LLaMA2 7B model surpasses the performance of the LLaMA2-chat 7B model, fine-tuned with over one million human annotations, on TruthfulQA-mc and Ethics benchmarks. Further analysis reveals that the improved alignment can be attributed to the superior instruction quality inherent to visual-text data. In releasing our code at github.com/UCSC-VLAA/Sight-Beyond-Text, we aspire to foster further exploration into the intrinsic value of visual-text synergies and, in a broader scope, multi-modal interactions in alignment research.
