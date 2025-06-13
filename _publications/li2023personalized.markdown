---
layout: publication
title: 'Posgen: Personalized Opening Sentence Generation For Online Insurance Sales'
authors: Yu Li, Yi Zhang, Weijia Wu, Zimu Zhou, Qiang Li
conference: "Arxiv"
year: 2023
bibkey: li2023personalized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.06470"}
tags: ['Agentic', 'Tools', 'Applications', 'Language Modeling', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism']
---
The insurance industry is shifting their sales mode from offline to online,
in expectation to reach massive potential customers in the digitization era.
Due to the complexity and the nature of insurance products, a cost-effective
online sales solution is to exploit chatbot AI to raise customers' attention
and pass those with interests to human agents for further sales. For high
response and conversion rates of customers, it is crucial for the chatbot to
initiate a conversation with personalized opening sentences, which are
generated with user-specific topic selection and ordering. Such personalized
opening sentence generation is challenging because (i) there are limited
historical samples for conversation topic recommendation in online insurance
sales and (ii) existing text generation schemes often fail to support
customized topic ordering based on user preferences. We design POSGen, a
personalized opening sentence generation scheme dedicated for online insurance
sales. It transfers user embeddings learned from auxiliary online user
behaviours to enhance conversation topic recommendation, and exploits a context
management unit to arrange the recommended topics in user-specific ordering for
opening sentence generation. POSGen is deployed on a real-world online
insurance platform. It achieves 2.33x total insurance premium improvement
through a two-month global test.
