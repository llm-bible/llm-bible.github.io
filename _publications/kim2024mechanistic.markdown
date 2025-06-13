---
layout: publication
title: 'A Mechanistic Interpretation Of Syllogistic Reasoning In Auto-regressive Language Models'
authors: Geonhee Kim, Marco Valentino, André Freitas
conference: "Arxiv"
year: 2024
bibkey: kim2024mechanistic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.08590"}
tags: ['Pre-Training', 'Ethics and Bias', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism']
---
Recent studies on logical reasoning in Language Models (LMs) have sparked a
debate on whether they can learn systematic reasoning principles during
pre-training or merely exploit superficial patterns in the training data. This
paper presents a mechanistic interpretation of syllogistic reasoning in LMs to
advance the understanding of internal dynamics. Specifically, we present a
methodology for circuit discovery aimed at interpreting content-independent
reasoning mechanisms. Through two distinct intervention methods, we uncover a
sufficient and necessary circuit involving middle-term suppression that
elucidates how LMs transfer information to derive valid conclusions from
premises. Furthermore, we investigate how belief biases manifest in syllogistic
reasoning, finding evidence of partial contamination from additional attention
heads responsible for encoding commonsense and contextualized knowledge.
Finally, we explore the generalization of the discovered mechanisms across
various syllogistic schemes, model sizes and architectures, finding that the
identified circuit is sufficient and necessary for the schemes on which the
models achieve high downstream accuracy (> 60%), and that the activation
patterns apply to models of different families. Overall, our findings suggest
that LMs indeed learn transferable content-independent reasoning mechanisms,
but that, at the same time, such mechanisms do not involve generalizable and
abstract logical primitives, being susceptible to contamination by the same
world knowledge acquired during pre-training.
