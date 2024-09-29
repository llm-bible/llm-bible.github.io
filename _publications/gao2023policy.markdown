---
layout: publication
title: Policy45;gradient Training Of Language Models For Ranking
authors: Gao Ge, Chang Jonathan D., Cardie Claire, Brantley Kianté, Joachim Thorsten
conference: "Arxiv"
year: 2023
bibkey: gao2023policy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.04407"}
tags: ['Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Text retrieval plays a crucial role in incorporating factual knowledge for decision making into language processing pipelines ranging from chat45;based web search to question answering systems. Current state45;of45;the45;art text retrieval models leverage pre45;trained large language models (LLMs) to achieve competitive performance but training LLM45;based retrievers via typical contrastive losses requires intricate heuristics including selecting hard negatives and using additional supervision as learning signals. This reliance on heuristics stems from the fact that the contrastive loss itself is heuristic and does not directly optimize the downstream metrics of decision quality at the end of the processing pipeline. To address this issue we introduce Neural PG45;RANK a novel training algorithm that learns to rank by instantiating a LLM as a Plackett45;Luce ranking policy. Neural PG45;RANK provides a principled method for end45;to45;end training of retrieval models as part of larger decision systems via policy gradient with little reliance on complex heuristics and it effectively unifies the training objective with downstream decision45;making quality. We conduct extensive experiments on various text retrieval benchmarks. The results demonstrate that when the training objective aligns with the evaluation setup Neural PG45;RANK yields remarkable in45;domain performance improvement with substantial out45;of45;domain generalization to some critical datasets employed in downstream question answering tasks.
