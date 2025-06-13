---
layout: publication
title: 'Sage-eval: Evaluating Llms For Systematic Generalizations Of Safety Facts'
authors: Chen Yueh-han, Guy Davidson, Brenden M. Lake
conference: "Arxiv"
year: 2025
bibkey: yuehhan2025sage
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.21828"}
  - {name: "Code", url: "https://huggingface.co/datasets/YuehHanChen/SAGE-Eval"}
  - {name: "Code", url: "https://github.com/YuehHanChen/SAGE-Eval/tree/main"}
tags: ['Responsible AI', 'Training Techniques', 'Has Code', 'Reinforcement Learning']
---
Do LLMs robustly generalize critical safety facts to novel situations? Lacking this ability is dangerous when users ask naive questions. For instance, "I'm considering packing melon balls for my 10-month-old's lunch. What other foods would be good to include?" Before offering food options, the LLM should warn that melon balls pose a choking hazard to toddlers, as documented by the CDC. Failing to provide such warnings could result in serious injuries or even death. To evaluate this, we introduce SAGE-Eval, SAfety-fact systematic GEneralization evaluation, the first benchmark that tests whether LLMs properly apply well established safety facts to naive user queries. SAGE-Eval comprises 104 facts manually sourced from reputable organizations, systematically augmented to create 10,428 test scenarios across 7 common domains (e.g., Outdoor Activities, Medicine). We find that the top model, Claude-3.7-sonnet, passes only 58% of all the safety facts tested. We also observe that model capabilities and training compute weakly correlate with performance on SAGE-Eval, implying that scaling up is not the golden solution. Our findings suggest frontier LLMs still lack robust generalization ability. We recommend developers use SAGE-Eval in pre-deployment evaluations to assess model reliability in addressing salient risks. We publicly release SAGE-Eval at https://huggingface.co/datasets/YuehHanChen/SAGE-Eval and our code is available at https://github.com/YuehHanChen/SAGE-Eval/tree/main.
