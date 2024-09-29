---
layout: publication
title: Are Llms Robust For Spoken Dialogues
authors: Mousavi Seyed Mahed, Roccabruna Gabriel, Alghisi Simone, Rizzoli Massimo, Ravanelli Mirco, Riccardi Giuseppe
conference: "Arxiv"
year: 2024
bibkey: mousavi2024are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.02297"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Security', 'Training Techniques']
---
Large Pre45;Trained Language Models have demonstrated state45;of45;the45;art performance in different downstream tasks including dialogue state tracking and end45;to45;end response generation. Nevertheless most of the publicly available datasets and benchmarks on task45;oriented dialogues focus on written conversations. Consequently the robustness of the developed models to spoken interactions is unknown. In this work we have evaluated the performance of LLMs for spoken task45;oriented dialogues on the DSTC11 test sets. Due to the lack of proper spoken dialogue datasets we have automatically transcribed a development set of spoken dialogues with a state45;of45;the45;art ASR engine. We have characterized the ASR45;error types and their distributions and simulated these errors in a large dataset of dialogues. We report the intrinsic (perplexity) and extrinsic (human evaluation) performance of fine45;tuned GPT45;2 and T5 models in two subtasks of response generation and dialogue state tracking respectively. The results show that LLMs are not robust to spoken noise by default however fine45;tuning/training such models on a proper dataset of spoken TODs can result in a more robust performance.
