---
layout: publication
title: 'Long-form Information Alignment Evaluation Beyond Atomic Facts'
authors: Danna Zheng, Mirella Lapata, Jeff Z. Pan
conference: "Arxiv"
year: 2025
bibkey: zheng2025long
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.15792'}
  - {name: "Code", url: 'https://github.com/dannalily/DoveScore'}
tags: ['Has Code', 'Security', 'Tools']
---
Information alignment evaluators are vital for various NLG evaluation tasks and trustworthy LLM deployment, reducing hallucinations and enhancing user trust. Current fine-grained methods, like FactScore, verify facts individually but neglect inter-fact dependencies, enabling subtle vulnerabilities. In this work, we introduce MontageLie, a challenging benchmark that constructs deceptive narratives by "montaging" truthful statements without introducing explicit hallucinations. We demonstrate that both coarse-grained LLM-based evaluators and current fine-grained frameworks are susceptible to this attack, with AUC-ROC scores falling below 65%. To enable more robust fine-grained evaluation, we propose DoveScore, a novel framework that jointly verifies factual accuracy and event-order consistency. By modeling inter-fact relationships, DoveScore outperforms existing fine-grained methods by over 8%, providing a more robust solution for long-form text alignment evaluation. Our code and datasets are available at https://github.com/dannalily/DoveScore.
