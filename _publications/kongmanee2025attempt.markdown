---
layout: publication
title: 'An Attempt To Unraveling Token Prediction Refinement And Identifying Essential Layers Of Large Language Models'
authors: Jaturong Kongmanee
conference: "Arxiv"
year: 2025
bibkey: kongmanee2025attempt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.15054"}
tags: ['Responsible AI', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Applications']
---
This research aims to unravel how large language models (LLMs) iteratively
refine token predictions (or, in a general sense, vector predictions). We
utilized a logit lens technique to analyze the model's token predictions
derived from intermediate representations. Specifically, we focused on how LLMs
access and use information from input contexts, and how positioning of relevant
information affects the model's token prediction refinement process. Our
findings for multi-document question answering task, by varying input context
lengths (the number of documents), using GPT-2, revealed that the number of
layers between the first layer that the model predicted next tokens correctly
and the later layers that the model finalized its correct predictions, as a
function of the position of relevant information (i.e., placing the relevant
one at the beginning, middle, or end of the input context), has a nearly
inverted U shape. We found that the gap between these two layers, on average,
diminishes when relevant information is positioned at the beginning or end of
the input context, suggesting that the model requires more refinements when
processing longer contexts with relevant information situated in the middle,
and highlighting which layers are essential for determining the correct output.
Our analysis provides insights about how token predictions are distributed
across different conditions, and establishes important connections to existing
hypotheses and previous findings in AI safety research and development.
