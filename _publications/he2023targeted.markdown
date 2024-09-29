---
layout: publication
title: Targeted Data Generation: Finding And Fixing Model Weaknesses
authors: He Zexue, Ribeiro Marco Tulio, Khani Fereshte
conference: "Arxiv"
year: 2023
bibkey: he2023targeted
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.17804"}
tags: ['Pretraining Methods', 'Tools']
---
Even when aggregate accuracy is high state-of-the-art NLP models often fail systematically on specific subgroups of data resulting in unfair outcomes and eroding user trust. Additional data collection may not help in addressing these weaknesses as such challenging subgroups may be unknown to users and underrepresented in the existing and new data. We propose Targeted Data Generation (TDG) a framework that automatically identifies challenging subgroups and generates new data for those subgroups using large language models (LLMs) with a human in the loop. TDG estimates the expected benefit and potential harm of data augmentation for each subgroup and selects the ones most likely to improve within group performance without hurting overall performance. In our experiments TDG significantly improves the accuracy on challenging subgroups for state-of-the-art sentiment analysis and natural language inference models while also improving overall test accuracy.
