---
layout: publication
title: Tear Improving Llm45;based Machine Translation With Systematic Self45;refinement
authors: Feng Zhaopeng, Zhang Yan, Li Hao, Wu Bei, Liao Jiayu, Liu Wenqiang, Lang Jun, Feng Yang, Wu Jian, Liu Zuozhu
conference: "Arxiv"
year: 2024
bibkey: feng2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16379"}
  - {name: "Code", url: "https://github.com/fzp0424/self&#95;correct&#95;mt"}
tags: ['Applications', 'Has Code', 'Interpretability And Explainability', 'Tools']
---
Large Language Models (LLMs) have achieved impressive results in Machine Translation (MT). However careful evaluations by human reveal that the translations produced by LLMs still contain multiple errors. Importantly feeding back such error information into the LLMs can lead to self45;refinement and result in improved translation performance. Motivated by these insights we introduce a systematic LLM45;based self45;refinement translation framework named textbf123;TEaR125; which stands for textbf123;T125;ranslate textbf123;E125;stimate textbf123;a125;nd textbf123;R125;efine marking a significant step forward in this direction. Our findings demonstrate that 1) our self45;refinement framework successfully assists LLMs in improving their translation quality across a wide range of languages whether its from high45;resource languages to low45;resource ones or whether its English45;centric or centered around other languages; 2) TEaR exhibits superior systematicity and interpretability; 3) different estimation strategies yield varied impacts directly affecting the effectiveness of the final corrections. Additionally traditional neural translation models and evaluation models operate separately often focusing on singular tasks due to their limited capabilities while general45;purpose LLMs possess the capability to undertake both tasks simultaneously. We further conduct cross45;model correction experiments to investigate the potential relationship between the translation and evaluation capabilities of general45;purpose LLMs. Our code and data are available at https://github.com/fzp0424/self&#95;correct&#95;mt
