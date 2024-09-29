---
layout: publication
title: Improving Long Context Document-level Machine Translation
authors: Herold Christian, Ney Hermann
conference: "Arxiv"
year: 2023
bibkey: herold2023improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.05183"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Transformer']
---
Document-level context for neural machine translation (NMT) is crucial to improve the translation consistency and cohesion the translation of ambiguous inputs as well as several other linguistic phenomena. Many works have been published on the topic of document-level NMT but most restrict the system to only local context typically including just the one or two preceding sentences as additional information. This might be enough to resolve some ambiguous inputs but it is probably not sufficient to capture some document-level information like the topic or style of a conversation. When increasing the context size beyond just the local context there are two challenges (i) the~memory usage increases exponentially (ii) the translation performance starts to degrade. We argue that the widely-used attention mechanism is responsible for both issues. Therefore we propose a constrained attention variant that focuses the attention on the most relevant parts of the sequence while simultaneously reducing the memory consumption. For evaluation we utilize targeted test sets in combination with novel evaluation techniques to analyze the translations in regards to specific discourse-related phenomena. We find that our approach is a good compromise between sentence-level NMT vs attending to the full context especially in low resource scenarios.
