---
layout: publication
title: 'RLHS: Mitigating Misalignment In RLHF With Hindsight Simulation'
authors: Kaiqu Liang, Haimin Hu, Ryan Liu, Thomas L. Griffiths, Jaime Fernández Fisac
conference: "Arxiv"
year: 2025
bibkey: liang2025mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.08617"}
tags: ['Agentic', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning']
---
While Reinforcement Learning from Human Feedback (RLHF) has shown promise in
aligning generative AI, we present empirical evidence that it can also cause
severe, systematic misalignment. We hypothesize that this stems from evaluator
feedback depending on downstream outcome predictions (foresight) that can be
influenced by the AI's output, inducing Goodhart's law dynamics. Conversely,
our theoretical analysis shows that conditioning evaluator feedback on
downstream observations (hindsight) inhibits this effect by decoupling the
alignment signal from potentially compromised predictions-crucially, the result
holds even if the observed outcomes are sampled from the AI's own world model.
Building on this insight, we introduce Reinforcement Learning from Hindsight
Simulation (RLHS), which presents plausible simulated outcomes to evaluators
before eliciting feedback. We demonstrate RLHS on online (PPO) and offline
(DPO) large language model fine-tuning, obtaining superior alignment over RLHF
in controlled consultancy-type experiments and user studies. We evaluate
post-hoc on the TruthfulQA benchmark and find that, even after single-task
fine-tuning, both RLHF misalignment and RLHS alignment carry over to
substantially different settings.
