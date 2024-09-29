---
layout: publication
title: Gistscore Learning Better Representations For In45;context Example Selection With Gist Bottlenecks
authors: Gupta Shivanshu, Rosenbaum Clemens, Elenberg Ethan R.
conference: "Arxiv"
year: 2023
bibkey: gupta2023learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09606"}
tags: ['Attention Mechanism', 'Model Architecture', 'Prompting', 'Training Techniques']
---
In45;context Learning (ICL) is the ability of Large Language Models (LLMs) to perform new tasks when conditioned on prompts comprising a few task examples. However ICL performance can be critically sensitive to the choice of examples. To dynamically select the best examples for every test input we propose Example Gisting a novel approach for training example encoders through supervised fine45;tuning with an attention bottleneck between the inputs and outputs. These gist models form the basis for GistScore a novel metric for scoring and selecting informative examples. Further we experiment with two variations (1) fine45;tuning gist models for each dataset and (2) multi45;task training a single model on a large collection of datasets. The latter can be used for new tasks out45;of45;the45;box enabling a training45;free ICL pipeline. Evaluations with 21 datasets spanning 9 tasks and 8 diverse LLMs show that our fine45;tuned models get state45;of45;the45;art ICL performance with over 2037; absolute gain over off45;the45;shelf retrievers and 537; over the best prior methods. Further our multi45;task model generalizes well to new tasks datasets and prompt templates. Selection using this model matches or outperforms prior methods while being three orders of magnitude faster than the strongest training45;free baseline.
