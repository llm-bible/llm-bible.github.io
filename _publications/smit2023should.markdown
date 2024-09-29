---
layout: publication
title: Should We Be Going MAD A Look At Multi45;agent Debate Strategies For Llms
authors: Smit Andries, Duckworth Paul, Grinsztajn Nathan, Barrett Thomas D., Pretorius Arnu
conference: "Arxiv"
year: 2023
bibkey: smit2023should
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.17371"}
tags: ['Agentic', 'Pretraining Methods', 'Prompting']
---
Recent advancements in large language models (LLMs) underscore their potential for responding to inquiries in various domains. However ensuring that generative agents provide accurate and reliable answers remains an ongoing challenge. In this context multi45;agent debate (MAD) has emerged as a promising strategy for enhancing the truthfulness of LLMs. We benchmark a range of debating and prompting strategies to explore the trade45;offs between cost time and accuracy. Importantly we find that multi45;agent debating systems in their current form do not reliably outperform other proposed prompting strategies such as self45;consistency and ensembling using multiple reasoning paths. However when performing hyperparameter tuning several MAD systems such as Multi45;Persona perform better. This suggests that MAD protocols might not be inherently worse than other approaches but that they are more sensitive to different hyperparameter settings and difficult to optimize. We build on these results to offer insights into improving debating strategies such as adjusting agent agreement levels which can significantly enhance performance and even surpass all other non45;debate protocols we evaluated. We provide an open45;source repository to the community with several state45;of45;the45;art protocols together with evaluation scripts to benchmark across popular research datasets.
