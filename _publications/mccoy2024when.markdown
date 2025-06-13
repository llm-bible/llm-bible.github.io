---
layout: publication
title: 'When A Language Model Is Optimized For Reasoning, Does It Still Show Embers Of Autoregression? An Analysis Of Openai O1'
authors: R. Thomas Mccoy, Shunyu Yao, Dan Friedman, Mathew D. Hardy, Thomas L. Griffiths
conference: "Arxiv"
year: 2024
bibkey: mccoy2024when
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.01792'}
tags: ['Reinforcement Learning']
---
In "Embers of Autoregression" (McCoy et al., 2023), we showed that several
large language models (LLMs) have some important limitations that are
attributable to their origins in next-word prediction. Here we investigate
whether these issues persist with o1, a new system from OpenAI that differs
from previous LLMs in that it is optimized for reasoning. We find that o1
substantially outperforms previous LLMs in many cases, with particularly large
improvements on rare variants of common tasks (e.g., forming acronyms from the
second letter of each word in a list, rather than the first letter). Despite
these quantitative improvements, however, o1 still displays the same
qualitative trends that we observed in previous systems. Specifically, o1 --
like previous LLMs -- is sensitive to the probability of examples and tasks,
performing better and requiring fewer "thinking tokens" in high-probability
settings than in low-probability ones. These results show that optimizing a
language model for reasoning can mitigate but might not fully overcome the
language model's probability sensitivity.
