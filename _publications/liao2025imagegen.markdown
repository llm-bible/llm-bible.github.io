---
layout: publication
title: 'Imagegen-cot: Enhancing Text-to-image In-context Learning With Chain-of-thought Reasoning'
authors: Jiaqi Liao, Zhengyuan Yang, Linjie Li, Dianqi Li, Kevin Lin, Yu Cheng, Lijuan Wang
conference: "Arxiv"
year: 2025
bibkey: liao2025imagegen
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.19312'}
  - {name: "Code", url: 'https://ImageGen-CoT.github.io/'}
tags: ['Has Code', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Prompting', 'Multimodal Models', 'In-Context Learning', 'Pretraining Methods']
---
In this work, we study the problem of Text-to-Image In-Context Learning
(T2I-ICL). While Unified Multimodal LLMs (MLLMs) have advanced rapidly in
recent years, they struggle with contextual reasoning in T2I-ICL scenarios. To
address this limitation, we propose a novel framework that incorporates a
thought process called ImageGen-CoT prior to image generation. To avoid
generating unstructured ineffective reasoning steps, we develop an automatic
pipeline to curate a high-quality ImageGen-CoT dataset. We then fine-tune MLLMs
using this dataset to enhance their contextual reasoning capabilities. To
further enhance performance, we explore test-time scale-up strategies and
propose a novel hybrid scaling approach. This approach first generates multiple
ImageGen-CoT chains and then produces multiple images for each chain via
sampling. Extensive experiments demonstrate the effectiveness of our proposed
method. Notably, fine-tuning with the ImageGen-CoT dataset leads to a
substantial 80% performance gain for SEED-X on T2I-ICL tasks. See our project
page at https://ImageGen-CoT.github.io/. Code and model weights will be
open-sourced.
