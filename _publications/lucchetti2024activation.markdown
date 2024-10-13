---
layout: publication
title: 'Activation Steering For Robust Type Prediction In Codellms'
authors: Lucchetti Francesca, Guha Arjun
conference: "Arxiv"
year: 2024
bibkey: lucchetti2024activation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.01903"}
tags: ['Uncategorized']
---
Contemporary LLMs pretrained on code are capable of succeeding at a wide
variety of programming tasks. However, their performance is very sensitive to
syntactic features, such as the names of variables and types, the structure of
code, and presence of type hints. We contribute an inference-time technique to
make CodeLLMs more robust to syntactic distractors that are semantically
irrelevant. Our methodology relies on activation steering, which involves
editing internal model activations to steer the model towards the correct
prediction. We contribute a novel way to construct steering vectors by taking
inspiration from mutation testing, which constructs minimal semantics-breaking
code edits. In contrast, we construct steering vectors from
semantics-preserving code edits. We apply our approach to the task of type
prediction for the gradually typed languages Python and TypeScript. This
approach corrects up to 90% of type mispredictions. Finally, we show that
steering vectors calculated from Python activations reliably correct type
mispredictions in TypeScript, and vice versa. This result suggests that LLMs
may be learning to transfer knowledge of types across programming languages.
