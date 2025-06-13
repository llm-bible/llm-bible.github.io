---
layout: publication
title: 'Evaluating Defences Against Unsafe Feedback In RLHF'
authors: Domenic Rosati, Giles Edkins, Harsh Raj, David Atanasov, Subhabrata Majumdar, Janarthanan Rajendran, Frank Rudzicz, Hassan Sajjad
conference: "Arxiv"
year: 2024
bibkey: rosati2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.12914"}
tags: ['Responsible AI', 'Agentic', 'Security', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Interpretability and Explainability']
---
While there has been progress towards aligning Large Language Models (LLMs)
with human values and ensuring safe behaviour at inference time, safety guards
can easily be removed when fine tuned on unsafe and harmful datasets. While
this setting has been treated extensively, another popular training paradigm,
learning from unsafe feedback with reinforcement learning, has previously been
unexplored. This is concerning due to the widespread deployment of feedback
collection systems. We address this gap by providing an analysis of learning
settings where feedback is harmful, i.e. that unsafe samples are preferred over
safe ones despite model developers goal to maintain safety. We find that
safety-aligned LLMs easily explore unsafe action spaces via generating harmful
text and optimize for reward that violates safety constraints indicating that
current safety guards are not enough to prevent learning from unsafe feedback.
In order to protect against this vulnerability, we adapt a number of both
"implict" and "explicit" harmful fine-tuning defences to evaluate whether they
are effective as learning constraints in an RLHF setting finding that no method
is generally effective pointing to the need for more defence research. We end
the paper with the observation that some defences work by performing "harmless
reward hacking" for which we provide a theoretical explanation drawn from the
theory of Constrained Markov Decision Processes and provide some direction for
future defence development.
