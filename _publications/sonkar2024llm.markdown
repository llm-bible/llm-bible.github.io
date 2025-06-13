---
layout: publication
title: 'Llm-based Cognitive Models Of Students With Misconceptions'
authors: Shashank Sonkar, Xinghe Chen, Naiming Liu, Richard G. Baraniuk, Mrinmaya Sachan
conference: "Arxiv"
year: 2024
bibkey: sonkar2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12294"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning']
---
Accurately modeling student cognition is crucial for developing effective
AI-driven educational technologies. A key challenge is creating realistic
student models that satisfy two essential properties: (1) accurately
replicating specific misconceptions, and (2) correctly solving problems where
these misconceptions are not applicable. This dual requirement reflects the
complex nature of student understanding, where misconceptions coexist with
correct knowledge. This paper investigates whether Large Language Models (LLMs)
can be instruction-tuned to meet this dual requirement and effectively simulate
student thinking in algebra. We introduce MalAlgoPy, a novel Python library
that generates datasets reflecting authentic student solution patterns through
a graph-based representation of algebraic problem-solving. Utilizing MalAlgoPy,
we define and examine Cognitive Student Models (CSMs) - LLMs instruction tuned
to faithfully emulate realistic student behavior. Our findings reveal that LLMs
trained on misconception examples can efficiently learn to replicate errors.
However, the training diminishes the model's ability to solve problems
correctly, particularly for problem types where the misconceptions are not
applicable, thus failing to satisfy second property of CSMs. We demonstrate
that by carefully calibrating the ratio of correct to misconception examples in
the training data - sometimes as low as 0.25 - it is possible to develop CSMs
that satisfy both properties. Our insights enhance our understanding of
AI-based student models and pave the way for effective adaptive learning
systems.
