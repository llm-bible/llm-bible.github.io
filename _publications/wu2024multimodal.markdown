---
layout: publication
title: Motionllm Multimodal Motion45;language Learning With Large Language Models
authors: Wu Qi, Zhao Yubo, Wang Yifan, Tai Yu-wing, Tang Chi-keung
conference: "Arxiv"
year: 2024
bibkey: wu2024multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.17013"}
  - {name: "Code", url: "https://knoxzhao.github.io/MotionLLM"}
tags: ['GPT', 'Has Code', 'Language Modeling', 'Merging', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Security', 'Tools', 'Transformer']
---
Recent advancements in Multimodal Large Language Models (MM45;LLMs) have demonstrated promising potential in terms of generalization and robustness when applied to different modalities. While previous works have already achieved 3D human motion generation using various approaches including language modeling they mostly 37; are mostly carefully designed use specialized architecture and are restricted to single45;human motion generation. Inspired by the success of MM45;LLMs we propose MotionLLM a simple and general framework that can achieve single45;human multi45;human motion generation and motion captioning by fine45;tuning pre45;trained LLMs. Specifically we encode and quantize motions into discrete LLM45;understandable tokens which results in a unified vocabulary consisting of both motion and text tokens. With only 145;45;337; parameters of the LLMs trained by using adapters our single45;human motion generation achieves comparable results to those diffusion models and other trained45;from45;scratch transformer45;based models. Additionally we show that our approach is scalable and flexible allowing easy extension to multi45;human motion generation through autoregressive generation of single45;human motions. Project page https://knoxzhao.github.io/MotionLLM
