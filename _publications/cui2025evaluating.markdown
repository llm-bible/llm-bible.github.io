---
layout: publication
title: 'CURIE: Evaluating Llms On Multitask Scientific Long Context Understanding And Reasoning'
authors: Hao Cui, Zahra Shamsi, Gowoon Cheon, Xuejian Ma, Shutong Li, Maria Tikhanovskaya, Peter Norgaard, Nayantara Mudur, Martyna Plomecka, Paul Raccuglia, Yasaman Bahri, Victor V. Albert, Pranesh Srinivasan, Haining Pan, Philippe Faist, Brian Rohr, Ekin Dogus Cubuk, Muratahan Aykol, Amil Merchant, Michael J. Statt, Dan Morris, Drew Purves, Elise Kleeman, Ruth Alcantara, Matthew Abraham, Muqthar Mohammad, Ean Phing Vanlee, Chenfei Jiang, Elizabeth Dorfman, Eun-ah Kim, Michael P Brenner, Viren Jain, Sameera Ponda, Subhashini Venugopalan
conference: "Arxiv"
year: 2025
bibkey: cui2025evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.13517"}
  - {name: "Code", url: "https://github.com/google/curie"}
tags: ['Model Architecture', 'GPT', 'Has Code']
---
Scientific problem-solving involves synthesizing information while applying expert knowledge. We introduce CURIE, a scientific long-Context Understanding,Reasoning and Information Extraction benchmark to measure the potential of Large Language Models (LLMs) in scientific problem-solving and assisting scientists in realistic workflows. This benchmark introduces ten challenging tasks with a total of 580 problems and solution pairs curated by experts in six disciplines - materials science, condensed matter physics, quantum computing, geospatial analysis, biodiversity, and proteins - covering both experimental and theoretical work-flows in science. We evaluate a range of closed and open LLMs on tasks in CURIE which requires domain expertise, comprehension of long in-context information,and multi-step reasoning. While Gemini Flash 2.0 and Claude-3 show consistent high comprehension across domains, the popular GPT-4o and command-R+ fail dramatically on protein sequencing tasks. With the best performance at 32% there is much room for improvement for all models. We hope that insights gained from CURIE can guide the future development of LLMs in sciences. Evaluation code and data are in https://github.com/google/curie
