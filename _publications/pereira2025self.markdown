---
layout: publication
title: 'Self-res: Self-reflection In Large Vision-language Models For Long Video Understanding'
authors: Joao Pereira, Vasco Lopes, David Semedo, Joao Neves
conference: "Arxiv"
year: 2025
bibkey: pereira2025self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.20362"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'RAG', 'Prompting', 'Applications', 'Attention Mechanism']
---
Large Vision-Language Models (LVLMs) demonstrate remarkable performance in
short-video tasks such as video question answering, but struggle in long-video
understanding. The linear frame sampling strategy, conventionally used by
LVLMs, fails to account for the non-linear distribution of key events in video
data, often introducing redundant or irrelevant information in longer contexts
while risking the omission of critical events in shorter ones. To address this,
we propose SelfReS, a non-linear spatiotemporal self-reflective sampling method
that dynamically selects key video fragments based on user prompts. Unlike
prior approaches, SelfReS leverages the inherently sparse attention maps of
LVLMs to define reflection tokens, enabling relevance-aware token selection
without requiring additional training or external modules. Experiments
demonstrate that SelfReS can be seamlessly integrated into strong base LVLMs,
improving long-video task accuracy and achieving up to 46% faster inference
speed within the same GPU memory budget.
