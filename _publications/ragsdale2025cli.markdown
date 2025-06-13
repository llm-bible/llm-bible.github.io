---
layout: publication
title: 'Shioenv: A CLI Behavior-capturing Environment Enabling Grammar-guided Command Synthesis For Dataset Curation'
authors: Jarrod Ragsdale, Rajendra Boppana
conference: "Arxiv"
year: 2025
bibkey: ragsdale2025cli
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18374"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Fine-Tuning']
---
Command-line interfaces (CLIs) provide structured textual environments for system administration. Explorations have been performed using pre-trained language models (PLMs) to simulate these environments for safe interaction in high-risk environments. However, their use has been constrained to frozen, large parameter models like GPT. For smaller architectures to reach a similar level of believability, a rich dataset of CLI interactions is required. Existing public datasets focus on mapping natural-language tasks to commands, omitting crucial execution data such as exit codes, outputs, and environmental side effects, limiting their usability for behavioral modeling. We introduce a Shell Input -Output Environment (ShIOEnv), which casts command construction as a Markov Decision Process whose state is the partially built sequence and whose actions append arguments. After each action, ShIOEnv executes the candidate and returns its exit status, output, and progress toward a minimal-length behavioral objective. Due to the intractable nature of the combinatorial argument state-action space, we derive a context-free grammar from man pages to mask invalid arguments from being emitted. We explore random and proximal-policy optimization (PPO)-optimized sampling of unrestricted and grammar-masked action spaces to produce four exploration strategies. We observed that grammar masking and PPO significantly improve sample efficiency to produce a higher quality dataset (maximizing the number of arguments while minimizing redundancies). Policy-generated datasets of shell input-output behavior pairs are used to fine-tune CodeT5, where we observe 85% improvements in BLEU-4 when constraining the action space to grammar productions with an additional 26% improvement when applying PPO. The ShIOEnv environment and curated command behavior datasets are released for use in future research.
