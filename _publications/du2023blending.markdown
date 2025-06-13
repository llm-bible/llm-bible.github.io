---
layout: publication
title: 'Blending Reward Functions Via Few Expert Demonstrations For Faithful And Accurate Knowledge-grounded Dialogue Generation'
authors: Wanyu Du, Yangfeng Ji
conference: "Arxiv"
year: 2023
bibkey: du2023blending
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.00953"}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Ethics and Bias', 'Pretraining Methods', 'Attention Mechanism']
---
The development of trustworthy conversational information-seeking systems
relies on dialogue models that can generate faithful and accurate responses
based on relevant knowledge texts. However, two main challenges hinder this
task. Firstly, language models may generate hallucinations due to data biases
present in their pretraining corpus. Secondly, knowledge texts often contain
redundant and irrelevant information that distracts the model's attention from
the relevant text span. Previous works use additional data annotations on the
knowledge texts to learn a knowledge identification module in order to bypass
irrelevant information, but collecting such high-quality span annotations can
be costly. In this work, we leverage reinforcement learning algorithms to
overcome the above challenges by introducing a novel reward function. Our
reward function combines an accuracy metric and a faithfulness metric to
provide a balanced quality judgment of generated responses, which can be used
as a cost-effective approximation to a human preference reward model when only
a few preference annotations are available. Empirical experiments on two
conversational information-seeking datasets demonstrate that our method can
compete with other strong supervised learning baselines.
