---
layout: publication
title: 'Graph Guided Question Answer Generation For Procedural Question-answering'
authors: Pham Hai X., Hadji Isma, Xu Xinnuo, Degutyte Ziedune, Rainey Jay, Kazakos Evangelos, Fazly Afsaneh, Tzimiropoulos Georgios, Martinez Brais
conference: "Arxiv"
year: 2024
bibkey: pham2024graph
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.13594"}
tags: ['Applications', 'GPT', 'Model Architecture', 'RAG', 'Training Techniques']
---
'In this paper, we focus on task-specific question answering (QA). To this end, we introduce a method for generating exhaustive and high-quality training data, which allows us to train compact (e.g., run on a mobile device), task-specific QA models that are competitive against GPT variants. The key technological enabler is a novel mechanism for automatic question-answer generation from procedural text which can ingest large amounts of textual instructions and produce exhaustive in-domain QA training data. While current QA data generation methods can produce well-formed and varied data, their non-exhaustive nature is sub-optimal for training a QA model. In contrast, we leverage the highly structured aspect of procedural text and represent each step and the overall flow of the procedure as graphs. We then condition on graph nodes to automatically generate QA pairs in an exhaustive and controllable manner. Comprehensive evaluations of our method show that: 1) small models trained with our data achieve excellent performance on the target QA task, even exceeding that of GPT3 and ChatGPT despite being several orders of magnitude smaller. 2) semantic coverage is the key indicator for downstream QA performance. Crucially, while large language models excel at syntactic diversity, this does not necessarily result in improvements on the end QA model. In contrast, the higher semantic coverage provided by our method is critical for QA performance.'
