---
layout: publication
title: Large Language Models For Expansion Of Spoken Language Understanding Systems To New Languages
authors: Hoscilowicz Jakub, Pawlowski Pawel, Skorupa Marcin, Sowański Marcin, Janicki Artur
conference: "Arxiv"
year: 2024
bibkey: hoscilowicz2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.02588"}
tags: ['Applications', 'BERT', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Spoken Language Understanding (SLU) models are a core component of voice assistants (VA) such as Alexa Bixby and Google Assistant. In this paper we introduce a pipeline designed to extend SLU systems to new languages utilizing Large Language Models (LLMs) that we fine45;tune for machine translation of slot45;annotated SLU training data. Our approach improved on the MultiATIS++ benchmark a primary multi45;language SLU dataset in the cloud scenario using an mBERT model. Specifically we saw an improvement in the Overall Accuracy metric from 5337; to 62.1837; compared to the existing state45;of45;the45;art method Fine and Coarse45;grained Multi45;Task Learning Framework (FC45;MTLF). In the on45;device scenario (tiny and not pretrained SLU) our method improved the Overall Accuracy from 5.3137; to 22.0637; over the baseline Global45;Local Contrastive Learning Framework (GL45;CLeF) method. Contrary to both FC45;MTLF and GL45;CLeF our LLM45;based machine translation does not require changes in the production architecture of SLU. Additionally our pipeline is slot45;type independent it does not require any slot definitions or examples.
