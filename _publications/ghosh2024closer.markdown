---
layout: publication
title: A Closer Look At The Limitations Of Instruction Tuning
authors: Ghosh Sreyan, Evuru Chandra Kiran Reddy, Kumar Sonal, S Ramaneswaran, Aneja Deepali, Jin Zeyu, Duraiswami Ramani, Manocha Dinesh
conference: "Arxiv"
year: 2024
bibkey: ghosh2024closer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.05119"}
tags: ['Agentic', 'Applications', 'Fine Tuning', 'Training Techniques']
---
Instruction Tuning (IT) the process of training large language models (LLMs) using instruction45;response pairs has emerged as the predominant method for transforming base pre45;trained LLMs into open45;domain conversational agents. While IT has achieved notable success and widespread adoption its limitations and shortcomings remain underexplored. In this paper through rigorous experiments and an in45;depth analysis of the changes LLMs undergo through IT we reveal various limitations of IT. In particular we show that (1) IT fails to enhance knowledge or skills in LLMs. LoRA fine45;tuning is limited to learning response initiation and style tokens and full45;parameter fine45;tuning leads to knowledge degradation. (2) Copying response patterns from IT datasets derived from knowledgeable sources leads to a decline in response quality. (3) Full45;parameter fine45;tuning increases hallucination by inaccurately borrowing tokens from conceptually similar instances in the IT dataset for generating responses. (4) Popular methods to improve IT do not lead to performance improvements over a simple LoRA fine45;tuned model. Our findings reveal that responses generated solely from pre45;trained knowledge consistently outperform responses by models that learn any form of new knowledge from IT on open45;source datasets. We hope the insights and challenges revealed in this paper inspire future work in related directions.
