---
layout: publication
title: 'Soft Token Attacks Cannot Reliably Audit Unlearning In Large Language Models'
authors: Haokun Chen, Sebastian Szyller, Weilin Xu, Nageen Himayat
conference: "Arxiv"
year: 2025
bibkey: chen2025soft
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.15836"}
tags: ['Security', 'Training Techniques', 'Tools']
---
Large language models (LLMs) have become increasingly popular. Their emergent
capabilities can be attributed to their massive training datasets. However,
these datasets often contain undesirable or inappropriate content, e.g.,
harmful texts, personal information, and copyrighted material. This has
promoted research into machine unlearning that aims to remove information from
trained models. In particular, approximate unlearning seeks to achieve
information removal by strategically editing the model rather than complete
model retraining.
  Recent work has shown that soft token attacks (STA) can successfully extract
purportedly unlearned information from LLMs, thereby exposing limitations in
current unlearning methodologies. In this work, we reveal that STAs are an
inadequate tool for auditing unlearning. Through systematic evaluation on
common unlearning benchmarks (Who Is Harry Potter? and TOFU), we demonstrate
that such attacks can elicit any information from the LLM, regardless of (1)
the deployed unlearning algorithm, and (2) whether the queried content was
originally present in the training corpus. Furthermore, we show that STA with
just a few soft tokens (1-10) can elicit random strings over 400-characters
long. Thus showing that STAs are too powerful, and misrepresent the
effectiveness of the unlearning methods.
  Our work highlights the need for better evaluation baselines, and more
appropriate auditing tools for assessing the effectiveness of unlearning in
LLMs.
