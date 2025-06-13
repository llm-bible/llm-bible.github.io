---
layout: publication
title: 'Raising The Bar: Investigating The Values Of Large Language Models Via Generative Evolving Testing'
authors: Han Jiang, Xiaoyuan Yi, Zhihua Wei, Ziang Xiao, Shu Wang, Xing Xie
conference: "Arxiv"
year: 2024
bibkey: jiang2024raising
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.14230'}
tags: ['Reinforcement Learning', 'Ethics and Bias', 'Training Techniques', 'Tools']
---
Warning: Contains harmful model outputs. Despite significant advancements, the propensity of Large Language Models (LLMs) to generate harmful and unethical content poses critical challenges. Measuring value alignment of LLMs becomes crucial for their regulation and responsible deployment. Although numerous benchmarks have been constructed to assess social bias, toxicity, and ethical issues in LLMs, those static benchmarks suffer from evaluation chronoeffect, in which, as models rapidly evolve, existing benchmarks may leak into training data or become saturated, overestimating ever-developing LLMs. To tackle this problem, we propose GETA, a novel generative evolving testing approach based on adaptive testing methods in measurement theory. Unlike traditional adaptive testing methods that rely on a static test item pool, GETA probes the underlying moral boundaries of LLMs by dynamically generating test items tailored to model capability. GETA co-evolves with LLMs by learning a joint distribution of item difficulty and model value conformity, thus effectively addressing evaluation chronoeffect. We evaluated various popular LLMs with GETA and demonstrated that 1) GETA can dynamically create difficulty-tailored test items and 2) GETA's evaluation results are more consistent with models' performance on unseen OOD and i.i.d. items, laying the groundwork for future evaluation paradigms.
