---
layout: publication
title: Tuning Large Multimodal Models For Videos Using Reinforcement Learning From AI Feedback
authors: Ahn Daechul, Choi Yura, Yu Youngjae, Kang Dongyeop, Choi Jonghyun
conference: "Arxiv"
year: 2024
bibkey: ahn2024tuning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.03746"}
tags: ['Agentic', 'Fine Tuning', 'Multimodal Models', 'Reinforcement Learning']
---
Recent advancements in large language models have influenced the development of video large multimodal models (VLMMs). The previous approaches for VLMMs involved Supervised Fine45;Tuning (SFT) with instruction45;tuned datasets integrating LLM with visual encoders and adding additional learnable modules. Video and text multimodal alignment remains challenging primarily due to the deficient volume and quality of multimodal instruction45;tune data compared to text45;only data. We present a novel alignment strategy that employs multimodal AI system to oversee itself called Reinforcement Learning from AI Feedback (RLAIF) providing self45;preference feedback to refine itself and facilitating the alignment of video and text modalities. In specific we propose context45;aware reward modeling by providing detailed video descriptions as context during the generation of preference feedback in order to enrich the understanding of video content. Demonstrating enhanced performance across diverse video benchmarks our multimodal RLAIF approach VLM45;RLAIF outperforms existing approaches including the SFT model. We commit to open45;sourcing our code models and datasets to foster further research in this area.
