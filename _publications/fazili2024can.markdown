---
layout: publication
title: Gensco\: Can Question Decomposition Based Passage Alignment Improve Question Answering?
authors: Fazili Barah, Goswami Koustava, Modani Natwar, Nair Inderjeet
conference: "Arxiv"
year: 2024
bibkey: fazili2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.10245"}
tags: ['Applications', 'Prompting', 'RAG', 'Security', 'Tools']
---
Retrieval augmented generation (RAG) with large language models (LLMs) for Question Answering (QA) entails furnishing relevant context within the prompt to facilitate the LLM in answer generation. During the generation inaccuracies or hallucinations frequently occur due to two primary factors inadequate or distracting context in the prompts and the inability of LLMs to effectively reason through the facts. In this paper we investigate whether providing aligned context via a carefully selected passage sequence leads to better answer generation by the LLM for multi-hop QA. We introduce GenSco a novel approach of selecting passages based on the predicted decomposition of the multi-hop questions. The framework consists of two distinct LLMs (i) Generator LLM which is used for question decomposition and final answer generation; (ii) an auxiliary open-sourced LLM used as the scorer to semantically guide the Generator for passage selection. The generator is invoked only once for the answer generation resulting in a cost-effective and efficient approach. We evaluate on three broadly established multi-hop question answering datasets 2WikiMultiHop Adversarial HotPotQA and MuSiQue and achieve an absolute gain of 15.1 and 5.9 points in Exact Match score with respect to the best performing baselines over MuSiQue and 2WikiMultiHop respectively.
