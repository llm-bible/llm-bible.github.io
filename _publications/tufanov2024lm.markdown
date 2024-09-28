---
layout: publication
title: LM Transparency Tool Interactive Tool for Analyzing Transformer Language Models
authors: Tufanov Igor, Hambardzumyan Karen, Ferrando Javier, Voita Elena
conference: "Arxiv"
year: 2024
bibkey: tufanov2024lm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.07004"}
tags: ['ARXIV', 'Attention Mechanism', 'Explainability', 'Interpretability', 'Reinforcement Learning', 'Tools', 'Transformer']
---
We present the LM Transparency Tool (LM-TT) an open-source interactive toolkit for analyzing the internal workings of Transformer-based language models. Differently from previously existing tools that focus on isolated parts of the decision-making process our framework is designed to make the entire prediction process transparent and allows tracing back model behavior from the top-layer representation to very fine-grained parts of the model. Specifically it (1) shows the important part of the whole input-to-output information flow (2) allows attributing any changes done by a model block to individual attention heads and feed-forward neurons (3) allows interpreting the functions of those heads or neurons. A crucial part of this pipeline is showing the importance of specific model components at each step. As a result we are able to look at the roles of model components only in cases where they are important for a prediction. Since knowing which components should be inspected is key for analyzing large models where the number of these components is extremely high we believe our tool will greatly support the interpretability community both in research settings and in practical applications.
