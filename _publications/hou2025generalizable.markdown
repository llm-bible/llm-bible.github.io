---
layout: publication
title: 'Molorec: A Generalizable And Efficient Framework For Llm-based Recommendation'
authors: Min Hou, Chenxi Bai, Le Wu, Hao Liu, Kun Zhang, Kai Zhang, Richang Hong, Meng Wang
conference: "Arxiv"
year: 2025
bibkey: hou2025generalizable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.08271'}
tags: ['Training Techniques', 'Tools', 'Fine-Tuning', 'RecSys', 'Reinforcement Learning', 'Pretraining Methods']
---
Large Language Models (LLMs) have achieved remarkable success in recent
years, owing to their impressive generalization capabilities and rich world
knowledge. To capitalize on the potential of using LLMs as recommender systems,
mainstream approaches typically focus on two paradigms. The first paradigm
designs multi-domain or multi-task instruction data for generalizable
recommendation, so as to align LLMs with general recommendation areas and deal
with cold-start recommendation. The second paradigm enhances domain-specific
recommendation tasks with parameter-efficient fine-tuning techniques, in order
to improve models under the warm recommendation scenarios. While most previous
works treat these two paradigms separately, we argue that they have
complementary advantages, and combining them together would be helpful.
  To that end, in this paper, we propose a generalizable and efficient
LLM-based recommendation framework MoLoRec. Our approach starts by
parameter-efficient fine-tuning a domain-general module with general
recommendation instruction data, to align LLM with recommendation knowledge.
Then, given users' behavior of a specific domain, we construct a
domain-specific instruction dataset and apply efficient fine-tuning to the
pre-trained LLM. After that, we provide approaches to integrate the above
domain-general part and domain-specific part with parameters mixture. Please
note that, MoLoRec is efficient with plug and play, as the domain-general
module is trained only once, and any domain-specific plug-in can be efficiently
merged with only domain-specific fine-tuning. Extensive experiments on multiple
datasets under both warm and cold-start recommendation scenarios validate the
effectiveness and generality of the proposed MoLoRec.
