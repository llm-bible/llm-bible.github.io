---
layout: publication
title: Can Large Language Models Follow Concept Annotation Guidelines A Case Study On Scientific And Financial Domains
authors: Fonseca Marcio, Cohen Shay B.
conference: "Arxiv"
year: 2023
bibkey: fonseca2023can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08704"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Tools']
---
Although large language models (LLMs) exhibit remarkable capacity to leverage in45;context demonstrations it is still unclear to what extent they can learn new concepts or facts from ground45;truth labels. To address this question we examine the capacity of instruction45;tuned LLMs to follow in45;context concept guidelines for sentence labeling tasks. We design guidelines that present different types of factual and counterfactual concept definitions which are used as prompts for zero45;shot sentence classification tasks. Our results show that although concept definitions consistently help in task performance only the larger models (with 70B parameters or more) have limited ability to work under counterfactual contexts. Importantly only proprietary models such as GPT45;3.5 and GPT45;4 can recognize nonsensical guidelines which we hypothesize is due to more sophisticated alignment methods. Finally we find that Falcon45;180B45;chat is outperformed by Llama45;245;70B45;chat is most cases which indicates that careful fine45;tuning is more effective than increasing model scale. Altogether our simple evaluation method reveals significant gaps in concept understanding between the most capable open45;source language models and the leading proprietary APIs.
