---
layout: publication
title: 'Playpen: An Environment For Exploring Learning Through Conversational Interaction'
authors: Nicola Horst, Davide Mazzaccara, Antonia Schmidt, Michael Sullivan, Filippo Momentè, Luca Franceschetti, Philipp Sadler, Sherzod Hakimov, Alberto Testoni, Raffaella Bernardi, Raquel Fernández, Alexander Koller, Oliver Lemon, David Schlangen, Mario Giulianelli, Alessandro Suglia
conference: "Arxiv"
year: 2025
bibkey: horst2025environment
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.08590'}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Interaction between learner and feedback-giver has come into focus recently for post-training of Large Language Models (LLMs), through the use of reward models that judge the appropriateness of a model's response. In this paper, we investigate whether Dialogue Games -- goal-directed and rule-governed activities driven predominantly by verbal actions -- can also serve as a source of feedback signals for learning. We introduce Playpen, an environment for off- and online learning through Dialogue Game self-play, and investigate a representative set of post-training methods: supervised fine-tuning; direct alignment (DPO); and reinforcement learning with GRPO. We experiment with post-training a small LLM (Llama-3.1-8B-Instruct), evaluating performance on unseen instances of training games as well as unseen games, and on standard benchmarks. We find that imitation learning through SFT improves performance on unseen instances, but negatively impacts other skills, while interactive learning with GRPO shows balanced improvements without loss of skills. We release the framework and the baseline training setups to foster research in the promising new direction of learning in (synthetic) interaction.
