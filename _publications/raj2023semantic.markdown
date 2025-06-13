---
layout: publication
title: 'Semantic Consistency For Assuring Reliability Of Large Language Models'
authors: Harsh Raj, Vipul Gupta, Domenic Rosati, Subhabrata Majumdar
conference: "Arxiv"
year: 2023
bibkey: raj2023semantic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.09138"}
tags: ['Prompting', 'Language Modeling', 'Applications', 'Reinforcement Learning']
---
Large Language Models (LLMs) exhibit remarkable fluency and competence across
various natural language tasks. However, recent research has highlighted their
sensitivity to variations in input prompts. To deploy LLMs in a safe and
reliable manner, it is crucial for their outputs to be consistent when prompted
with expressions that carry the same meaning or intent. While some existing
work has explored how state-of-the-art LLMs address this issue, their
evaluations have been confined to assessing lexical equality of single- or
multi-word answers, overlooking the consistency of generative text sequences.
For a more comprehensive understanding of the consistency of LLMs in open-ended
text generation scenarios, we introduce a general measure of semantic
consistency, and formulate multiple versions of this metric to evaluate the
performance of various LLMs. Our proposal demonstrates significantly higher
consistency and stronger correlation with human evaluations of output
consistency than traditional metrics based on lexical consistency. Finally, we
propose a novel prompting strategy, called Ask-to-Choose (A2C), to enhance
semantic consistency. When evaluated for closed-book question answering based
on answer variations from the TruthfulQA benchmark, A2C increases accuracy
metrics for pretrained and finetuned LLMs by up to 47%, and semantic
consistency metrics for instruction-tuned models by up to 7-fold.
