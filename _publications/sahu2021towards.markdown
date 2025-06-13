---
layout: publication
title: 'Towards Solving Multimodal Comprehension'
authors: Pritish Sahu, Karan Sikka, Ajay Divakaran
conference: "Arxiv"
year: 2021
bibkey: sahu2021towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2104.10139"}
tags: ['Ethics and Bias', 'Applications', 'RAG', 'Model Architecture', 'Attention Mechanism', 'Multimodal Models']
---
This paper targets the problem of procedural multimodal machine comprehension
(M3C). This task requires an AI to comprehend given steps of multimodal
instructions and then answer questions. Compared to vanilla machine
comprehension tasks where an AI is required only to understand a textual input,
procedural M3C is more challenging as the AI needs to comprehend both the
temporal and causal factors along with multimodal inputs. Recently Yagcioglu et
al. [35] introduced RecipeQA dataset to evaluate M3C. Our first contribution is
the introduction of two new M3C datasets- WoodworkQA and DecorationQA with 16K
and 10K instructional procedures, respectively. We then evaluate M3C using a
textual cloze style question-answering task and highlight an inherent bias in
the question answer generation method from [35] that enables a naive baseline
to cheat by learning from only answer choices. This naive baseline performs
similar to a popular method used in question answering- Impatient Reader [6]
that uses attention over both the context and the query. We hypothesized that
this naturally occurring bias present in the dataset affects even the best
performing model. We verify our proposed hypothesis and propose an algorithm
capable of modifying the given dataset to remove the bias elements. Finally, we
report our performance on the debiased dataset with several strong baselines.
We observe that the performance of all methods falls by a margin of 8% - 16%
after correcting for the bias. We hope these datasets and the analysis will
provide valuable benchmarks and encourage further research in this area.
