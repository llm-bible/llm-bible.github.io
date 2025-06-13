---
layout: publication
title: 'Untying The Reversal Curse Via Bidirectional Language Model Editing'
authors: Jun-yu Ma, Jia-chen Gu, Zhen-hua Ling, Quan Liu, Cong Liu
conference: "Arxiv"
year: 2023
bibkey: ma2023untying
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.10322'}
tags: ['Training Techniques', 'Applications', 'Tools']
---
Recent studies have demonstrated that large language models (LLMs) store
massive factual knowledge within their parameters. But existing LLMs are prone
to hallucinate unintended text due to false or outdated knowledge. Since
retraining LLMs is resource intensive, there has been a growing interest in the
concept of model editing. Despite the emergence of benchmarks and approaches,
these unidirectional editing and evaluation have failed to explore the reversal
curse. Intuitively, if "The capital of France is" is edited to be a counterfact
"London" within a model, then it should be able to naturally reason and recall
the reverse fact, i.e., "London is the capital of" followed by "France" instead
of "England". In this paper, we study bidirectional language model editing,
aiming to provide rigorous model editing evaluation to assess if edited LLMs
can recall the editing knowledge bidirectionally. A new evaluation metric of
reversibility is introduced, and a benchmark dubbed as Bidirectional Assessment
for Knowledge Editing (BAKE) is constructed to evaluate the reversibility of
edited models in recalling knowledge in the reverse direction of editing. We
surprisingly observe that while current editing methods and LLMs can
effectively recall editing facts in the direction of editing, they suffer
serious deficiencies when evaluated in the reverse direction. To mitigate the
reversal curse, a method named Bidirectionally Inversible Relationship moDeling
(BIRD) is proposed. A set of editing objectives that incorporate bidirectional
relationships between subject and object into the updated model weights are
designed. Experiments show that BIRD improves the performance of four
representative LLMs of different sizes via question answering and judgement.
