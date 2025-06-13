---
layout: publication
title: 'Llms For Generalizable Language-conditioned Policy Learning Under Minimal Data Requirements'
authors: Thomas Pouplin, Katarzyna Kobalczyk, Hao Sun, Mihaela Van Der Schaar
conference: "Arxiv"
year: 2024
bibkey: pouplin2024llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.06877"}
tags: ['Agentic', 'Agent', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG']
---
To develop autonomous agents capable of executing complex, multi-step
decision-making tasks as specified by humans in natural language, existing
reinforcement learning approaches typically require expensive labeled datasets
or access to real-time experimentation. Moreover, conventional methods often
face difficulties in generalizing to unseen goals and states, thereby limiting
their practical applicability. This paper presents TEDUO, a novel training
pipeline for offline language-conditioned policy learning. TEDUO operates on
easy-to-obtain, unlabeled datasets and is suited for the so-called in-the-wild
evaluation, wherein the agent encounters previously unseen goals and states. To
address the challenges posed by such data and evaluation settings, our method
leverages the prior knowledge and instruction-following capabilities of large
language models (LLMs) to enhance the fidelity of pre-collected offline data
and enable flexible generalization to new goals and states. Empirical results
demonstrate that the dual role of LLMs in our framework-as data enhancers and
generalizers-facilitates both effective and data-efficient learning of
generalizable language-conditioned policies.
