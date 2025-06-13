---
layout: publication
title: 'Exploring Explainable Selection To Control Abstractive Summarization'
authors: Wang Haonan, Gao Yang, Bai Yu, Mirella Lapata, Huang Heyan
conference: "Arxiv"
year: 2020
bibkey: haonan2020exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2004.11779"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Interpretability', 'BERT', 'Transformer', 'Interpretability and Explainability', 'Applications', 'Attention Mechanism']
---
Like humans, document summarization models can interpret a document's
contents in a number of ways. Unfortunately, the neural models of today are
largely black boxes that provide little explanation of how or why they
generated a summary in the way they did. Therefore, to begin prying open the
black box and to inject a level of control into the substance of the final
summary, we developed a novel select-and-generate framework that focuses on
explainability. By revealing the latent centrality and interactions between
sentences, along with scores for sentence novelty and relevance, users are
given a window into the choices a model is making and an opportunity to guide
those choices in a more desirable direction. A novel pair-wise matrix captures
the sentence interactions, centrality, and attribute scores, and a mask with
tunable attribute thresholds allows the user to control which sentences are
likely to be included in the extraction. A sentence-deployed attention
mechanism in the abstractor ensures the final summary emphasizes the desired
content. Additionally, the encoder is adaptable, supporting both Transformer-
and BERT-based configurations. In a series of experiments assessed with ROUGE
metrics and two human evaluations, ESCA outperformed eight state-of-the-art
models on the CNN/DailyMail and NYT50 benchmark datasets.
