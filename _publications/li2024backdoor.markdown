---
layout: publication
title: 'Backdoor Removal For Generative Large Language Models'
authors: Li Haoran, Chen Yulin, Zheng Zihao, Hu Qi, Chan Chunkit, Liu Heshan, Song Yangqiu
conference: "Arxiv"
year: 2024
bibkey: li2024backdoor
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.07667"}
tags: ['Agentic', 'Fine Tuning', 'Pretraining Methods', 'Reinforcement Learning', 'Responsible AI', 'Security', 'Tools', 'Training Techniques']
---
With rapid advances, generative large language models (LLMs) dominate various
Natural Language Processing (NLP) tasks from understanding to reasoning. Yet,
language models' inherent vulnerabilities may be exacerbated due to increased
accessibility and unrestricted model training on massive textual data from the
Internet. A malicious adversary may publish poisoned data online and conduct
backdoor attacks on the victim LLMs pre-trained on the poisoned data.
Backdoored LLMs behave innocuously for normal queries and generate harmful
responses when the backdoor trigger is activated. Despite significant efforts
paid to LLMs' safety issues, LLMs are still struggling against backdoor
attacks. As Anthropic recently revealed, existing safety training strategies,
including supervised fine-tuning (SFT) and Reinforcement Learning from Human
Feedback (RLHF), fail to revoke the backdoors once the LLM is backdoored during
the pre-training stage. In this paper, we present Simulate and Eliminate
(SANDE) to erase the undesired backdoored mappings for generative LLMs. We
initially propose Overwrite Supervised Fine-tuning (OSFT) for effective
backdoor removal when the trigger is known. Then, to handle the scenarios where
the trigger patterns are unknown, we integrate OSFT into our two-stage
framework, SANDE. Unlike previous works that center on the identification of
backdoors, our safety-enhanced LLMs are able to behave normally even when the
exact triggers are activated. We conduct comprehensive experiments to show that
our proposed SANDE is effective against backdoor attacks while bringing minimal
harm to LLMs' powerful capability without any additional access to unbackdoored
clean models. We will release the reproducible code.
