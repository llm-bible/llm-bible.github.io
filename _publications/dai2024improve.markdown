---
layout: publication
title: Improve Students Reasoning Generalizability Through Cascading Decomposed Cots Distillation
authors: Dai Chengwei, Li Kun, Zhou Wei, Hu Songlin
conference: "Arxiv"
year: 2024
bibkey: dai2024improve
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.19842"}
  - {name: "Code", url: "https://github.com/C&#45;W&#45;D/CasCoD"}
tags: ['Distillation', 'Efficiency And Optimization', 'Has Code', 'Training Techniques']
---
Large language models (LLMs) exhibit enhanced reasoning at larger scales driving efforts to distill these capabilities into smaller models via teacher45;student learning. Previous works simply fine45;tune student models on teachers generated Chain45;of45;Thoughts (CoTs) data. Although these methods enhance in45;domain (IND) reasoning performance they struggle to generalize to out45;of45;domain (OOD) tasks. We believe that the widespread spurious correlations between questions and answers may lead the model to preset a specific answer which restricts the diversity and generalizability of its reasoning process. In this paper we propose Cascading Decomposed CoTs Distillation (CasCoD) to address these issues by decomposing the traditional single45;step learning process into two cascaded learning steps. Specifically by restructuring the training objectives 45;45; removing the answer from outputs and concatenating the question with the rationale as input 45;45; CasCoDs two45;step learning process ensures that students focus on learning rationales without interference from the preset answers thus improving reasoning generalizability. Extensive experiments demonstrate the effectiveness of CasCoD on both IND and OOD benchmark reasoning datasets. Code can be found at https://github.com/C&#45;W&#45;D/CasCoD.
