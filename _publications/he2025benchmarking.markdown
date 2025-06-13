---
layout: publication
title: 'Benchmarking And Rethinking Knowledge Editing For Large Language Models'
authors: Guoxiu He, Xin Song, Futing Wang, Aixin Sun
conference: "Arxiv"
year: 2025
bibkey: he2025benchmarking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.18690'}
tags: ['Reinforcement Learning', 'GPT', 'Pretraining Methods']
---
Knowledge editing aims to update the embedded knowledge within Large Language Models (LLMs). However, existing approaches, whether through parameter modification or external memory integration, often suffer from inconsistent evaluation objectives and experimental setups. To address this gap, we conduct a comprehensive benchmarking study. In addition to fact-level datasets, we introduce more complex event-based datasets and general-purpose datasets drawn from other tasks. Our evaluation covers both instruction-tuned and reasoning-oriented LLMs, under a realistic autoregressive inference setting rather than teacher-forced decoding. Beyond single-edit assessments, we also evaluate multi-edit scenarios to better reflect practical demands. We employ four evaluation dimensions, including portability, and compare all recent methods against a simple and straightforward baseline named Selective Contextual Reasoning (SCR). Empirical results reveal that parameter-based editing methods perform poorly under realistic conditions. In contrast, SCR consistently outperforms them across all settings. This study offers new insights into the limitations of current knowledge editing methods and highlights the potential of context-based reasoning as a more robust alternative.
