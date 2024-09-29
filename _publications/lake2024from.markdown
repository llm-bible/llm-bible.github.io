---
layout: publication
title: From Distributional To Overton Pluralism Investigating Large Language Model Alignment
authors: Lake Thom, Choi Eunsol, Durrett Greg
conference: "Arxiv"
year: 2024
bibkey: lake2024from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.17692"}
  - {name: "Code", url: "https://github.com/thomlake/investigating&#45;alignment"}
tags: ['Has Code', 'Pretraining Methods', 'Reinforcement Learning']
---
The alignment process changes several properties of a large language models (LLMs) output distribution. We analyze two aspects of post45;alignment distributional shift of LLM responses. First we re45;examine previously reported reductions in response diversity post45;alignment. Our analysis suggests that an apparent drop in the diversity of responses is largely explained by quality control and information aggregation. Alignment suppresses irrelevant and unhelpful content while shifting the output distribution toward longer responses that cover information spanning several responses from the base LLM essentially presenting diverse information in a single response. Finding little evidence that alignment suppresses useful information it is natural to ask the opposite question do aligned models surface information that cannot be recovered from base models Our second investigation shows this is not the case and the behavior of aligned models is recoverable from base models without fine45;tuning. A combination of in45;context examples and lower45;resolution semantic hints about response content can elicit responses from base LLMs that are as similar to alignment45;tuned LLM responses as alignment45;tuned LLM responses are to each other. Taken together these results indicate that current alignment techniques capture but do not extend the useful subset of assistant45;like base LLM behavior providing further evidence for the Superficial Alignment Hypothesis. They also show that in45;context alignment can go surprisingly far as a strategy for imitating aligned LLMs without fine45;tuning. Our code and data is available at https://github.com/thomlake/investigating&#45;alignment.
