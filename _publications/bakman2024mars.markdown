---
layout: publication
title: MARS Meaning-Aware Response Scoring for Uncertainty Estimation in Generative LLMs
authors: Bakman Yavuz Faruk, Yaldiz Duygu Nur, Buyukates Baturalp, Tao Chenyang, Dimitriadis Dimitrios, Avestimehr Salman
conference: "Arxiv"
year: 2024
bibkey: bakman2024mars
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11756"}
  - {name: "Code", url: "https://github.com/Ybakman/LLM_Uncertainity"}
tags: ['ARXIV', 'Applications', 'Has Code', 'LLM']
---
Generative Large Language Models (LLMs) are widely utilized for their excellence in various tasks. However their tendency to produce inaccurate or misleading outputs poses a potential risk particularly in high-stakes environments. Therefore estimating the correctness of generative LLM outputs is an important task for enhanced reliability. Uncertainty Estimation (UE) in generative LLMs is an evolving domain where SOTA probability-based methods commonly employ length-normalized scoring. In this work we propose Meaning-Aware Response Scoring (MARS) as an alternative to length-normalized scoring for UE methods. MARS is a novel scoring function that considers the semantic contribution of each token in the generated sequence in the context of the question. We demonstrate that integrating MARS into UE methods results in a universal and significant improvement in UE performance. We conduct experiments using three distinct closed-book question-answering datasets across five popular pre-trained LLMs. Lastly we validate the efficacy of MARS on a Medical QA dataset. Code can be found https://github.com/Ybakman/LLM_Uncertainity.
