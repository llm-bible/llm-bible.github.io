---
layout: publication
title: 'Socio-emotional Response Generation: A Human Evaluation Protocol For Llm-based Conversational Systems'
authors: Lorraine Ids, S2a, Ltci Vanel, Ariel R. Ramos Ids, S2a, Ltci Vela, Alya Ids, S2a, Ltci Yacoubi, Chloé Ids, S2a, Ltci Clavel
conference: "AHRI 2024 Sep 2024 Glasgow United Kingdom"
year: 2024
bibkey: vanel2024socio
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.04492"}
tags: ['Tools', 'Applications', 'Ethics and Bias', 'Model Architecture', 'Reinforcement Learning', 'Interpretability']
---
Conversational systems are now capable of producing impressive and generally
relevant responses. However, we have no visibility nor control of the
socio-emotional strategies behind state-of-the-art Large Language Models
(LLMs), which poses a problem in terms of their transparency and thus their
trustworthiness for critical applications. Another issue is that current
automated metrics are not able to properly evaluate the quality of generated
responses beyond the dataset's ground truth. In this paper, we propose a neural
architecture that includes an intermediate step in planning socio-emotional
strategies before response generation. We compare the performance of
open-source baseline LLMs to the outputs of these same models augmented with
our planning module. We also contrast the outputs obtained from automated
metrics and evaluation results provided by human annotators. We describe a
novel evaluation protocol that includes a coarse-grained consistency
evaluation, as well as a finer-grained annotation of the responses on various
social and emotional criteria. Our study shows that predicting a sequence of
expected strategy labels and using this sequence to generate a response yields
better results than a direct end-to-end generation scheme. It also highlights
the divergences and the limits of current evaluation metrics for generated
content. The code for the annotation platform and the annotated data are made
publicly available for the evaluation of future models.
