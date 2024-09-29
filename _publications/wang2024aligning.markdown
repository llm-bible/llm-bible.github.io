---
layout: publication
title: 'Secokd: Aligning Large Language Models For In-context Learning With Fewer Shots'
authors: Wang Weixing, Yang Haojin, Meinel Christoph
conference: "Arxiv"
year: 2024
bibkey: wang2024aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14208"}
tags: ['Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'In Context Learning', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques']
---
Previous studies have shown that demonstrations can significantly help Large Language Models (LLMs ) perform better on the given tasks. However this so-called In-Context Learning ( ICL ) ability is very sensitive to the presenting context and often dozens of demonstrations are needed. In this work we investigate if we can reduce the shot number while still maintaining a competitive performance. We present SeCoKD a self-Knowledge Distillation ( KD ) training framework that aligns the student model with a heavily prompted variation thereby increasing the utilization of a single demonstration. We experiment with the SeCoKD across three LLMs and six benchmarks focusing mainly on reasoning tasks. Results show that our method outperforms the base model and Supervised Fine-tuning ( SFT ) especially in zero-shot and one-shot settings by 3037; and 1037; respectively. Moreover SeCoKD brings little negative artifacts when evaluated on new tasks which is more robust than Supervised Fine-tuning.
