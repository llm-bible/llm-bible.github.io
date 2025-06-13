---
layout: publication
title: 'CLOVA: A Closed-loop Visual Assistant With Tool Usage And Update'
authors: Zhi Gao, Yuntao Du, Xintong Zhang, Xiaojian Ma, Wenjuan Han, Song-chun Zhu, Qing Li
conference: "Arxiv"
year: 2023
bibkey: gao2023closed
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2312.10908'}
tags: ['Training Techniques', 'Applications', 'Tools', 'Prompting', 'Multimodal Models', 'Reinforcement Learning']
---
Utilizing large language models (LLMs) to compose off-the-shelf visual tools
represents a promising avenue of research for developing robust visual
assistants capable of addressing diverse visual tasks. However, these methods
often overlook the potential for continual learning, typically by freezing the
utilized tools, thus limiting their adaptation to environments requiring new
knowledge. To tackle this challenge, we propose CLOVA, a Closed-Loop Visual
Assistant, which operates within a framework encompassing inference,
reflection, and learning phases. During the inference phase, LLMs generate
programs and execute corresponding tools to complete assigned tasks. In the
reflection phase, a multimodal global-local reflection scheme analyzes human
feedback to determine which tools require updating. Lastly, the learning phase
employs three flexible approaches to automatically gather training data and
introduces a novel prompt tuning scheme to update the tools, allowing CLOVA to
efficiently acquire new knowledge. Experimental findings demonstrate that CLOVA
surpasses existing tool-usage methods by 5% in visual question answering and
multiple-image reasoning, by 10% in knowledge tagging, and by 20% in image
editing. These results underscore the significance of the continual learning
capability in general visual assistants.
