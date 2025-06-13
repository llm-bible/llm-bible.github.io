---
layout: publication
title: 'What Matters For In-context Learning: A Balancing Act Of Look-up And In-weight Learning'
authors: Jelena Bratulić, Sudhanshu Mittal, Christian Rupprecht, Thomas Brox
conference: "Arxiv"
year: 2025
bibkey: bratulić2025what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.06256"}
tags: ['GPT', 'Model Architecture', 'Language Modeling', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Large Language Models (LLMs) have demonstrated impressive performance in
various tasks, including In-Context Learning (ICL), where the model performs
new tasks by conditioning solely on the examples provided in the context,
without updating the model's weights. While prior research has explored the
roles of pretraining data and model architecture, the key mechanism behind ICL
remains unclear. In this work, we systematically uncover properties present in
LLMs that support the emergence of ICL. To disambiguate these factors, we
conduct a study with a controlled dataset and data sequences using a deep
autoregressive model. We show that conceptual repetitions in the data sequences
are crucial for ICL, more so than previously indicated training data properties
like burstiness or long-tail distribution. Conceptual repetitions could refer
to \\(n\\)-gram repetitions in textual data or exact image copies in image sequence
data. Such repetitions also offer other previously overlooked benefits such as
reduced transiency in ICL performance. Furthermore, we show that the emergence
of ICL depends on balancing the in-weight learning objective with the
in-context solving ability during training.
