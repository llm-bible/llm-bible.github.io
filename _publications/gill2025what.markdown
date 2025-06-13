---
layout: publication
title: 'What Has Been Lost With Synthetic Evaluation?'
authors: Alexander Gill, Abhilasha Ravichander, Ana Marasović
conference: "Arxiv"
year: 2025
bibkey: gill2025what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.22830"}
tags: ['Prompting', 'Merging']
---
Large language models (LLMs) are increasingly used for data generation. However, creating evaluation benchmarks raises the bar for this emerging paradigm. Benchmarks must target specific phenomena, penalize exploiting shortcuts, and be challenging. Through two case studies, we investigate whether LLMs can meet these demands by generating reasoning over-text benchmarks and comparing them to those created through careful crowdsourcing. Specifically, we evaluate both the validity and difficulty of LLM-generated versions of two high-quality reading comprehension datasets: CondaQA, which evaluates reasoning about negation, and DROP, which targets reasoning about quantities. We find that prompting LLMs can produce variants of these datasets that are often valid according to the annotation guidelines, at a fraction of the cost of the original crowdsourcing effort. However, we show that they are less challenging for LLMs than their human-authored counterparts. This finding sheds light on what may have been lost by generating evaluation data with LLMs, and calls for critically reassessing the immediate use of this increasingly prevalent approach to benchmark creation.
