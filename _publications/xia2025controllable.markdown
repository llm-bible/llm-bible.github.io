---
layout: publication
title: 'Tokenskip: Controllable Chain-of-thought Compression In Llms'
authors: Heming Xia, Chak Tou Leong, Wenjie Wang, Yongqi Li, Wenjie Li
conference: "Arxiv"
year: 2025
bibkey: xia2025controllable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12067"}
tags: ['Pretraining Methods', 'GPT', 'Reinforcement Learning']
---
Chain-of-Thought (CoT) has been proven effective in enhancing the reasoning capabilities of large language models (LLMs). Recent advancements, such as OpenAI's o1 and DeepSeek-R1, suggest that scaling up the length of CoT sequences during inference could further boost LLM reasoning performance. However, due to the autoregressive nature of LLM decoding, longer CoT outputs lead to a linear increase in inference latency, adversely affecting user experience, particularly when the CoT exceeds 10,000 tokens. To address this limitation, we analyze the semantic importance of tokens within CoT outputs and reveal that their contributions to reasoning vary. Building on this insight, we propose TokenSkip, a simple yet effective approach that enables LLMs to selectively skip less important tokens, allowing for controllable CoT compression. Extensive experiments across various models and tasks demonstrate the effectiveness of TokenSkip in reducing CoT token usage while preserving strong reasoning performance. Notably, when applied to Qwen2.5-14B-Instruct, TokenSkip reduces reasoning tokens by 40% (from 313 to 181) on GSM8K, with less than a 0.4% performance drop.
