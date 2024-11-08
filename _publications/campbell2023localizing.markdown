---
layout: publication
title: 'Localizing Lying In Llama: Understanding Instructed Dishonesty On True-false Questions Through Prompting, Probing, And Patching'
authors: Campbell James, Ren Richard, Guo Phillip
conference: "Arxiv"
year: 2023
bibkey: campbell2023localizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.15131"}
tags: ['Attention Mechanism', 'Interpretability And Explainability', 'Model Architecture', 'Prompting']
---
Large language models (LLMs) demonstrate significant knowledge through their
outputs, though it is often unclear whether false outputs are due to a lack of
knowledge or dishonesty. In this paper, we investigate instructed dishonesty,
wherein we explicitly prompt LLaMA-2-70b-chat to lie. We perform prompt
engineering to find which prompts best induce lying behavior, and then use
mechanistic interpretability approaches to localize where in the network this
behavior occurs. Using linear probing and activation patching, we localize five
layers that appear especially important for lying. We then find just 46
attention heads within these layers that enable us to causally intervene such
that the lying model instead answers honestly. We show that these interventions
work robustly across many prompts and dataset splits. Overall, our work
contributes a greater understanding of dishonesty in LLMs so that we may hope
to prevent it.
