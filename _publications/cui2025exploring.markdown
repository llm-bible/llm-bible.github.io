---
layout: publication
title: 'Exploring Jailbreak Attacks On Llms Through Intent Concealment And Diversion'
authors: Tiehan Cui, Yanxu Mao, Peipei Liu, Congying Liu, Datao You
conference: "Arxiv"
year: 2025
bibkey: cui2025exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.14316"}
tags: ['Security', 'Model Architecture', 'Efficiency and Optimization', 'Language Modeling', 'Prompting', 'Applications', 'Attention Mechanism']
---
Although large language models (LLMs) have achieved remarkable advancements, their security remains a pressing concern. One major threat is jailbreak attacks, where adversarial prompts bypass model safeguards to generate harmful or objectionable content. Researchers study jailbreak attacks to understand security and robustness of LLMs. However, existing jailbreak attack methods face two main challenges: (1) an excessive number of iterative queries, and (2) poor generalization across models. In addition, recent jailbreak evaluation datasets focus primarily on question-answering scenarios, lacking attention to text generation tasks that require accurate regeneration of toxic content. To tackle these challenges, we propose two contributions: (1) ICE, a novel black-box jailbreak method that employs Intent Concealment and divErsion to effectively circumvent security constraints. ICE achieves high attack success rates (ASR) with a single query, significantly improving efficiency and transferability across different models. (2) BiSceneEval, a comprehensive dataset designed for assessing LLM robustness in question-answering and text-generation tasks. Experimental results demonstrate that ICE outperforms existing jailbreak techniques, revealing critical vulnerabilities in current defense mechanisms. Our findings underscore the necessity of a hybrid security strategy that integrates predefined security mechanisms with real-time semantic decomposition to enhance the security of LLMs.
