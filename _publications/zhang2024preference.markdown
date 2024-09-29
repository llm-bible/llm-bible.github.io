---
layout: publication
title: "Plad: Preference-based Large Language Model Distillation With Pseudo-preference Pairs"
authors: Zhang Rongzhi, Shen Jiaming, Liu Tianqi, Wang Haorui, Qin Zhen, Han Feng, Liu Jialu, Baumgartner Simon, Bendersky Michael, Zhang Chao
conference: "Arxiv"
year: 2024
bibkey: zhang2024preference
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.02886"}
tags: ['Distillation', 'Efficiency And Optimization', 'RAG', 'Tools']
---
Large Language Models (LLMs) have exhibited impressive capabilities in various tasks yet their vast parameter sizes restrict their applicability in resource-constrained settings. Knowledge distillation (KD) offers a viable solution by transferring expertise from large teacher models to compact student models. However traditional KD techniques face specific challenges when applied to LLMs including restricted access to LLM outputs significant teacher-student capacity gaps and the inherited mis-calibration issue. In this work we present PLaD a novel preference-based LLM distillation framework. PLaD exploits the teacher-student capacity discrepancy to generate pseudo-preference pairs where teacher outputs are preferred over student outputs. Then PLaD leverages a ranking loss to re-calibrate students estimation of sequence likelihood which steers the students focus towards understanding the relative quality of outputs instead of simply imitating the teacher. PLaD bypasses the need for access to teacher LLMs internal states tackles the students expressivity limitations and mitigates the student mis-calibration issue. Through extensive experiments on two sequence generation tasks and with various LLMs we demonstrate the effectiveness of our proposed PLaD framework.
