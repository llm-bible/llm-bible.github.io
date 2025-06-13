---
layout: publication
title: 'Reasoning In Conversation: Solving Subjective Tasks Through Dialogue Simulation For Large Language Models'
authors: Xiaolong Wang, Yile Wang, Yuanchi Zhang, Fuwen Luo, Peng Li, Maosong Sun, Yang Liu
conference: "Arxiv"
year: 2024
bibkey: wang2024reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17226"}
tags: ['Tools', 'GPT', 'Applications', 'Model Architecture']
---
Large Language Models (LLMs) have achieved remarkable performance in
objective tasks such as open-domain question answering and mathematical
reasoning, which can often be solved through recalling learned factual
knowledge or chain-of-thought style reasoning. However, we find that the
performance of LLMs in subjective tasks is still unsatisfactory, such as
metaphor recognition, dark humor detection, etc. Compared to objective tasks,
subjective tasks focus more on interpretation or emotional response rather than
a universally accepted reasoning pathway. Based on the characteristics of the
tasks and the strong dialogue-generation capabilities of LLMs, we propose RiC
(Reasoning in Conversation), a method that focuses on solving subjective tasks
through dialogue simulation. The motivation of RiC is to mine useful contextual
information by simulating dialogues instead of supplying chain-of-thought style
rationales, thereby offering potential useful knowledge behind dialogues for
giving the final answers. We evaluate both API-based and open-source LLMs
including GPT-4, ChatGPT, and OpenChat across twelve tasks. Experimental
results show that RiC can yield significant improvement compared with various
baselines.
