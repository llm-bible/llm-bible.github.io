---
layout: publication
title: 'MARGE: Improving Math Reasoning For Llms With Guided Exploration'
authors: Jingyue Gao, Runji Lin, Keming Lu, Bowen Yu, Junyang Lin, Jianyu Chen
conference: "Arxiv"
year: 2025
bibkey: gao2025improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.12500'}
  - {name: "Code", url: 'https://github.com/georgao35/MARGE}{this'}
tags: ['Fine-Tuning', 'Has Code', 'Training Techniques']
---
Large Language Models (LLMs) exhibit strong potential in mathematical reasoning, yet their effectiveness is often limited by a shortage of high-quality queries. This limitation necessitates scaling up computational responses through self-generated data, yet current methods struggle due to spurious correlated data caused by ineffective exploration across all reasoning stages. To address such challenge, we introduce \textbf\{MARGE\}: Improving \textbf\{Ma\}th \textbf\{R\}easoning with \textbf\{G\}uided \textbf\{E\}xploration, a novel method to address this issue and enhance mathematical reasoning through hit-guided exploration. MARGE systematically explores intermediate reasoning states derived from self-generated solutions, enabling adequate exploration and improved credit assignment throughout the reasoning process. Through extensive experiments across multiple backbone models and benchmarks, we demonstrate that MARGE significantly improves reasoning capabilities without requiring external annotations or training additional value models. Notably, MARGE improves both single-shot accuracy and exploration diversity, mitigating a common trade-off in alignment methods. These results demonstrate MARGE's effectiveness in enhancing mathematical reasoning capabilities and unlocking the potential of scaling self-generated training data. Our code and models are available at \href\{https://github.com/georgao35/MARGE\}\{this link\}.
