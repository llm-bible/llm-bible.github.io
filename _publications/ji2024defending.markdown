---
layout: publication
title: 'Defending Large Language Models Against Jailbreak Attacks Via Semantic Smoothing'
authors: Jiabao Ji, Bairu Hou, Alexander Robey, George J. Pappas, Hamed Hassani, Yang Zhang, Eric Wong, Shiyu Chang
conference: "Arxiv"
year: 2024
bibkey: ji2024defending
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16192"}
  - {name: "Code", url: "https://github.com/UCSB-NLP-Chang/SemanticSmooth"}
tags: ['Prompting', 'Security', 'Has Code']
---
Aligned large language models (LLMs) are vulnerable to jailbreaking attacks,
which bypass the safeguards of targeted LLMs and fool them into generating
objectionable content. While initial defenses show promise against token-based
threat models, there do not exist defenses that provide robustness against
semantic attacks and avoid unfavorable trade-offs between robustness and
nominal performance. To meet this need, we propose SEMANTICSMOOTH, a
smoothing-based defense that aggregates the predictions of multiple
semantically transformed copies of a given input prompt. Experimental results
demonstrate that SEMANTICSMOOTH achieves state-of-the-art robustness against
GCG, PAIR, and AutoDAN attacks while maintaining strong nominal performance on
instruction following benchmarks such as InstructionFollowing and AlpacaEval.
The codes will be publicly available at
https://github.com/UCSB-NLP-Chang/SemanticSmooth.
