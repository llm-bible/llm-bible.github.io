---
layout: publication
title: Learning to Ask Informative Questions Enhancing LLMs with Preference Optimization and Expected Information Gain
authors: Mazzaccara Davide, Testoni Alberto, Bernardi Raffaella
conference: "Arxiv"
year: 2024
bibkey: mazzaccara2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.17453"}
tags: ['ARXIV', 'LLM', 'Tools', 'Training Techniques']
---
Questions are essential tools for acquiring the necessary information to complete information-seeking tasks. However large language models (LLMs) especially open-source models often perform poorly in generating informative questions as measured by expected information gain (EIG). In this paper we propose a method to enhance the informativeness of LLM-generated questions in 20-question game dialogues. We sample multiple questions from the same model (LLAMA 2-CHAT 7B) for each game and create pairs of low-EIG and high-EIG questions to apply a Direct Preference Optimization (DPO) algorithm. Our results show that this method produces more effective questions (in terms of EIG) even in domains different from those used to train the DPO model.
