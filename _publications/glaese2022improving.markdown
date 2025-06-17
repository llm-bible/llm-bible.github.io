---
layout: publication
title: Improving Alignment Of Dialogue Agents Via Targeted Human Judgements
authors: Amelia Glaese et al.
conference: Arxiv
year: 2022
citations: 105
bibkey: glaese2022improving
additional_links:
- name: Paper
  url: http://arxiv.org/abs/2209.14375v1
tags:
- Agentic
- Reinforcement Learning
- Ethics and Bias
---
We present Sparrow, an information-seeking dialogue agent trained to be more
helpful, correct, and harmless compared to prompted language model baselines.
We use reinforcement learning from human feedback to train our models with two
new additions to help human raters judge agent behaviour. First, to make our
agent more helpful and harmless, we break down the requirements for good
dialogue into natural language rules the agent should follow, and ask raters
about each rule separately. We demonstrate that this breakdown enables us to
collect more targeted human judgements of agent behaviour and allows for more
efficient rule-conditional reward models. Second, our agent provides evidence
from sources supporting factual claims when collecting preference judgements
over model statements. For factual questions, evidence provided by Sparrow
supports the sampled response 78% of the time. Sparrow is preferred more often
than baselines while being more resilient to adversarial probing by humans,
violating our rules only 8% of the time when probed. Finally, we conduct
extensive analyses showing that though our model learns to follow our rules it
can exhibit distributional biases.