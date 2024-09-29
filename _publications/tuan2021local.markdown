---
layout: publication
title: Local Explanation Of Dialogue Response Generation
authors: Tuan Yi-lin, Pryor Connor, Chen Wenhu, Getoor Lise, Wang William Yang
conference: "Arxiv"
year: 2021
bibkey: tuan2021local
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.06528"}
tags: ['Applications', 'Attention Mechanism', 'Ethics And Bias', 'Interpretability And Explainability', 'Language Modeling', 'Model Architecture']
---
In comparison to the interpretation of classification models the explanation of sequence generation models is also an important problem however it has seen little attention. In this work we study model-agnostic explanations of a representative text generation task -- dialogue response generation. Dialog response generation is challenging with its open-ended sentences and multiple acceptable responses. To gain insights into the reasoning process of a generation model we propose a new method local explanation of response generation (LERG) that regards the explanations as the mutual interaction of segments in input and output sentences. LERG views the sequence prediction as uncertainty estimation of a human response and then creates explanations by perturbing the input and calculating the certainty change over the human response. We show that LERG adheres to desired properties of explanations for text generation including unbiased approximation consistency and cause identification. Empirically our results show that our method consistently improves other widely used methods on proposed automatic- and human- evaluation metrics for this new task by 4.4-12.837;. Our analysis demonstrates that LERG can extract both explicit and implicit relations between input and output segments.
