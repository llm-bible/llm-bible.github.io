---
layout: publication
title: BLSP45;KD Bootstrapping Language45;speech Pre45;training Via Knowledge Distillation
authors: Wang Chen, Liao Minpeng, Huang Zhongqiang, Zhang Jiajun
conference: "Arxiv"
year: 2024
bibkey: wang2024blsp
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.19041"}
tags: ['Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Recent end45;to45;end approaches have shown promise in extending large language models (LLMs) to speech inputs but face limitations in directly assessing and optimizing alignment quality and fail to achieve fine45;grained alignment due to speech45;text length mismatch. We introduce BLSP45;KD a novel approach for Bootstrapping Language45;Speech Pretraining via Knowledge Distillation which addresses these limitations through two key techniques. First it optimizes speech45;text alignment by minimizing the divergence between the LLMs next45;token prediction distributions for speech and text inputs using knowledge distillation. Second it employs a continuous45;integrate45;andfire strategy to segment speech into tokens that correspond one45;to45;one with text tokens enabling fine45;grained alignment. We also introduce Partial LoRA (PLoRA) a new adaptation method supporting LLM finetuning for speech inputs under knowledge distillation. Quantitative evaluation shows that BLSP45;KD outperforms previous end45;to45;end baselines and cascaded systems with comparable scale of parameters facilitating general instruction45;following capabilities for LLMs with speech inputs. This approach provides new possibilities for extending LLMs to spoken language interactions.
