---
layout: publication
title: 'Asma-tune: Unlocking Llms'' Assembly Code Comprehension Via Structural-semantic Instruction Tuning'
authors: Xinyi Wang, Jiashui Wang, Jinbo Su, Ke Wang, Peng Chen, Yanming Liu, Long Liu, Xiang Li, Yangdong Wang, Qiyuan Chen, Rongze Chen, Chunfu Jia
conference: "Arxiv"
year: 2025
bibkey: wang2025asma
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.11617"}
tags: ['Tools', 'GPT', 'Applications', 'Language Modeling', 'Model Architecture', 'Merging', 'Masked Language Model', 'Pretraining Methods', 'BERT']
---
Assembly code analysis and comprehension play critical roles in applications like reverse engineering, yet they face substantial challenges due to low information density and a lack of explicit syntactic structures. While traditional masked language modeling (MLM) approaches do not explicitly focus on natural language interaction, emerging decoder-focused large language models (LLMs) demonstrate partial success in binary analysis yet remain underexplored for holistic comprehension. We present Assembly Augmented Tuning, an end-to-end structural-semantic instruction tuning framework that synergizes encoder architecture with decoder-based LLMs through a projector module, where the assembly encoder extracts hardware-level structural features, the projector bridges representations with the semantic space, and the instruction-tuned LLM preserves natural language capabilities. Experimental results demonstrate three key advantages: (1) State-of-the-art performance in assembly comprehension with +39.7% Recall@1 and +17.8% MRR improvements over GPT-4-Turbo, (2) Consistent enhancements across base models (24.6-107.4% Recall@1 and 15.2-106.3% MRR on Qwen2.5-Coder, Deepseek-Coder and CodeLlama variants), and (3) Superior instruction-following capabilities (41.5%-118% improvements) with controlled code generation degradation (-8.9% to -35% across architectures).
