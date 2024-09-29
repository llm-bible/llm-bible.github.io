---
layout: publication
title: Passage45;specific Prompt Tuning For Passage Reranking In Question Answering With Large Language Models
authors: Wu Xuyang, Peng Zhiyuan, Sai Krishna Sravanthi Rajanala, Wu Hsin-tai, Fang Yi
conference: "Arxiv"
year: 2024
bibkey: wu2024passage
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.20654"}
tags: ['Applications', 'Prompting', 'RAG']
---
Effective passage retrieval and reranking methods have been widely utilized to identify suitable candidates in open45;domain question answering tasks recent studies have resorted to LLMs for reranking the retrieved passages by the log45;likelihood of the question conditioned on each passage. Although these methods have demonstrated promising results the performance is notably sensitive to the human45;written prompt (or hard prompt) and fine45;tuning LLMs can be computationally intensive and time45;consuming. Furthermore this approach limits the leverage of question45;passage relevance pairs and passage45;specific knowledge to enhance the ranking capabilities of LLMs. In this paper we propose passage45;specific prompt tuning for reranking in open45;domain question answering (PSPT) a parameter45;efficient method that fine45;tunes learnable passage45;specific soft prompts incorporating passage45;specific knowledge from a limited set of question45;passage relevance pairs. The method involves ranking retrieved passages based on the log45;likelihood of the model generating the question conditioned on each passage and the learned soft prompt. We conducted extensive experiments utilizing the Llama45;245;chat45;7B model across three publicly available open45;domain question answering datasets and the results demonstrate the effectiveness of the proposed approach.
