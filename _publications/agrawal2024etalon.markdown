---
layout: publication
title: Etalon Holistic Performance Evaluation Framework for LLM Inference Systems
authors: Agrawal Amey, Agarwal Anmol, Kedia Nitin, Mohan Jayashree, Kundu Souvik, Kwatra Nipun, Ramjee Ramachandran, Tumanov Alexey
conference: "Arxiv"
year: 2024
bibkey: agrawal2024etalon
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.07000"}
  - {name: "Code", url: "https://github.com/project-etalon/etalon"}
tags: ['ARXIV', 'Applications', 'Ethics And Bias', 'Has Code', 'LLM', 'Tools']
---
Serving large language models (LLMs) in production can incur substantial costs which has prompted recent advances in inference system optimizations. Today these systems are evaluated against conventional latency and throughput metrics (eg. TTFT TBT Normalised Latency and TPOT). However these metrics fail to fully capture the nuances of LLM inference leading to an incomplete assessment of user-facing performance crucial for real-time applications such as chat and translation. In this paper we first identify the pitfalls of current performance metrics in evaluating LLM inference systems. We then propose Etalon a comprehensive performance evaluation framework that includes fluidity-index -- a novel metric designed to reflect the intricacies of the LLM inference process and its impact on real-time user experience. Finally we evaluate various existing open-source platforms and model-as-a-service offerings using Etalon discussing their strengths and weaknesses. Etalon is available at https://github.com/project-etalon/etalon.
