---
layout: publication
title: 'A Mechanistic Interpretation Of Syllogistic Reasoning In Auto-regressive Language Models'
authors: Kim Geonhee, Valentino Marco, Freitas André
conference: "Arxiv"
year: 2024
bibkey: kim2024mechanistic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.08590"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Recent studies on logical reasoning in auto-regressive Language Models (LMs)
have sparked a debate on whether such models can learn systematic reasoning
principles during pre-training or merely exploit superficial patterns in the
training data. This paper presents a mechanistic interpretation of syllogistic
reasoning in LMs to further enhance our understanding of internal dynamics.
Specifically, we present a methodology for circuit discovery aimed at
disentangling content-independent reasoning mechanisms from world knowledge
acquired during pre-training. Through two distinct intervention methods, we
uncover a sufficient and necessary circuit involving middle-term suppression
that elucidates how LMs transfer information to derive valid conclusions from
premises. Furthermore, we investigate how belief biases manifest in syllogistic
reasoning, finding evidence of partial contamination from additional attention
heads responsible for encoding commonsense and contextualized knowledge.
Finally, we explore the generalization of the discovered mechanisms across
various syllogistic schemes and model sizes, finding that the identified
circuit is sufficient and necessary for all the schemes on which the model
achieves high downstream accuracy (\\(\geq\\) 60\%). Overall, our findings suggest
that LMs indeed learn transferable content-independent reasoning mechanisms,
but that, at the same time, such mechanisms do not involve generalisable and
abstract logical primitives, being susceptible to contamination by the same
world knowledge acquired during pre-training.
