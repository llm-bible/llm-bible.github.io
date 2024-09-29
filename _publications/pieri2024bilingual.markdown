---
layout: publication
title: Bimedix Bilingual Medical Mixture Of Experts LLM
authors: Pieri Sara, Mullappilly Sahal Shaji, Khan Fahad Shahbaz, Anwer Rao Muhammad, Khan Salman, Baldwin Timothy, Cholakkal Hisham
conference: "Arxiv"
year: 2024
bibkey: pieri2024bilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13253"}
  - {name: "Code", url: "https://github.com/mbzuai&#45;oryx/BiMediX"}
tags: ['Applications', 'Has Code', 'RAG']
---
In this paper we introduce BiMediX the first bilingual medical mixture of experts LLM designed for seamless interaction in both English and Arabic. Our model facilitates a wide range of medical interactions in English and Arabic including multi45;turn chats to inquire about additional details such as patient symptoms and medical history multiple45;choice question answering and open45;ended question answering. We propose a semi45;automated English45;to45;Arabic translation pipeline with human refinement to ensure high45;quality translations. We also introduce a comprehensive evaluation benchmark for Arabic medical LLMs. Furthermore we introduce BiMed1.3M an extensive Arabic45;English bilingual instruction set covering 1.3 Million diverse medical interactions resulting in over 632 million healthcare specialized tokens for instruction tuning. Our BiMed1.3M dataset includes 250k synthesized multi45;turn doctor45;patient chats and maintains a 12 Arabic45;to45;English ratio. Our model outperforms state45;of45;the45;art Med42 and Meditron by average absolute gains of 2.537; and 4.137; respectively computed across multiple medical evaluation benchmarks in English while operating at 845;times faster inference. Moreover our BiMediX outperforms the generic Arabic45;English bilingual LLM Jais45;30B by average absolute gains of 1037; on our Arabic medical benchmark and 1537; on bilingual evaluations across multiple datasets. Our project page with source code and trained model is available at https://github.com/mbzuai&#45;oryx/BiMediX .
