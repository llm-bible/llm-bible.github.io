---
layout: publication
title: 'Activation Space Interventions Can Be Transferred Between Large Language Models'
authors: Narmeen Oozeer, Dhruv Nathawani, Nirmalendu Prakash, Michael Lan, Abir Harrasse, Amirali Abdullah
conference: "Arxiv"
year: 2025
bibkey: oozeer2025activation
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.04429'}
tags: ['Applications', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Responsible AI']
---
The study of representation universality in AI models reveals growing
convergence across domains, modalities, and architectures. However, the
practical applications of representation universality remain largely
unexplored. We bridge this gap by demonstrating that safety interventions can
be transferred between models through learned mappings of their shared
activation spaces. We demonstrate this approach on two well-established AI
safety tasks: backdoor removal and refusal of harmful prompts, showing
successful transfer of steering vectors that alter the models' outputs in a
predictable way. Additionally, we propose a new task, \textit\{corrupted
capabilities\}, where models are fine-tuned to embed knowledge tied to a
backdoor. This tests their ability to separate useful skills from backdoors,
reflecting real-world challenges. Extensive experiments across Llama, Qwen and
Gemma model families show that our method enables using smaller models to
efficiently align larger ones. Furthermore, we demonstrate that autoencoder
mappings between base and fine-tuned models can serve as reliable ``lightweight
safety switches", allowing dynamic toggling between model behaviors.
