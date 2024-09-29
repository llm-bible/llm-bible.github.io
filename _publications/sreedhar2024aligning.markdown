---
layout: publication
title: Canttalkaboutthis Aligning Language Models To Stay On Topic In Dialogues
authors: Sreedhar Makesh Narsimhan, Rebedea Traian, Ghosh Shaona, Zeng Jiaqi, Parisien Christopher
conference: "Arxiv"
year: 2024
bibkey: sreedhar2024aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.03820"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Responsible AI', 'Training Techniques']
---
Recent advancements in instruction45;tuning datasets have predominantly focused on specific tasks like mathematical or logical reasoning. There has been a notable gap in data designed for aligning language models to maintain topic relevance in conversations 45; a critical aspect for deploying chatbots to production. We introduce the CantTalkAboutThis dataset to help language models remain focused on the subject at hand during task45;oriented interactions. It consists of synthetic dialogues on a wide range of conversation topics from different domains. These dialogues are interspersed with distractor turns that intentionally divert the chatbot from the predefined topic. Fine45;tuning language models on this dataset helps make them resilient to deviating from the role assigned and improves their ability to maintain topical coherence compared to general45;purpose instruction45;tuned LLMs like GPT45;445;turbo and Mixtral45;Instruct. Additionally preliminary observations suggest that training models on this dataset also enhance their performance on fine45;grained instruction following tasks including safety alignment.
