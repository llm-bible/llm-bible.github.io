---
layout: publication
title: 'Verifiable Format Control For Large Language Model Generations'
authors: Zhaoyang Wang, Jinqi Jiang, Huichi Zhou, Wenhao Zheng, Xuchao Zhang, Chetan Bansal, Huaxiu Yao
conference: "Arxiv"
year: 2025
bibkey: wang2025verifiable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.04498'}
tags: ['RAG', 'Model Architecture', 'Tools', 'Applications', 'Training Techniques', 'GPT', 'Reinforcement Learning', 'Ethics and Bias']
---
Recent Large Language Models (LLMs) have demonstrated satisfying general
instruction following ability. However, small LLMs with about 7B parameters
still struggle fine-grained format following (e.g., JSON format), which
seriously hinder the advancements of their applications. Most existing methods
focus on benchmarking general instruction following while overlook how to
improve the specific format following ability for small LLMs. Besides, these
methods often rely on evaluations based on advanced LLMs (e.g., GPT-4), which
can introduce the intrinsic bias of LLMs and be costly due to the API calls. In
this paper, we first curate a fully verifiable format following dataset VFF. In
contrast to existing works often adopting external LLMs for
instruction-following validations, every sample of VFF can be easily validated
with a Python function. Further, we propose to leverage this verifiable feature
to synthesize massive data for progressively training small LLMs, in order to
improve their format following abilities. Experimental results highlight the
prevalent limitations in the format following capabilities of 7B level
open-source LLMs and demonstrate the effectiveness of our method in enhancing
this essential ability.
