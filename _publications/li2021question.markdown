---
layout: publication
title: 'Question-aware Memory Network For Multi-hop Question Answering In Human-robot Interaction'
authors: Xinmeng Li, Mamoun Alazab, Qian Li, Keping Yu, Quanjun Yin
conference: "Arxiv"
year: 2021
bibkey: li2021question
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2104.13173'}
tags: ['Attention Mechanism', 'Training Techniques', 'Applications', 'Model Architecture', 'Reinforcement Learning']
---
Knowledge graph question answering is an important technology in intelligent
human-robot interaction, which aims at automatically giving answer to human
natural language question with the given knowledge graph. For the
multi-relation question with higher variety and complexity, the tokens of the
question have different priority for the triples selection in the reasoning
steps. Most existing models take the question as a whole and ignore the
priority information in it. To solve this problem, we propose question-aware
memory network for multi-hop question answering, named QA2MN, to update the
attention on question timely in the reasoning process. In addition, we
incorporate graph context information into knowledge graph embedding model to
increase the ability to represent entities and relations. We use it to
initialize the QA2MN model and fine-tune it in the training process. We
evaluate QA2MN on PathQuestion and WorldCup2014, two representative datasets
for complex multi-hop question answering. The result demonstrates that QA2MN
achieves state-of-the-art Hits@1 accuracy on the two datasets, which validates
the effectiveness of our model.
