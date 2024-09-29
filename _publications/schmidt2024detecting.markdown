---
layout: publication
title: "Detecting Generated Native Ads In Conversational Search"
authors: Schmidt Sebastian, Zelch Ines, Bevendorff Janek, Stein Benno, Hagen Matthias, Potthast Martin
conference: "Arxiv"
year: 2024
bibkey: schmidt2024detecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.04889"}
tags: ['Model Architecture', 'Pretraining Methods', 'Transformer']
---
Conversational search engines such as YouChat and Microsoft Copilot use large language models (LLMs) to generate responses to queries. It is only a small step to also let the same technology insert ads within the generated responses - instead of separately placing ads next to a response. Inserted ads would be reminiscent of native advertising and product placement both of which are very effective forms of subtle and manipulative advertising. Considering the high computational costs associated with LLMs for which providers need to develop sustainable business models users of conversational search engines may very well be confronted with generated native ads in the near future. In this paper we thus take a first step to investigate whether LLMs can also be used as a countermeasure i.e. to block generated native ads. We compile the Webis Generated Native Ads 2024 dataset of queries and generated responses with automatically inserted ads and evaluate whether LLMs or fine-tuned sentence transformers can detect the ads. In our experiments the investigated LLMs struggle with the task but sentence transformers achieve precision and recall values above 0.9.
