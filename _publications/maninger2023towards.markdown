---
layout: publication
title: 'Towards Trustworthy AI Software Development Assistance'
authors: Daniel Maninger, Krishna Narasimhan, Mira Mezini
conference: "Arxiv"
year: 2023
bibkey: maninger2023towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2312.09126'}
tags: ['Interpretability and Explainability', 'Security', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning']
---
It is expected that in the near future, AI software development assistants
will play an important role in the software industry. However, current software
development assistants tend to be unreliable, often producing incorrect,
unsafe, or low-quality code. We seek to resolve these issues by introducing a
holistic architecture for constructing, training, and using trustworthy AI
software development assistants. In the center of the architecture, there is a
foundational LLM trained on datasets representative of real-world coding
scenarios and complex software architectures, and fine-tuned on code quality
criteria beyond correctness. The LLM will make use of graph-based code
representations for advanced semantic comprehension. We envision a knowledge
graph integrated into the system to provide up-to-date background knowledge and
to enable the assistant to provide appropriate explanations. Finally, a modular
framework for constrained decoding will ensure that certain guarantees (e.g.,
for correctness and security) hold for the generated code.
