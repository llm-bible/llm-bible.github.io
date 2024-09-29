---
layout: publication
title: AICoderEval Improving AI Domain Code Generation of Large Language Models
authors: Xia Yinghui, Chen Yuyan, Shi Tianyu, Wang Jun, Yang Jinsong
conference: "Arxiv"
year: 2024
bibkey: xia2024aicodereval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.04712"}
tags: ['Agentic', 'Applications', 'Multimodal Models', 'Reinforcement Learning', 'Tools']
---
Automated code generation is a pivotal capability of large language models (LLMs). However assessing this capability in real-world scenarios remains challenging. Previous methods focus more on low-level code generation such as model loading instead of generating high-level codes catering for real-world tasks such as image-to-text text classification in various domains. Therefore we construct AICoderEval a dataset focused on real-world tasks in various domains based on HuggingFace PyTorch and TensorFlow along with comprehensive metrics for evaluation and enhancing LLMs task-specific code generation capability. AICoderEval contains test cases and complete programs for automated evaluation of these tasks covering domains such as natural language processing computer vision and multimodal learning. To facilitate research in this area we open-source the AICoderEval dataset at . After that we propose CoderGen an agent-based framework to help LLMs generate codes related to real-world tasks on the constructed AICoderEval. Moreover we train a more powerful task-specific code generation model named AICoder which is refined on llama-3 based on AICoderEval. Our experiments demonstrate the effectiveness of CoderGen in improving LLMs task-specific code generation capability (by 12.00 on pass@1 for original model and 9.50 on pass@1 for ReAct Agent). AICoder also outperforms current code generation LLMs indicating the great quality of the AICoderEval benchmark.
