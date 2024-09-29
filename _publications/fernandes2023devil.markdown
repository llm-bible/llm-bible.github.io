---
layout: publication
title: The Devil Is In The Errors Leveraging Large Language Models For Fine45;grained Machine Translation Evaluation
authors: Fernandes Patrick, Deutsch Daniel, Finkelstein Mara, Riley Parker, Martins André F. T., Neubig Graham, Garg Ankush, Clark Jonathan H., Freitag Markus, Firat Orhan
conference: "Arxiv"
year: 2023
bibkey: fernandes2023devil
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.07286"}
tags: ['Applications', 'Interpretability And Explainability', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
Automatic evaluation of machine translation (MT) is a critical tool driving the rapid iterative development of MT systems. While considerable progress has been made on estimating a single scalar quality score current metrics lack the informativeness of more detailed schemes that annotate individual errors such as Multidimensional Quality Metrics (MQM). In this paper we help fill this gap by proposing AutoMQM a prompting technique which leverages the reasoning and in45;context learning capabilities of large language models (LLMs) and asks them to identify and categorize errors in translations. We start by evaluating recent LLMs such as PaLM and PaLM45;2 through simple score prediction prompting and we study the impact of labeled data through in45;context learning and finetuning. We then evaluate AutoMQM with PaLM45;2 models and we find that it improves performance compared to just prompting for scores (with particularly large gains for larger models) while providing interpretability through error spans that align with human annotations.
