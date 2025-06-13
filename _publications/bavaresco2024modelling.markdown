---
layout: publication
title: 'Modelling Multimodal Integration In Human Concept Processing With Vision-language Models'
authors: Anna Bavaresco, Marianne De Heer Kloots, Sandro Pezzelle, Raquel Fernández
conference: "Arxiv"
year: 2024
bibkey: bavaresco2024modelling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.17914"}
tags: ['Transformer', 'GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'BERT', 'Multimodal Models']
---
Text representations from language models have proven remarkably predictive
of human neural activity involved in language processing, with the recent
transformer-based models outperforming previous architectures in downstream
tasks and prediction of brain responses. However, the word representations
learnt by language-only models may be limited in that they lack sensory
information from other modalities, which several cognitive and neuroscience
studies showed to be reflected in human meaning representations. Here, we
leverage current pre-trained vision-language models (VLMs) to investigate
whether the integration of visuo-linguistic information they operate leads to
representations that are more aligned with human brain activity than those
obtained by models trained with language-only input. We focus on fMRI responses
recorded while participants read concept words in the context of either a full
sentence or a picture. Our results reveal that VLM representations correlate
more strongly than those by language-only models with activations in brain
areas functionally related to language processing. Additionally, we find that
transformer-based vision-language encoders -- e.g., LXMERT and VisualBERT --
yield more brain-aligned representations than generative VLMs, whose
autoregressive abilities do not seem to provide an advantage when modelling
single words. Finally, our ablation analyses suggest that the high brain
alignment achieved by some of the VLMs we evaluate results from semantic
information acquired specifically during multimodal pretraining as opposed to
being already encoded in their unimodal modules. Altogether, our findings
indicate an advantage of multimodal models in predicting human brain
activations, which reveals that modelling language and vision integration has
the potential to capture the multimodal nature of human concept
representations.
