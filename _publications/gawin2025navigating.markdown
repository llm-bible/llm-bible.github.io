---
layout: publication
title: 'Navigating Semantic Relations: Challenges For Language Models In Abstract Common-sense Reasoning'
authors: Cole Gawin, Yidan Sun, Mayank Kejriwal
conference: "Arxiv"
year: 2025
bibkey: gawin2025navigating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.14086'}
tags: ['Few-Shot', 'GPT', 'Applications', 'Model Architecture', 'Prompting', 'Ethics and Bias', 'In-Context Learning']
---
Large language models (LLMs) have achieved remarkable performance in
generating human-like text and solving reasoning tasks of moderate complexity,
such as question-answering and mathematical problem-solving. However, their
capabilities in tasks requiring deeper cognitive skills, such as common-sense
understanding and abstract reasoning, remain under-explored. In this paper, we
systematically evaluate abstract common-sense reasoning in LLMs using the
ConceptNet knowledge graph. We propose two prompting approaches: instruct
prompting, where models predict plausible semantic relationships based on
provided definitions, and few-shot prompting, where models identify relations
using examples as guidance. Our experiments with the gpt-4o-mini model show
that in instruct prompting, consistent performance is obtained when ranking
multiple relations but with substantial decline when the model is restricted to
predicting only one relation. In few-shot prompting, the model's accuracy
improves significantly when selecting from five relations rather than the full
set, although with notable bias toward certain relations. These results suggest
significant gaps still, even in commercially used LLMs' abstract common-sense
reasoning abilities, compared to human-level understanding. However, the
findings also highlight the promise of careful prompt engineering, based on
selective retrieval, for obtaining better performance.
