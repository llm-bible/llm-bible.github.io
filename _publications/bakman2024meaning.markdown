---
layout: publication
title: MARS Meaning45;aware Response Scoring For Uncertainty Estimation In Generative Llms
authors: Bakman Yavuz Faruk, Yaldiz Duygu Nur, Buyukates Baturalp, Tao Chenyang, Dimitriadis Dimitrios, Avestimehr Salman
conference: "Arxiv"
year: 2024
bibkey: bakman2024meaning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11756"}
  - {name: "Code", url: "https://github.com/Ybakman/LLM&#95;Uncertainity"}
tags: ['Applications', 'Has Code', 'Reinforcement Learning']
---
Generative Large Language Models (LLMs) are widely utilized for their excellence in various tasks. However their tendency to produce inaccurate or misleading outputs poses a potential risk particularly in high45;stakes environments. Therefore estimating the correctness of generative LLM outputs is an important task for enhanced reliability. Uncertainty Estimation (UE) in generative LLMs is an evolving domain where SOTA probability45;based methods commonly employ length45;normalized scoring. In this work we propose Meaning45;Aware Response Scoring (MARS) as an alternative to length45;normalized scoring for UE methods. MARS is a novel scoring function that considers the semantic contribution of each token in the generated sequence in the context of the question. We demonstrate that integrating MARS into UE methods results in a universal and significant improvement in UE performance. We conduct experiments using three distinct closed45;book question45;answering datasets across five popular pre45;trained LLMs. Lastly we validate the efficacy of MARS on a Medical QA dataset. Code can be found https://github.com/Ybakman/LLM&#95;Uncertainity.
