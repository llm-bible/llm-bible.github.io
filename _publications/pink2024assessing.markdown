---
layout: publication
title: 'Assessing Episodic Memory In Llms With Sequence Order Recall Tasks'
authors: Mathis Pink, Vy A. Vo, Qinyuan Wu, Jianing Mu, Javier S. Turek, Uri Hasson, Kenneth A. Norman, Sebastian Michelmann, Alexander Huth, Mariya Toneva
conference: "Arxiv"
year: 2024
bibkey: pink2024assessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.08133"}
tags: ['Tools', 'Training Techniques', 'Merging']
---
Current LLM benchmarks focus on evaluating models' memory of facts and
semantic relations, primarily assessing semantic aspects of long-term memory.
However, in humans, long-term memory also includes episodic memory, which links
memories to their contexts, such as the time and place they occurred. The
ability to contextualize memories is crucial for many cognitive tasks and
everyday functions. This form of memory has not been evaluated in LLMs with
existing benchmarks. To address the gap in evaluating memory in LLMs, we
introduce Sequence Order Recall Tasks (SORT), which we adapt from tasks used to
study episodic memory in cognitive psychology. SORT requires LLMs to recall the
correct order of text segments, and provides a general framework that is both
easily extendable and does not require any additional annotations. We present
an initial evaluation dataset, Book-SORT, comprising 36k pairs of segments
extracted from 9 books recently added to the public domain. Based on a human
experiment with 155 participants, we show that humans can recall sequence order
based on long-term memory of a book. We find that models can perform the task
with high accuracy when relevant text is given in-context during the SORT
evaluation. However, when presented with the book text only during training,
LLMs' performance on SORT falls short. By allowing to evaluate more aspects of
memory, we believe that SORT will aid in the emerging development of
memory-augmented models.
