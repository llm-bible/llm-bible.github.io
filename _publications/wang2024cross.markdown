---
layout: publication
title: 'Cross-refine: Improving Natural Language Explanation Generation By Learning In Tandem'
authors: Wang Qianli, Anikina Tatiana, Feldhus Nils, Ostermann Simon, Möller Sebastian, Schmitt Vera
conference: "Arxiv"
year: 2024
bibkey: wang2024cross
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.07123"}
tags: ['GPT', 'Interpretability And Explainability', 'Model Architecture', 'Training Techniques', 'Uncategorized']
---
Natural language explanations (NLEs) are vital for elucidating the reasoning behind large language model (LLM) decisions. Many techniques have been developed to generate NLEs using LLMs. However, like humans, LLMs might not always produce optimal NLEs on first attempt. Inspired by human learning processes, we introduce Cross-Refine, which employs role modeling by deploying two LLMs as generator and critic, respectively. The generator outputs a first NLE and then refines this initial explanation using feedback and suggestions provided by the critic. Cross-Refine does not require any supervised training data or additional training. We validate Cross-Refine across three NLP tasks using three state-of-the-art open-source LLMs through automatic and human evaluation. We select Self-Refine (Madaan et al., 2023) as the baseline, which only utilizes self-feedback to refine the explanations. Our findings from automatic evaluation and a user study indicate that Cross-Refine outperforms Self-Refine. Meanwhile, Cross-Refine can perform effectively with less powerful LLMs, whereas Self-Refine only yields strong results with ChatGPT. Additionally, we conduct an ablation study to assess the importance of feedback and suggestions. Both of them play an important role in refining explanations. We further evaluate Cross-Refine on a bilingual dataset in English and German.
