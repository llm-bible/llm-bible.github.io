---
layout: publication
title: Normsage Multi-lingual Multi-cultural Norm Discovery From Conversations On-the-fly
authors: Fung Yi R., Chakraborty Tuhin, Guo Hao, Rambow Owen, Muresan Smaranda, Ji Heng
conference: "Arxiv"
year: 2022
bibkey: fung2022normsage
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.08604"}
tags: ['Ethics And Bias', 'GPT', 'Interpretability And Explainability', 'Model Architecture', 'Prompting', 'RAG', 'Tools']
---
Norm discovery is important for understanding and reasoning about the acceptable behaviors and potential violations in human communication and interactions. We introduce NormSage a framework for addressing the novel task of conversation-grounded multi-lingual multi-cultural norm discovery based on language model prompting and self-verification. NormSAGE leverages the expressiveness and implicit knowledge of the pretrained GPT-3 language model backbone to elicit knowledge about norms through directed questions representing the norm discovery task and conversation context. It further addresses the risk of language model hallucination with a self-verification mechanism ensuring that the norms discovered are correct and are substantially grounded to their source conversations. Evaluation results show that our approach discovers significantly more relevant and insightful norms for conversations on-the-fly compared to baselines (10+37; in Likert scale rating). The norms discovered from Chinese conversation are also comparable to the norms discovered from English conversation in terms of insightfulness and correctness (<337; difference). In addition the culture-specific norms are promising quality allowing for 8037; accuracy in culture pair human identification. Finally our grounding process in norm discovery self-verification can be extended for instantiating the adherence and violation of any norm for a given conversation on-the-fly with explainability and transparency. NormSAGE achieves an AUC of 95.437; in grounding with natural language explanation matching human-written quality.
