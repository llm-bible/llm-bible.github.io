---
layout: publication
title: 'Exploring Backdoor Attack And Defense For Llm-empowered Recommendations'
authors: Liangbo Ning, Wenqi Fan, Qing Li
conference: "Arxiv"
year: 2025
bibkey: ning2025exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.11182"}
tags: ['Responsible AI', 'Agentic', 'Security', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Merging', 'RecSys', 'Attention Mechanism']
---
The fusion of Large Language Models (LLMs) with recommender systems (RecSys)
has dramatically advanced personalized recommendations and drawn extensive
attention. Despite the impressive progress, the safety of LLM-based RecSys
against backdoor attacks remains largely under-explored. In this paper, we
raise a new problem: Can a backdoor with a specific trigger be injected into
LLM-based Recsys, leading to the manipulation of the recommendation responses
when the backdoor trigger is appended to an item's title? To investigate the
vulnerabilities of LLM-based RecSys under backdoor attacks, we propose a new
attack framework termed Backdoor Injection Poisoning for RecSys (BadRec).
BadRec perturbs the items' titles with triggers and employs several fake users
to interact with these items, effectively poisoning the training set and
injecting backdoors into LLM-based RecSys. Comprehensive experiments reveal
that poisoning just 1% of the training data with adversarial examples is
sufficient to successfully implant backdoors, enabling manipulation of
recommendations. To further mitigate such a security threat, we propose a
universal defense strategy called Poison Scanner (P-Scanner). Specifically, we
introduce an LLM-based poison scanner to detect the poisoned items by
leveraging the powerful language understanding and rich knowledge of LLMs. A
trigger augmentation agent is employed to generate diverse synthetic triggers
to guide the poison scanner in learning domain-specific knowledge of the
poisoned item detection task. Extensive experiments on three real-world
datasets validate the effectiveness of the proposed P-Scanner.
