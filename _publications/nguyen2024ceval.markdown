---
layout: publication
title: Ceval A Benchmark For Evaluating Counterfactual Text Generation
authors: Nguyen Van Bach, Schlötterer Jörg, Seifert Christin
conference: "INLG"
year: 2024
bibkey: nguyen2024ceval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.17475"}
tags: ['Applications', 'Language Modeling', 'Prompting', 'RAG', 'Tools']
---
Counterfactual text generation aims to minimally change a text such that it is classified differently. Judging advancements in method development for counterfactual text generation is hindered by a non-uniform usage of data sets and metrics in related work. We propose CEval a benchmark for comparing counterfactual text generation methods. CEval unifies counterfactual and text quality metrics includes common counterfactual datasets with human annotations standard baselines (MICE GDBA CREST) and the open-source language model LLAMA-2. Our experiments found no perfect method for generating counterfactual text. Methods that excel at counterfactual metrics often produce lower-quality text while LLMs with simple prompts generate high-quality text but struggle with counterfactual criteria. By making CEval available as an open-source Python library we encourage the community to contribute more methods and maintain consistent evaluation in future work.
