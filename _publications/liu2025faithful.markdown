---
layout: publication
title: 'Metafaith: Faithful Natural Language Uncertainty Expression In Llms'
authors: Gabrielle Kaili-may Liu, Gal Yona, Avi Caciularu, Idan Szpektor, Tim G. J. Rudner, Arman Cohan
conference: "Arxiv"
year: 2025
bibkey: liu2025faithful
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.24858"}
tags: ['Prompting']
---
A critical component in the trustworthiness of LLMs is reliable uncertainty communication, yet LLMs often use assertive language when conveying false claims, leading to over-reliance and eroded trust. We present the first systematic study of \\(\textit\{faithful confidence calibration\}\\) of LLMs, benchmarking models' ability to use linguistic expressions of uncertainty that \\(\textit\{faithfully reflect\}\\) their intrinsic uncertainty, across a comprehensive array of models, datasets, and prompting strategies. Our results demonstrate that LLMs largely fail at this task, and that existing interventions are insufficient: standard prompt approaches provide only marginal gains, and existing, factuality-based calibration techniques can even harm faithful calibration. To address this critical gap, we introduce MetaFaith, a novel prompt-based calibration approach inspired by human metacognition. We show that MetaFaith robustly improves faithful calibration across diverse models and task domains, enabling up to 61% improvement in faithfulness and achieving an 83% win rate over original generations as judged by humans.
