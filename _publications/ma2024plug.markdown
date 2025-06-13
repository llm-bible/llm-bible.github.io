---
layout: publication
title: 'Plug-and-play Training Framework For Preference Optimization'
authors: Jingyuan Ma, Rui Li, Zheng Li, Lei Sha, Zhifang Sui
conference: "Arxiv"
year: 2024
bibkey: ma2024plug
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.20996"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Recently, preference optimization methods such as DPO have significantly
enhanced large language models (LLMs) in wide tasks including dialogue and
question-answering. However, current methods fail to account for the varying
difficulty levels of training samples during preference optimization, leading
to mediocre performance in tasks with high accuracy requirements, particularly
in mathematical reasoning. To address this limitation, we propose a novel
training framework, which employs multiple sampling to analyze output
distributions, assign different weights to samples, and incorporate these
weights into the preference optimization process. This plug-and-play approach
enables LLMs to prioritize challenging examples during training, improving
learning efficiency. Experimental results demonstrate that our framework
integrates seamlessly with various preference optimization methods and achieves
consistent improvements in mathematical reasoning tasks.
