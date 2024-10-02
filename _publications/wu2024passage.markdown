---
layout: publication
title: 'Passage-specific Prompt Tuning For Passage Reranking In Question Answering With Large Language Models'
authors: Wu Xuyang, Peng Zhiyuan, Sai Krishna Sravanthi Rajanala, Wu Hsin-tai, Fang Yi
conference: "Arxiv"
year: 2024
bibkey: wu2024passage
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.20654"}
tags: ['Applications', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
'Effective passage retrieval and reranking methods have been widely utilized to identify suitable candidates in open-domain question answering tasks, recent studies have resorted to LLMs for reranking the retrieved passages by the log-likelihood of the question conditioned on each passage. Although these methods have demonstrated promising results, the performance is notably sensitive to the human-written prompt (or hard prompt), and fine-tuning LLMs can be computationally intensive and time-consuming. Furthermore, this approach limits the leverage of question-passage relevance pairs and passage-specific knowledge to enhance the ranking capabilities of LLMs. In this paper, we propose passage-specific prompt tuning for reranking in open-domain question answering (PSPT): a parameter-efficient method that fine-tunes learnable passage-specific soft prompts, incorporating passage-specific knowledge from a limited set of question-passage relevance pairs. The method involves ranking retrieved passages based on the log-likelihood of the model generating the question conditioned on each passage and the learned soft prompt. We conducted extensive experiments utilizing the Llama-2-chat-7B model across three publicly available open-domain question answering datasets and the results demonstrate the effectiveness of the proposed approach.'
