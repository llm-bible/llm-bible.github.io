---
layout: publication
title: OPDAI at SemEval-2024 Task 6 Small LLMs can Accelerate Hallucination Detection with Weakly Supervised Data
authors: Wei Chengcheng, Chen Ze, Fang Songtan, He Jiarong, Gao Max
conference: "Arxiv"
year: 2024
bibkey: wei2024opdai
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.12913"}
tags: ['ARXIV', 'Applications', 'GPT', 'LLM', 'Prompt', 'Supervised', 'Tools']
---
This paper mainly describes a unified system for hallucination detection of LLMs which wins the second prize in the model-agnostic track of the SemEval-2024 Task 6 and also achieves considerable results in the model-aware track. This task aims to detect hallucination with LLMs for three different text-generation tasks without labeled training data. We utilize prompt engineering and few-shot learning to verify the performance of different LLMs on the validation data. Then we select the LLMs with better performance to generate high-quality weakly supervised training data which not only satisfies the consistency of different LLMs but also satisfies the consistency of the optimal LLM with different sampling parameters. Furthermore we finetune different LLMs by using the constructed training data and finding that a relatively small LLM can achieve a competitive level of performance in hallucination detection when compared to the large LLMs and the prompt-based approaches using GPT-4.
