---
layout: publication
title: 'Introducing Language Guidance In Prompt-based Continual Learning'
authors: Khan Muhammad Gul Zain Ali, Naeem Muhammad Ferjad, Van Gool Luc, Stricker Didier, Tombari Federico, Afzal Muhammad Zeshan
conference: "Arxiv"
year: 2023
bibkey: khan2023introducing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.15827"}
tags: ['Prompting', 'Reinforcement Learning']
---
Continual Learning aims to learn a single model on a sequence of tasks
without having access to data from previous tasks. The biggest challenge in the
domain still remains catastrophic forgetting: a loss in performance on seen
classes of earlier tasks. Some existing methods rely on an expensive replay
buffer to store a chunk of data from previous tasks. This, while promising,
becomes expensive when the number of tasks becomes large or data can not be
stored for privacy reasons. As an alternative, prompt-based methods have been
proposed that store the task information in a learnable prompt pool. This
prompt pool instructs a frozen image encoder on how to solve each task. While
the model faces a disjoint set of classes in each task in this setting, we
argue that these classes can be encoded to the same embedding space of a
pre-trained language encoder. In this work, we propose Language Guidance for
Prompt-based Continual Learning (LGCL) as a plug-in for prompt-based methods.
LGCL is model agnostic and introduces language guidance at the task level in
the prompt pool and at the class level on the output feature of the vision
encoder. We show with extensive experimentation that LGCL consistently improves
the performance of prompt-based continual learning methods to set a new
state-of-the art. LGCL achieves these performance improvements without needing
any additional learnable parameters.
