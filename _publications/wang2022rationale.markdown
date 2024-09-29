---
layout: publication
title: Rationale45;augmented Ensembles In Language Models
authors: Xuezhi Wang, Jason Wei, Dale Schuurmans, Quoc Le, Ed Chi, Denny Zhou
conference: "Arxiv"
year: 2022
bibkey: wang2022rationale
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2207.00747v1"}
tags: ['Applications', 'Interpretability And Explainability', 'Merging', 'Prompting', 'RAG', 'Tools']
---
Recent research has shown that rationales or step45;by45;step chains of thought can be used to improve performance in multi45;step reasoning tasks. We reconsider rationale45;augmented prompting for few45;shot in45;context learning where (input 45; output) prompts are expanded to (input rationale 45; output) prompts. For rationale45;augmented prompting we demonstrate how existing approaches which rely on manual prompt engineering are subject to sub45;optimal rationales that may harm performance. To mitigate this brittleness we propose a unified framework of rationale45;augmented ensembles where we identify rationale sampling in the output space as the key component to robustly improve performance. This framework is general and can easily be extended to common natural language processing tasks even those that do not traditionally leverage intermediate steps such as question answering word sense disambiguation and sentiment analysis. We demonstrate that rationale45;augmented ensembles achieve more accurate and interpretable results than existing prompting approaches45;45;including standard prompting without rationales and rationale45;based chain45;of45;thought prompting45;45;while simultaneously improving interpretability of model predictions through the associated rationales.
