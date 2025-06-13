---
layout: publication
title: 'Fine-tuning Large Language Models For Domain-specific Machine Translation'
authors: Jiawei Zheng, Hanghai Hong, Feiyan Liu, Xiaoli Wang, Jingsong Su, Yonggui Liang, Shikai Wu
conference: "Arxiv"
year: 2024
bibkey: zheng2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.15061"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Few-Shot', 'Prompting']
---
Large language models (LLMs) have shown great potential in domain-specific
machine translation (MT). However, one major issue is that LLMs pre-trained on
general domain corpus might not generalize well to specific domains due to the
lack of domain-specific knowledge. To address this issue, this paper focuses on
enhancing the domain-specific MT capability of LLMs, by providing high-quality
training datasets and proposing a novel fine-tuning framework denoted by
DragFT. DragFT augments LLMs via three techniques: (i) Dictionary-enhanced
prompting integrates dictionary information into prompts to improve the
translation of domain-specific terminology.; (ii) RAG-based few-shot example
selection provides high-quality examples that simulate both the domain and
style characteristics; (iii) Fine-tuning with few-shot examples further
enhances performance when using in-domain examples. We deploy DragFT on three
well-known LLM backbones with 13B training parameters to validate its
effectiveness. The results on three domain-specific datasets show that DragFT
achieves a significant performance boost and shows superior performance
compared to advanced models such as GPT-3.5 and GPT-4o. The drastic performance
improvement of DragFT over existing LLMs can be attributed to incorporating
relevant knowledge while mitigating noise.
