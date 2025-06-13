---
layout: publication
title: 'Wolf Hidden In Sheep''s Conversations: Toward Harmless Data-based Backdoor Attacks For Jailbreaking Large Language Models'
authors: Jiawei Kong, Hao Fang, Xiaochen Yang, Kuofeng Gao, Bin Chen, Shu-tao Xia, Yaowei Wang, Min Zhang
conference: "Arxiv"
year: 2025
bibkey: kong2025wolf
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17601"}
tags: ['Fine-Tuning', 'Responsible AI', 'Efficiency and Optimization', 'GPT', 'RAG', 'Model Architecture', 'Language Modeling', 'Security', 'Training Techniques', 'Pretraining Methods']
---
Supervised fine-tuning (SFT) aligns large language models (LLMs) with human intent by training them on labeled task-specific data. Recent studies have shown that malicious attackers can inject backdoors into these models by embedding triggers into the harmful question-answer (QA) pairs. However, existing poisoning attacks face two critical limitations: (1) they are easily detected and filtered by safety-aligned guardrails (e.g., LLaMAGuard), and (2) embedding harmful content can undermine the model's safety alignment, resulting in high attack success rates (ASR) even in the absence of triggers during inference, thus compromising stealthiness. To address these issues, we propose a novel \clean-data backdoor attack for jailbreaking LLMs. Instead of associating triggers with harmful responses, our approach overfits them to a fixed, benign-sounding positive reply prefix using harmless QA pairs. At inference, harmful responses emerge in two stages: the trigger activates the benign prefix, and the model subsequently completes the harmful response by leveraging its language modeling capacity and internalized priors. To further enhance attack efficacy, we employ a gradient-based coordinate optimization to enhance the universal trigger. Extensive experiments demonstrate that our method can effectively jailbreak backdoor various LLMs even under the detection of guardrail models, e.g., an ASR of 86.67% and 85% on LLaMA-3-8B and Qwen-2.5-7B judged by GPT-4o.
