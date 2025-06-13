---
layout: publication
title: 'Evaluating And Improving Context Attention Distribution On Multi-turn Response Generation Using Self-contained Distractions'
authors: Yujie Xing, Jon Atle Gulla
conference: "Arxiv"
year: 2022
bibkey: xing2022evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.04943"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'Model Architecture', 'Attention Mechanism']
---
Despite the rapid progress of open-domain generation-based conversational
agents, most deployed systems treat dialogue contexts as single-turns, while
systems dealing with multi-turn contexts are less studied. There is a lack of a
reliable metric for evaluating multi-turn modelling, as well as an effective
solution for improving it. In this paper, we focus on an essential component of
multi-turn generation-based conversational agents: context attention
distribution, i.e. how systems distribute their attention on dialogue's
context. For evaluation of this component, We introduce a novel
attention-mechanism-based metric: DAS ratio. To improve performance on this
component, we propose an optimization strategy that employs self-contained
distractions. Our experiments on the Ubuntu chatlogs dataset show that models
with comparable perplexity can be distinguished by their ability on context
attention distribution. Our proposed optimization strategy improves both
non-hierarchical and hierarchical models on the proposed metric by about 10%
from baselines.
