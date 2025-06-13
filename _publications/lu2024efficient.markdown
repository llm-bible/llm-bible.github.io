---
layout: publication
title: 'Versatune: An Efficient Data Composition Framework For Training Multi-capability Llms'
authors: Keer Lu, Keshi Zhao, Zhuoran Zhang, Zheng Liang, Da Pan, Shusen Zhang, Xin Wu, Guosheng Dong, Bin Cui, Tengjiao Wang, Wentao Zhang
conference: "Arxiv"
year: 2024
bibkey: lu2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.11266"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
As demonstrated by the proprietary Large Language Models (LLMs) such as GPT and Claude series, LLMs have the potential to achieve remarkable proficiency across a wide range of domains, including law, medicine, finance, science, code, etc., all within a single model. These capabilities are further augmented during the Supervised Fine-Tuning (SFT) phase. Despite their potential, existing work mainly focuses on domain-specific enhancements during fine-tuning, the challenge of which lies in catastrophic forgetting of knowledge across other domains. In this study, we introduce **VersaTune**, a novel data composition framework designed for enhancing LLMs' overall multi-domain capabilities during training. We begin with detecting the distribution of domain-specific knowledge within the base model, followed by the training data composition that aligns with the model's existing knowledge distribution. During the subsequent training process, domain weights are dynamically adjusted based on their learnable potential and forgetting degree. Experimental results indicate that VersaTune is effective in multi-domain fostering, with an improvement of 35.21% in the overall multi-ability performances compared to uniform domain weights. Furthermore, we find that Qwen-2.5-32B + VersaTune even surpasses frontier models, including GPT-4o, Claude3.5-Sonnet and DeepSeek-V3 by 0.86%, 4.76% and 4.60%. Additionally, in scenarios where flexible expansion of a specific domain is required, VersaTune reduces the performance degradation in other domains by 38.77%, while preserving the training efficacy of the target domain.
