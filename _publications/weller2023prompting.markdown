---
layout: publication
title: '"according To ...": Prompting Language Models Improves Quoting From Pre-training Data'
authors: Weller Orion, Marone Marc, Weir Nathaniel, Lawrie Dawn, Khashabi Daniel, Van Durme Benjamin
conference: "Arxiv"
year: 2023
bibkey: weller2023prompting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13252"}
tags: ['Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) may hallucinate and generate fake information despite pre-training on factual data. Inspired by the journalistic device of according to sources we propose according-to prompting directing LLMs to ground responses against previously observed text. To quantify this grounding we propose a novel evaluation metric (QUIP-Score) that measures the extent to which model-produced answers are directly found in underlying text corpora. We illustrate with experiments on three corpora (Wikipedia PubMed and the U.S. legal tax code) that these prompts improve grounding under our metrics with the additional benefit of often improving end-task performance. Furthermore prompts that ask the model to decrease grounding (or to ground to other corpora) indeed decrease QUIP-Score indicating the ability of LLMs to increase or decrease grounded generations on request.
