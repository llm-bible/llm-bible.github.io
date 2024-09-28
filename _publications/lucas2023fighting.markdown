---
layout: publication
title: Fighting Fire with Fire The Dual Role of LLMs in Crafting and Detecting Elusive Disinformation
authors: Lucas Jason, Uchendu Adaku, Yamashita Michiharu, Lee Jooyoung, Rohatgi Shaurya, Lee Dongwon
conference: "Arxiv"
year: 2023
bibkey: lucas2023fighting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.15515"}
  - {name: "Code", url: "https://github.com/mickeymst/F3"}
tags: ['ARXIV', 'GPT', 'Has Code', 'LLM', 'Merging', 'Model Architecture', 'Prompt', 'RAG']
---
Recent ubiquity and disruptive impacts of large language models (LLMs) have raised concerns about their potential to be misused (.i.e generating large-scale harmful and misleading content). To combat this emerging risk of LLMs we propose a novel Fighting Fire with Fire (F3) strategy that harnesses modern LLMs generative and emergent reasoning capabilities to counter human-written and LLM-generated disinformation. First we leverage GPT-3.5-turbo to synthesize authentic and deceptive LLM-generated content through paraphrase-based and perturbation-based prefix-style prompts respectively. Second we apply zero-shot in-context semantic reasoning techniques with cloze-style prompts to discern genuine from deceptive posts and news articles. In our extensive experiments we observe GPT-3.5-turbos zero-shot superiority for both in-distribution and out-of-distribution datasets where GPT-3.5-turbo consistently achieved accuracy at 68-72 unlike the decline observed in previous customized and fine-tuned disinformation detectors. Our codebase and dataset are available at https://github.com/mickeymst/F3.
