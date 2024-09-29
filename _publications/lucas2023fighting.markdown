---
layout: publication
title: Fighting Fire With Fire The Dual Role Of Llms In Crafting And Detecting Elusive Disinformation
authors: Lucas Jason, Uchendu Adaku, Yamashita Michiharu, Lee Jooyoung, Rohatgi Shaurya, Lee Dongwon
conference: "Arxiv"
year: 2023
bibkey: lucas2023fighting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.15515"}
  - {name: "Code", url: "https://github.com/mickeymst/F3"}
tags: ['GPT', 'Has Code', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG']
---
Recent ubiquity and disruptive impacts of large language models (LLMs) have raised concerns about their potential to be misused (.i.e generating large45;scale harmful and misleading content). To combat this emerging risk of LLMs we propose a novel Fighting Fire with Fire (F3) strategy that harnesses modern LLMs generative and emergent reasoning capabilities to counter human45;written and LLM45;generated disinformation. First we leverage GPT45;3.545;turbo to synthesize authentic and deceptive LLM45;generated content through paraphrase45;based and perturbation45;based prefix45;style prompts respectively. Second we apply zero45;shot in45;context semantic reasoning techniques with cloze45;style prompts to discern genuine from deceptive posts and news articles. In our extensive experiments we observe GPT45;3.545;turbos zero45;shot superiority for both in45;distribution and out45;of45;distribution datasets where GPT45;3.545;turbo consistently achieved accuracy at 6845;7237; unlike the decline observed in previous customized and fine45;tuned disinformation detectors. Our codebase and dataset are available at https://github.com/mickeymst/F3.
