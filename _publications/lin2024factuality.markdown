---
layout: publication
title: FLAME&#58; Factuality-aware Alignment For Large Language Models
authors: Lin Sheng-chieh, Gao Luyu, Oguz Barlas, Xiong Wenhan, Lin Jimmy, Yih Wen-tau, Chen Xilun
conference: "Arxiv"
year: 2024
bibkey: lin2024factuality
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.01525"}
tags: ['Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Alignment is a standard procedure to fine-tune pre-trained large language models (LLMs) to follow natural language instructions and serve as helpful AI assistants. We have observed however that the conventional alignment process fails to enhance the factual accuracy of LLMs and often leads to the generation of more false facts (i.e. hallucination). In this paper we study how to make the LLM alignment process more factual by first identifying factors that lead to hallucination in both alignment steps supervised fine-tuning (SFT) and reinforcement learning (RL). In particular we find that training the LLM on new knowledge or unfamiliar texts can encourage hallucination. This makes SFT less factual as it trains on human labeled data that may be novel to the LLM. Furthermore reward functions used in standard RL can also encourage hallucination because it guides the LLM to provide more helpful responses on a diverse set of instructions often preferring longer and more detailed responses. Based on these observations we propose factuality-aware alignment comprised of factuality-aware SFT and factuality-aware RL through direct preference optimization. Experiments show that our proposed factuality-aware alignment guides LLMs to output more factual responses while maintaining instruction-following capability.
