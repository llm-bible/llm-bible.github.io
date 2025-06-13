---
layout: publication
title: 'Assessing Language Comprehension In Large Language Models Using Construction Grammar'
authors: Wesley Scivetti, Melissa Torgbi, Austin Blodgett, Mollie Shichman, Taylor Hudson, Claire Bonial, Harish Tayyar Madabushi
conference: "Arxiv"
year: 2025
bibkey: scivetti2025assessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.04661"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Prompting', 'Pre-Training', 'Applications']
---
Large Language Models, despite their significant capabilities, are known to
fail in surprising and unpredictable ways. Evaluating their true
`understanding' of language is particularly challenging due to the extensive
web-scale data they are trained on. Therefore, we construct an evaluation to
systematically assess natural language understanding (NLU) in LLMs by
leveraging Construction Grammar (CxG), which provides insights into the meaning
captured by linguistic elements known as constructions (Cxns). CxG is
well-suited for this purpose because provides a theoretical basis to construct
targeted evaluation sets. These datasets are carefully constructed to include
examples which are unlikely to appear in pre-training data, yet intuitive and
easy for humans to understand, enabling a more targeted and reliable
assessment. Our experiments focus on downstream natural language inference and
reasoning tasks by comparing LLMs' understanding of the underlying meanings
communicated through 8 unique Cxns with that of humans. The results show that
while LLMs demonstrate some knowledge of constructional information, even the
latest models including GPT-o1 struggle with abstract meanings conveyed by
these Cxns, as demonstrated in cases where test sentences are dissimilar to
their pre-training data. We argue that such cases provide a more accurate test
of true language understanding, highlighting key limitations in LLMs' semantic
capabilities. We make our novel dataset and associated experimental data
including prompts and model responses publicly available.
