---
layout: publication
title: 'SAG: Style-aligned Article Generation Via Model Collaboration'
authors: Chenning Xu, Fangxun Shu, Dian Jin, Jinghao Wei, Hao Jiang
conference: "Arxiv"
year: 2024
bibkey: xu2024style
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.03137"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
Large language models (LLMs) have increased the demand for personalized and
stylish content generation. However, closed-source models like GPT-4 present
limitations in optimization opportunities, while the substantial training costs
and inflexibility of open-source alternatives, such as Qwen-72B, pose
considerable challenges. Conversely, small language models (SLMs) struggle with
understanding complex instructions and transferring learned capabilities to new
contexts, often exhibiting more pronounced limitations. In this paper, we
present a novel collaborative training framework that leverages the strengths
of both LLMs and SLMs for style article generation, surpassing the performance
of either model alone. We freeze the LLMs to harness their robust
instruction-following capabilities and subsequently apply supervised
fine-tuning on the SLM using style-specific data. Additionally, we introduce a
self-improvement method to enhance style consistency. Our new benchmark,
NoteBench, thoroughly evaluates style-aligned generation. Extensive experiments
show that our approach achieves state-of-the-art performance, with improvements
of 0.78 in ROUGE-L and 0.55 in BLEU-4 scores compared to GPT-4, while
maintaining a low hallucination rate regarding factual and faithfulness.
