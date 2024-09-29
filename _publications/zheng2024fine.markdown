---
layout: publication
title: "Fine-tuning Large Language Models For Domain-specific Machine Translation"
authors: Zheng Jiawei, Hong Hanghai, Wang Xiaoli, Su Jingsong, Liang Yonggui, Wu Shikai
conference: "Arxiv"
year: 2024
bibkey: zheng2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.15061"}
tags: ['Applications', 'Fine Tuning', 'In Context Learning', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Large language models (LLMs) have made significant progress in machine translation (MT). However their potential in domain-specific MT remains under-explored. Current LLM-based MT systems still face several challenges. First for LLMs with in-context learning their effectiveness is highly sensitive to input translation examples and processing them can increase inference costs. They often require extra post-processing due to over-generation. Second LLMs with fine-tuning on domain-specific data often require high training costs for domain adaptation and may weaken the zero-shot MT capabilities of LLMs due to over-specialization. The aforementioned methods can struggle to translate rare words in domain transfer scenarios. To address these challenges this paper proposes a prompt-oriented fine-tuning method denoted as LlamaIT to effectively and efficiently fine-tune a general-purpose LLM for domain-specific MT tasks. First we construct a task-specific mix-domain dataset which is then used to fine-tune the LLM with LoRA. This can eliminate the need for input translation examples post-processing or over-specialization. By zero-shot prompting with instructions we adapt the MT tasks to the target domain at inference time. To further elicit the MT capability for rare words we construct new prompts by incorporating domain-specific bilingual vocabulary. We also conduct extensive experiments on both publicly available and self-constructed datasets. The results show that our LlamaIT can significantly enhance the domain-specific MT capabilities of the LLM meanwhile preserving its zero-shot MT capabilities.
