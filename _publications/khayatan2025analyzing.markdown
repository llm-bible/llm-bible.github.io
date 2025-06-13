---
layout: publication
title: 'Analyzing Fine-tuning Representation Shift For Multimodal Llms Steering Alignment'
authors: Pegah Khayatan, Mustafa Shukor, Jayneel Parekh, Matthieu Cord
conference: "Arxiv"
year: 2025
bibkey: khayatan2025analyzing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.03012"}
  - {name: "Code", url: "https://github.com/mshukor/xl-vlms"}
tags: ['Fine-Tuning', 'Ethics and Bias', 'Interpretability and Explainability', 'Model Architecture', 'Reinforcement Learning', 'Interpretability', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods', 'Multimodal Models']
---
Multimodal LLMs have reached remarkable levels of proficiency in
understanding multimodal inputs, driving extensive research to develop
increasingly powerful models. However, much less attention has been paid to
understanding and explaining the underlying mechanisms of these models. Most
existing explainability research examines these models only in their final
states, overlooking the dynamic representational shifts that occur during
training. In this work, we systematically analyze the evolution of hidden state
representations to reveal how fine-tuning alters the internal structure of a
model to specialize in new multimodal tasks. Using a concept-based approach, we
map hidden states to interpretable visual and textual concepts, enabling us to
trace changes in encoded concepts across modalities as training progresses. We
also demonstrate the use of shift vectors to capture these concepts changes.
These shift vectors allow us to recover fine-tuned concepts by shifting those
in the original model. Finally, we explore the practical impact of our findings
on model steering, showing that we can adjust multimodal LLMs behaviors without
any training, such as modifying answer types, captions style, or biasing the
model toward specific responses. Our work sheds light on how multimodal
representations evolve through fine-tuning and offers a new perspective for
interpreting model adaptation in multimodal tasks. The code for this project is
publicly available at https://github.com/mshukor/xl-vlms.
