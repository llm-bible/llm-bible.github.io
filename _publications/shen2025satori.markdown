---
layout: publication
title: 'SATORI-R1: Incentivizing Multimodal Reasoning With Spatial Grounding And Verifiable Rewards'
authors: Chuming Shen, Wei Wei, Xiaoye Qu, Yu Cheng
conference: "Arxiv"
year: 2025
bibkey: shen2025satori
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.19094"}
  - {name: "Code", url: "https://github.com/justairr/SATORI-R1"}
tags: ['Agentic', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Multimodal Models']
---
DeepSeek-R1 has demonstrated powerful reasoning capabilities in the text domain through stable reinforcement learning (RL). Recently, in the multimodal domain, works have begun to directly apply RL to generate R1-like free-form reasoning for Visual Question Answering (VQA) tasks. However, multimodal tasks share an intrinsically different nature from textual tasks, which heavily rely on the understanding of the input image to solve the problem. Therefore, such free-form reasoning faces two critical limitations in the VQA task: (1) Extended reasoning chains diffuse visual focus away from task-critical regions, degrading answer accuracy. (2) Unverifiable intermediate steps amplify policy-gradient variance and computational costs overhead. To address these issues, in this paper, we introduce SATORI (\\(\textbf\{S\}patially\\) \\(\textbf\{A\}nchored\\) \\(\textbf\{T\}ask\\) \\(\textbf\{O\}ptimization\\) with \\(\textbf\{R\}e\textbf\{I\}nforcement\\) Learning), which decomposes VQA into three verifiable stages, including global image captioning, region localization, and answer prediction, each supplying explicit reward signals. Furthermore, we also introduce VQA-Verify, a 12k dataset annotated with answer-aligned captions and bounding-boxes to facilitate training. Experiments demonstrate consistent performance improvements across seven VQA benchmarks, achieving up to \\(15.7%\\) improvement in accuracy in accuracy compared to the R1-like baseline. Our analysis of the attention map confirms enhanced focus on critical regions, which brings improvements in accuracy. Our code is available at https://github.com/justairr/SATORI-R1.
