---
layout: publication
title: 'No Free Lunch For Defending Against Prefilling Attack By In-context Learning'
authors: Zhiyu Xue, Guangliang Liu, Bocheng Chen, Kristen Marie Johnson, Ramtin Pedarsani
conference: "Arxiv"
year: 2024
bibkey: xue2024no
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.12192'}
tags: ['In-Context Learning', 'Security', 'GPT', 'Model Architecture', 'Prompting', 'Responsible AI']
---
The security of Large Language Models (LLMs) has become an important research
topic since the emergence of ChatGPT. Though there have been various effective
methods to defend against jailbreak attacks, prefilling attacks remain an
unsolved and popular threat against open-sourced LLMs. In-Context Learning
(ICL) offers a computationally efficient defense against various jailbreak
attacks, yet no effective ICL methods have been developed to counter prefilling
attacks. In this paper, we: (1) show that ICL can effectively defend against
prefilling jailbreak attacks by employing adversative sentence structures
within demonstrations; (2) characterize the effectiveness of this defense
through the lens of model size, number of demonstrations, over-defense,
integration with other jailbreak attacks, and the presence of safety alignment.
Given the experimental results and our analysis, we conclude that there is no
free lunch for defending against prefilling jailbreak attacks with ICL. On the
one hand, current safety alignment methods fail to mitigate prefilling
jailbreak attacks, but adversative structures within ICL demonstrations provide
robust defense across various model sizes and complex jailbreak attacks. On the
other hand, LLMs exhibit similar over-defensiveness when utilizing ICL
demonstrations with adversative structures, and this behavior appears to be
independent of model size.
