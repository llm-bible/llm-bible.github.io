---
layout: publication
title: 'Reason-to-recommend: Using Interaction-of-thought Reasoning To Enhance LLM Recommendation'
authors: Keyu Zhao, Fengli Xu, Yong Li
conference: "Arxiv"
year: 2025
bibkey: zhao2025reason
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.05069'}
  - {name: "Code", url: 'https://anonymous.4open.science/r/R2Rec-7C5D'}
tags: ['Agentic', 'Has Code', 'Interpretability and Explainability', 'RAG', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Driven by advances in Large Language Models (LLMs), integrating them into recommendation tasks has gained interest due to their strong semantic understanding and prompt flexibility. Prior work encoded user-item interactions or metadata into prompts for recommendations. In parallel, LLM reasoning, boosted by test-time scaling and reinforcement learning, has excelled in fields like mathematics and code, where reasoning traces and correctness signals are clear, enabling high performance and interpretability. However, directly applying these reasoning methods to recommendation is ineffective because user feedback is implicit and lacks reasoning supervision. To address this, we propose \\(\textbf\{R2Rec\}\\), a reasoning-enhanced recommendation framework that samples interaction chains from the user-item graph and converts them into structured interaction-of-thoughts via a progressive masked prompting strategy, with each thought representing stepwise reasoning grounded in interaction context. This allows LLMs to simulate step-by-step decision-making based on implicit patterns. We design a two-stage training pipeline: supervised fine-tuning teaches basic reasoning from high-quality traces, and reinforcement learning refines reasoning via reward signals, alleviating sparse explicit supervision. Experiments on three real-world datasets show R2Rec outperforms classical and LLM-based baselines with an average \\(\textbf\{10.48%\}\\) improvement in HitRatio@1 and \\(\textbf\{131.81%\}\\) gain over the original LLM. Furthermore, the explicit reasoning chains enhance interpretability by revealing the decision process. Our code is available at: https://anonymous.4open.science/r/R2Rec-7C5D.
